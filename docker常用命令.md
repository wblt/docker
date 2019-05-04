### 1.docker 拉取镜像
docker pull hello-world

### 1.docker 查看镜像
docker images 

### 1.docker 查看运行的镜像
docker ps & docker ps -a

### 1.docker 后台运行镜像
docker run -d hub.c.163.com/library/nginx

### 1.docker 停止运行镜像
docker stop 977720ec527f

### 1.docker 进入运行的镜像内部
docker exec -it 977 bash

### 1.docker 网络端口映射
docker run -d -p 80:80 hub.c.163.com/library/nginx

### 1.docker 网络端口映射
netstat -na|grep 80

### 1.docker 删除镜像
docker rmi 46102226f2fd

### 1.docker 删除容器
docker rm 9a05ec6db2b1

### 1.docker build包
docker build -t docker_test:latest .


