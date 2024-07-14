# 这是我的第一个web项目

## 图书借阅管理系统   
version：v 1.0   
框架： mybatis、servlet、thymeleaf   
服务器容器：tomcat 10.1.10   
jdk17   
前端页面为魔改下载的页面
### 已实现的功能  
* 管理员账号的登录，使用cookie实现“记住用户”功能，退出登录后清除cookie
* 首页显示用户头像，学生数量统计、书籍数量统计、借阅数量统计
* 功能模块：借阅管理、书籍管理、学生列表
* 借阅管理：显示借阅信息，包括书籍信息、借阅时间、借阅学生信息，
添加借阅信息（已经被借阅的书籍无法被借阅，但一个学生同时可以借阅多本书籍
归还功能删除借阅信息）
* 书籍管理：显示书籍的信息、借阅状态，以及删除相应书籍信息
* 学生列表：显示所有学生的信息列表  

### 待完善功能
* 忘记密码功能和注册功能
* 可以添加删除处于正在被借阅状态的书籍时500状态码跳转页面或提示功能
* 非法路径404页面
* 学生信息管理功能，包括对学生信息的增删改查功能
* 其他待新增功能

2024/0715 By@renai