---
layout: post
category : baseline
tagline: "Supporting tagline"
tags : [intro, beginner, tutorial]
title : Java基线
---
{% include JB/setup %}

## 总览

这篇是基线项目的一部分，本文讲解了基本的Java技术的基线及验收条件（即题目）。

### 基线描述

* 语言基础知识。掌握其跨平台、面向对象、反射、泛型等特性；
* Servlet，了解标准 Servlet 的工作模式、生命周期，会通过实现 Servlet 接口来编写 Web 应用；
* 掌握 Spring Framework 一些特性；
* 基于 Java 的单元测试框架，比如 JUnit；

验收条件如下：

## 语言基础知识。掌握其跨平台、面向对象、反射、泛型等特性

### 跨平台：

1. 写作描述Java语言，讲述跨平台等特征及其实际的限制，可以描述一下SWT，要描述到运行时，编译这些概念。
2. 写一个简单程序，分别在linux, windows和mac的虚拟机下运行。（commandline版和GUI版都可以试试）

### 语言的基本语法及面向对象:

1. FizzBuzz题目
2. [武器进化与OO](https://gist.github.com/jtong/deaf54d5f7d3a44825b1) 完成全部6问并得到reviewer认可，要用到OO，合理的设计模式及泛型。
3. 画图讲解23种设计模式，并用一小时做presentation


### 反射，泛型，标注：

1. 用反射自己造一个依赖注入的框架，要支持构造器参数，支持初始化方法调用，支持基于setter的field注入，支持标注（待细化）
2. 用反射自己造一个ORM框架（1，2二选一）(待完成)
3. 深度反射元编程练习（可选）（待完成）
4. 深度泛型练习（可选）（待完成）

## Servlet，了解标准 Servlet 的工作模式、生命周期，会通过实现 Servlet 接口来编写 Web 应用

1. 写文章结合源码解释，描述标准 Servlet 的工作模式、生命周期，并可以用(待完成)
2. 一个基于Servlet的用户管理界面，基于RESTful的风格，需要登录(待完成)

## 掌握 Spring Framework 一些特性(反射练习建议在使用完Spring之后进行)

1. 搭建一个基于Spring MVC的Web网站。实现用户管理模块。用Spring访问数据库。(待完成)
2. 搭建一个Spring MVC+Spring IOC+Hibernate的网站。用到Spring的IOC和AOP (待完成)
3. 写作描述Spring MVC，Spring IOC，Spring AOP，Spring的事务(检查点待完成)
4. 画图描述Spring Framework并用半小时做presentation

## 基于 Java 的单元测试框架，比如 JUnit

1. [猜数字题目](/workshop/tdd-workshop.html),四问全部完成，要求学会使用junit，mockito和fest或hamcrest
2. 写作描述TDD，常用的mock场景，可以说pattern，也可以不说，但是起码要提到stub和mock。并在写作中画图讲解。

