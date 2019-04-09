
1. 下载

从[官网下载](https://redis.io/)redis源码包；

也可以在redis的[github页面](https://github.com/antirez/redis/releases)进行下载


2. 安装
```
$ wget http://download.redis.io/releases/redis-5.0.4.tar.gz
$ tar xzf redis-5.0.4.tar.gz
$ cd redis-5.0.4
$ make


```

3. 启动

```
$ src/redis-server
```

后台启动
```
$ nohup src/redis-server > redis.file 2>&1 &
```

4. 客户端（命令行）
```
$ src/redis-cli
redis> set foo bar
OK
redis> get foo
"bar"
```

5. 图形化客户端

RDM(RedisDesktopManager) https://github.com/uglide/RedisDesktopManager/releases

RedisClient https://github.com/caoxinyu/RedisClient/releases

RedisStudio (Redis GUI Client) https://github.com/cinience/RedisStudio


