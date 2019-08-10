---
layout: Python研发攻城狮
title:  慕课网《聚焦Python分布式爬虫必学框架Scrapy 打造搜索引擎》
date: 2019-08-03 21:01:13
tags:
  - Python研发
  - 爬虫
  - Scrapy
  - 慕课网
categories:
  - 运维研发攻城狮
keywords: 慕课网《聚焦Python分布式爬虫必学框架Scrapy 打造搜索引擎》
---
『课程目录』:  
聚焦Python分布式爬虫必学框架Scrapy 打造搜索引擎（长期维护）
未来是什么时代？是数据时代！数据分析服务、互联网金融，数据建模、自然语言处理、医疗病例分析……越来越多的工作会基于数据来做，而爬虫正是快速获取数据最重要的方式，相比其它语言，Python爬虫更简单、高效

<!-- more --> 
第1章 课程介绍
介绍课程目标、通过课程能学习到的内容、和系统开发前需要具备的知识

 1-1 python分布式爬虫打造搜索引擎简介 试看
第2章 windows下搭建开发环境
介绍项目开发需要安装的开发软件、 python虚拟virtualenv和 virtualenvwrapper的安装和使用、 最后介绍pycharm和navicat的简单使用

 2-1 pycharm的安装和简单使用
 2-2 mysql和navicat的安装和使用
 2-3 windows和linux下安装python2和python3
 2-4 虚拟环境的安装和配置
第3章 爬虫基础知识回顾
介绍爬虫开发中需要用到的基础知识包括爬虫能做什么，正则表达式，深度优先和广度优先的算法及实现、爬虫url去重的策略、彻底弄清楚unicode和utf8编码的区别和应用。

 3-1 技术选型 爬虫能做什么
 3-2 正则表达式-1
 3-3 正则表达式-2
 3-4 正则表达式-3
 3-5 深度优先和广度优先原理
 3-6 url去重方法
 3-7 彻底搞清楚unicode和utf8编码
第4章 scrapy爬取知名技术文章网站
搭建scrapy的开发环境，本章介绍scrapy的常用命令以及工程目录结构分析，本章中也会详细的讲解xpath和css选择器的使用。然后通过scrapy提供的spider完成所有文章的爬取。然后详细讲解item以及item loader方式完成具体字段的提取后使用scrapy提供的pipeline分别将数据保存到json文件以及mysql数据库中。...

 4-1 关于文章网站不能访问的解决办法(本章学习之前的注意事项) 
 4-2 scrapy安装以及目录结构介绍
 4-3 pycharm 调试scrapy 执行流程
 4-4 xpath的用法 - 1
 4-5 xpath的用法 - 2
 4-6 xpath的用法 - 3
 4-7 css选择器实现字段解析 - 1
 4-8 css选择器实现字段解析 - 2
 4-9 编写spider爬取jobbole的所有文章 - 1
 4-10 编写spider爬取jobbole的所有文章 - 2
 4-11 items设计 - 1
 4-12 items设计 - 2
 4-13 items设计 - 3
 4-14 数据表设计和保存item到json文件
 4-15 通过pipeline保存数据到mysql - 1
 4-16 通过pipeline保存数据到mysql - 2
 4-17 scrapy item loader机制 - 1
 4-18 scrapy item loader机制- 2
第5章 scrapy爬取知名问答网站
本章主要完成网站的问题和回答的提取。本章除了分析出问答网站的网络请求以外还会分别通过requests和scrapy的FormRequest两种方式完成网站的模拟登录， 本章详细的分析了网站的网络请求并分别分析出了网站问题回答的api请求接口并将数据提取出来后保存到mysql中。...

 5-1 session和cookie自动登录机制 试看
 5-2 . selenium模拟登录知乎 - 1new
 5-3 . selenium模拟登录知乎-2new
 5-4 . selenium模拟登录知乎-3new
 5-5 . 知乎倒立文字识别 new
 5-6 . selenium自动识别验证码完成模拟登录-1new
 5-7 . selenium自动识别验证码完成模拟登录 - 2 new
 5-8 requests模拟登陆知乎 - 1(可选观看)
 5-9 requests模拟登陆知乎 - 2（可选观看）
 5-10 requests模拟登陆知乎 - 3（可选观看）
 5-11 scrapy模拟知乎登录（可选观看）
 5-12 知乎分析以及数据表设计1
 5-13 知乎分析以及数据表设计 - 2
 5-14 item loder方式提取question - 1
 5-15 item loder方式提取question - 2
 5-16 item loder方式提取question - 3
 5-17 知乎spider爬虫逻辑的实现以及answer的提取 - 1
 5-18 知乎spider爬虫逻辑的实现以及answer的提取 - 2
 5-19 保存数据到mysql中 -1
 5-20 保存数据到mysql中 -2
 5-21 保存数据到mysql中 -3
第6章 通过CrawlSpider对招聘网站进行整站爬取
本章完成招聘网站职位的数据表结构设计，并通过link extractor和rule的形式并配置CrawlSpider完成招聘网站所有职位的爬取，本章也会从源码的角度来分析CrawlSpider让大家对CrawlSpider有深入的理解。

 6-1 数据表结构设计
 6-2 CrawlSpider源码分析-新建CrawlSpider与settings配置
 6-3 CrawlSpider源码分析
 6-4 Rule和LinkExtractor使用
 6-5 拉勾网302之后的模拟登录和cookie传递(网站需要登录时学习本视频教程)
 6-6 item loader方式解析职位
 6-7 职位数据入库-1
 6-8 职位信息入库-2
