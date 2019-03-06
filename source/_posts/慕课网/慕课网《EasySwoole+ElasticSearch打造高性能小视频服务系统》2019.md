---
title: EasySwoole+ElasticSearch打造高性能小视频服务系统
date: 2019-03-01 14:18:13
tags:
  - PHP
  - 慕课网
  - 2019
  - Swoole
  - 小视频服务
  - 实战
  - ElasticSearch
  - 后端开发
categories:
  - 后端开发
keywords: EasySwoole+ElasticSearch打造高性能小视频服务系统
---
![image](//szimg.mukewang.com/5bce9a04000115d105400300-360-202.jpg)

EasySwoole+ElasticSearch打造高性能小视频服务系统
EasySwoole底层是基于swoole开发的常驻内存型的分布式PHP框架，专为API而生，是swoole专业型上层PHP框架，让开发者以最低的学习成本和精力编写出多进程，可异步，高可用的应用服务。本课程将理论结合实战，带你从基础开始系统学习EasySwoole框架, 同时利用EasySwoole带你打造高性能API服务，并结合分布式搜索引擎-ElasticSearch带你打造一个高性能小视频服务系统，让你从容处理各种高并发高性能业务场景。

<!-- more -->
<blockquote class="blockquote-center">
请支持原版！课程官方链：https://coding.imooc.com/class/287.html</blockquote>
</blockquote>
第1章 课程概述
本章介绍课程技术点、需要的环境准备以及easyswoole的简介，让大家轻松掌握课程的特色，明确学好本门课的技术储备。

 1-1 导学
 1-2 easyswoole简介
 1-3 环境准备以及课程技术点介绍 试看
第2章 EasySwoole框架快速上手
本章讲解easyswoole的安装、easyswoole的结构分析、easyswoole 的其它特性以及 实战第一个easyswoole服务，带领大家快速上手ES框架。

 2-1 easyswoole安装以及结构分析
 2-2 easyswoole基本使用
 2-3 easyswoole深入使用
 2-4 EasySwoole结合Mysql使用
第3章 性能测试
本章会介绍为什么要学习性能测试、性能测试工具ab的介绍、ab测试详细讲解以及 最后产出easyswoole http性能测试报告，带你深入理解性能测试的真谛。

 3-1 性能测试介绍
 3-2 ab工具安装以及详细讲解
 3-3 easyswoole http性能测试报告
第4章 玩转高性能消息队列服务
本章讲解消息队列、学习消息队列的原因、常用消息队列介绍以及使用场景解刨以及利用easySwoole打造高性能消息队列服务。

 4-1 为什么要学习消息队列
 4-2 Redis准备工作
 4-3 Redis底层类库封装
 4-4 Redis底层类库封装优化
 4-5 引入高性能配置文件服务
 4-6 解读easyswoole进程以及redis的list
 4-7 生产者 消费者端业务编写
第5章 小视频服务平台 - 前后端分离以及平台后端整体架构
本章介绍视频、视频技术栈、视频上传功能开发、性能优化以及利用easyswoole高性能消息队列处理视频上传处理任务。

 5-1 前后端分离介绍
 5-2 前端环境安装以及页面部署
 5-3 前端页面构建以及让Nginx 请求转发到swoole服务器 试看
 5-4 小视频服务平台整体架构
第6章 利用EasySwoole处理小视频业务
本章介绍首页视频页面、利用easyswoole开发首页视频API业务、高并发下性能优化-首页页面API数据优化等，带大家使用easyswoole的websocket打造小视频信息推送服务。

 6-1 小视频介绍
 6-2 开发流程介绍
 6-3 视频上传到本地
 6-4 视频上传到本地优化方案1
 6-5 视频上传到本地优化方案2
 6-6 视频封面图功能上传
 6-7 利用反射机制优化处理上传文件思想
 6-8 视频基本数据入库
 6-9 视频基本数据入库-优化工作
 6-10 前后端联调
第7章 打造高性能API服务系统 - EasySwoole API篇
本章讲解swoole table场景在API高并发下的使用以及性能分析、API场景下如何利用Swoole的异步任务高效的处理相关统计及API场景下如何利用Swoole的协程高效处理相关统计等，带你处理API场景下的多种业务。

 7-1 视频转码、加速播放以及第三方视频云平台介绍
 7-2 阿里云sdk获取以及基本使用
 7-3 阿里云视频点播服务底层类库封装(一)
 7-4 阿里云视频点播服务底层类库封装(二)
 7-5 小视频API底层服务改造 - 接入阿里云点播服务
 7-6 首页视频页面技术点介绍
 7-7 利用easyswoole开发首页视频API业务-原始方案(1) 试看
 7-8 利用easyswoole开发首页视频API业务-原始方案(2)
 7-9 利用easyswoole开发首页视频API业务-原始方案(3) - 优化
 7-10 性能优化 - 静态化API(easyswoole的crontab基础类库讲解以及基本使用)
 7-11 性能优化 - 静态化API(定时备份基础类库编写)
 7-12 性能优化 - 静态化API(业务层逻辑替换)
 7-13 性能优化 - 静态化API(easyswoole定时器完美解决方案)
 7-14 性能优化 – 高性能easyswoole table方案
 7-15 性能优化 – redis解决方案
 7-16 代码高度复用 - 底层cache基础类库优化
 7-17 代码高度复用 - 底层cache基础类库优化
 7-18 代码高度复用 - 预留作业
 7-19 API缓存总结
 7-20 视频播放页面基本信息
 7-21 播放数统计 – 高性能swoole task异步任务引入
 7-22 播放数统计 – 高性能redis有序集合服务引入
 7-23 视频排行榜(总排行、今日排行、本周排行等)接口
 7-24 代码高度优化
 7-25 基于redis的视频点赞逻辑开发以及预留给大家的作业
第8章 利用EasySwoole和ElasticSearch打造高性能的小视频搜索服务
本章介绍高性能分布式 elasticsearch、技术选型、 jdk获取和安装、es单机安装和分布式安装 、easyswoole集成elasticearch等，带大家实战easyswoole层和elasticsearch层优化搜索服务。

 8-1 elasticsearch简介
 8-2 elasticsearch安装 - es单机安装
 8-3 head插件安装
 8-4 elasticsearch分布式处理
 8-5 elasticsearch索引精讲
 8-6 文档的新增操作
 8-7 文档的查询操作
 8-8 elasticsearch-php底层基础类库安装和部署
 8-9 easyswoole结合elasticsearch初探
 8-10 利用easyswoole底层DI容器对es底层基础类库封装
 8-11 视频搜索底层类库封装
 8-12 视频搜索底层类库封装优化
 8-13 应用层大数据下搜索API逻辑开发
 8-14 应用层大数据下搜索API逻辑开发优化方案以及IK分词器介绍
第9章 性能调优 - 让系统轻轻松松应对高并发
本章进行性能调优，带你深入掌握高并发技术，轻松处理高并发业务。

 9-1 本章性能调优概括
 9-2 swoole的升级
 9-3 easyswoole2.x 升级到easyswoole 3
 9-4 让业务层代码轻松适配easyswoole 3.x (一)
 9-5 让业务层代码轻松适配easyswoole 3.x (二)
 9-6 性能优化- swoole协程连接池
 9-7 性能调优大体介绍以及openresty工具的介绍
 9-8 高并发下性能调优 -负载均衡
第10章 课程总结
本章进行课程总结。

 10-1 10.1 课程总结
本课程已完结
<div class="post-copyright">
    <div class="post-copyright__author">
      <span class="post-copyright-meta">声明：视频资料等内容据来自各大网络交流群以及互联网收集，本网只收取信息整理费用和网站维护费用，版权归原作者所有，本网站不对所涉及的版权问题负法律责任，如作品原作者出版单位认为本网站出现侵权，请即时与本网站联系，将立刻删除处理。 </span>
      <span style="color: red;display: block;text-align: center;">**内容打赏后可见**</span> 
      <span style="color:red;display: block;text-align: center;font-size: 20px;"><a href="http://t.cn/EITrp7s">打赏</a></span>
    </div>
</div>
            
