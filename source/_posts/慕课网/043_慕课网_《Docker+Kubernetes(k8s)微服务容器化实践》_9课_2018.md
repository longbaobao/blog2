---
title: Docker+Kubernetes(k8s)微服务容器化实践
date: 2018-10-12 17:12:21
tags:
  - 云计算&大数据
  - 慕课网
  - 2018
  - Docker
  - DevOps
categories:
  - 云计算&大数据
keywords: Docker+Kubernetes(k8s)微服务容器化实践
---
![image](//szimg.mukewang.com/5ab3a1240001e67910800600-360-202.jpg)

Docker+Kubernetes(k8s)微服务容器化实践
从整体上把握微服务，体会服务Docker化，理解服务编排，以及主流的服务编排框架——Kubernetes，了解它的架构，知道它的运作原理，知道如何安装、使用及如何部署微服务

<!-- more -->
<blockquote class="blockquote-center">
请支持原版！课程官方链：https://coding.imooc.com/class/chapter/198.html</blockquote>
</blockquote>
第1章 初识微服务
微服务的入门，我们从传统的单体架构入手，看看在什么样的环境和需求下一步步走到微服务的，然后再具体了解一下什么才是微服务，让大家对微服务的概念有深入的理解。然后我们一起画一个微服务的架构图，再从架构上去分析微服务架构的优势和不足。 ...

1-1 微服务-导学
1-2 软件架构的进化
1-3 什么是微服务
1-4 画出微服务架构图
1-5 微服务架构的优势和不足
第2章 微服务带来的问题及解决方案分析
通过传统服务与微服务对比的方式去学习，如果使用微服务架构会遇到什么问题，这些问题在业内都有什么解决方案。之后我们插了一段SpringBoot和SpringCloud的内容，主要目的是让大家搞清楚它们跟微服务的关系，跟docker的关系，以及跟服务编排的关系。...

2-1 微服务架构带来的问题
2-2 微服务间如何通讯
2-3 服务发现、部署更新和扩容
2-4 springboot&springcloud（上）
2-5 springboot&springcloud（下）
第3章 微服务开发
我们首先假定一个业务场景，分析一下微服务的划分、每个微服务完成什么功能、它们之间的依赖关系以及它们之间如何通讯。然后从0开始，一行不落的开发完整的服务。服务的开发过程我们会用到SpringBoot，用到Dubbo，用到Thrift，用到API网关Zuul。 ...

3-1 微服务业务分析
3-2 Thirft安装和验证
3-3 Python开发信息服务
3-4 开发用户服务（上）
3-5 开发用户服务（下）
3-6 开发用户EdgeService_A
3-7 开发用户EdgeService_B
3-8 开发用户EdgeService_C
3-9 开发用户EdgeService_D
3-10 dubbo入门操练(上)
3-11 dubbo入门操练(下)
3-12 开发课程服务
3-13 开发课程EdgeService
3-14 APIGatewayZuul
第4章 服务编排前奏
为服务编排做准备，首先我们把所有微服务进行docker化，然后用原生的docker-compose把它们都运行在容器中，并且保证它们之间在容器中也可以正常通讯。最后我们搭建一个私有仓库，用于存放我们的镜像，使用的是业内主流的 - harbor。 ...

4-1 服务docker化（上）
4-2 服务docker化（下）
4-3 docker下的服务通讯（上）
4-4 docker下的服务通讯（下）
4-5 镜像仓库
4-6 三大平台扬帆起航
第5章 服务编排-Mesos
我们从概念到架构设计到调度策略逐步去了解Mesos，然后画出我们要搭建的Mesos集群架构图，之后参照架构图我们一步一步搭建好整个集群环境，最后调整我们的微服务，把他们部署在Mesos集群中。

5-1 了解Mesos
5-2 画出Mesos集群架构图
5-3 集群环境搭建_A
5-4 集群环境搭建_B
5-5 集群环境搭建_C
5-6 调整微服务适应Mesos
5-7 微服务部署_A
5-8 微服务部署_B
5-9 微服务部署_C
第6章 服务编排-DockerSwarm
学习的过程跟Mesos类似，也是先从概念入手，了解Swarm的架构设计，了解它的服务发现，服务编排，然后搭建Swarm集群环境，之后调整我们的微服务适应于Swarm，最后把他们部署在Swarm集群中。

6-1 了解Swarm
6-2 集群环境搭建（上）
6-3 集群环境搭建（下）
6-4 调整微服务及服务配置
6-5 微服务部署
第7章 服务编排-Kubernetes
Kubernetes学习的整体的思路也是从概念到集群搭建最后到微服务部署。但由于它在服务编排领域的领导地位和它的高门槛。我们将它剥离成三部分，核心部分、kube-proxy&kube-dns、认证授权。采用循序渐进的方式逐步渗透，不但可以让大家更容易入门，也会对它有更深刻的理解。 ...

7-1 了解kubernetes（上）
7-2 了解kubernetes（下）
7-3 环境搭建前奏
7-4 预先准备环境
7-5 基础集群部署（上）
7-6 基础集群部署（下）
7-7 小试牛刀
7-8 kube-proxy和kube-dns
7-9 理解认证、授权
7-10 为集群添加认证授权（上）
7-11 为集群添加认证授权（下）
7-12 再试牛刀
7-13 部署我们的微服务
第8章 CICD和DevOps
首先从实践的角度看看为什么要有CICD和DevOps，然后从本质上了解CICD和DevOps的概念。接着分析我们要做的CICD的流程是什么样子的。最后我们搭建Gitlab，Jenkins环境，再结合镜像仓库和Kubernetes集群，构建一个从代码提交到服务更新完全自动化的流程。 ...

8-1 了解CICD和DevOps
8-2 准备GitLab和Jenkins
8-3 CICD实践（上）
8-4 CICD实践（下）
第9章 课程总结
对前面所学内容的总结。

9-1 -课程总结
本课程已完结

<blockquote class="blockquote-center">声明：此资源由巨菜站博客 收集整理于网络，如有侵权，请联系巨菜站删除处理。</blockquote>

<div id="jspay" sid="kpf8VHU1602" style="display:none">kpf8VHU1602</div>
<script type="text/javascript" src="https://www.fageka.com/j.js"></script>
<script type="text/javascript" src="https://www.fageka.com/f.js" charset="utf-8"></script>
