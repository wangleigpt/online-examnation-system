# 文档介绍
## 文档目的
通过对系统所采用的技术，数据结构，功能架构等主要信息的介绍，使软件的管理者和使用者能够有效合理的对软件功能进行使用，维护以及后续开发。
## 文档范围
文档主要包括以下几项内容：
### 功能需求分析
1. 前台需求分析
2. 后台需求分析 
### 系统介绍
1. 运行环境
2. 权限管理
3. 模块结构
4. 数据库设计
### 使用流程
1. 管理员
2. 教师
3. 学生
# 功能需求分析
学员考试系统主要用于四海对学员的日常训练以及定期考评，是一个面向内部人员的封闭系统，需要在权限分层上做较为完善地划分，系统主要面向两类群体——四海教师和学员，学员通过注册进入系统进行学生端的日常训练，定期考试和历史成绩查看，教师通过注册进入系统完成教师端的出题，批改以及成绩的数据统计，因此该系统需要前台，后台相分离，共用一套数据库完成操作。
## 前台
前台主要面向四海学员，基本需要以下几项功能：
1. 注册和登录功能
2. 在线练习功能
3. 参加考试功能
5. 回顾已考试卷功能
4. 查询历史成绩功能
## 后台
后台主要面向四海教师，基本需要以下几项功能：
1. 注册和登录功能
2. 学员管理功能
3. 课程管理功能
4. 题库管理功能
5. 创建考试功能
6. 批改试卷功能
7. 查询成绩功能
# 产品介绍
## 运行环境
1. OS：Ubuntu 16.04.2 LTS (GNU/Linux 4.4.0-63-generic x86_64)
2. web server：apache-tomcat-8.5.12
3. JDK：1.8.0_121
4. 数据库：mysql_5.7.17-1ubuntu16.10_amd64
##权限管理
