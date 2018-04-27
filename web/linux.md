# linux
## 笔记 
* 用户管理
  * w
  ```
  00:28:25 up  1:03,  3 users,  load average: 0.00, 0.01, 0.05
  USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
  root     pts/1    111.199.184.247  23:39   36:41   0.17s  0.09s /usr/bin/docker-current pull mysql:5.6
  root     pts/2    111.199.184.247  00:21    1.00s  0.03s  0.00s w
  root     pts/3    111.199.184.247  00:26    2:07   0.01s  0.01s -bash
  ```
  pkill -kill -t pts/3 强制用户下线

## 文章列表
- [rm 添加垃圾桶](https://linux.cn/article-9425-1.html)
- [Linux创建用户、设置密码、修改用户、删除用户命令](https://www.linuxidc.com/Linux/2017-06/144916.htm)
- [Linux为普通用户添加sudo权限](https://www.linuxidc.com/Linux/2017-01/139361.htm)
- [勒索病毒](https://pastebin.com/irRUf14s)

## pgsql安装
- [CentOS下，yum安装PostgreSQL](https://blog.csdn.net/gaojinshan/article/details/40980653)
- [PostgreSQL安装详细步骤（linux)](https://www.cnblogs.com/qiyebao/p/4562557.html)
```
su postgres
sudo chown postgres /var/lib/pgsql/data
initdb /var/lib/pgsql/data
postmaster -D /var/lib/pgsql/data
createdb weather
```
