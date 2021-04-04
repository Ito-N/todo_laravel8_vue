## 環境の再構築(初回構築)する
- https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4#%E7%92%B0%E5%A2%83%E3%81%AE%E5%86%8D%E6%A7%8B%E7%AF%89  参照
- Laravelインストール、.env 環境変数ファイルは作成、APP_KEYの作成が必要

    $ git clone git@github.com:Ito-N/laravel_container.git

- cloneしたリポジトリを別リポジトリとしてリモートにpushする(https://qiita.com/SR_midori/items/52730907c1cddeb78b4d)

# mysql接続
    
    $ docker-compose exec db bash -c 'mysql -u root -psecret'


    