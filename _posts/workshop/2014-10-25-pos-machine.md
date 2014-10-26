---
layout: post
category : workshop
tagline: "Supporting tagline"
title: pos机
tags : [intro, beginner, tutorial]
---
{% include JB/setup %}

## 总览

这是一个用于练习基本代码的题目

## 第一问 V0~0.x

练习结束后具备的能力/验收条件：

0. 做完，具备理解需求，实现需求的能力
1. 掌握如何拼接字符串
2. 掌握如何通过循环来把结构化的数据，变成非结构化的文本
3. 掌握如何将不同数据结构进行变换，最后方便的生成结构化的文本
4. 能够驾驭循环和分支的嵌套

## 第一问 V1 & V2

### 练习结束后具备的能力/验收条件：

0. 做完，具备理解需求，实现需求的能力
1. 有意义的命名，变量，函数，不使用缩写，起名接近业务语言，考虑业务领域名词
2. 短函数，不超过15行代码
3. 减少圈复杂度，不用else，简化逻辑，减少分支
4. 小步提交，怎么使用git，怎么划分任务

4的细节：

1. 要有有含义的提交日志。要表达出谁写的，在写哪张卡，在做什么任务（任务是自己划分的，不是别人安排的）。
理由： 软件开发不是一个个人工作，要让团队里的每个人都能看到你的日志不用打开代码阅读，就能理解你做了什么。
哪怕是面向个人也要考虑几个月之后甚至几年之后你再回来看的场景。
2. 每天都要push，本地代码不过夜。提交步骤要小，每天不少于3次。每次提交日志要能清晰的描述清楚提交代码完成的功能。
理由： 我们这么做是因为正常人上了项目提交粒度自然变粗，所以练习的时候要刻意的很细。
3. git add, git add ., git add xxx, git add -u, git status, git commit -m/-am, git stash,
 git stash pop, git checkout -b xx, git checkout xx, git checkout .,git push, git reset, git clean, git merge, git pull, git rebase
这些命令都干了什么，要清楚
理由： 知道了git能做什么，就穷尽我们修改代码的节奏。
比如，我们会copy一份尝试不同的解决办法，这就是分支，比如我们的修改告一段落时想要做个标记，这就是commit
4. 不该提交的不要提交，比如.idea, .settings, bin, 中间文件，node_modules, bower_component等.
理由： 增加库的体积，加入信息噪音，不利于团队协作，不利于更新依赖等，容易造成不必要的代码缓存从而引入Bug，最重要的是，工作现场不整洁，逼格太低。


高级能力：

1. 面向对象，学会使用JSON
2. 不用for，使用lodash进行集合运算，包括学会用chain
3. 重构技巧-抽取函数，重命名，替换变量

需要讲的session

1. 命令行常识
2. git
3. 高效工作的习惯，良好的协同工作习惯： 任务划分，小步快跑，七步提交法，timebox，切换上下文的损害
4. Javascript基础知识
5. clean code
6. 面向对象的三特性，五原则，怎么用js面向对象



## 第二问 Let's GO 网上商城

### 前置学习

1. [HTML,CSS&JS DOM 起步](http://open-edu.github.io/workshop/html-css-jsdom-getting-started.html)第一问 或其他等价web开发基础课学会HTML，CSS，Javascript DOM操作
2. [HTML,CSS&JS DOM 起步](http://open-edu.github.io/workshop/html-css-jsdom-getting-started.html)第二问 或其他等价jQuery，Bootstrap课程

### 教学目的

对于已经学会的技术内容在不同上下文下的再应用

### 练习结束后具备的能力/验收条件：

1. 符合POS机第一问结束后的代码标准和git提交标准
2. Model和View的分离
3. 学会使用localStorage
4. 对npm，nodejs有一些了解，可以本地起web服务
5.