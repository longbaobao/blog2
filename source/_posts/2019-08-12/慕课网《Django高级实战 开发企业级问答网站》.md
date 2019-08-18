---
layout: Python研发攻城狮
title:  慕课网《Django高级实战 开发企业级问答网站》
date: 2019-08-12 19:34:13
tags:
  - Python
  - Django
  - 企业级问答网站
  - 慕课网
categories:
  - Python研发攻城狮
keywords: 慕课网《Django高级实战 开发企业级问答网站》
---
『课程目录』:  
Django开发企业实战 面向就业/升职（中高级教程）
从实际需求分析开始，实现当今主流知识问答应用的功能，包括动态、文章、问答、私信、消息通知、搜索、个人中心，打造企业级知识问答网站，由此全面学习Python后端开发技术栈，内容涵盖Python、Django生态、通用类视图的源码、DFS/BFS/C3线性化算法、组合模式与观察者模式、TestCase测试用例、MySQL数据库、Redis缓存、WebSocket实时推送、Haystack+Elasticsearch搜索、应用部署和运维、云计算服务。从零开发到阿里云上线，讲解企业项目开发的全过程。
第1章 Django企业开发实战 （10篇教辅文档+5道大作业+全站源码提供）
本教程是专门为 求职/跳槽涨薪/优质毕设 量身打造的实战教程！课程不单项目是企业级的就连 开发流程，技术选型，都严格按照真实的企业开发流程。让你足不出户就能体验到真实的企业开发场景是什么样的。不再惶恐没有面试作品和工作经验，助力你斩获高薪offer！...
<!-- more --> 
<blockquote class="blockquote-center">
请支持原版！课程官方链：https://coding.imooc.com/class/chapter/333.html</blockquote>
</blockquote>
 1-1 《Django高级实战-开发企业级问答网站》课程导学 试看
第2章 Django项目的一些最佳实践
最佳实践目的是使生产或管理实践的结果达到最优，并减少出错的可能性。本章讲的一些实践方法在后面都会用到，算是项目知识铺垫。每小节都会举例和大家说明。

 2-1 Pipenv管理项目环境（附文档）
 2-2 Pipenv管理Python虚拟环境
 2-3 优先使用自定义的用户模型
 2-4 使用通用类视图（GCBV）
 2-5 在系统环境变量中保存敏感信息
 2-6 为不同环境分别配置settings.py文件
 2-7 一定要编写测试用例
第3章 项目需求分析，功能设计和技术选型
本章将从用户的角度，分析需要实现哪些功能，学习需求分析，Markdown写项目需求文档，贴近“高内聚，低耦合”原则，模块化设计网站功能。前后端的技术选型，规划各个软件的版本。

 3-1 项目需求分析（附文档）
 3-2 赞乎产品需求规格说明书
 3-3 模块化设计网站功能 试看
 3-4 确定开发技术栈
第4章 Cookiecutter火速搭建项目+开发环境介绍
介绍神器Cookiecutter，它的优点和局限，按照确定的技术栈选择cookiecutter-django搭建具有高完成度的项目，学习Python项目如何组织代码，如何管理配置，如何管理依赖。项目开发环境介绍：Pycharm连接CentOS 7远程开发设置，以及MySQL用户权限管理和安全设置。 ...

 4-1 Cookiecutter安装和使用（附文档）
 4-2 使用Cookiecutter快速搭建Django应用
 4-3 cookiecutter-django火速搭建项目
 4-4 项目开发环境介绍（服务器环境和Pycharm远程开发设置）
 4-5 删改部分文件完成项目初始模板
第5章 django-allauth同时实现本地和第三方认证
继承AbstractUser自定义用户模型类，引入django-allauth认证系统，同时完成本地账户功能和集成第三方账户登录注册，再回头讲解OAuth 2.0协议的原理。学习使用TestCase为Django模型类、网址、视图编写测试用例。

 5-1 用户模块数据库设计
 5-2 django-allauth的介绍和使用
 5-3 用户登录-注册-注销-找回密码
 5-4 GitHub为例集成第三方账号注册和登录
 5-5 理解OAuth 2.0协议的原理
 5-6 完成用户个人中心开发
 5-7 为模型类-网址-视图编写测试用例 试看
