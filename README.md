# 部署文件
> 部署emq、mysql、redis、elasticsearch、kibana

## 启动

```
cd 到目录下

docker-compose up -d // 后台运行

如果需要进入镜像查看

docker-compose exec emq sh

```

## 简述

这里只是部署了依赖的内容，mqtt和其他服务暂时没有在这里一起部署。

此时再进入mqtt或者account的目录

```
make run

```

就会启动程序