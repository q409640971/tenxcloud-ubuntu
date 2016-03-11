# docker-ubuntu
采用国内apt源的Ubuntu镜像

##VOLUME 
    /data
##环境变量
 - PATH = /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
 - AUTHORIZED_KEYS = **None**
 - ROOT_PASS = root
 
##端口映射
    容器端口    22
    协议        tcp
    映射端口    37619（随机）

##执行命令 
    /run.sh

##运行效果
    SSH-2.0-OpenSSH_6.0p1 Debian-4+deb7u2
