---
title: HBase+SpringBoot实战分布式文件存储
date: 2018-09-21 18:27:21
tags:
  - 实战
  - 后端开发
  - 慕课网
  - 2018
  - HBase
  - 大数据
categories:
  - 大数据
keywords: HBase+SpringBoot实战分布式文件存储
---
![image](http://szimg.mukewang.com/5acc60d80001ef7605400300-360-202.jpg)

第1章 课程简介
课程简介及期望学习本门课程可以达到的目标。对本门课程所用到的技术进行概览

1-1 导学
1-2 课程技术分析
第2章 HBase简介与环境部署
介绍HBase是什么，能做什么，有哪些优缺点，适用于哪些应用场景，与常用关系数据库有什么不同。并配置安装Hadoop伪分布式集群，HBase伪分布式集群。为后面章节实战测试提供环境支持。
<!-- more -->
<blockquote class="blockquote-center">
请支持原版！课程官方链接：https://www.cniao5.com/course/lessons/10076</blockquote>
</blockquote>

2-1 HBase简介及其在大数据生态圈的位置
2-2 HBase数据存储模型及与关系型数据库的区别
2-3 Hadoop伪分布式集群安装
2-4 HBase伪分布式集群安装
2-5 HBase基础架构
2-6 HBase阶段小结
第3章 HBase原理与实战
介绍HBase基础原理，以读写流程为引，结合前面集群部署所展现的HBase三大模块，讲解HBase各个模块之间的协作，帮助我们了解HBase的运行机制。并对HBase进行实战操作，讲解基本的shell命令及java api。重点讲解如何通过过滤器筛选数据...

3-1 HBase写流程
3-2 HBase读流程
3-3 HBase模块协作
3-4 HBase实战：Shell命令实战
3-5 HBase实战：Java Api实现HBase连接类
3-6 HBase实战：Java Api实现HBase操作类
3-7 HBase实战：用过滤器筛选数据
3-8 HBase阶段小结
第4章 HBase进阶
讲解HBase的高级特性，常用的优化策略，协处理器等，并实战开发协处理器，将开发的协处理器加载到HBase测试环境，验证其功能

4-1 HBase优化策略一：服务端优化策略
4-2 HBase优化策略二：常用优化策略
4-3 HBase优化策略三：读写优化策略
4-4 HBase协处理器简介
4-5 HBase实战：开发RegionObserver协处理器
4-6 HBase实战：HBase协处理器加载
第5章 容灾与监控
HBase容灾策略的简要介绍，配合命令演示如何对数据进行备份和恢复。简要介绍HBase的监控重要性以及常用的监控方式。实战开发通过jmx获取HBase运行时数据，监控集群状态

5-1 HBase备份与恢复
5-2 HBase监控简介
5-3 Hadoop JMX监控实战
5-4 HBase JMX监控实战
第6章 Phoenix & Sqoop
HBase相关工具的介绍和使用，重点讲解Phoenix和Sqoop。并对两者进行实战操作。

6-1 Phoenix简介
6-2 Phoenix安装
6-3 Phoenix实战：shell命令操作Phoenix
6-4 Phoenix实战：java jdbc操作Phoenix
6-5 通过mybatis操作Phoenix
6-6 通过mybatis操作Phoenix
6-7 Sqoop简介
6-8 Sqoop数据导入实战
6-9 课程小结
第7章 需求分析与技术选型
对象存储服务项目的需求分析及技术选型

7-1 老板提出一个需求
7-2 技术选型
第8章 功能梳理与方案设计
对象存储服务功能点梳理以及实现方案的设计，讨论两种设计方案的优缺点，进行正式开发前期准备工作。

8-1 功能梳理和数据库设计
8-2 文件存储设计方案一
8-3 文件存储设计方案二
第9章 子模块-数据库操作模块
hos服务基础数据库选用mysql，实现基于Mybatis的对mysql数据库的操作模块

9-1 Zookeeper安装与HBase配置优化
9-2 Hos开发逻辑梳理
9-3 Hos模块划分及mybatis配置
第10章 子模块-用户管理模块
Hos服务用户管理模块开发，包含对用户的增删改查操作

10-1 Hos用户管理模块开发1
10-2 Hos用户管理模块开发2
第11章 子模块-权限管理模块
Hos服务权限管理模块开发，包含对Token的增删该查以及授权操作

11-1 Hos权限管理模块开发1
11-2 Hos权限管理模块开发2
第12章 子模块-文件管理模块
Hos服务核心模块 文件管理模块开发，包含Bucket的增删改查以及对设计方案一中 HBase相关的操作。

12-1 Bucket管理模块开发
12-2 HDFS和HBASE操作类1
12-3 HDFS和HBASE操作类2
12-4 Hos文件管理模块实体类开发
12-5 Hos创建删除Bucket方法开发
12-6 Hos上传文件方法开发
12-7 Hos获取文件方法开发
12-8 Hos删除文件及列出文件方法开发
第13章 子模块-接口模块
Hos服务接口模块的开发，完成登录认证，权限验证以及各个功能的restful API

13-1 Hos服务登陆验证
13-2 Hos服务web权限配置类开发
13-3 Hos服务用户及权限管理接口开发
13-4 Hos服务文件管理接口开发
13-5 Hos服务API接口测试
第14章 子模块-SDK模块
Hos服务SDK模块开发及测试

14-1 SDK模块HosClient类开发
14-2 SDK模块HosClient功能开发
14-3 SDK模块测试
第15章 课程总结
对整个课程的所用到的理论，技术做一个简单的回顾总结，提出优化的空间

15-1 课程总结
本课程已完结

<blockquote class="blockquote-center">声明：此资源由下载街博客 收集整理于网络，如有侵权，请联系巨菜站删除处理。</blockquote>

<div id="jspay" sid="HxNS01A0954" style="display:none">HxNS01A0954</div>
<script type="text/javascript" src="https://www.fageka.com/j.js"></script>
<script type="text/javascript" src="https://www.fageka.com/f.js" charset="utf-8"></script>
