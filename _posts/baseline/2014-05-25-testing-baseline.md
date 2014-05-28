---
layout: post
category : baseline
tagline: "Supporting tagline"
tags : [intro, beginner, tutorial]
title : 测试基线
---
{% include JB/setup %}


## 总览

这篇是基线项目的一部分，本文讲解了基本的测试方面的基线


### 基线描述

* 掌握单元测试的写法，会使用测试工具编写单元测试，比如 JUnit、rspec 等；
* 掌握基于页面的测试工具，比如 capybara 等，会使用PageObject模式和组件模式抽象测试步骤；
* 了解 moco,sonar,JMeter 等测试工具；

验收标准如下：

## 掌握单元测试的写法，会使用测试工具编写单元测试，比如 JUnit、rspec 等；

1. 使用Java或其他语言完成猜数字全部四问,如果可能完成对战的第五问,试着给测试编写DSL
2. 写文章描述TDD的主要重点，Mock技法的重点

## 掌握基于页面的测试工具，比如 capybara 等，会使用PageObject模式和组件模式抽象测试步骤；

1. 学习BDD Workshop
2. 对于一个准备好的遗留系统提取Page Object模式的测试步骤DSL
3. 对于一个准备好的单页面application遗留系统提取组件模式的测试步骤DSL(用bootstrap搭建一个单页面application就可以)

## 了解 moco,sonar,JMeter 等测试工具；

1. 用moco搭建一个mock server模拟服务端
2. 用sonar对之前的猜数字进行测试覆盖率统计
3. 用Jmeter对一个准备好的系统进行测试, 用Locust和Gatling重新实现一下(系统可以用node.js写,这样承载的内容大一些.准备一个vagrant虚拟机就好了)
