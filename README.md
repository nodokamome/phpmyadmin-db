# phpmyadmin-db

### how to start
```
$ git clone git@github.com:nodokamome/phpmyadmin-db.git

$ cd phpmyadmin-db

// .envで設定編集
// MYSQL_ROOT_PASSWORD = `データベースの管理パスワード`
$ cp .env.sample .env

$ vi .env

$ docker-compose up -d
```

以下にアクセス  
http://localhost:8080/
- サーバ：db  
- ユーザ名：root  
- パスワード：`.envで設定したもの`  
