window

```
cd到ngnix目录

start nginx                             启动
nginx.exe                               启动
tasklist /fi "imagename eq nginx.exe"   查看nginx服务
netstat -ano | findstr 0.0.0.0:80       检查80端口是否被占用
netstat -ano | findstr "80"             检查80端口是否被占用
nginx.exe -t                            测试配置文件
nginx.exe -t -c conf/default.conf       测试制定配置文件 
start nginx.exe -c conf/default.conf    载入指定配置文件 
nginx -s reload                         重新加载Nginx配置文件 重新启动nginx
nginx -s stop                           快速停止nginx
nginx -s quit                           完整有序的停止nginx

```

mac

```
cd到ngnix目录

nginx -v                                     显示版本信息并退出
nginx -V                                     显示版本和配置选项信息，然后退出
sudo nginx                                   启动
sudo nginx -t                                检测配置文件是否有语法错误，然后退出
nginx -T                                     检测配置文件是否有语法错误，转储并退出
nginx -q                                     在检测配置文件期间屏蔽非错误信息
sudo nginx -s reload                         重新加载Nginx配置文件 重新启动nginx
nginx -s reopen                              重启Nginx
sudo nginx -s stop                           快速停止nginx
sudo nginx -s quit                           优雅的停止nginx
nginx -p prefix                              设置前缀路径(默认是:/usr/share/nginx/)
nginx -c filename                            设置配置文件(默认是:/etc/nginx/nginx.conf)
nginx -g directives                          设置配置文件外的全局指令
nginx -?,-h                                  打开帮助信息
killall nginx                                杀死所有nginx进程
sudo vim /usr/local/etc/nginx/nginx.conf     编辑nginx配置文件
⬆️+ i（先要退出编辑状态）                     编辑nginx命令
⬆️+ w（先要退出编辑状态）                     保存nginx命令
⬆️+ wq（先要退出编辑状态）                    保存退出nginx命令
⬆️+ q（先要退出编辑状态）                     退出nginx命令
esc                                          退出nginx编辑命令

```
