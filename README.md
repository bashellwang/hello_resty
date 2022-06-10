```
启动 nginx
nginx -p ./ -c conf/nginx.conf

查看服务进程
ps -ef | grep nginx

停止 nginx
nginx -p ./ -s stop

请求服务
curl 127.0.0.1:8080

重启 nginx
nginx -p ./ -s reload
```
