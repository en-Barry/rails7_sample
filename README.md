# README
Rails7をDockerで起動する雛形

* Ruby version
3.1.0

* Database
MySQL

* Getting Started
```
dockerのappコンテナでDB作成コマンドを実行
# bundle exec rails db:create

imageを作成
% docker compose build

appコンテナ、dbコンテナを起動
% docker compose up -d
```