# 数据库配置
位于根目录下/dbtool/connection.js

var connection = mysql.createConnection({     
  host     : 'localhost',       
  user     : 'root',              
  password : 'password',       
  port: '3305',                   
  database: 'vuesocket' 
});
数据库为根目录下的vuesocket.sql
测试用户：
用户名：a 密码：a
用户名：www 密码：www

# 运行

根目录下npm start