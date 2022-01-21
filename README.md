## 概要
docker-composeを使用し、Ruby,Rails,MySQL,Nginxの環境を構築した。

## 構築コマンド
1. `git clone git@github.com:kenji-kk/docker-compose-rails.git`
2. `cd docker-compose-rails`
3. `docker-compose up -d`
4. `docker-compose exec app rails webpacker:install`
5. `docker-compose exec app rails webpacker:compile`

## 確認URL
- http://localhost