第7章 Scrapy突破反爬虫的限制
本章会从爬虫和反爬虫的斗争过程开始讲解，然后讲解scrapy的原理，然后通过随机切换user-agent和设置scrapy的ip代理的方式完成突破反爬虫的各种限制。本章也会详细介绍httpresponse和httprequest来详细的分析scrapy的功能，最后会通过云打码平台来完成在线验证码识别以及禁用cookie和访问频率来降低爬虫被屏蔽的可能性。...

 7-1 爬虫和反爬的对抗过程以及策略 试看
 7-2 scrapy架构源码分析
 7-3 Requests和Response介绍
 7-4 通过downloadmiddleware随机更换user-agent-1
 7-5 通过downloadmiddleware随机更换user-agent - 2
 7-6 scrapy实现ip代理池 - 1
 7-7 scrapy实现ip代理池 - 2
 7-8 scrapy实现ip代理池 - 3
 7-9 云打码实现验证码识别
 7-10 cookie禁用、自动限速、自定义spider的settings
第8章 scrapy进阶开发
本章将讲解scrapy的更多高级特性，这些高级特性包括通过selenium和phantomjs实现动态网站数据的爬取以及将这二者集成到scrapy中、scrapy信号、自定义中间件、暂停和启动scrapy爬虫、scrapy的核心api、scrapy的telnet、scrapy的web service和scrapy的log配置和email发送等。 这些特性使得我们不仅只是可以通过scrapy来完成...

 8-1 selenium动态网页请求与模拟登录知乎
 8-2 selenium模拟登录微博， 模拟鼠标下拉
 8-3 chromedriver不加载图片、phantomjs获取动态网页
 8-4 selenium集成到scrapy中
 8-5 其余动态网页获取技术介绍-chrome无界面运行、scrapy-splash、selenium-grid, splinter
 8-6 scrapy的暂停与重启
 8-7 scrapy url去重原理
 8-8 scrapy telnet服务
 8-9 spider middleware 详解
 8-10 scrapy的数据收集
 8-11 scrapy信号详解
 8-12 scrapy扩展开发
第9章 scrapy-redis分布式爬虫
Scrapy-redis分布式爬虫的使用以及scrapy-redis的分布式爬虫的源码分析， 让大家可以根据自己的需求来修改源码以满足自己的需求。最后也会讲解如何将bloomfilter集成到scrapy-redis中。

 9-1 分布式爬虫要点
 9-2 redis基础知识 - 1
 9-3 redis基础知识 - 2
 9-4 scrapy-redis编写分布式爬虫代码
 9-5 scrapy源码解析-connection.py、defaults.py-
 9-6 scrapy-redis源码剖析-dupefilter.py-
 9-7 scrapy-redis源码剖析- pipelines.py、 queue.py-
 9-8 scrapy-redis源码分析- scheduler.py、spider.py-
 9-9 集成bloomfilter到scrapy-redis中
第10章 elasticsearch搜索引擎的使用
本章将讲解elasticsearch的安装和使用，将讲解elasticsearch的基本概念的介绍以及api的使用。本章也会讲解搜索引擎的原理并讲解elasticsearch-dsl的使用，最后讲解如何通过scrapy的pipeline将数据保存到elasticsearch中。

 10-1 elasticsearch介绍
 10-2 elasticsearch安装
 10-3 elasticsearch-head插件以及kibana的安装
 10-4 elasticsearch的基本概念
 10-5 倒排索引
 10-6 elasticsearch 基本的索引和文档CRUD操作
 10-7 elasticsearch的mget和bulk批量操作
 10-8 elasticsearch的mapping映射管理
 10-9 elasticsearch的简单查询 - 1
 10-10 elasticsearch的简单查询 - 2
 10-11 elasticsearch的bool组合查询
 10-12 scrapy写入数据到elasticsearch中 - 1
 10-13 scrapy写入数据到elasticsearch中 - 2
第11章 django搭建搜索网站
本章讲解如何通过django快速搭建搜索网站， 本章也会讲解如何完成django与elasticsearch的搜索查询交互。

 11-1 es完成搜索建议-搜索建议字段保存 - 1
 11-2 es完成搜索建议-搜索建议字段保存 - 2
 11-3 django实现elasticsearch的搜索建议 - 1
 11-4 django实现elasticsearch的搜索建议 - 2
 11-5 django实现elasticsearch的搜索功能 -1
 11-6 django实现elasticsearch的搜索功能 -2
 11-7 django实现搜索结果分页
 11-8 搜索记录、热门搜索功能实现 - 1
 11-9 搜索记录、热门搜索功能实现 - 2
第12章 scrapyd部署scrapy爬虫
本章主要通过scrapyd完成对scrapy爬虫的线上部署。

 12-1 scrapyd部署scrapy项目
第13章 课程总结
重新梳理一遍系统开发的整个过程， 让同学对系统和开发过程有一个更加直观的理解

 13-1 课程总结

<div class="post-copyright">
    <div class="post-copyright__author">
      <span class="post-copyright-meta">声明：视频资料等内容据来自各大网络交流群以及互联网收集，本网只收取信息整理费用和网站维护费用，版权归原作者所有，本网站不对所涉及的版权问题负法律责任，如作品原作者出版单位认为本网站出现侵权，请即时与本网站联系，将立刻删除处理。 </span>
    </div>
</div>

<blockquote class="blockquote-center">
链接：https://pan.baidu.com/s/19N1dqg-lB8J2vjmRlb2nLg 
提取码：rdf8 
复制这段内容后打开百度网盘手机App，操作更方便哦
</blockquote>

