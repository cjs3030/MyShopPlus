# MyShopPlus

## 概述

**MyShopPlus** 项目致力于推广并普及 **微服务架构** 思想，采用全新 **服务网格** 系统打造电商生态级产品。

## 开发工具

工具 | 下载地址 
----|----
Intellij IDEA | https://www.jetbrains.com/idea/download 
SwitchHosts | https://oldj.github.io/SwitchHosts/
FinalShell | http://www.hostbuf.com/ 
Postman | https://www.getpostman.com/downloads/ 
SQLyog | https://sqlyog.en.softonic.com/ 
PicPick | https://picpick.app/zh/download 
亿图图示 | https://www.edrawsoft.cn/edrawmax/ 
亿图导图 | https://www.edrawsoft.cn/mindmaster/ 

## 后端技术

技术 | 说明 
----|----
Spring Boot | 新一代 JavaEE 开发标准 
Spring Cloud Alibaba | 阿里巴巴基于 Spring Cloud 编程模型的微服务生态 
Spring Cloud Alibaba Dubbo | 与 Spring Cloud Alibaba 生态相结合的高性能 Java RPC 框架 
Spring Security oAuth2 | 安全认证和授权框架 
Spring Social | 第三方登录接入框架 
TkMyBatis | 基于 MyBatis 二次开发的轻量级框架，用于简化 MyBatis 操作 
MyBatisGenerator | Maven 插件，用于 MyBatis 相关代码生成 
MybatisCodeHelper | Intellij IDEA 插件，用于 MyBatis 相关代码生成 
PageHelper | MyBatis 分页插件 
Swagger | API 文档生成工具
HikariCP | 数据库连接池 
Docker | 容器化引擎 
Docker Compose | 容器编排工具 
Kubernetes | 容器编排系统 

## 前端技术

技术 | 说明 
----|----
Vue | 前端框架，MVVM 模式的实现者 
Vue CLI | Vue 脚手架，基于 NodeJS 
Vue Router | Vue 路由框架 
Vuex | Vue 全局状态管理框架 
Axios | 前端 HTTP 框架 
Element UI | 饿了么 UI 框架 
Vue Element Admin | 基于 Element UI 的前端后台解决方案 

## 框架集成

集成 | 完成 
----|----
Spring Boot | ✔
Spring Cloud Alibaba | ✔ 
Spring Cloud Alibaba Dubbo | ✔ 
Spring Security oAuth2 | 

## 后台功能清单

### 后台登录

功能 | 完成 
----|----
用户注册 | 
用户登录 | 
获取 Token | 
刷新 Token | 

### 权限管理

角色 | 菜单 
----|----
超级管理员 | 所有菜单权限 
运营人员 | 首页、用户、促销、运营、内容 

功能 | 说明 | 完成 
----|----|----
权限管理 | 添加权限、删除权限、修改权限、以树形结构返回权限 | 
角色管理 | 添加角色、删除角色、更新角色、角色列表、获取角色权限、修改角色权限 | 
成员管理 | CRUD、为成员分配角色、获取成员角色、权限分配、获取权限列表 | 