第6章 首页功能- ListView/DeleteView完成动态功能-源码和MRO算法
本章在实现需求的同时，穿插讲解Django的高级知识，如ORM中多对多外键。先使用通用类视图ListView/DeleteView开发功能，再讲解框架的源码，然后是Python语言中多继承的MRO算法，按业务→框架→源码→Python底层算法顺序由浅入深讲解。 ...

 6-1 动态功能models.py设计
 6-2 完成动态列表页开发
 6-3 通用类视图ListView源码详解
 6-4 理解Python中的多继承-MRO
 6-5 新式类的MRO算法-C3线性化算法
 6-6 用户发表动态
 6-7 用户删除动态
 6-8 通用类视图DeleteView源码详解
 6-9 Django通用类视图源码详解
 6-10 用户给动态点赞
 6-11 用户评论动态
 6-12 模型类的测试用例test_models.py
 6-13 视图的测试用例test_views.py
 6-14 本章总结与课后作业
第7章 [文章]GCBV使用和自定义QuerySet，DTL语法精讲
本章首先讲解问答类业务中最常见的两个功能需求：详情页的slug和标签管理。依据软件开发中DRY原则，在模型类中自定义查询集QuerySet，模仿主流问答类网站，实现文章的Markdown编辑与实时预览效果，实现功能之后再剖析CreateView/UpdateView源码。 ...

 7-1 文章模块models.py设计
 7-2 使用python-slugify和django-taggit
 7-3 models.py中自定义QuerySet
 7-4 完成文章列表页开发
 7-5 用户发表文章与保存草稿
 7-6 实现Markdown编辑与实时预览
 7-7 通用类视图CreateView源码详解
 7-8 用户浏览文章内容
 7-9 django-contrib-comments实现评论文章
 7-10 用户编辑文章
 7-11 通用类视图UpdateView源码详解
 7-12 Django Template Language语法精讲
 7-13 Django Template Language语法精讲
 7-14 模型类和视图的测试用例
 7-15 本章总结与课后作业.
第8章 GenericRelation关联模型类与RequestFactory类测试视图
实现问答功能：本章为赞乎产品的核心功能，业务逻辑颇为复杂，首先将梳理“用户-问题-回答-点赞/踩-采纳”之间的关系，然后介绍Django中的ContentType，使用更高级外键GenericForeignKey与GenericRelation来解决问题。在测试用例中，我们将改用更加符合企业实践的方式—RequestFactory类直接测试视图。 ...

 8-1 “用户-问 -回答-点赞或踩-采纳”逻辑关系梳理
 8-2 Question模型类及自定义QuerySet
 8-3 Answer模型类
 8-4 Django中的contenttypes框架
 8-5 什么是GenericRelation和GenericForeignKey
 8-6 一张表搞定用户点赞-踩关联关系
 8-7 定义问答模型类的方法-使代码更易扩展
 8-8 ListView开发所有问题页
 8-9 已回答和待回答问题页
 8-10 用户提问-视图及表单开发
 8-11 问题详情页前后端开发
 8-12 回答问题-CreateView的fields属性
 8-13 用户点赞或踩的场景分析
 8-14 给问题或回答点赞踩
 8-15 提问者接受答案-用户验证或PermissionDenied
 8-16 模型类的测试用例
 8-17 RequestFactory类直接测试视图（上）
 8-18 RequestFactory类直接测试视图（下）
 8-19 知识拓展与课后作业
第9章 [私信]消息查询集设计，发送和接收处理
私信功能包括私信记录、在线回复、私信提示，难点在于后端消息的实时推送，本章先讲解消息模型类与查询集的设计，实现用户发送消息与接收消息处理，然后是WebSocket原理，再介绍Django Channels，什么是consumer，routing，Django应用中如何实现WebSocket认证。 ...

 9-1 消息模型类与查询集
 9-2 私信列表页前后端开发
 9-3 用户发送与接收消息处理
 9-4 WebSocket协议的概念和原理
 9-5 WebSocket协议的优缺点及应用场景
 9-6 Django中如何实现WebSocket编程
 9-7 Django Channels的原理
 9-8 WSGI和ASGI的区别
 9-9 Channel Layers的配置和使用
 9-10 理解Consumers的基本用法
 9-11 Generic Consumers同步与异步通信
 9-12 Channels的路由Routing开发
 9-13 用户实时接收私信后端设计
 9-14 前端WebSocket API讲解
 9-15 用户中心信息统计
 9-16 本章回顾与总结
