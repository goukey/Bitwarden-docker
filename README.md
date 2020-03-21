
# 必须使用ssl，否则无法注册新用户 # 登录地址为 ip:444

## 准备工作

将证书文件分别改名certs.pem和key.pem 放入/etc/certs目录

## 开始使用

> git clone https://github.com/goukey/Bitwarden-docker.git Bitwarden-docker

> cd Bitwarden-docker

> docker-compose up -d


## 关闭容器

> docker-compose down

## 升级容器

> cd Bitwarden-docker

> docker-compose down  #停止容器

> git pull

> docker-compose pull  #更新image

> docker-compose up -d  #启动容器

> docker image prune  #删除旧的镜像
