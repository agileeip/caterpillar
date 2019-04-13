# caterpillar


# getting start

 **本地部署**
- 通过git下载源码
- idea、eclipse需安装lombok插件，不然会提示找不到entity的get set方法
- 创建数据库caterpillar，数据库编码为UTF-8
- 执行rapid-admin/db/mysql.sql文件，初始化数据【按需导入表结构及数据】
- 修改application-dev.yml文件，更新MySQL账号和密码
- 在caterpillar目录下，执行mvn clean install


- Eclipse、IDEA运行AdminApplication.java，则可启动项目【rapid-admin】
- rapid-admin访问路径：http://localhost:8080/rapid-admin
- swagger文档路径：http://localhost:8080/rapid-admin/swagger/index.html
- swagger注解路径：http://localhost:8080/rapid-admin/swagger-ui.html
- 账号密码：admin/admin