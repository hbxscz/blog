---

title: Docker Learning Note 
layout: default

---

1. Mac上 安装 boot2docker， 启动
2. docker 下载 centos镜像sudo docker pull centos:latest
3. 进入 docker 环境 docker run -i -t lcentos:latest /bin/bash  
4. 安装 jdk tomcat
5. commit镜像前注册https://hub.docker.com/account/welcome/ 
6. docker commit  containerID  hbxscz/java_image 
   docker push hbxscz/java_image
7. 以后就可以下载这个镜像 docker pull hbxscz/java_image
