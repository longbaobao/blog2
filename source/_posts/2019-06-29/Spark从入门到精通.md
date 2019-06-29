---
layout: Spark从入门到精通
title: Spark从入门到精通
date: 2019-06-29 20:03:13
tags:
  - 大数据
  - 综合
  - Spark
categories:
  - 后端研发工程师-Go
keywords: Spark从入门到精通
---

『课程目录』:
├─1 Scala编程详解
│      1.1、Spark的前世今生-1
│      1.2、Spark的前世今生-2
│      1.3、课程介绍、特色与价值-1
│      1.4、课程介绍、特色与价值-2
│      1.5、基础语法（1）
│      1.6、基础语法（2）
│      1.7、条件控制与循环-1
│      1.8、条件控制与循环-2
│      1.9、函数入门
│      1.10、函数入门之默认参数和带名参数
│      1.11、函数入门之变长参数
│      1.12、函数入门之过程、lazy值和异常
│      1.13、数组操作之Array、ArrayBuffer以及遍历数组(1)
│      1.14、数组操作之Array、ArrayBuffer以及遍历数组(2)
│      1.15、数组操作之数组转换
│      1.16、Map与Tuple
│      1.17、面向对象编程之类-1
│      1.18、面向对象编程之类-2
│      1.19、面向对象编程之对象
│      1.20、面向对象编程之继承-1
│      1.21、面向对象编程之继承-2
│      1.22、面向对象编程之Trait-1
│      1.23、面向对象编程之Trait-2
│      1.24、函数式编程-1
│      1.25、函数式编程-2
│      1.26、函数式编程之集合操作-1
│      1.27、函数式编程之集合操作-2
│      1.28、模式匹配-1
│      1.29、模式匹配-2
│      1.30、类型参数-1
│      1.31、类型参数-2
│      1.32、隐式转换与隐式参数
│      1.33、Actor入门
│      
├─2 Scala编程进阶
│      2.1、Scaladoc的使用
│      2.2、跳出循环语句的3种方法
│      2.3、多维数组、Java数组与Scala数组的隐式转换
│      2.4、Tuple拉链操作、Java Map与Scala Map的隐式转换
│      2.5、扩大内部类作用域的2种方法、内部类获取外部类引用
│      2.6、package与import实战详解
│      2.7、重写field的提前定义、Scala继承层级、对象相等性
│      2.8、文件操作实战详解
│      2.9、偏函数实战详解
│      2.10、执行外部命令
│      2.11、正则表达式支持
│      2.12、提取器实战详解
│      2.13、样例类的提取器实战详解
│      2.14、只有一个参数的提取器
│      2.15、注解实战详解
│      2.16、常用注解介绍
│      2.17、XML基础操作实战详解
│      2.18、XML中嵌入scala代码
│      2.19、XML修改元素实战详解
│      2.20、XML加载和写入外部文档
│      2.21、集合元素操作
│      2.22、集合的常用操作方法
│      2.23、map、flatMap、collect、foreach实战详解
│      2.24、fold上半截
│      2.25、fold下半截
│      
<!-- more -->
├─3 Spark深入剖析
│  ├─第1章 Spark核心编程
│  │      1.1、Spark基本工作原理与RDD-1
│  │      1.2、Spark基本工作原理与RDD-2
│  │      1.3、使用Java开发本地测试的wordcount程序-1
│  │      1.4、使用Java开发本地测试的wordcount程序-2
│  │      1.5、将java开发的wordcount程序提交到spark集群上运行
│  │      1.6、使用scala开发wordcount程序
│  │      1.7、使用spark-shell开发wordcount程序
│  │      1.8、Spark UI补充说明
│  │      1.9、spark-submit中的--master选项的补充说明（重要，必看！）
│  │      1.10、wordcount程序原理深度剖析
│  │      1.11、Spark架构原理
│  │      1.12、创建RDD（集合、本地文件、HDFS文件）-1
│  │      1.13、创建RDD（集合、本地文件、HDFS文件）-2
│  │      1.14、transformation和action讲解与原理剖析
│  │      1.15、案例：统计每行出现的次数（操作key-value对）
│  │      1.16、常用transformation和action操作概览
│  │      1.17、map案例实战：将集合中的数字乘以2
│  │      1.18、filter案例实战：过滤集合中的偶数
│  │      1.19、flatMap案例实战：将文本行拆分为单词
│  │      1.20、groupByKey案例实战：将每个班级的成绩进行分组
│  │      1.21、reduceByKey案例实战：统计每个班级的总分
│  │      1.22、sortByKey案例实战：按照学生成绩进行排序
│  │      1.23、join和cogroup案例实战：打印学生成绩
│  │      1.24、action操作开发实战
│  │      1.25、RDD持久化详解
│  │      1.26、共享变量（Broadcast Variable和Accumulator）
│  │      1.27、高级编程之基于排序机制的wordcount程序
│  │      1.28、使用Java实现二次排序
│  │      1.29、使用Scala实现二次排序
│  │      1.30、获取文本内最大的前3个数字
│  │      1.31、获取每个班级排名前3的成绩（分组取topn）
│  │      
│  ├─第2章 Spark内核源码深度剖析
│  │      2.1、Spark内核架构深度剖析
│  │      2.2、宽依赖与窄依赖深度剖析
│  │      2.3、基于Yarn的两种提交模式深度剖析
│  │      2.4、基于yarn的提交模式的spark-env.sh配置补充
│  │      2.5、SparkContext原理剖析
│  │      2.6、SparkContext源码分析
│  │      2.7、Master主备切换机制原理剖析与源码分析
│  │      2.8、Master注册机制原理剖析与源码分析
│  │      2.9、Master状态改变处理机制原理剖析与源码分析
│  │      2.10、Master资源调度算法原理剖析与源码分析
│  │      2.11、Worker原理剖析与源码分析-1
│  │      2.12、Worker原理剖析与源码分析-2
│  │      2.13、job触发流程原理剖析与源码分析
│  │      2.14、stage划分算法原理剖析
│  │      2.15、DAGScheduler源码分析（stage划分算法、task最佳位置计算算法）
│  │      2.16、TaskScheduler原理剖析与源码分析
│  │      2.17、Executor原理剖析与源码分析
│  │      2.18、Task原理剖析
│  │      2.19、Task源码分析
│  │      2.20、普通Shuffle操作的原理剖析
│  │      2.21、优化后的Shuffle操作的原理剖析
│  │      2.22、Shuffle读写源码分析
│  │      2.23、BlockManager原理剖析
│  │      2.24、BlockManager源码分析-1
│  │      2.25、BlockManager源码分析-2
│  │      2.26、CacheManager原理剖析
│  │      2.27、CacheManager源码分析
│  │      2.28、Checkpoint原理剖析
│  │      
│  └─第3章 Spark性能优化
│          3.1、性能优化概览
│          3.2、诊断内存的消耗
│          3.3、高性能序列化类库
│          3.4、优化数据结构
│          3.5、对多次使用的RDD进行持久化或Checkpoint
│          3.6、使用序列化的持久化级别
│          3.7、Java虚拟机垃圾回收调优
│          3.8、提高并行度
│          3.9、广播共享数据
│          3.10、数据本地化
│          3.11、reduceByKey和groupByKey
│          3.12、shuffle性能优化
│          
└─4 内存计算框架Spark
    ├─第1章 Spark初识入门
    │      1.1、 与MapReduce对比性介绍Spark是什么
    │      1.2、 Spark四大特性及与MapReduce比较
    │      1.3、 如何指定Hadoop版本进行编译Spark
    │      1.4、 Spark 应用程序测试讲解一
    │      1.5、 Spark应用程序测试讲解二
    │      1.6、 Scala基本知识讲解（变量，函数及高阶函数）
    │      1.7、 Spark Standalone安装部署讲解一
    │      1.8、 Spark Standalone安装部署讲解二
    │      1.9、 Spark Standalone安装部署讲解三
    │      1.10、 Spark 实现WordCount功能讲解
    │      1.11、 Spark如何提交应用程序及各个组件名词解释
    │      
    ├─第2章 Spark核心RDD
    │      2.1、 Spark RDD五大特性讲解（以WordCount案例和比较MapReduce）
    │      2.2、 RDD创建的两种方式讲解
    │      2.3、 RDD Operation讲解（transformation和action）
    │      2.4、 RDD 依赖讲解（宽依赖和窄依赖）
    │      2.5、 Spark RDD Shuffle讲解（类似MapReduce中的Shuffle）
    │      2.6、 如何创建Spark Application
    │      2.7、 Spark 内核剖析讲解
    │      2.8、 Spark Core应用案例讲解一
    │      2.9、 Spark Core应用案例讲解二
    │      2.10、 Spark Core应用案例讲解三(1)
    │      2.11、 Spark Core应用案例讲解三(2)
    │      
    └─第3章 Spark高阶应用
            3.1、 如何使用IDEA开发Spark Application及Local与打包测试讲解
            3.2、 Spark Application监控（HistoryServer历史服务器配置使用）
            3.3、 Spark Application运行的两种方式Client和Cluster区别
            3.4、 Spark 如何运行在YARN上（两种模式的区别）和解决NodeManager节点不健康问题
            3.5、 演示讲解Spark-shell运行在YARN上及以yarn cluster方式提交应用到yarn运行
            3.6、 回顾复习Spark Core知识点
            3.7、 Spark Streaming功能介绍和Demo演示
            3.8、 通过Demo演示深入理解Spark Streaming如何工作
            3.9、 Spark Streaming编程模型讲解
            3.10、 Spark Streaming如何读取出来HDFS上数据
            3.11、 Spark Streaming核心概念DStream及相关Operation讲解
            3.12、 Spark Streaming与Flume集成讲解一
            3.13、 Spark Streaming与Flume集成讲解二
            3.14、 Kafka架构功能、环境搭建与演示
            3.15、 Spark Streaming与Kafka集成方式一使用讲解
            3.16、 Spark Streaming与Kafka集成方式二使用讲解
            3.17、 Spark Streaming与Kafka集成结合UpdateStateByKey统计案例讲解

<div class="post-copyright">
    <div class="post-copyright__author">
      <span class="post-copyright-meta">声明：视频资料等内容据来自各大网络交流群以及互联网收集，本网只收取信息整理费用和网站维护费用，版权归原作者所有，本网站不对所涉及的版权问题负法律责任，如作品原作者出版单位认为本网站出现侵权，请即时与本网站联系，将立刻删除处理。 </span>
    </div>
</div>

<blockquote class="blockquote-center">
链接：https://pan.baidu.com/s/1-pBE8rd_nXXOH6pyIUSKfA
提取码：kvl9
复制这段内容后打开百度网盘手机App，操作更方便哦
</blockquote>
