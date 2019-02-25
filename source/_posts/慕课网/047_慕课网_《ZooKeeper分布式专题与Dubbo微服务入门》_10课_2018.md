---
title: ZooKeeper分布式专题与Dubbo微服务入门
date: 2019-02-25 14:01:13
tags:
  - 后端开发
  - 慕课网
  - 2018
  - 分布式
  - ZooKeeper
  - Dubbo
  - 微服务
categories:
  - 后端开发
keywords: ZooKeeper分布式专题与Dubbo微服务入门 成长与加薪必备的分布式技能
---
![image](//szimg.mukewang.com/5ab9be440001b21f05400300-360-202.jpg)

ZooKeeper分布式专题与Dubbo微服务入门
ZooKeeper是一种分布式协调服务，他用简单的架构和API，解决了在分布式环境中协调和管理服务的难题。本课程从零开始，带你系统学习ZooKeeper，并结合Dubbo，实践服务治理和分布式锁，帮你入门ZooKeeper+Dubbo的服务治理

<!-- more -->
<blockquote class="blockquote-center">
请支持原版！课程官方链：https://coding.imooc.com/class/201.html</blockquote>
</blockquote>
第1章 分布式系统概念与ZooKeeper简介
对分布式系统以及ZooKeeper进行简介，使得大家对其有大致的了解

1-1 zookeeper简介
1-2 什么是分布式系统
1-3 分布式系统的瓶颈以及zk的相关特性
第2章 ZooKeeper安装
如何安装ZooKeeper以及对ZooKeeper最基本的数据模型进行剖析

2-1 JDK的安装
2-2 zookeeper下载、安装以及配置环境变量
2-3 zookeeper文件夹主要目录介绍
2-4 zookeeper配置文件介绍，运行zk
第3章 ZooKeeper基本数据模型
学习客户端命令行之前需要对ZooKeeper的一些基本特性有一定的了解，便于便于对ZooKeeper有全面的理解

3-1 zk数据模型介绍
3-2 zk客户端连接关闭服务端，查看znode
3-3 zookeeper的作用体现
第4章 ZK基本特性与基于Linux的ZK客户端命令行学习
了解ZK在Linux上的命令行操作，这部分需要会，至少要了解如何进行操作的，做好笔记记录好相关命令

4-1 zookeeper常用命令行操作
4-2 session的基本原理与create命令的使用
4-3 set与delete命令的使用_(有一处打点 内容不确定)
4-4 zk特性 – 理解watcher机制
4-5 父节点watcher事件
4-6 子节点watcher事件
4-7 watcher常用使用场景
4-8 权限acl详解，acl的构成-scheme与id
4-9 acl的构成-permissions
4-10 acl命令行world讲解
4-11 acl命令行auth讲解
4-12 acl命令行digest讲解
4-13 acl命令行ip讲解
4-14 acl之super超级管理员
4-15 acl的常用使用场景
4-16 zk四字命令 上
4-17 zk四字命令 下
第5章 选举模式和ZooKeeper的集群安装
学习选举模式和ZooKeeper集群安装，模拟商用环境，测试集群角色以及选举

5-1 集群的一些基本概念
5-2 单机伪分布式安装zookeeper集群
5-3 三台物理机(虚拟机)安装zookeeper集群
5-4 测试集群角色以及选举
第6章 使用ZooKeeper原生Java API进行客户端开发
使用java原生api进行客户端开发

6-1 建立客户端与zk服务端的连接
6-2 zk会话重连机制
6-3 同步异步创建zk节点
6-4 修改zk节点数据
6-5 同步异步删除zk节点
6-6 CountDownLatch的介绍
6-7 CountDownLatch代码示例
6-8 获取zk节点数据
6-9 获取zk子节点列表
6-10 判断zk节点是否存在
6-11 acl - 默认匿名权限
6-12 acl -自定义用户权限
6-13 acl - ip权限
第7章 Apache Curator客户端的使用
企业最喜欢使用的ZK开源客户端，方便实用，要学会

7-1 curator简介与客户端之间的异同点
7-2 搭建maven工程，建立curator与zkserver的连接
7-3 zk命名空间以及创建节点
7-4 修改节点以及删除节点
7-5 查询节点相关信息
7-6 curator之usingWatcher
7-7 curator之nodeCache一次注册N次监听
7-8 curator之PathChildrenCache子节点监听
7-9 zk-watcher实例 统一更新N台节点的配置文件
7-10 curator之acl权限操作与认证授权
第8章 Dubbo入门到重构服务
将SpringMVC构建的商品秒杀Demo重构为Dubbo微服务系统

8-1 架构演变过程
8-2 dubbo 入门简介
8-3 单体到分层模式代码演示
8-4 重构商品服务，抽取抽象工程
8-5 暴露商品服务
8-6 使用tomcat启动dubbo服务
8-7 使用main主线程启动dubbo服务
8-8 使用dubbo内置main打包jar启动
8-9 重构并且暴露订单服务
8-10 开发dubbo消费者服务调用方
8-11 测试dubbo消费者调用商品服务和订单服务
8-12 安装启动dubbo监控服务
8-13 测试dubbo监控服务的统计数据以及图表
8-14 如何升级dubbo到最新版本
第9章 分布式锁
ZooKeeper+Dubbo实践分布式锁的案例

9-1 死锁与活锁的概念
9-2 分布式锁的概念与数据最终不一致性的场景
9-3 curator与spring的整合
9-4 获取分布式锁的流程
9-5 开发分布式锁
第10章 课程总结
对整个课程的所用到的理论，技术做一个简单的回顾总结

10-1 课程总结
本课程已完结

<div class="post-copyright">
    <div class="post-copyright__author">
      <span class="post-copyright-meta">声明：视频资料等内容据来自各大网络交流群以及互联网收集，本网只收取信息整理费用和网站维护费用，版权归原作者所有，本网站不对所涉及的版权问题负法律责任，如作品原作者出版单位认为本网站出现侵权，请即时与本网站联系，将立刻删除处理。 </span>
      <span style="color: red;display: block;text-align: center;">**内容打赏后可见**</span> 
      <span style="color:red;display: block;text-align: center;font-size: 20px;"><a href="http://t.cn/EfozJC9">打赏</a></span>
    </div>
</div>
            
