# SSH_PersonInformation

##基于SSH的个人信息管理系统


----------
**系统架构：**

前端使用Bootstrap，后端采用Struts2+Spring3+Hibernate4集成框架，数据库使用MySQL数据库搭建的个人信息管理系统。


----------

**功能模块：**

 - 个人用户的登录及注册，登录成功后对个人信息的修改以及头像的更换。（其中使用了拦截器，只有登录后才可以进行相关操作，否则只能访问主页。）
 - 对通讯录中联系人的增删改查，支持通过姓名或者手机号进行模糊查询。(支持批量删除)
 - 对日程安排的增删改查。
 - 对文件的操作（实现文件从本地上传功能，将文件信息传到数据库中并在页面上显示）
----------

请点击该链接在CSDN博客上查看项目具体介绍：[基于SSH的个人信息管理系统](http://blog.csdn.net/hlk_1135/article/details/66472207)
