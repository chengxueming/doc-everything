#### 1.注册服务(Service 是如何注册的，systemctl和service有什么关系)
*   概述
    ```
    /usr/lib/systemd/
    /usr/lib/systemd/system/*.service
    ```
*   related command
    ```
    systemctl （显示所有服务并描述）
    systemctl list-unit-files
    systemctl enable  postgresql.service
    systemctl start postgresql.service
    systemctl status postgresql.service(日志）
    ```
*   Link
    *   [在CentOS 7上利用systemctl添加自定义系统服务](https://www.linuxidc.com/Linux/2014-07/104487.htm)
    *   [CentOS7利用systemctl添加自定义系统服务](https://blog.csdn.net/gbenson/article/details/51083817)
#### 2.Pid文件是什么时候产生的，是程序创建的还是linux系统，作用是什么
*   概述
    ```
    /var/run/*.pid
    ```
*   link
    *   [linux/unix下 pid文件作用浅析](https://blog.csdn.net/yinqingwang/article/details/52841744)
#### 3.普通用户使用sudo命令，如何配置权限，还是sudoer都和root一样只是被记录
*   概述
    ```
    sudo passwd
    visudo  #cxm ALL=(ALL)     ALL
    /etc/sudoers
    sudo -l
    *保持用户环境
    *开启部分权限
    如何查看操作日志？
    ```
*   link
    *   [知乎#命令前加sudo执行和用真正的root用户执行有什么区别？](https://www.zhihu.com/question/51746286?from=profile_question_card)
    *   [Linux用户配置sudo权限(visudo)](https://blog.csdn.net/a19881029/article/details/18730671)
    *   [sudo及日志添加](https://blog.csdn.net/xyz846/article/details/26406955)
#### 4.Chmod 421 421 421 分别代表读写执行 root：当前用户：所在组，那么chmod后不同用户执行的效果就不一样，组成员还可以改变组的权限么，root如何给其他用户加权限的
    ```
    owner ownergroup other
    /etc/passwd
    /etc/shadow
    /etc/group
    man 5 shadow
    finger cxm
    groups centos
    id centos
    ```
*   link
    *   [Linux基础知识之用户和用户组以及 Linux 权限管理](https://www.linuxidc.com/Linux/2016-10/136251.htm)
    *   [linux系统644、755、777权限详解](https://blog.csdn.net/u014316462/article/details/52241685)
    *   [linux下查看所有用户及所有用户组](https://www.cnblogs.com/jackyyou/p/5498083.html)
#### 5.ddos 攻击
    ```
    lastb
    last
    /etc/hosts.deny
    ```
*   link
    *   [Linux用户登录记录日志和相关查看命令汇总](https://www.cnblogs.com/lizhaoxian/p/5981029.html)
    *   [发起SSH攻击主机IP地址列表](http://antivirus.neu.edu.cn/scan/ssh.php)
