# 超市管理系统简介 java308

## 项目概述

本项目是基于SpringBoot开发的超市管理系统，采用前后端分离的设计模式，实现了商品管理、库存管理、会员管理、人事管理和销售管理等一系列功能。

## 技术栈

- 后端：SpringBoot、Mybatis-Plus、MySQL、Redis
- 前端：Vue、Element-ui

## 功能模块

### 系统角色

- 管理员（Admin）
- 销售（Sales people）

### 管理员功能

- 商品管理：创建商品分类、创建商品、创建积分商品、查看销售统计
- 库存管理：创建仓库、商品出库、商品入库、创建供货商、查看仓库存储明细
- 会员管理：录入会员
- 人事管理：创建部门、新建员工、指定职务
- 销售管理：查看销售记录、查看兑换记录

### 销售功能

- 销售管理：购物结账、积分兑换、查看销售记录、查看兑换记录
- 会员管理：录入会员信息

## 运行环境

- 操作系统：Win10/11
- 开发工具：ideaIU-2022.3.3.win
- 开发语言：Java (jdk-8u371)、Vue(node.js 18.20)
- 项目管理工具：apache-maven-3.9.4
- 数据库：MySQL 8.0、Redis 7.0.10

## 部署步骤

1. 执行目录中的sql文件，Mysql用户名密码为 root / root
2. 启动Redis
3. 解压项目压缩包
4. 使用IDEA导入项目
5. 等待Maven下载Jar包，下载完成后点击启动项目
6. 运行前端工程：npm run dev

## 目录结构

```
本项目目录结构如下：
- src
  - main
    - java
      - com.example.demo
        - controller
        - service
        - mapper
        - pojo
    - resources
      - application.properties
      - mybatis-config.xml
  - test
- pom.xml
```

## 核心亮点

- 基于SpringBoot框架，系统性能稳定，易于维护和扩展
- 前后端分离，分工明确，方便不同团队协同开发
- 采用Redis作为缓存，提高系统运行效率
- Mybatis-Plus简化了数据库操作，提高开发效率
- Vue和Element-ui提供了丰富的界面组件，易于构建友好的用户界面

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img12.360buyimg.com/ddimg/jfs/t1/345849/14/7090/39429/68d3ed37F345528ec/9d9b77308fbf5474.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/330935/2/16926/36194/68d3ed37F88711ff3/37042f0f1319b203.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/288240/7/23773/32996/68d3ed37Fd20882ca/4f4ab644b401d765.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/351415/33/6949/21088/68d3ed37Fa209fdd5/86e94824588f984e.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/348841/10/6988/26397/68d3ed38F704aacd5/7e5d48df3f87f940.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/340831/27/14654/24163/68d3ed38Fa8001457/fa25efdd04ab8392.jpg)

