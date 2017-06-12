---
layout: post
title: "drools起步"
date: 2017-06-12
---

# 安装
1. 下载drools docker镜像[下载](https://hub.docker.com/r/jboss/drools-workbench/)
2. 根据文档，启动镜像:`docker run -p 8080:8080 -p 8001:8001 -d --name drools-workbench jboss/drools-workbench:latest`
3. 登录到镜像上，运行`add-user.sh`脚本，分别添加管理用户和应用用户。
4. 打开http://localhost:8080/drools-wb，并用上面添加的应用用户名称与密码登录。 
