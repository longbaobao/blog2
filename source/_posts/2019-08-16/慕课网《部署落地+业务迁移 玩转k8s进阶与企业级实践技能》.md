---
layout: 后端研发攻城狮
title:  慕课网《部署落地+业务迁移 玩转k8s进阶与企业级实践技能》
date: 2019-08-16 19:34:13
tags:
  - 云计算
  - kubernete
  - 容器云
  - 慕课网
categories:
  - 后端研发攻城狮
keywords: 慕课网《部署落地+业务迁移 玩转k8s进阶与企业级实践技能》
---
『课程目录』:  
部署落地+业务迁移 玩转k8s进阶与企业级实践技能
Kubernetes早在2017年底就已成为容器编排领域的事实标准，时至今日，围绕着Kubernetes的生态持续爆发。除了Google、BAT、京东、美团等巨头大厂外，越来越多的中小互联网企业也都在向Kubernetes迁移。容器技术大势所趋，已逐渐成为开发/运维工程师、架构师的必备技能之一。本门课程从集群部署到业务迁移、持续集成再到核心知识点梳理，不仅可以帮助有志从事Kubernetes相关工作的同学做基本的入门指导，也可以帮助有一定基础的工程师快速实现k8s生产落地，少走弯路，避免踩坑。

<!-- more --> 
<blockquote class="blockquote-center">
请支持原版！课程官方链：https://coding.imooc.com/class/335.html</blockquote>
</blockquote>
第1章 课程简介【学前须知】
本章对这门课程进行说明，包括：课程整体设计思路、课程使用的技术介绍、课程的学习规划、高效学习的方式方法等。

 1-1 课程介绍 试看
第2章 kubernetes快速入门【k8s必知必会】
本章中将从核心概念、架构设计、认证授权以及集群搭建方案对比几方面，带领大家快速掌握kubernetes的重要知识点，助力快速入门。

 2-1 了解kubernetes 试看
 2-2 kubernetes的核心概念
 2-3 kubernetes的架构设计 试看
 2-4 kubernetes认证的密码学原理
 2-5 kubernetes的认证与授权
 2-6 集群搭建方案对比
第3章 高可用集群搭建---kubeadm方式【集群落地方案1】
本章中将讲解，如何使用kubeadm自动化的方式，搭建最新版本的kubernetes高可用集群。以三个master，两个worker节点为例，同时还会对集群可用性进行的测试，并完成dashboard的搭建和使用。并在本章结尾，通过文档方式，针对前面内容进行总结，便于同学们回顾查阅。...

 3-1 实践环境准备
 3-2 高可用集群部署
 3-3 集群可用性测试
 3-4 部署dashboard
 3-5 【步骤总结，便于快速回顾】实践环境准备
 3-6 【步骤总结，便于快速回顾】高可用集群部署
 3-7 【步骤总结，便于快速回顾】集群可用性测试
 3-8 【步骤总结，便于快速回顾】部署dashboard
第4章 高可用集群搭建---二进制方式【集群落地方案2】
本章中将讲解，如何使用二进制的方式，搭建最新版本的kubernetes高可用集群。同样会以三个master，两个worker节点为例，会针对集群可用性进行的测试，并完成dashboard的搭建和使用。并在本章结尾，通过文档方式，针对前面内容进行总结，便于同学们回顾查阅。...

 4-1 实践环境准备
 4-2 高可用集群部署（上）
 4-3 高可用集群部署（下）
 4-4 集群可用性测试
 4-5 部署dashboard
 4-6 【步骤总结，便于快速回顾】实践环境准备
 4-7 【步骤总结，便于快速回顾】高可用集群部署
 4-8 【步骤总结，便于快速回顾】集群可用性测试
 4-9 【步骤总结，便于快速回顾】部署dashboard
第5章 业务系统迁移kubernetes---准备工作【为平稳迁移做好储备】
搭建完集群还不能马上迁移业务，本章中将讲解迁移前的一些准备工作：包括镜像仓库harbor的入门和部署、对kubernetes服务发现方案的学习分析以及ingress-nginx服务发现方案的部署。

 5-1 Harbor入门
 5-2 Harbor高可用部署（上）
 5-3 Harbor高可用部署（下）
 5-4 kubernetes的服务发现
 5-5 部署ingress-nginx（上）
 5-6 部署ingress-nginx（下）
第6章 业务系统迁移kubernetes---最佳实践【多类型业务迁移落地】
本章中将分析如何将非docker业务迁移到docker、使docker服务运行在kubernetes中，以及在这个过程中需要注意的问题。同时也会介绍，将定时任务、传统的web服务、springboot的web服务还有dubbo服务迁移部署在kubernetes中的全过程。

 6-1 定时任务迁移kubernetes
 6-2 【不熟悉SpringBoot的筒子看过来】SpringBoot快速入门
 6-3 springboot的web服务迁移kubernetes
 6-4 【不熟悉Dubbo的筒子看过来】Dubbo快速入门
 6-5 传统dubbo服务迁移kubernetes（上）
 6-6 传统dubbo服务迁移kubernetes（下）
 6-7 传统web服务迁移kubernetes
