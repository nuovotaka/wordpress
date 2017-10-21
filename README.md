Docker for Mac + docker-compose でWordpressの開発環境を作成


docker-compose.yml ファイルのあるところで下記のコマンドを実行
```
docker-compose up -d

localhost:8000にアクセス
```

### カレントディレクトリの確認

カレントディレクトリに.data(dbは隠しファイル)とwpディレクトリが作成されます。
wp/wp-content/themes/にテーマディレクトリを作成し、そこにindex.phpなどを配置して開発。
