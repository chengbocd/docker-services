# docker-services 

## 配置本机环境简易版
.env环境配置
data目录数据映射

## 配置文件
cp .env.local .env

## 拉取镜像
docker compose pull

## 镜像地址
DockerHub镜像仓库	镜像加速器地址
Docker镜像加速站	https://hub.uuuadc.top/
docker.1panel.live
hub.rat.dev
DockerHub 镜像加速代理	https://docker.anyhub.us.kg
https://docker.chenby.cn
https://dockerhub.jobcher.com/
镜像使用说明	https://dockerhub.icu
Docker镜像加速站	https://docker.ckyl.me
镜像使用说明	https://docker.awsl9527.cn
镜像使用说明	https://docker.hpcloud.cloud
镜像使用说明	https://dislabaiot.xyz
Docker Proxy 镜像加速（来源地址）	https://dockerpull.com
AtomHub 可信镜像仓库平台 （只包含基础镜像，共336个）	https://atomhub.openatom.cn
DaoCloud 镜像站	https://docker.m.daocloud.io

## 镜像上传到阿里云镜像
https://zhuanlan.zhihu.com/p/669796818
目前our_image全部是 arm64

docker tag abe5b73b628f registry.cn-hangzhou.aliyuncs.com/our_image/mysql:8.0.39
docker push registry.cn-hangzhou.aliyuncs.com/our_image/mysql:8.0.39

docker tag f54100876780 registry.cn-hangzhou.aliyuncs.com/our_image/kafka:3.5.2
docker push registry.cn-hangzhou.aliyuncs.com/our_image/kafka:3.5.2

docker tag b68c7793ea72 registry.cn-hangzhou.aliyuncs.com/our_image/kibana:8.15.0
docker push registry.cn-hangzhou.aliyuncs.com/our_image/kibana:8.15.0

docker tag 7f156f60be2a registry.cn-hangzhou.aliyuncs.com/our_image/elasticsearch:8.15.0
docker push registry.cn-hangzhou.aliyuncs.com/our_image/elasticsearch:8.15.0

docker tag da3096552709 registry.cn-hangzhou.aliyuncs.com/our_image/logstash:8.15.0
docker push registry.cn-hangzhou.aliyuncs.com/our_image/logstash:8.15.0

docker tag 35042a754d27 registry.cn-hangzhou.aliyuncs.com/our_image/postgres:16
docker push registry.cn-hangzhou.aliyuncs.com/our_image/postgres:16

docker tag 25c710c0f9d3 registry.cn-hangzhou.aliyuncs.com/our_image/etcd:latest
docker push registry.cn-hangzhou.aliyuncs.com/our_image/etcd:latest

docker tag 7ec24066439f registry.cn-hangzhou.aliyuncs.com/our_image/redis:7.4-alpine
docker push registry.cn-hangzhou.aliyuncs.com/our_image/redis:7.4-alpine


docker tag eb433c5673fb registry.cn-hangzhou.aliyuncs.com/our_image/mongo:latest
docker push registry.cn-hangzhou.aliyuncs.com/our_image/mongo:latest
