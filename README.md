# BookStore
书城项目



一.开发环境介绍
1.IDEA 2017 
2.jdk 8 以上
3.mysql 8.0
4.tomcat 3.9


二.部署介绍
1.创建数据库 create.sql

2.插入商品数据(图片在WebContent/bookCover文件夹下)
	格式如下:
	insert into products(id,name,category,price,pnum,imgurl) values("1","算法导论","计算机","25",100,"/bookcover/101.jpg");

3.使用IDEA打开文件

4.配置配置文件
  Uitls中的C3P0Utils的数据库密码和用户设为自己电脑上的数据库用户和密码。

5.配置IDEA的tomcat
 同时将classes文件设为Web-INF下的classes文件，添加jar or directory 在同文件夹的lib目录下。
 将libs文件夹中的文件 as library
6.运行。
