---
layout: cv
title: 游正材 || Skyzc
email:
  url: mailto:youzhengcai@gmail.com
  text: youzhengcai@gmail.com
homepage:
  url: https://www.skyzc.top
  text: https://www.skyzc.top
phone: 15750769828
---

# I'm 游正材

<!--
include contact information from the front matter
Supported arguments:

    - homepage: url, text
        - phone
        - email
-->

{% include cv-contact.html %}

## 👨‍💻&nbsp; 专业技能 Skill points

1. 理解面向对象编程，熟练掌握 Java 编程语言及其相关开发框架的应用。
2. 熟悉 Linux 操作系统，能够在其上进行开发部署项目。
3. 熟悉 SSH、SSM 框架的应用，以及 Tomcat、jetty 等 WEB 容器的应用。 
4. 独立搭建过项目的系统框架，熟练掌握 SpringBoot 开发框架及其应用。 
5. 熟悉关系型数据库MySQL、PostgreSQL，具备一定的数据库设计和优化经验。 
6. 了解前端主流框架 Vue，熟练掌握 JavaScript 及其相关框架。 
7. 熟悉使用 Nginx 的应用。 
8. 熟悉 Git 版本控制工具及协同开发。
9. 熟悉树莓派开发及运用。
10. 熟悉 python 语言及简单爬虫设计， Python Web 开发，能够 Flask 的进行开发。



## 🎓&nbsp; 教育及实习经历  Education & Internship

### **阳光学院** `2020.9 -`

```
福州，福建
```

- 计算机科学与技术

### **厦门知晓物联技术服务有限公司** `2019.3 - 2019.10`

```
厦门，福建
```

- Java 后端开发实习生

### **厦门软件学院** `2017.9 - 2020.6`

```
厦门，福建
```

- 大数据技术与运用

##  🏅&nbsp; 荣誉和奖励 Honor & Award

\- 参加 2020 openEuler 高校开发者大赛，获得二等奖。 `阳光学院, 2021` <br>

\- 参加 2020 Ti 杯电子设计大赛，设计基于树莓派的人脸识别项目，获得福建省三等奖。`阳光学院, 2020` <br>

\- 参与公司项目，负责项目后端开发，并带领项目成果参加 2019 宁波世界数字经济大会。 <br>`厦门知晓物联技术服务有限公司, 2019` <br>

\- 参与设计基于 Java EasyPR 的车牌识别管理系统 Web 端，项目获 2017 年福建省职业技能大赛省赛三等奖。 `厦门软件学院, 2017` <br>

## 🚀 &nbsp; 项目经验 Experience

### **1. Observer - Linux下可扩展的应用可视化配置软件** `2021.07 -`

_[开源地址 ：https://gitee.com/openeuler-competition/summer2021-96](https://gitee.com/openeuler-competition/summer2021-96)_<br>

Observer 是一个适用于 openEuler 的可扩展的应用可视化配置软件，该项目使用 Golang 来进行开发。使用了 Gin Web Framework 来进行开发。通过扫描并读取所需软件的配置文件，抽取相关的配置项目，并显示在 Web 前端页面上。同时除了可视化配置之外，也提供一个“高级配置”，用于直接配置对应的配置文件。

该项目为参加 Summer2021- 开源软件供应链点亮计划  的项目成果，目前仍在开发中，由我个人进行开发并贡献。

该项目是我接触到 Golang 之后的第一个正式的开源项目，在该项目中我加深了我对 Golang 的认识，以及对 Web 开发的认识。并且在开发过程中，得益与之前 Java 的开发经验，让我感受到了技术的一些共通性。

### **2. HopeHome-室内温度智能化监测系统** `2020.12 -`

_[开源地址 ：https://gitee.com/openeuler2020/team-1647788699](https://gitee.com/openeuler2020/team-1647788699)_<br>

HopeHome 是一个基于 “云管边端” 架构的智能温度监测系统，整个系统分为了云、边、端三大节点。云节点使用 SpringBoot 开发负责对边端采集到的数据进行可视化及持久化，部署在 openEuler 上；边节点使用了基于 openEuler 生态构建的 HopeEdge OS ，搭载在 Raspberry Pi 4 Model B 上，作为智能 AP。端节点使用 ESP8266 来进行搭建。

该项目为参加 2020 openEuler 全国高校开发者大赛第 34 题的成果，项目在大赛中获得了二等奖。我在项目中担任队长，负责了整个系统的架构设计以及云节点、边节点的开发工作，以及团队协作管理。该系统目前已开源，并在长期维护中。

在该项目的开发过程中，不仅学习和巩固了很多关于 Python ，SpringBoot 以及操作系统的知识，更是深入的了解了很多关于 Linux , Docker 的知识。

### **3. 财务共享单据难度系数测评系统** `2020.03 -2020.04`

_校企合作外包项目_<br>

该系统是一个基于 SpringBoot 开发的一个财务单据评测系统，主要功能为对员工导入的公司单据（Excel）进行解析识别并且导入到数据库，实现后端界面对数据进行统一管理；并且实现一个单据难度测评系统，能够根据员工自定义的规则模型对导入的单据数据进行难度系数的测算。

在该项目中，主要涉及到 Excel 文件的解析以及大数据量的导入优化和查询优化。

经过该项目的开发，我更加熟悉了 SpringBoot 的开发与运用，以及学到了很多 MySQL 的插入、查询优化，并且还接触到了 Redis 的运用。

### **4. 环境监测可视化系统** `2019.04 -2019.09`

_实习项目_<br>

该项目是一个采用前后端分离架构的空气环境监测系统，后端使用了 Spring Boot 2.1，前端采用 了 Vue 框架。该系统主要功能为管理公司研发的设备、处理设备相关数据，以供研究人员查看与管理。 具有 Web 端以及小程序端。后台是基于 spring boot 的技术框架，安全框架 Apache Shiro，持久层框架 MyBatis,数据库连接 池 Druid，日志管理采用 SLF4J/Log4j，前端使用 Vue。

在项目中，主要负责了后端接口的设计编写，前端交互设计，后期功能维护与修改。

这也是个人参与的第一个基于前后端分离的项目，在项目完成过程中学到了很多新知识，以及对项目的整个开发流 程更加了解。 更深入的学习了 Vue 框架，了解了在前后端分离项目中的使用。 联合中国科学院环境环境研究所所参加宁波 2019 世界数字经济大会。

##  🛰  &nbsp; 链接 Links

个人博客：[https://skyzc.top](https://skyzc.top)

Github : [https://github.com/SkyzcYou](https://github.com/SkyzcYou)

Gitee : [https://gitee.com/SkyzcYou](https://gitee.com/SkyzcYou)



<!-- ### Footer

Last updated: August 2021-->