第10章 [通知功能]处理器的实现-channels实战WebSocket编程
本章是项目的重难点，将着重讲，内容包括通知功能的业务场景分析，通知处理器设计与实现，进一步实战实战WebSocket编程，什么是ASGI服务器，以及ASGI请求的通道服务(Redis) ，如何继承AsyncWebSocketConsumer类实现用户异步连接、断开、接收通知。 ...

 10-1 消息通知的业务场景分析
 10-2 GenericForeignKey让模型类可复用
 10-3 Django serializers序列化查询集
 10-4 未读通知列表页前后端开发
 10-5 标记所有或单条通知为已读
 10-6 WebSocket消息接收和处理
 10-7 通知处理器设计与实现
 10-8 JS中进一步实战WebSocket API编程
 10-9 首页有新动态时冒泡提示
 10-10 动态被点赞或评论时推送通知
 10-11 WebSocket触发Ajax请求-自动更新点赞数和评论数
 10-12 一个隐藏的bug, github也有？
 10-13 结合django-comments信号机制实现文章评论的通知
 10-14 回答被采纳时WebSocket消息通知
 10-15 排错思路讲解与课后作业
第11章 django-haystack+elasticsearch实现全站搜索
本章将学习使用django-haystack + elasticsearch实现全站搜索，可以同时搜索文章、动态、问答、用户、标签。包括Elasticsearch搜索引擎安装和配置，haystack通过型号量机制实时生成索引，以及搜索结果分类处理。

 11-1 全站搜索的实现思路
 11-2 Elasticsearch介绍和安装
 11-3 django-haystack elasticsearch-py elasticsearch-dsl-py比较
 11-4 配置Haystack Elasticsearch和创建索引类
 11-5 完成searh search.html前端开发
第12章 网站优化与Django Channels应用部署
本章将先讲解Django项目优化的知识，包括功能优化，缓存优化，SQL优化等，然后是Python应用的部署原理，各种WSGI/ASGI协议，Nginx反向代理的作用，然后精讲两大类4种Django应用的部署方式，包括部署的配置文件、配置项、日志内容的含义，如何排错。...

 12-1 善用django-debug-toolbar 解锁新技能
 12-2 BUG修复和功能优化
 12-3 使用django-compressor压缩静态文件
 12-4 Celery异步发送邮件
 12-5 Django缓存优化之Redis缓存
 12-6 ORM语句和SQL优化（上）
 12-7 ORM语句和SQL优化（下）
 12-8 Python应用部署的原理
 12-9 Nginx Tornado部署Django应用
 12-10 Nginx+Tornado部署Django应用 
 12-11 Apache mod_wsgi部署Django应用
 12-12 Apache+mod_wsgi部署Django应用 
 12-13 Nginx Gunicorn Daphne部署Django Channels应用
 12-14 Nginx+uWSGI+Daphne部署Django Channels应用 
 12-15 Nginx uWSGI Daphne Supervisor Django生产环境部署
 12-16 Nginx+Gunicorn+Daphne部署Django Channels应用 
第13章 阿里云ECS+RDS上线项目
云计算成为主流趋势，熟悉使用云产品成为企业招聘需求，本章将讲解如何使用阿里云ECS+RDS上线项目，包括选择合适的ECS，做初始化配置、安全配置等；RDS实例创建，账号及数据库管理，ECS连接RDS。需要同学们动手申请云账号，项目上线成功后可以公网访问，互相监督促进。 ...

 13-1 什么是云计算
 13-2 云服务器ECS配置
 13-3 云数据库RDS MySQL配置
 13-4 ECS RDS_MySQL上线项目
 13-5 ECS+RDS MySQL上线项目 
 13-6 作业：CDN OSS网站与应用加速
第14章 课程回顾与总结
回顾整个课程，梳理开发过程，复习课程中的重难点知识。总结经验，提出项目中可以进一步完善的功能，如使用Django缓存优化，并给出实现思路，让同学们主动思考，探索。

 14-1 Django开发企业级问答网站-课程回顾与总结

<div class="post-copyright">
    <div class="post-copyright__author">
      <span class="post-copyright-meta">声明：视频资料等内容据来自各大网络交流群以及互联网收集，本网只收取信息整理费用和网站维护费用，版权归原作者所有，本网站不对所涉及的版权问题负法律责任，如作品原作者出版单位认为本网站出现侵权，请即时与本网站联系，将立刻删除处理。 </span>
    </div>
</div>

<div id="jspay" sid="DQ586cefa6dR1" style="display:none">DQ586cefa6dR1</div>
<script type="text/javascript" src="https://x-x.fun/c.js" charset="UTF-8"></script>

