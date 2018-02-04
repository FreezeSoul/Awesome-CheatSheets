﻿> 本文正在逐步完善中，为了保证文章的整体性请务必不要在笔者宣告完成之前擅自转载，谢谢。因为笔者主要投递的方向是 Web 前端开发与服务端应用程序/大数据分析开发这两个方向，对于 iOS、Android、C++、机器学习算法涉及不多，不过它山之石，可以攻玉，如果你在目录中发现感兴趣的部分也欢迎阅读相关部分。另外，如果有涉及 iOS、Android、C++、机器学习算法与本文类似的提纲挈领的文章也很欢迎推荐，经原作者允许可以在本文添加外链以方便大家知识共享。另外，需要实现说明的是，本文以校招时笔者水准，对于很多知识点并不能深入，若有谬误烦请包涵指正。

>

* [google-interview-university](https://github.com/jwasham/google-interview-university#recursion)

# 编程基础

## Java

关于此部分的详细索引可以参考笔者的[Java 入门与最佳实践](https://github.com/wxyyxc1992/WXJavaToolkits)系列文章。

### 字符串处理

### 集合类型

### 流程控制

#### 分支循环

Java 中 Switch 可以使用 String 作为校验值，不过是在 1.6 之后才添加进来的，并且只能使用`hashCode`作为校验值。

#### 运算符

#### 异常处理

### 并发编程

#### 锁

#### 内置的线程安全模型

### JVM 内部原理

关于 JVM 部分的详细索引可以参考笔者的[JVM 入门与最佳实践](https://github.com/wxyyxc1992/WXJavaToolkits#jvmjava-virtual-machine)

## JavaScript

关于 JavaScript 部分的详细索引可以参考笔者的[JavaScript 入门与最佳实践](https://github.com/wxyyxc1992/web-frontend-practice-handbook#javascript)

### 常用数据类型

### 函数与闭包

### 面向对象:原型继承与 this

# CS 通识

## 操作系统

## 网络

## 并发编程

## 设计模式

# 数据结构与算法

关于数据结构与算法系列详细的文章列表可以参考笔者的[数据结构与算法系列综述](https://github.com/wxyyxc1992/just-coder-handbook/blob/master/DataStructure/README.md#graph%E5%9B%BE)
笔者也是本次校招开始之后短短月余的时间才开始刷题，如果只是为了应付校招多学点套路也能说得过去，但是刷题本身的热趣确实挺有意思。关注笔者的博客或者 Github 的朋友应该知道，笔者过去几年里一直以工程应用于产品开发为重，老实说，很多时候解决真实场景下的问题需要动的脑子不如做几个算法题，可能带来的成就感也见仁见智。以华为为例，还有一种常见的 OJ 题目便是场景题，并不需要多么复杂的算法设计与考虑，而主要考察你对于用户需求的理解与具体编程能力、编程的精细度与代码掌控力的探查。

## 字符串操作

### 模式匹配

### 回文字串

## 树与图

### BFS 与 DFS

#### 迷宫问题

## 排序

## 搜索

## 科学计算

## 优化算法

### 递归

### 动态规划

#### 股票买卖

### 回溯

# Web 前端开发

## DOM 基础

## HTML+CSS 基础

## 常用框架与类库

### React

## 常用构建工具

### Webpack

## 前端优化

### 性能优化

前端优化的根本目的是为了有一个更好地用户体验的同时尽可能减少后端负载压力。即保证更少的加载时间、更快的首屏渲染、更流畅的用户交互。在笔者自己的知识体系内，当我们想为用户呈现更好的视觉效果与用户体验时，我们往往会从[性能评测与监控](https://github.com/wxyyxc1992/web-frontend-practice-handbook/blob/master/advanced/Optimization/FrontendOptimization-Benchmark.md)、[资源与请求优化](https://github.com/wxyyxc1992/web-frontend-practice-handbook/blob/master/advanced/Optimization/FrontendOptimization-Resource-Request.md)、[加载策略](https://github.com/wxyyxc1992/web-frontend-practice-handbook/blob/master/advanced/Optimization/FrontendOptimization-Load.md)、[首页与关键路径](https://github.com/wxyyxc1992/web-frontend-practice-handbook/blob/master/advanced/Optimization/FrontendOptimization-HomePage-CriticalPath.md)、[渲染优化](https://github.com/wxyyxc1992/web-frontend-practice-handbook/blob/master/advanced/Optimization/FrontendOptimization-Render.md)这几个方面进行考虑。

### 响应式网页

## Web 网络安全

这部分可以参考笔者的[信息安全系列文章](https://github.com/wxyyxc1992/infosecurity-handbook)，如果对 Web 网络安全基础想要有个了解可以阅读[笔者翻译的 Martin Fowler 的 Web 应用安全基础](https://segmentfault.com/a/1190000004983446)。

### SQL 注入

### XSS

### CSRF

### WebShell

# 服务端应用程序

## API 层

## 应用层

### Spring

#### Bean

* 远程 Bean 的构建

### Express

#### AOP

# 基础架构与大数据

## 数据存储

### MySQL

### Redis

关于 Redis 部分的详细知识点可以参考笔者的[Redis 入门与最佳实践](https://github.com/wxyyxc1992/infrastructure-handbook#redis)

#### Redis 基础数据结构

#### Redis 集群

#### Redis 底层架构

#### Redis 调优

## Hadoop Ecosystem

笔者在这里并没有列举 Spark/Storm/Flink 这些，感觉这些针对性可能更强一点，如果大家觉得这部分也有很大的必要列入清单请留言。

### HDFS

### MapReduce

### HBase

### Hive

## Virtualization

# 面试随笔

一般而言，准备的充分应付笔试应该绰绰有余，不要像笔者这样在校招开始之后才猛然发现自己两手空空的奔赴战场，被打个手足无措就好。笔试之后即是面试，从笔者自己的经验来看，面试一定要掌握好节奏。笔者自己原来创业或者带团队的时候也经常招聘面试别人，如果你的简历一穷二白，或者千篇一律，毫无特色，那么面试官也是觉得很难做的，只能按照程序化的东西问题。面试官更想了解的是你做过啥，那么我们应该尽可能地寻找机会去展示自己会的东西。譬如如果问你 Log4j 的用法，那么在标准回答之后可以适当扩展，从经典的基于 ELK 的日志处理到基于 Flume、HDFS、Hive 这一系列的日志处理方案或者基于 Kafka+Flink 的实时日志处理，应该尽可能地去回答自己懂的东西。瑕不掩瑜，那也要尽可能地去将自己的闪光点展示出来。
