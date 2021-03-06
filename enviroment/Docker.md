# Docker

容器化管理工具

- [官方網站](https://www.docker.com/)

## 安裝 Docker

```
brew install docker
```

## Docker 常用指令

### 刪除所有容器

```
# bash
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)

# fish shell
docker stop (docker ps -a -q)
docker rm (docker ps -a -q)
```

### 刪除所有未啟動的容器

```
docker container prune
```

### 刪除所有映像檔

```
# bash
docker image prune
```

### 刪除舊的映像檔

```
docker image prune
```

### 使用docker node container開發

```
// version: dubnium, expose port: 80, server port: 3000
docker run --rm -it --name node-docker -v $PWD:/usr/src -w /usr/src -p 80:3000 -u node node:dubnium /bin/bash
```
