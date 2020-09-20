MySQL的基本使用
=========================
#### 连接到MySQL客户端：

    shell> mysql -h localhost -P 3306 -u<username> -p<password>
    
注意使用这种方法会出现一个warning提示在命令行输入了密码，不安全。可以将密码项留白而后后面会出现`Enter Password：`

#### 查看当前用户：  

    shell> whoami
   
#### 断开连接：
Ctrl+D or exit  
#### 撤销命令：
Ctrl+C or \c  

一旦连接到命令行指示符之后，可以执行SQL语句，可以以;, \g, \G结尾。  
\g：输出水平显示。  
\G：输出垂直显示。
