![logo](screenshots/logo.png)
# FS-Blog 
# 基于 Spring Boot 的个人博客
[![Build Status](https://www.travis-ci.org/JamesZBL/FS-Blog.svg?branch=master)](https://www.travis-ci.org/JamesZBL/FS-Blog)
[![LICENSE](https://img.shields.io/badge/license-Apache%202-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
![GitHub release](https://img.shields.io/github/release/jameszbl/fs-blog.svg)
### 1. 涉及技术及工具

- 核心框架：SpringBoot
- ORM 框架：MyBatis
- MyBatis 工具：MyBatis Mapper 
- MVC 框架：Spring MVC
- 模板引擎：Freemarker
- 编译辅助插件：Lombok
- CSS 框架：BootStrap 4.0
- Markdown 编辑器：Editor.md
- 数据库：MySQL
- 构建工具：maven


### 2. 效果图

#### 2.1 首页
![首页](screenshots/home.png)

#### 2.2 博客列表页
![文章列表](screenshots/posts.png)


#### 2.3 博客阅读页
![文章阅读](screenshots/blog.png)


#### 2.4 个人简历页
![个人简历](screenshots/resume.png)


#### 2.5 文章编辑页
![编辑器](screenshots/editor.png)


### 3. 构建及运行

#### 3.1 服务器环境

- 安装 ``MySQL``
- 安装 ``maven``
- 在项目目录下运行 ``maven clean build``，生成的 jar 包位于 ``build/libs`` 目录下，使用 ``java -jar .../fsblog.jar`` 运行
- 在 ``application-dev.yml`` 中配置数据库用户名和密码，默认为：``username: root password: root``
- 默认自动创建数据库、数据表并自动导入初始数据，同样在``application-dev.yml``中配置
- 后台管理默认用户名为 ``admin``，密码为 ``123456``

#### 3.2 开发环境

- 可直接在 IntelliJ IDEA 或 Eclipse 中打开项目进行二次开发

### 4. 联系方式

- Email （简体中文）：ishiningway@qq.com
- Email （English）：ishiningway@gmail.com


### 5. 相关链接

- 原作者链接 [FS-Blog](https://github.com/JamesZBL/FS-Blog)

- 我的个人博客 [ishiningways' Blog](https://ishiningway.blogspot.com/)

### 6. 代码修改  

- 请在Git仓库提交记录查看

### 7. 开源协议

[![LICENSE](https://img.shields.io/badge/license-Apache%202-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

Copyright (c) 2017-2020, ishiningway,ALL rights reserved.