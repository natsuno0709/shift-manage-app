#LAMP環境構築

```
PHP Nginx MySQL
```

# 環境構築手順

1. ローカルにプロジェクトを入れるためのディレクトリを作成
2. 1.で作成したディレクトリ内に移動し、githubからプロジェクトをクローン  
   `$ git clone https://github.com/takaokouki/shift-manage-app.git`
3. 作成されたプロジェクト内のappのディレクトリに移動  
   `$ cd shift-manage-app/app`
4. 必要なライブラリをインストール  
  ` $ composer install`
5. dockerの立ち上げ  
   `$ docker-compose up -d --build` 
