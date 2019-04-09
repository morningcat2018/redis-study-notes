
src/redis-server

正常启动日志
```log

➜  redis-5.0.4 src/redis-server
12225:C 09 Apr 2019 13:27:19.098 # oO0OoO0OoO0Oo Redis is starting oO0OoO0OoO0Oo
12225:C 09 Apr 2019 13:27:19.098 # Redis version=5.0.4, bits=64, commit=00000000, modified=0, pid=12225, just started
12225:C 09 Apr 2019 13:27:19.098 # Warning: no config file specified, using the default config. In order to specify a config file use src/redis-server /path/to/redis.conf
12225:M 09 Apr 2019 13:27:19.100 * Increased maximum number of open files to 10032 (it was originally set to 256).
                _._                                                  
           _.-``__ ''-._                                             
      _.-``    `.  `_.  ''-._           Redis 5.0.4 (00000000/0) 64 bit
  .-`` .-```.  ```\/    _.,_ ''-._                                   
 (    '      ,       .-`  | `,    )     Running in standalone mode
 |`-._`-...-` __...-.``-._|'` _.-'|     Port: 6379
 |    `-._   `._    /     _.-'    |     PID: 12225
  `-._    `-._  `-./  _.-'    _.-'                                   
 |`-._`-._    `-.__.-'    _.-'_.-'|                                  
 |    `-._`-._        _.-'_.-'    |           http://redis.io        
  `-._    `-._`-.__.-'_.-'    _.-'                                   
 |`-._`-._    `-.__.-'    _.-'_.-'|                                  
 |    `-._`-._        _.-'_.-'    |                                  
  `-._    `-._`-.__.-'_.-'    _.-'                                   
      `-._    `-.__.-'    _.-'                                       
          `-._        _.-'                                           
              `-.__.-'                                               

12225:M 09 Apr 2019 13:27:19.101 # Server initialized
12225:M 09 Apr 2019 13:27:19.101 * Ready to accept connections
^C
12225:signal-handler (1554787951) Received SIGINT scheduling shutdown...
12225:M 09 Apr 2019 13:32:31.118 # User requested shutdown...
12225:M 09 Apr 2019 13:32:31.118 * Saving the final RDB snapshot before exiting.
12225:M 09 Apr 2019 13:32:31.121 * DB saved on disk
12225:M 09 Apr 2019 13:32:31.121 # Redis is now ready to exit, bye bye...
```