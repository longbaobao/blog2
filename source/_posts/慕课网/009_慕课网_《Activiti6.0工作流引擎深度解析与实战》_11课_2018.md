---
layout: 后端开发
title: Activiti6.0工作流引擎深度解析与实战
date: 2018-09-17 16:40:13
tags:
  - 后端开发
  - 实战
  - Activiti6.0
  - 慕课网
categories:
  - 后端开发
keywords: Activiti6.0工作流引擎深度解析与实战
---
第1章 课程介绍（提供问答区答疑解惑）
本课程将系统且深入源码讲解Activiti6.0工作流引擎的使用、配置、核心api以及BPMN2.0规范、数据库设计及模型映射，Spring Boot2.0集成，工作流平台搭建、部署与运维等，通过本课程的学习，你将切实学会Activiti6.0工作流引擎开发，大大提升自己的业务建模能力，技术架构能力，开源库研究能力，流程梳理能力，从而进阶为Jav...

1-1 课程导学
第2章 工作流入门
本章首先介绍了工作流是什么，工作流技术选型，然后带大家快速体验activiti6.0，让大家在最短的时间内体验工作流系统的操作过程，对activiti工作流有个感性的认识。
<!-- more -->
2-1 本章概述
2-2 工作流介绍
2-3 工作流引擎技术选型
2-4 Activiti6.0快速体验-部署环境介绍
2-5 Activiti6.0快速体验-部署环境实操
2-6 Activiti6.0快速体验-流程体验
第3章 Activiti6.0源码初探
本章带大家对Activiti6.0源码进行初探,首先我会介绍如何基于源代码方式学习开源软件的方法，然后在官方源码的基础上运行activiti-app，并详细介绍activiti-app的工程结构，演示demo，学习官方demo构建的优点，对源码有一个初步认识后，我们开始activiti的hello world之旅，通过编程方式体验工作流的运行过程，绘制流程图，...

3-1 本章概述
3-2 Activiti6.0源码初探-概览与获取
3-3 Activiti6.0源码初探-engine
3-4 Activiti6.0源码初探-模块介绍
3-5 Activiti6.0源码初探-activiti-app运行
3-6 Activiti6.0源码初探-WebConfigurer
3-7 Activiti6.0源码初探-helloword-1
3-8 Activiti6.0源码初探-helloword-2
3-9 Activiti6.0源码初探-helloword_idea-1
3-10 Activiti6.0源码初探-helloword_idea-2
3-11 Activiti6.0源码初探-helloword_idea-3
第4章 Activiti6.0引擎配置
本章为大家介绍Activiti6.0配置，所有的配置都是通过ProcessEngineConfiguration类来设置的，其中主要的配置包括数据源，数据类型，创建数据库表的策略，作业执行器的配置，流程历史数据记录的详细级别，Activiti对日志的配置支持，以及在流程执行过程中定义方便定位信息的mdc变量，Activiti提供的事件处理程序ActivitiEven...

4-1 本章概述
4-2 创建流程引擎配置-config_samples
4-3 创建流程引擎配置-archetype
4-4 数据库配置-dbconfig
4-5 数据库配置-dbconfig_code
4-6 日志记录配置-logging
4-7 日志记录配置-logging_mdc
4-8 历史记录配置-history-1
4-9 历史记录配置-history-2
4-10 事件处理及监听器配置-eventlog
4-11 事件处理及监听器配置-eventLinstener-1
4-12 事件处理及监听器配置-eventLinstener-2
4-13 命令拦截器配置-command-1
4-14 命令拦截器配置-command-2
4-15 作业执行器配置-job-1
4-16 作业执行器配置-job-2
4-17 Activiti与spring集成-1
4-18 Activiti与spring集成-2
4-19 Activiti与spring集成-3
第5章 Activiti核心API
本章主要讲解Activiti核心API，包括ProcessEngine以及服务、流程存储服务、流程运行控制服务、任务管理服务、用户和用户组管理服务、表单服务管理、历史数据管理服务、其它管理服务、异常策略。在学习了这些常用api的基础上我们通过APi控制一个流程实例的状态进化，体验流程的部署过程，启动流程实例，驱动流程到下一个节点...

