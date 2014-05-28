---
layout: post
category : baseline
tagline: "Supporting tagline"
tags : [intro, beginner, tutorial]
title : 服务器、网络基线
---
{% include JB/setup %}


## 总览

这篇是基线项目的一部分，本文讲解了基本的服务器、网络方面的基线

### 基线描述

* 了解 DNS、负载均衡、反向代理、CDN 等网络知识；
* 了解常见的 linux 服务器操作系统；
* 会配置常用的 Web 服务器，比如 apache、nginx；
* 了解 MySql 的配置管理；
* 了解基于网络的文件共享；
* 了解 SSH、用户、权限等；
* 了解常用的命令及 shell script；

验收条件如下：

## 了解 DNS、负载均衡、反向代理、CDN 等网络知识；

1. 写一篇博客讲解DNS，负载均衡，反向代理，CDN：优点缺点。

## 了解常见的 linux 服务器操作系统；

1. 讲解linux操作系统历史，常见的发行版。

## 会配置常用的 Web 服务器，比如 apache、nginx；

1. 用apache或者nginx，基于多个vm，本地host或路由器dns配置一个网站。在配置完毕后，在阿里云上重现。
2. 写一篇博客讲解这些内容，结合前面的dns，负载均衡，反向代理，CDN

## 了解 MySql 的配置管理

1. 安装部署，配置一个mysql，建立起用户，设置权限，远程连接。
2. 写博客讲解

## 了解基于网络的文件共享；

1. 搭建ftp，smb，afp，使用scp复制文件
2. 写博客讲解ftp,smb,afp等协议，以及使用scp与他们的差别。

## 了解 SSH、用户、权限等；

1. 创建用户，赋予可以ssh的权限，然后用ssh登录
2. 写一篇博客讲解ssh，用户和权限

## 了解常用的命令及 shell script；

1. 学习并使用ls、rm、mkdir、cd、chown、chmod、sudo,ln等
2. 写博客讲解上述命令
3. 学习基本的shell script，完成练习
4. 写博客讲解上述shell脚本语法，常用知识和练习的解决思路