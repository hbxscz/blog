---

title: Docker Learning Note
layout: default

---

1. ####Mac上安装boot2docker，启动docker 

2. ####下载centos镜像 

	>sudo docker pull centos:latest
		
3. ####进入 docker 环境 
		 
	>docker run -i -t lcentos:latest /bin/bash

4. ####安装jdk, tomcat

5. ####commit镜像前注册 [前往](https://hub.docker.com/account/welcome/)

6. #### 提交镜像

	>*  docker commit  containerID  hbxscz/java_image  
	>
	>*  docker push hbxscz/java_image
				
7. ####以后就可以下载这个镜像 

	>docker pull hbxscz/java_image