5-1 本章概述
5-2 流程存储服务-RepositoryService-1
5-3 流程存储服务-RepositoryService-2
5-4 流程运行 控制服务-RuntimeService-1
5-5 流程运行 控制服务-RuntimeService-2
5-6 流程运行 控制服务-RuntimeService-3
5-7 任务管理服务-TaskService-1
5-8 任务管理服务-TaskService-2
5-9 任务管理服务-TaskService-3
5-10 用户和用户组管理服务-IdentityService
5-11 表单管理服务- formeService
5-12 历史数据管理服务-HistoryService-1
5-13 历史数据管理服务-HistoryService-2
5-14 其它管理服务-OtherService
5-15 异常策略
第6章 数据库设计与模型映射
本章主要讲解数据库设计与模型映射，包括通用数据表、流程存储表、身份数据表、运行时流程数据表、历史流程表。我们通过流程执行观察数据库内容的变化体会流程引擎表结构之间的关系。

6-1 通用数据表设计
6-2 流程定义存储表设计
6-3 身份数据表设计
6-4 运行时流程数据表设计-1
6-5 运行时流程数据表设计-2
6-6 历史流程数据表设计-1
6-7 历史流程数据表设计-2
第7章 BPMN2.0规范
本章主要讲解BPMN2.0规范，这里主要介绍BPMN中规范的基本元素Activities(活动)、Gateways（网关）、Events（事件），事件一般按照位置分类为开始事、结束事件、中间事件、边界事件。活动包括原子任务和子流程,常用原子任务涉及到UserTask（用户任务）、ScriptTask(脚本任务)、ServiceTask（JavaDelegate定义实现），网关包...

7-1 本章概述
7-2 BPMN2.0流程事件-事件分类
7-3 BPMN2.0流程事件-错误事件
7-4 BPMN2.0流程事件-信号消息事件
7-5 BPMN2.0流程任务-用户任务-1
7-6 BPMN2.0流程任务-用户任务-2
7-7 BPMN2.0脚本任务
7-8 BPMN2.0服务任务-1
7-9 BPMN2.0服务任务-2
7-10 BPMN2.0顺序流和网关-1
7-11 BPMN2.0顺序流和网关-2
7-12 BPMN2.0顺序流和网关-3
7-13 BPMN2.0子流程-1
7-14 BPMN2.0子流程-2
7-15 BPMN2.0子流程-3
7-16 BPMN2.0子流程-4
第8章 Activiti6.0集成Spring Boot2.0
本章讲解集成Spring Boot2.0，主要包括Spring Boot2.0特性、启动依赖starter、 自动装配AutoConfigure、运维监控Acutator、微服务Stand-alone、 启动入口SpringBootApplication、外部化配置yaml、Profiles、日志logging、 web mvc、SQL数据库集成、单元测试。 ...

8-1 本章概述
8-2 Spring Boot2.0入门实例-1
8-3 Spring Boot2.0入门实例-2
8-4 Spring Boot2.0启动依赖和自动装配-1
8-5 Spring Boot2.0启动依赖和自动装配-2
8-6 Activiti6.0与Spring Boot2.0集成-1
8-7 Activiti6.0与Spring Boot2.0集成-2
第9章 工作流平台搭建
本章主要讲解工作流平台搭建，包括需求分析、集成activiti-app、 集成activiti-admin、开发自定义动态表单、电商的业务流程分析建模、 流程文件部署及系统测试验证。

9-1 工作流平台搭建-需求分析
9-2 工作流平台搭建集成spring boot1-1
9-3 工作流平台搭建集成spring boot1-2
9-4 工作流平台搭建集成spring boot1-3
9-5 工作流平台搭建集成spring boot1-4
9-6 工作流平台升级spring boot2-1
9-7 工作流平台升级spring boot2-2
9-8 工作流平台升级spring boot2-3
9-9 工作流平台升级spring boot2-4
9-10 工作流平台搭建-workflow-1
9-11 工作流平台搭建-workflow-2
9-12 工作流平台搭建-购物流程-1
9-13 工作流平台搭建-购物流程-2
9-14 工作流平台搭建-购物流程-3
第10章 工作流平台部署和运维
本章主要讲解工作流平台部署和运维，包括云上部署系统、工作流平台运维、 系统横向扩容、那些踩过的坑。

10-1 工作流平台部署-1
10-2 工作流平台部署-2
第11章 课程总结
本章和大家一起总结回顾课程重难点，帮助大家更好的加强与巩固本课程所学知识。

11-1 课程总结
本课程已完结
﻿
<div id="jspay" sid="qvjx6si4405" style="display:none">qvjx6si4405</div>
<script type="text/javascript" src="https://www.fageka.com/j.js"></script>
<script type="text/javascript" src="https://www.fageka.com/f.js" charset="utf-8"></script>
