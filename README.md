# PHPMyAdmin

phpMyAdmin 是一个以PHP为基础，以Web-Base方式架构在网站主机上的MySQL的数据库管理工具，让管理者可用Web接口管理MySQL数据库。借由此Web接口可以成为一个简易方式输入繁杂SQL语法的较佳途径，尤其要处理大量数据的导入及导出更为方便。其中一个更大的优势在于由于phpMyAdmin跟其他PHP程序一样在网页服务器上运行，但是您可以在任何地方使用这些程序产生的HTML页面，也就是于远程管理MySQL数据库，方便的创建、修改、删除数据库及数据表。也可借由phpMyAdmin创建常用的php语法，方便编写网页时所需要的sql语法正确性。

## 版本

4.4.5

## 部署

##### 点击“部署最新版本“，开始部署phpMyAdmin容器

![create "PHPMyAdmin" service](https://dn-daoweb-resource.qbox.me/phpmyadmin/1-1-1.png)

##### 绑定您想管理的MySQL数据库实例，并设置服务别名为“__mysql__”

![bind MySQL service](https://dn-daoweb-resource.qbox.me/images/phpmyadmin/1-2.png)

##### 根据您的MySQL实例参数，在启动页面的填写相应的用户名和密码

![set username/password](https://dn-daoweb-resource.qbox.me/images/phpmyadmin/1-3.png)

![login PHPMySQL](https://dn-daoweb-resource.qbox.me/phpmyadmin/1-5-1.png)
