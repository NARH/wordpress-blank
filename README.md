== Wordpress ローカル環境構築
これは空っぽのプロジェクトです。

clone 後に
`` docker-compose up -d ``
で起動します。
その後 http://localhost:8000 でWordpress のインストール画面になります。

DB は `mysql 5.7`

- dataabse: wpdb
- id: wordpress
- password wordpress

になっています。DBのポートは外部に未公開です。