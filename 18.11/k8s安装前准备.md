# k8s安装前准备

## 虚拟机软件

https://www.vmware.com/
下载安装虚拟机软件VMWare

## 虚拟机镜像

下载官方ubuntu 18.2.3 server镜像
使用VMware安装基础版本镜像

## 概述

cpu 双核cpu内存
内存 2g内存
20g 硬盘

node由于需要部署除了kubectl的组件还有部署应用，所以内存需要更高。

## 节点配置

## 统一环境配置

### 关闭交换空间

### 避免开机启动交换空间

### 关闭防火墙

### 配置DNS

### 安装DOCKER

### 配置DOCKER加速器

### 安装Kubernate必备工具

### 同步时间

### 修改cloud.cfg

## 单独节点配置

### 配置IP

### 配置主机名