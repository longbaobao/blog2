---
layout: 人工智能研发攻城狮
title:  慕课网《 Google老师亲授 TensorFlow2.0 入门到进阶》 前9章
date: 2019-08-07 19:34:13
tags:
  - 后端研发
  - 人工智能
  - TensorFlow
  - 慕课网
categories:
  - 人工智能研发攻城狮
keywords: 慕课网《 Google老师亲授 TensorFlow2.0 入门到进阶》 前9章
---
『课程目录』:  
Google老师亲授 TensorFlow2.0 入门到进阶
课程以Tensorflow2.0框架为主体，以图像分类、房价预测、文本分类、文本生成、机器翻译、泰坦尼克生存预测等项目为依托，讲解Tensorflow框架的使用方法，让学员获得灵活使用Tensorflow的能力，同时学习到相关的深度学习/机器学习知识，达到初级深度学习工程师的水平

<!-- more --> 
<blockquote class="blockquote-center">
请支持原版！课程官方链：https://coding.imooc.com/class/344.html</blockquote>
</blockquote>
第1章 Tensorflow简介与环境搭建
本门课程的入门章节，简要介绍了tensorflow是什么，详细介绍了Tensorflow历史版本变迁以及tensorflow的架构和强大特性。并在Tensorflow1.0、pytorch、Tensorflow2.0之间做了对比。最后通过实战讲解了在Google cloud和AWS两个平台上的环境配置。

 1-1 课程导学 试看
 1-2 Tensorflow是什么
 1-3 Tensorflow版本变迁与tf1.0架构
 1-4 Tensorflow2.0架构 试看
 1-5 Tensorflow&pytorch比较 试看
 1-6 Tensorflow环境配置
 1-7 Google_cloud无GPU环境搭建
 1-8 Google_cloud_远程jupyter_notebook配置
 1-9 Google_cloud_gpu_tensorflow配置
 1-10 Google_cloud_gpu_tensorflow镜像配置
 1-11 AWS云平台环境配置
第2章 Tensorflow keras实战
本门课程的基础章节，详细介绍了如何使用tf.keras进行模型的搭建以及大量的深度学习的理论知识。理论知识包括分类问题、回归问题、损失函数、神经网络、激活函数、dropout、批归一化、深度神经网络、Wide&Deep模型、密集特征、稀疏特征、超参数搜索等及其在图像分类、房价预测上的实现。...

 2-1 tfkeras简介
 2-2 分类回归与目标函数
 2-3 实战分类模型之数据读取与展示
 2-4 实战分类模型之模型构建
 2-5 实战分类模型之数据归一化
 2-6 实战回调函数
 2-7 实战回归模型
 2-8 神经网络讲解
 2-9 实战深度神经网络
 2-10 实战批归一化、激活函数、dropout
 2-11 wide_deep模型
 2-12 函数API实现wide&deep模型
 2-13 子类API实现wide&deep模型
 2-14 wide&deep模型的多输入与多输出实战
 2-15 超参数搜索
 2-16 手动实现超参数搜索实战
 2-17 实战sklearn封装keras模型
 2-18 实战sklearn超参数搜索
第3章 Tensorflow基础API使用
接上一节课中使用高级抽象的API tf.keras搭建模型，本节课则介绍了基础的API来方便大家更加灵活的定义和使用模型。课程内容包括tensorflow基础数据类型、自定义模型和损失函数、自定义求导、tf.function、图结构等以及其在图像分类、房价预测上的实现。...

 3-1 tf基础API引入
 3-2 实战tf.constant
 3-3 实战tf.strings与ragged tensor
 3-4 实战sparse tensor与tf.Variable
 3-5 实战自定义损失函数与DenseLayer回顾
 3-6 使子类与lambda分别实战自定义层次
 3-7 tf.function函数转换
 3-8 @tf.function函数转换
 3-9 函数签名与图结构
 3-10 近似求导
 3-11 tf.GradientTape基本使用方法
 3-12 tf.GradientTape与tf.keras结合使用
 3-13 章节总结
第4章 Tensorflow dataset使用
介绍Tensorflow dataset空间下API的使用，dataset API主要用于读取数据。本届课程通过在房价预测问题上的实战详细的介绍如何使用tf.dataset读取csv文件和tfrecord文件。

 4-1 data_API引入
 4-2 tf_data基础API使用
 4-3 生成csv文件
 4-4 tf.io.decode_csv使用
 4-5 tf.data读取csv文件并与tf.keras结合使用
 4-6 tfrecord基础API使用
 4-7 生成tfrecords文件
 4-8 tf.data读取tfrecord文件并与tf.keras结合使用
 4-9 章节总结
