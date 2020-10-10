# mysql

- download: community servo；

- 解压，然后在主文件夹下，创建my.ini (内容百度),注意改变里面的地址；

- 设置环境变量，路径最好不要有中文；

- mysqld –-initialize，（注意：不用先创建data）

- 安装MySQL服务。

  还是在bin路径下输入：

  ```
  mysqld install
  ```

- 启动服务：net start mysql

- 登录密码：mysql -u root -p

- 卸载MySQL。sc delete mysql

- desc查看表结构的详细信息：desc table_name；

