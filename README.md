# **環境構築**
以下をclone
```
$ git clone https://github.com/sakamoto-kohei-44/avi-app-src.git ※1
$ git clone https://github.com/sakamoto-kohei-44/avi-app-docker.git ※2
```
```
git/avi-app (ルートディレクトリ)
 ├── src ※1
 ├── docker ※2
```
**インストール**
```
$ make install
```
**確認**
以下にアクセス\
http://localhost:8080/

# **操作**
**起動**
※$ docker compose up -dと同じ
```
$ make up
```
**停止**
※$ docker compose down --remove-orphansと同じ
```
$ make down
```
