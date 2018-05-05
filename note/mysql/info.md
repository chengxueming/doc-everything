#### 1.Mysql 如何权限管理的（host，username connect-ip三个维度），不同用户看到的数据库不一样么，FLUSH PRIVILEGES;和grant时分别做了什么
*   link
    *   [MySQL用户权限管理详解](http://www.jb51.net/article/87979.htm)
#### 2.如何快速查看整个数据库每个表的行数和存储
    ```
    SELECT TABLE_NAME,DATA_LENGTH+INDEX_LENGTH,TABLE_ROWS,concat(round((DATA_LENGTH+INDEX_LENGTH)/1024/1024,2), 'MB') as data FROM TABLES WHERE TABLE_SCHEMA='mysql';
    ```
*   link
    *   [如何查看mysql数据库中各个表的大小](https://blog.csdn.net/dufufd/article/details/77604620)
    *   [mysql查询表的数据大小](https://www.cnblogs.com/diandiandidi/p/5582309.html)
