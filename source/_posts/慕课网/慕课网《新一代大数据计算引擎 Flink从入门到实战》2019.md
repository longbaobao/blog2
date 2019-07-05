---
layout: 大数据研发攻城狮
title: 慕课网《新一代大数据计算引擎 Flink从入门到实战》2019
date: 2019-07-04 21:26:13
tags:
  - 流计算
  - Flink
  - 大数据
  - 慕课网
categories:
  - 大数据研发攻城狮
keywords: 慕课网《新一代大数据计算引擎 Flink从入门到实战》2019
---

『课程目录』: 
新一代大数据计算引擎 Flink从入门到实战
随着云计算和大数据的快速发展，在企业中需要处理和分析的数据量越来越大，随着Flink社区的快速发展，很多公司采用以Flink为核心技术栈来打造统一的大数据处理平台 ，Flink正变得越来越火，此时学习，正当其时。课程中从核心知识的多语言（Java-Scala）讲解到部署实战，循序渐进，助力系统入门Flink企业级应用
第1章 初识Flink
了解Flink是什么，Flink应用程序运行的多样化，对比业界常用的流处理框架，Flink的发展趋势，Flink生态圈，Flink应用场景及Flink如何进行高效的Flink学习。

 1-1 课程导学 试看
 1-2 ***学前必读***（助你平稳踩坑，畅学无忧，课程学习与解决问题指南）
 1-3 课程目录
 1-4 Flink概述 试看
 1-5 Flink Layered API
 1-6 Flink运行多样化
 1-7 业界流处理框架对比
 1-8 Flink Use Cases
 1-9 Flink发展趋势
 1-10 如何以正确的姿势来学习Flink
 <!-- more -->
第2章 快速上手开发第一个Flink应用程序
动手搭建Flink的开发环境，快速使用Java和Scala语言开发第一个基于Flink的批处理和流式处理的应用程序。

 2-1 课程目录
 2-2 开发环境准备之JDK安装
 2-3 开发环境准备之Maven安装
 2-4 开发环境准备之IDEA安装
 2-5 Flink批处理应用开发之需求描述
 2-6 Flink批处理应用Java开发之环境准备
 2-7 Flink批处理应用开发之八股文编程
 2-8 Flink批处理应用Java开发之功能实现 试看
 2-9 Flink批处理应用Scala开发之环境准备
 2-10 Flink批处理应用Scala开发之功能实现
 2-11 使用Java和Scala开发Flink应用程序对比
 2-12 Flink实时处理应用Java开发之功能实现
 2-13 Flink实时处理应用Java开发之代码重构
 2-14 Flink实时处理应用Scala开发之代码重构
 2-15 开发过程中依赖的注意事项
第3章 编程模型及核心概念
掌握Flink的核心概念及编程模型，如何在编程中执行key及转换函数，Flink支持的数据类型。

 3-1 课程目录
 3-2 核心概念概述
 3-3 DataSet和DataStream
 3-4 Flink编程模型
 3-5 延迟执行
 3-6 指定key之Tuple
 3-7 指定key之字段表达式
 3-8 指定key之key选择器函数
 3-9 指定转换函数
 3-10 Flink支持的数据类型
第4章 DataSet API编程
掌握Flink批处理开发的DataSet API的编程，包括数据源、转换函数、Sink、计数器以及分布式缓存的编程。

 4-1 课程目录
 4-2 DataSet API开发概述
 4-3 Flink综合Java和Scala开发的项目构建creenflow
 4-4 Data Source宏观概述
 4-5 从集合创建DataSet之Scala实现
 4-6 从集合创建DataSet之Java实现
 4-7 从文件或者文件夹创建DataSet之Scala实现
 4-8 从文件或者文件夹创建DataSet之Java实现
 4-9 从csv文件创建Dataset之Scala实现
 4-10 从递归文件夹的内容创建DataSet之Scala实现
 4-11 从压缩文件中创建DataSet之Scala实现
 4-12 Transformation概述
 4-13 Transformation函数map之Scala实现
 4-14 Transformation函数map之Java实现
 4-15 Transformation函数filter之Scala实现
 4-16 Transformation函数filter之Java实现
 4-17 Transformation函数mapPartition之Scala实现
 4-18 Transformation函数mapPartition之Java实现
 4-19 Transformation函数first之Scala实现
 4-20 Transformation函数first之Java实现
 4-21 Transformation函数flatMap之Scala实现
 4-22 Transformation函数flatMap之Java实现
 4-23 Transformation函数distinct之Scala和Java实现
 4-24 Transformation函数join之Scala实现
 4-25 Transformation函数outerJoin之Scala实现
 4-26 Transformation函数join之Java实现
 4-27 Transformation函数outerJoin之Java实现
 4-28 Transformation函数cross之Scala实现
 4-29 Transformation函数cross之Java实现
 4-30 Transformation小结
 4-31 Sink函数Scala实现
 4-32 Sink函数Java实现
 4-33 通过案例引入Flink的计数器
 4-34 基于Flink编程的计时器之Scala实现
 4-35 基于Flink编程的计时器之Java实现
 4-36 基于Flink的分布式缓存功能的Scala实现
 4-37 基于Flink的分布式缓存功能的Java实现
 4-38 本章节小结及作业
