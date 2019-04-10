1. 找到redis的配置文件

找到`requirepass`参数
```
# requirepass foobared
# 修改为
requirepass myRedisPassword
```

使用redis-cli登录
> redis-cli -h 127.0.0.1 -p 6379 -a myRedisPassword

也可以这两个命令配合使用校验密码
> redis-cli -h 127.0.0.1 -p 6379  
> auth myRedisPassword

2. 使用命令修改

> config set requirepass myRedisPassword

> config get requirepass

此种方式仅一次有效，下次启动还会使用配置文件中的配置

3. 主从配置-从节点密码

从节点在配置文件找到masterauth参数
```
#masterauth  mstpassword
```
