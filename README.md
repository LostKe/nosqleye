# nosqleye
nosql数据库管理工具，目前实现了对Redis、MongoDB的监控功能。
演示：http://106.14.181.95:7004

安装环境：
推荐：centos7（6.*也可以）、MySQL5.7、JDK8
安装步骤：

1、安装初始数据，在MySQL数据库上新建nosql_eye数据库，导入build/nosql_eye.sql文件。新建数据库账户:dev，密码：123456

2、将build/nosql-eye-1.4.jar传输到服务器，java -jar nosql-eye-1.4.jar启动应用即可。如需在后台启动请使用：nohup java -jar nosql-eye-1.4.jar > /dev/null 2>&1 &
