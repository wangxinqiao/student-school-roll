# ssm学生学籍管理系统

## 项目介绍
SSM项目-学生学籍管理系统。该项目分管理员、老师、学生三种用户角色。每种角色分别对应不同的菜单；

以下分别介绍各个角色对应的功能模块：

### 管理员角色：
- 用户登录和退出
- 权限控制
- 系统管理
- 专业管理
- 班级管理
- 学生管理
- 老师管理
- 课程管理
- 开课管理
- 用户管理
### 老师角色：
- 老师管理
- 成绩管理
- 学生查询
### 学生角色：
- 学生管理
- 选课管理
- 成绩查询

## 技术路线
- 开发工具：IDEA 2020.1

- 技术框架：Spring、SpringMVC、MyBatis
- Web容器：Tomcat 8.5.7
- 数据库：MySQL 5.7
- 前端UI框架：LayUI

- 项目管理：Maven 3.6.3

## 使用说明
1. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，下载所需jar包；

2. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
3. 将项目中application.yml配置文件中的数据库配置改为自己的配置
4. 配置tomcat，然后运行项目，输入localhost:8080 登录
5. 管理员账户:admin  密码:123456
老师账户：zhangping 密码：123456

学生账户：0001      密码：123456

## 运行截图
