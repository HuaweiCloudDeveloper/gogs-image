# gogs部署指南

## ‌一、环境准备

### 一、更新系统

```bash
yum -y update  
yum -y upgrade
```

## ‌二、安装docker

#### EulerOS2.0
参考：[安装Docker](https://support.huaweicloud.com/bestpractice-hce/hce_bp_0002.html)

## ‌三、拉取镜像和创建容器

### 1.拉取镜像
```bash
docker pull apache/gogs:latest
```

### 2.创建容器
```bash
docker run -d \
  --name gogs \
  -p 3000:3000 \
  -p 10022:22 \
  -v /opt/gogs/data:/data \
  -e GOGS_RUN_USER=git \
  --restart always \
  gogs/gogs:latest
```