第5章 Tensorflow Estimator使用与tf1.0
本节课分为两部分，第一部分介绍tensorflow中estimator和特征列的API的使用，estimator是和keras平级的用于模型抽象的高级API，会使用泰坦尼克生存预测项目来详细的讲解特征抽取和estimator使用。学习完以上的基础知识后，在第二部分中会讲解tf1.0的知识点来方便大家对比2.0与1.0的区别。...

 5-1 课程引入
 5-2 泰坦尼克问题引入分析
 5-3 feature_column使用
 5-4 keras_to_estimator
 5-5 预定义estimator使用
 5-6 交叉特征实战
 5-7 TF1.0引入
 5-8 TF1.0计算图构建
 5-9 TF1.0模型训练
 5-10 TF1_dataset使用
 5-11 TF1_自定义estimator
 5-12 API改动升级与课程总结
第6章 卷积神经网络
本节课程依托图像分类与两个Kaggle数据集项目，主要讲解卷积神经网络，包括卷积、池化、卷积网络、数据增强、迁移学习等知识。详细的讲解了卷积操作的过程。同时还对如何使用Kaggle平台上的GPU进行的讲解。

 6-1 卷积神经网络引入与总体结构
 6-2 卷积解决的问题
 6-3 卷积的计算
 6-4 池化操作
 6-5 卷积神经网络实战
 6-6 深度可分离卷积网络
 6-7 深度可分离卷积网络实战
 6-8 Kaggle平台与10monkeys数据集介绍
 6-9 Keras generator读取数据
 6-10 10monkeys基础模型搭建与训练
 6-11 10monkeys模型微调
 6-12 keras generator读取cifar10数据集
 6-13 模型训练与预测
 6-14 章节总结
第7章 循环神经网络
本节课程依托文本分类和文本生成两个项目，对序列式问题、循环神经网络、LSTM、双向LSTM等模型进行了详细的讲解和实战。

 7-1 循环神经网络引入与embedding
 7-2 数据集载入与构建词表索引
 7-3 数据padding、模型构建与训练
 7-4 序列式问题与循环神经网络
 7-5 循环神经网络实战文本分类
 7-6 文本生成之数据处理
 7-7 文本生成实战之构建模型
 7-8 文本生成实战之采样生成文本
 7-9 LSTM长短期记忆网络
 7-10 LSTM文本分类与文本生成实战
 7-11 subword文本分类之数据集载入与tokenizer 
 7-12 subword文本分类之dataset变换与模型训练 
 7-13 章节总结 
第8章 Tensorflow分布式
本节课程依托图像分类项目，对tensorflow框架中的分布式原理和策略进行了详细的讲解，并在实战中予以实现。尤其是对参数服务器的分布式的并行架构进行详细的阐述。

 8-1 课程引入与GPU设置
 8-2 GPU默认设置
 8-3 内存增长和虚拟设备实战
 8-4 GPU手动设置实战
 8-5 分布式策略
 8-6 keras分布式实战
 8-7 estimator分布式实战
 8-8 自定义流程实战
 8-9 分布式自定义流程实战
第9章 Tensorflow模型保存与部署(未完待续)
本节课程依托图像分类项目，对tensorflow模型和部署进行了详细的讲解，包括普通的模型保存、tflite的使用、模型的android的部署、在js上的部署等以及对应的实战。

 9-1 课程引入与TFLite_x264 
 9-2 保存模型结构加参数与保存参数实战 
 9-3 Keras模型转化为SavedModel 
 9-4 签名函数转化为SavedModel 
 9-5 签名函数，SavedModel和Keras模型到具体函数转换 
 9-6 tflite保存与解释与量化 
第10章 机器翻译与tensor2tensor使用(未完待续)
本节课程依托机器翻译项目，对transformer模型进行了详细的讲解，包括可缩放点积注意力、多头注意力等知识。并对该模型进行了实现。同时，讲解了tensorflow中常用算法库tensor2tensor的使用，并使用tensor2tensor中已有的最新算法在图像分类和机器翻译上进行了最高效果的训练。...

 10-1 课程引入与seq2seq+attention模型讲解 
 10-2 数据预处理理与读取 
 10-3 数据id化与dataset生成 
 10-4 Encoder构建 
 10-5 attention构建 
 10-6 Decoder构建 
 10-7 损失函数与单步训练函数 
 10-8 模型训练 
 10-9 模型预测实现 
 10-10 样例例分析与总结 
 10-11 Transformer模型总体架构 
 10-12 Transformer模型之Encoder-Decoder架构与缩放点击注意力 
 10-13 Transformer模型之多头注意力与位置编码 
 10-14 Transformer模型之Add、Normalize、Decoding过程与总结 
<div class="post-copyright">
    <div class="post-copyright__author">
      <span class="post-copyright-meta">声明：视频资料等内容据来自各大网络交流群以及互联网收集，本网只收取信息整理费用和网站维护费用，版权归原作者所有，本网站不对所涉及的版权问题负法律责任，如作品原作者出版单位认为本网站出现侵权，请即时与本网站联系，将立刻删除处理。 </span>
    </div>
</div>

<blockquote class="blockquote-center">
链接：https://pan.baidu.com/s/1rep2-6rpCJrFndZMIfdc3A 
提取码：zjn7 
复制这段内容后打开百度网盘手机App，操作更方便哦
</blockquote>

