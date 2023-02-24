# Docker-React-CRA
コマンドは、Dockerfileが存在するディレクトリで実行する必要があります。

cdコマンドでディレクトリを移動しておいてください。


## イメージの構築
```docker-compose build```


## React＋TypeScriptでプロジェクトを作成
```docker-compose run --rm front sh -c 'npx create-react-app react-app --template typescript'```


## コンテナの作成と起動
```docker-compose up -d```


## ローカルホストに接続
ここまで完了したらWebブラウザで「 http://localhost:3000/ 」へアクセスしてください。

以下のようにReactのページが起動すれば環境構築完了です。

![image](https://user-images.githubusercontent.com/96112023/221098457-bc501e1b-8a7b-4b68-8f81-19a9b2ed1e5a.png)