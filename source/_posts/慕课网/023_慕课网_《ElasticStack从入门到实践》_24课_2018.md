---
title: ElasticStack从入门到实践
date: 2018-09-22 17:30:28
tags:
  - 大数据
  - 慕课网
  - 2017
  - ElasticStack
categories:
  - 大数据
keywords: ElasticStack从入门到实践
---
![image](https://img.mukewang.com/szimg/5a7441e30001d4f805400300-360-202.jpg)

Elastic Stack从入门到实践
不管是想做大数据工程师还是数据分析师，本课都是很好的起点！掌握Elastic Stack的组成及原理应用，详解Elasticsearch、Kibana、Beats及Logstash 的原理与应用技巧，助你快速收集、处理和分析数据，以达成助力业务增长的目标！

第1章 课程概述
对课程整体进行介绍给出相关学习说明和建议

1-1 课程导学
1-2 说明和建议
第2章 Elasticsearch 篇之 入门
本章会对 Elasticsearch 篇进行一个总体的介绍，让大家对该篇每一章要讲解的内容有初步的了解。然后会讲解 Elasticsearch 中常见的术语、api，然后运行 Elasticsearch 并实际感受 api 的调用方式，为接下来的课程做好准备。

<!-- more -->
<blockquote class="blockquote-center">
请支持原版！课程官方链接：https://coding.imooc.com/class/181.html</blockquote>
</blockquote>


2-1 -术语介绍
2-2 -Document介绍
2-3 -Index介绍
2-4 -restapi介绍
2-5 -index_api
2-6 -document_api
第3章 Elasticsearch 篇之倒排索引与分词
本章会讲解搜索引擎的基础倒排索引，让大家对倒排索引有一个直观的认识，掌握它的组成。然后为大家讲解分词的相关知识，介绍 es 内置的分词器，还会介绍中文分词的常见解决方案。

3-1 -书的目录与索引
3-2 -正排与倒排索引简介
3-3 -倒排索引详解
3-4 -分词介绍
3-5 -analyze_api
3-6 -自带分词器
3-7 -中文分词
3-8 -自定义分词之CharacterFilter
3-9 -自定义分词之Tokenizer
3-10 -自定义分词之 TokenFilter
3-11 -自定义分词
3-12 -分词使用说明
3-13 -官方文档说明
第4章 Elasticsearch 篇之Mapping 设置
本章会讲解 Elasticsearch 中数据建模的基础--Mapping，即如何定义数据字段和类型。让大家熟悉 mapping 中常见的配置项，也会讲解 dynamic mapping 和 template 的相关知识。

4-1 -mapping简介
4-2 -自定义 mapping
4-3 -mapping演示
4-4 -copy_to参数说明
4-5 -index参数说明
4-6 -index_options参数说明
4-7 -mapping文档说明
4-8 -数据类型
4-9 -dynamic-mapping简介
4-10 -dynamic日期与数字识别
4-11 -dynamic-template简介
4-12 -自定义mapping的建议
4-13 -索引模板.mp4
第5章 Elasticsearch 篇之Search API 介绍
本章会讲解搜索特性，详细讲解 Search API 的组成和分类，带领大家逐个了解、掌握 API 的使用方法和技巧。

5-1 -SearchAPI概览
5-2 -URISearch详解与演示
5-3 -QueryDSL简介
5-4 -字段类查询简介及match-query
5-5 -相关性算分.mp4
5-6 -match-phrase-query_音频.mp4
5-7 -query-string-query
5-8 -simple-query-string-query
5-9 -term-terms-query
5-10 -range-query
5-11 -复合查询介绍及ConstantScore
5-12 -bool-query
5-13 -count-and-source-filtering
第6章 Elasticsearch 篇之分布式特性介绍
本章会讲解 Elasticsearch 集群是如何一步步搭建起来的，让大家了解不同节点类型的作用，shard 设计的意义以及文档是如何存储到 shard 上的，也会给大家介绍脑裂等问题。

6-1 -分布式介绍及cerebro
6-2 -构建集群
6-3 -副本与分片
6-4 -两个问题
6-5 -集群状态
6-6 -故障转移.mp4
6-7 -文档分布式存储
6-8 -脑裂问题
6-9 -shard详解
第7章 Elasticsearch 篇之深入了解 Search 的运行机制
本章会深入讲解 Search 的运行机制，比如 Query 和 Fetch 阶段具体哪些工作，分片为相关性算分带来了哪些问题。另外还会讲解排序、分页与遍历的解决方案和相关问题。

7-1 -Query-Then-Fetch
7-2 -相关性算分
7-3 -sorting-doc-values-fielddata
7-4 -分页与遍历-fromsize
7-5 -分页与遍历-scroll
7-6 分页与遍历-search_after
7-7 文档说明.mp4
第8章 Elasticsearch 篇之聚合分析入门
本章会介绍 Elasticsearch 聚合分析的功能，让大家了解其分类、组成，带领大家逐个了解、掌握每一个聚合 API 的使用方法和技巧，为后续 Kibana 使用打好基础。

8-1 -聚合分析简介
8-2 -metric聚合分析
8-3 -bucket聚合分析
8-4 -bucket和metric聚合分析
8-5 -pipeline聚合分析
8-6 -作用范围
8-7 -排序
8-8 -原理与精准度问题
8-9 -文档说明
第9章 Elasticsearch 篇之数据建模
本章会介绍使用 Elasticsearch 中要注意的数据建模常见问题以及优化思路和方案，让大家可以根据自己的业务场景设置最合理的模型。

9-1 -数据建模简介
9-2 -ES数据建模配置相关介绍
9-3 -ES数据建模实例.mp4
9-4 -Nested_Object
9-5 -Parent_Child
9-6 -nested_vs_parent_child
9-7 -reindex
9-8 其他建议
第10章 Elasticsearch 篇之集群调优建议
本章会介绍 Elasticsearch 集群在搭建、配置上的注意事项，也会讲解读写性能优化的方案和调优的方式。

10-1 生产环境部署建议
10-2 写性能优化
10-3 读性能优化
10-4 如何设定shard数
10-5 xpack监控功能介绍
第11章 Logstash 篇之入门与运行机制
本章会介绍 Logstash 的作用、使用方法，让大家了解其组成和运行机制，带领大家实际操作 Logstash 来收集1个日志文件。

11-1 入门及架构简介
11-2 -Life_of_an_Event
11-3 -queue简介
11-4 -线程简介
11-5 配置简介
11-6 多实例运行
11-7 pipeline配置简介
第12章 Logstash 篇之插件详解
本章会详细介绍 Input、Filter、Ouput 以及 Codec 插件 的作用和相关配置，让大家了解常见相关插件的使用场景和效果，以及如何合理选择各个插件来实现自己的业务需求。

12-1 input插件详解及glob讲解
12-2 -codec插件详解
12-3 filter插件简介及date插件讲解
12-4 filter插件之grok简介（上）
12-5 filter插件之grok简介（下）
12-6 filter插件之dissect讲解
12-7 filter插件之mutate 讲解
12-8 filter插件之 json讲解
12-9 filter 插件之geoip和ruby 讲解
12-10 output插件简介
12-11 文档说明
第13章 Logstash 篇之实例分析
本章会以实例的形式为大家演示如何使用 Logstash 收集各种类型的数据，比如日志文件、数据库、tcp/udp 等。

13-1 -Logstash实战建议
13-2 -实战之apacheLogs（上）
13-3 实战之apacheLogs（下）
13-4 实战之csv
13-5 监控运维建议
第14章 Beats 篇之Filebeat
本章会介绍 Beats 的作用和组成，然后为大家详细介绍 Filebeat 的功能和常见配置，同时会详细讲解如何使用 Module 模块来快速完成日志的收集到分析工作。

14-1 beats简介
14-2 Filebeat_Demo
14-3 Filebeat 简介及流程介绍
14-4 Filebeat常见架构及ingest_node介绍
14-5 Filebeat_Module简介
第15章 Beats 篇之Metricbeat
本章会介绍 Metricbeat 的功能和使用技巧，让大家对 Metricbeat 的使用有一个直观的感受。

15-1 -简介
15-2 -Module简介
15-3 -实战.mp4
第16章 Beats 篇之Packetbeat
本章会介绍 Packetbeat 的功能和使用技巧，带领大家用 Packetbeat 来收集网络数据并进行分析，让大家对 Packetbeat 有一个直观的感受。

16-1 1-简介
16-2 2-实战
第17章 Beats 篇之其他 beat
本章会介绍其他众多beat的作用和应用场景，带领大家去发现社区提供的多种多样的beat,以满足日常业务开发的需求。

17-1 1-Heartbeat
17-2 2-Community_beats
第18章 Kibana 篇之 入门与管理
本章会介绍 Kibana 的入门知识，让大家对 Kibana 有一个整体的了解，另外还会详细介绍Management 的功能，熟悉 Kibana 的配置。

18-1 -配置与线上部署建议
18-2 -Index_Pattern_Objects_Settings使用
第19章 Kibana 篇之 数据探索 Discovery
本章会介绍 Kibana 的数据探索功能，让大家了解 Discovery 的功能和使用技巧。

19-1 -导入数据
19-2 -Discover实战
第20章 Kibana 篇之 可视化分析
本章会介绍Kibana 的可视化分析功能，首先会带领大家逐个操作 Kibana 提供的每一个图表，并会介绍时序分析工具 Timelion，然后会介绍如何使用 Dashboard功能来整合图表后讲故事或者做报表，也会讲解 Dashboard 使用中要注意的问题和使用技巧。 ...

20-1 -可视化简介
20-2 -Basic_Charts_介绍
20-3 -Basic_Charts_其他说明
20-4 -Data图表介绍
20-5 -Map图表介绍
20-6 -Timelion介绍
20-7 -VisualBuilder介绍
20-8 -other图表介绍
20-9 -Dashboard介绍
第21章 实践篇 之搜索项目
本章会讲解一个搜索引擎相关的实践项目，带领大家通过编写少量的代码，快速基于 Elastic Stack 来构建一个具备常见搜索功能的系统，比如类似 Airbnb 的搜房系统、豆瓣电影等。

21-1 -项目介绍
21-2 项目实战
第22章 实践篇 之日志分析项目
本章会根据慕课网的日志为大家展示如何使用 Elastic Stack 来快速分析日志数据，带领大家一步步完成数据收集、处理、存储到可视化分析的步骤，最终打造属于自己的 Dashboard。

22-1 介绍和数据导入
22-2 -实战（上）
22-3 -实战（下）
第23章 实践篇 之数据分析项目
本章会为大家展示如何使用 Elastic Stack 来分析身边的数据，比如空气质量分析、订单数据分析等等，让大家通过本章的学习可以快速将 Elastic Stack 应用到实际生活中。

23-1 项目简介
23-2 实战（上）
23-3 实战（下）
第24章 课程总结
本章会为大家总结本课程的内容，为大家再次梳理 Elastic Stack 的知识点，并为大家接下来的进阶学习提供一些建议和思路。

24-1 课程总结
本课程已完结


<blockquote class="blockquote-center">声明：此资源由巨菜站博客 收集整理于网络，如有侵权，请联系巨菜站删除处理。</blockquote>

<div id="jspay" sid="2J8falz1403" style="display:none">2J8falz1403</div>
<script type="text/javascript" src="https://www.fageka.com/j.js"></script>
<script type="text/javascript" src="https://www.fageka.com/f.js" charset="utf-8"></script>
