#### 1.Upstream 是什么，是nginx原生的还是拓展，有什么用
     ```
     upstream webservers {
          server localhost:9000 weight=1;
          server localhost:8000 weight=1;
     }
     server {
        location / {
           proxy_pass        http://webservers;
        }
     }
     ```
* links
  *  [在已经安装Nginx的基础上增加新Nginx-echo模块](https://blog.csdn.net/hb1707/article/details/52510611)
  *  [Nginx的upstream模块和反向代理(一)](http://blog.sina.com.cn/s/blog_70898f3f0100s6uq.html)
  *  [Variables as Value Containers](http://openresty.org/download/agentzh-nginx-tutorials-en.html#01-nginxvariables01)
  *  [Nginx 反向代理、负载均衡、页面缓存、URL重写及读写分离详解](http://blog.51cto.com/freeloda/1288553)
