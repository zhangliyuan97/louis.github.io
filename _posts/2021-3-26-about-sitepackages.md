---
layout: post
comments: true
title: Anaconda环境配置
excerpt: 服务器内网环境，本地保留镜像端口
categories: Tools
date: 2021-03-26 10:00:00
---
离线环境配置
问题描述：
当前工作环境是内网环境，只在本地保留了镜像的端口，server是没法直接通过pip install或者conda install进行安装或者是package的。

解决方案：
1.在本地创建一个新的环境

2.在新的环境里pip或者conda安装所有需要的package

3.然后sftp连接到server，把本地环境的anaconda3/envs/xxx/lib/python3.6/site-packages/*全部put到server.