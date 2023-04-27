## Laradock

> 自用 laradock master 与主库保持一致，hzz分支自用

## 常用命令
```
# 按需启动服务容器
docker-compose up -d nginx mysql57 php-fpm82

# 修改了yml文件后，重新创建docker container
docker-compose up -d --force-recreate nginx

# 进入指定容器bash
docker-compose exec nginx bash
```