第5章 DataStream API编程
掌握Flink流处理开发的DataStream API的编程，包括数据源、转换函数、Sink的用法，以及如何自定义数据源和自定义Sink的实现。

 5-1 DataStream API编程概述
 5-2 从Socket创建DataStream之Java实现
 5-3 从Socket创建DataStream之Scala实现
 5-4 自定义数据源方式SourceFunction之Scala实现
 5-5 自定义数据源方式ParallelSourceFunction之Scala实现
 5-6 自定义数据源方式RichParallelSourceFunction之Scala实现
 5-7 自定义数据源方式之Java实现
 5-8 Transformation函数map和filter之Scala实现
 5-9 Transformation函数map和filter之Java实现
 5-10 Transformation函数union之Scala和Java实现
 5-11 Transformation函数split和select之Scala实现
 5-12 Transformation函数split和select之Java实现
 5-13 自定义Sink之需求描述及表创建
 5-14 自定义Sink之功能测试
 5-15 DataStream API开发小结
第6章 Flink Table API & SQL编程
了解Flink中统一编程模式的编程Table API以及SQL API的开发及使用。

 6-1 课程目录
 6-2 什么是Flink关系型API
 6-3 Table API&SQL概述
 6-4 使用Scala完成Table API&SQL功能的开发
 6-5 使用Java完成Table API&SQL功能的开发
 6-6 Table API&SQL其他功能介绍
第7章 Flink中的Time及Windows的使用
掌握Flink中三种常用的Time处理方式，掌握Flink中滚动窗口以及滑动窗口的使用，了解Flink中的watermark。

 7-1 课程目录
 7-2 Processing Time详解
 7-3 Event Time详解
 7-4 Ingestion Time详解
 7-5 如何在Flink中指定Time的类型
 7-6 Windows概述
 7-7 Window Assigners详解
 7-8 基于Time和Count的Windows
 7-9 Tumbling Windows详解及Scala编程
 7-10 Tumbling Windows Java编程
 7-11 Sliding Windows详解及Scala编程
 7-12 Window Functions之ReduceFunction的Scala实现
 7-13 Window Functions之ReduceFunction的Java实现
 7-14 Window Functions之ProcessWindowFunction的Java实现
 7-15 作业--Window Functions之ProcessWindowFunction的Scala实现
 7-16 Flink watermark概述
第8章 Flink Connectors
了解Flink中常用的Connector有哪些，了解HDFS Connector的用户，掌握Flink和Kafka对接的Connnector用法。

 8-1 课程目录
 8-2 Connectors概述
 8-3 HDFS Connector的使用
 8-4 Kafka Connector概述
 8-5 OOTB环境的使用
 8-6 ZooKeeper部署
 8-7 Kafka部署及测试
 8-8 Flink对接Kafka作为Source使用
 8-9 Flink对接Kafka作为Sink使用
 8-10 作业
 8-11 Flink整合Kafka的offset管理及EXACTLY_ONCE语义
 8-12 Flink整合Kafka的checkpoint常用参数设置梳理
第9章 Flink部署及作业提交
掌握Flink的local、standalone、yarn模式的部署，如何提交Flink作业进行运行，熟悉Flink中常用的配置参数，掌握Flink cli的用法。

 9-1 课程目录
 9-2 Flink部署准备及源码编译
 9-3 单机模式部署及代码提交测试
 9-4 Flink Standalone模式部署及参数详解
 9-5 Hadoop集群快速搭建
 9-6 Flink on YARN两种方式
 9-7 Flink on YARN第一种模式实操
 9-8 Flink on YARN第二种模式实操
 9-9 Flink on YARN作业
 9-10 如何查找需要配置的Flink参数及UI对应关系介绍
 9-11 Flink Scala Shell的使用
 9-12 本章作业
第10章 Flink监控及调优
掌握Flink的常用监控方式以及调优策略。

 10-1 课程目录
 10-2 HistoryServer概述及配置
 10-3 HistoryServer的使用
 10-4 HistoryServer REST API使用
 10-5 Monitoring REST API
 10-6 Flink Metrics
 10-7 Flink常用优化策略
第11章 基于Flink的互联网直播平台日志分析项目实战
掌握基于Flink的大数据项目的开发流程、处理流程及架构分析，根据需求进行功能的实现，涉及到基于Flink的实时数据清洗、业务统计、可视化展示等流程。

 11-1 课程目录
 11-2 项目背景
 11-3 项目功能需求描述
 11-4 项目架构
 11-5 Mock数据之Kafka生产者代码主流程开发
 11-6 Mock数据之Kafka生产者代码日志生产开发
 11-7 使用Flink消费Kafka生产的数据
 11-8 使用Flink完成实时日志清洗功能开发
 11-9 数据清洗过程中添加业务逻辑条件的过滤
 11-10 Flink中Watermark的定义及使用
 11-11 WindowFunction业务逻辑的实现
 11-12 ES部署
 11-13 Kibana部署
 11-14 统计分析数据写入ES并通过Kibana展示出来
 11-15 通过Kibana图形化展示ES中存储的结果
 11-16 第一个功能作业
 11-17 功能二需求及数据准备
 11-18 自定义MySQL数据源读取
 11-19 完成两个流关联的数据清洗功能
 11-20 本章节总结
 第12章 Flink版本升级