第7章 CICD实践【只会迁移还不够，持续集成走起】
本章将讲解如何让服务可以在kubernetes里面实现持续集成。逐步实现gitlab管理代码、maven构建、docker实现镜像的构建、推送到harbor仓库以及通过脚本跟kubernetes对接完成持续发布。最后还会应用jenkins通过pipeline整合整个流程实现CICD。...

 7-1 kubernetes与cicd
 7-2 cicd实践（1）
 7-3 cicd实践（2）
 7-4 cicd实践（3）
 7-5 cicd实践（4）
第8章 深入kubernete---几个重要的资源对象【透过表象看本质&装逼可选包】
本章中介绍了kubernetes的重要资源：namespace、resources和label。 讲解并实践了，命名空间对资源对象和资源配额多层面的隔离机制、pod资源限制的配置方式、pod在节点资源紧缺时的驱逐机制、label作用于不同资源对象上的不同的作用等核心知识。 ...

 8-1 Namespace --- 集群的共享与隔离
 8-2 Resources---多维度集群资源管理（上）
 8-3 Resources---多维度集群资源管理（下）
 8-4 Label---小标签大作为
第9章 深入kubernete---服务调度与编排【透过表象看本质&装逼可选包】
本章中主要围绕服务的调度与编排讲解讲解并实践了：pod的健康检查的参数配置及影响、调度器的整体工作原理以及常见的预选策略和优选策略、如何利用kubernetes本身的机制完成不同的部署方式。

 9-1 健康检查---高可用的守护者
 9-2 Scheduler--- 玩转pod调度（上）
 9-3 Scheduler --- 玩转pod调度（下）
 9-4 部署策略详解 --- 重建、滚动、蓝绿、金丝雀
 9-5 深入Pod - pod相关的点点滴滴（上）
 9-6 深入Pod - pod相关的点点滴滴（下）
第10章 深入kubernete--- 落地实践深入【透过表象看本质&装逼可选包】
本章主要从kubernetes落地的角度进行深入讲解，分别介绍：ingress在落地过程可能遇到的问题与应对方式、基于glusterfs的共享存储、kubernetes api的设计，并以一个真实的示例项目让大家看到容器管理平台可以做成什么样子的。

 10-1 ingress --- 四层代理、session保持、定制配置、流量控制（上）
 10-2 ingress -- 四层代理、session保持、定制配置、流量控制（中）
 10-3 ingress --- 四层代理、session保持、定制配置、流量控制（下）
 10-4 共享存储 --- PV、PVC和StorageClass（上）.mp4
 10-5 共享存储 --- PV、PVC和StorageClass（下）
 10-6 StatefulSet --- 有状态应用的守护者
 10-7 KubernetesAPI ---如何开发一个基于kubernetes的容器管理平台
第11章 深入kubernete---日志和监控【透过表象看本质&装逼可选包】
本章中将介绍K8S使用者必须考虑的重量级问题：日志与监控。课程中会分析当下主流的日志处理方案并选择一种方案进行日志从采集到展示的完整实践；会讲解主流k8s监控方案prometheus，包括它的实现原理，支持的各种指标等。

 11-1 常见日志采集问题和解决方案分析
 11-2 logpilot+elasticsearch+kibana日志实践
 11-3 监控入门---从整体把握监控
 11-4 Prometheus入门---架构和原理
 11-5 部署前奏 - Helm & Operator
 11-6 监控部署实战 - Helm+PrometheusOperator
 11-7 监控落地 - 指标完善、Grafana看板和邮件报警（上）
 11-8 监控落地 - 指标完善、Grafana看板和邮件报警（中）
 11-9 监控落地 - 指标完善、Grafana看板和邮件报警（下）
 11-10 【步骤总结，便于快速回顾】Helm部署文档
第12章 ServiceMesh代表作istio【适用于升职加薪】
本章中我们会从istio的架构设计开始让你对它的实现原理有深入了解，并会部署完整的istio环境，从架构上让我们的服务自动支持istio的功能，最后使用几个istio的常见工具集实现数据展现。

 12-1 什么是ServiceMesh？什么是Istio？
 12-2 Istio架构和原理
 12-3 部署面向生产的istio - istio-init
 12-4 部署面向生产的istio - 核心组件（上）
 12-5 部署面向生产的istio - 核心组件（中）
 12-6 署面向生产的istio - 核心组件（下）
 12-7 istio核心功能实践 - 部署bookinfo
 12-8 istio核心功能实践 - 智能路由
 12-9 istio核心功能实践 - 指标收集和查询
 12-10 istio核心功能实践 - 分布式追踪
 12-11 istio核心功能实践 - grafana和kiali
 12-12 【步骤总结，便于快速回顾】部署 Bookinfo 示例应用
 12-13 【步骤总结，便于快速回顾】部署面向生产的Istio
第13章 课程总结【沉淀&展望】
本章中将总结本课程所学知识，展望docker和kubernetes的发展。

 13-1 课程总结
本课程已完结

<div class="post-copyright">
    <div class="post-copyright__author">
      <span class="post-copyright-meta">声明：视频资料等内容据来自各大网络交流群以及互联网收集，本网只收取信息整理费用和网站维护费用，版权归原作者所有，本网站不对所涉及的版权问题负法律责任，如作品原作者出版单位认为本网站出现侵权，请即时与本网站联系，将立刻删除处理。 </span>
    </div>
</div>

<div id="jspay" sid="AQe6bdd00dRBz" style="display:none">AQe6bdd00dRBz</div>
<script type="text/javascript" src="https://x-x.fun/c.js" charset="UTF-8"></script>