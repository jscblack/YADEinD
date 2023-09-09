# YADEinD
[![Docker Image CI](https://github.com/jscblack/YADED/actions/workflows/docker-image.yml/badge.svg)](https://github.com/jscblack/YADED/actions/workflows/docker-image.yml)

Yet Another Development Environment in Docker

Required Font:**MesloLGS NF**

Example:
![image](https://user-images.githubusercontent.com/33062157/196014804-635d846d-9647-4a02-8f92-cb3f73b606aa.png)


Usage:``docker run -d -n container_name -p port:22 -v $pwd/yaded_root:/root/workspace -e TZ="Asia/Shanghai" jscblack/yaded:latest``
