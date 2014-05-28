---
layout: post
category : baseline
tagline: "Supporting tagline"
tags : [intro, beginner, tutorial]
title : 持续交付基线
---
{% include JB/setup %}

## 总览

这篇是基线项目的一部分，本文讲解了基本的持续交付方面的基线


### 基线描述

* 会用常见的 CI 工具，比如 Jenkins 等；
* 了解如何通过代码来部署，比如 shell、chef、RPM、DEB 等；

验收条件如下：

## 会用常见的 CI 工具，比如 Jenkins 等；

1. 给予一个github上的基于Rails的Web项目(node.js, JEE,and so on...)和一个vagrant vm.然后用GoCD完成他的持续部署.
2. 对上面的项目用GoCD建立一个Pipeline, 在这个项目上有单元测试,自动化验收测试
3. 用jenkins完成持续部署,并建立一个pipeline

## 了解如何通过代码来部署，比如 shell、chef、RPM、DEB 等；

1. 上面的练习就兼顾到了,如果需要就先练怎么手动用脚本部署,再用CI工具自动化
2. 试着用chef或puppet来准备vm
