# env-docker
## mariadb
## redis
## nacos
## rocketmq
## xxljob
## mqtt
## elk

# 命令
## mariadb
```shell
# 启动
docker-compose -f docker-compose.db.yml up -d

# 停止服务
docker-compose -f docker-compose.db.yml stop

# 开启服务
docker-compose -f docker-compose.db.yml start

# 删除服务
docker-compose -f docker-compose.db.yml down

# -v 选项会删除所有匿名卷和数据卷。如果你不使用-v，则卷不会被删除
docker-compose -f docker-compose.db.yml down -v 
# 进入容器
sudo docker exec -it 容器ID /bin/bash
# 登录数据库
GRANT ALL PRIVILEGES ON *.* TO 'root'@'%'WITH GRANT OPTION;
```
