# 项目名称

servlet徐州旅游网站管理系统源码+论文三篇+答辩ppt+查重报告+答疑

# 系统介绍
4.2.1 前台界面

显示界面,其功能如下:

(1)徐州旅游景区的信息显示:显示最近的动态的旅游景点,徐州最近的相关新闻,等等。

(2)信息交互,可以提交一个消息函数,可以得到有关旅游景点和建议的网站系统。

前台界面设计如下图所示：

图4-2 前台设计图

 

4.2.2 后台管理

管理的背景下,其功能如下:

(1)个人信息管理:管理员登录和个人信息,密码,和改变;

(2)信息管理:上传的徐州新闻信息,并可以删除和编辑以前的消息;

(3)景区管理:徐州各景点的执行添加、删除和编辑;

(4)留言板管理:用户信息的查看和删除管理;

(5)通过照片管理:前台页面显示点圆图。

后台管理界面设计如图4 - 3所示：

图4-3 后台设计图

# 环境需要

1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。\
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;\
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可\
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS； \
5.数据库：MySql 5.7版本；\
6.是否Maven项目：否；

# 技术栈

1. 后端：Spring+SpringMVC+Mybatis\
2. 前端：JSP+CSS+JavaScript+jQuery

# 使用说明

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；\
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;\
若为maven项目，导入成功后请执行maven clean;maven install命令，然后运行；\
3. 将项目中springmvc-servlet.xml配置文件中的数据库配置改为自己的配置;\
4. 运行项目，在浏览器中输入http://localhost:8080/ 登录

# 高清视频演示

https://www.bilibili.com/video/BV1YL4y1w72d/

​