掌握Flink应用程序的版本升级，Flink环境的升级。

 12-1 课程目录
 12-2 Flink版本升级概述
 12-3 Flink部署包升级及工程依赖的Flink版本升级
 12-4 将升级后的代码运行到升级后的Flink上去

3-3　Flink streaming和Batch代码层面的使用.mp4
4-1　Flink local集群安装以及集群代码提交执行.mp4
4-2　Flink standalone集群安装部署.mp4
4-3　Flink on yarn的两种方式.mp4
4-4　Flink on yarn内部实现.mp4
5-1　Flink standalone集群HA配置.mp4
5-2　如何解决集群启动失败的问题.mp4
5-3　Flink on yarn集群HA配置.mp4
6-1　Flink scala shell代码调试.mp4

Flink入门及实战(下)
1-1   课件资料下载
1-2　课程内容介绍.mp4
1-3　DataStream之source讲解-java.mp4
1-4　DataStream之自定义source-1.mp4
1-5　DataStream之自定义source-2.mp4
1-6　DataStream之算子操作-java.mp4
1-7　DataStream之partition-java.mp4
1-8　DataStream之sink-java.mp4
1-9　DataStream之source-scala.mp4
1-10 DataStream之算子操作-scala.mp4
1-11 DataStream之partition-scala.mp4
1-12 DataStream之sink-scala.mp4
2-1　DataSet之算子操作-java-1.mp4
2-2　DataSet之算子操作-java-2.mp4
2-3　DataSet之partition-java.mp4
2-4　DataSet之算子操作-scala-1.mp4
2-5　DataSet之算子操作-scala-2.mp4
3-1　Flink支持的dataType和序列化.mp4
4-1　Flink Broadcast广播变量-(java代码).mp4
4-2　Flink Broadcast广播变量-(scala代码).mp4
5-1　Flink Counters-java代码.mp4
5-2　Flink Counters-scala代码.mp4
6-1　Flink Distributed Cache.mp4
7-1　state之keyedState分析.mp4
7-2　state之operatorState分析.mp4
7-3　Flink checkPoint分析.mp4
7-4　Flink state backend详细分析.mp4
7-5　Flink state backend实战演示.mp4
7-6　Flink 重启策略分析.mp4
7-7　Flink 从checkpoint恢复数据.mp4
7-8　Flink savePoint的使用详解.mp4
8-1 Flink Window详解.mp4
8-2 Flink time介绍.mp4
8-3 Flink Waternakr介绍.mp4
8-4 Flink Waternak解决乱序数据.mp4
8-5 Flink Waternak解决乱序数据.mp4
9-1 Flink paralleism并行度分析.mp4
10-1  Flink UI界面介绍.mp4
11-1 Flink kafka-connector分析.mp4
11-2 kafka-connector代码操作-java.mp4
11-3 kafka-connector代码操作-scala.mp4
12-1 Flink生产环境配置介绍.mp4
13-1 实战需求分析(数据清洗[实时ETL]).mp4
13-2 数据清洗[实时ETL]-java代码实现-1.mp4
13-2 数据清洗[实时ETL]-java代码实现-2.mp4
13-4 数据清洗[实时ETL]-java代码提交集群运行.mp4
13-5 数据清洗[实时ETL]-把任务提交命令封装成脚本.mp4
13-6 数据清洗[实时ETL]-scala代码实现.mp4
13-7 实战需求分析(数据报表).mp4
13-8 数据报表-java代码实现-1.mp4
13-9 数据报表-java代码实现-2.mp4
13-10 数据报表-es和kibana的安装.mp4
13-11 数据报表-运行任务.mp4
13-12 数据报表-执行脚本封装.mp4
13-13 数据报表-scala代码实现.mp4
 
<div class="post-copyright">
    <div class="post-copyright__author">
      <span class="post-copyright-meta">声明：视频资料等内容据来自各大网络交流群以及互联网收集，本网只收取信息整理费用和网站维护费用，版权归原作者所有，本网站不对所涉及的版权问题负法律责任，如作品原作者出版单位认为本网站出现侵权，请即时与本网站联系，将立刻删除处理。 </span>
    </div>
</div>

<blockquote class="blockquote-center">
链接：https://pan.baidu.com/s/166yoDRKnMoZzUTXTOKy9uQ 
提取码：wudf 
复制这段内容后打开百度网盘手机App，操作更方便哦
</blockquote>

