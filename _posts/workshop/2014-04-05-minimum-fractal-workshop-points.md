---
layout: post
category : workshop
tagline: "Supporting tagline"
title: 最小分形体验
tags : [intro, beginner, tutorial]
---
{% include JB/setup %}

## 总览

该部分是为一年级大学生体验用的课程设计，整个课程是为了让初学者体验完整的开发过程。
虽然简化，但是非常完整。各个环节有所省略，但是整个过程确实是完整的。
所谓完整是从开发到用户可以接触到为止。

简单来说，这就是一个可以走完全程的最小环境。就像分型图形的最小图形，甚至是变过一次形的。
以这个为媒介，让学生对于未来的软件开发过程有一个整体的体验。以后说起某个环节能让他跟曾做过的某件事情相联系。
因为关联是记忆的本质。

简单说来，这个课程就类似武术套路，如果没有合适的指点，只是一个花架子而已。
但是花架子有花架子的好处，起码把该具备的动作都已经记住了，提起某些概念不至于模糊不清，不知道说什么了。
这个时候，有些讲课的人就会说，你慢慢悟吧。
讲知识时让别人悟除了让讲的人觉得自己比听得人聪明以外实在是没有其他的作用，所以应该做些什么减少悟的时间。

### 教学节奏与教学内容

一共6个全天，每个半天都要有自己的教学目标。教学的内容以软件开发为主线，穿插各个阶段的配置管理为教学核心。

主要涉及的内容及辅助工具有：

1. 需求管理 - Trello
2. 源代码管理 - Github
3. 测试管理 - Cucumber
4. 构建管理 - Rake/Thor/Shell & GO
5. 部署管理 - GO & 阿里云/个人机器/某虚拟机
6. 运维管理 - Splunk

## 教学安排

### 第一天

#### 上午

第0课， GoAgent，翻过墙，知识不需要墙。
要求所有学生复制Trello到自己的Board，理解需求卡片，为什么这么写需求。在真实项目中，我们会怎么使用卡片。
试图找出卡上不合逻辑的地方和模棱两可的地方。
练习返讲。

#### 下午

安装Ruby，Rails，用Rails创建一个基本的Rails app。然后把它传到Github上去。
预先需求： git, github账号, sublime/eclipse/notepad++/rubymine/emacs/vim

练习的内容：

- clone
- push
- pull
- commit
- add
- rename
- move
- delete
- ignore
- diff
- status
- log
- merge

讲到的内容：

- revert
- fork
- pull request
- branch
- tag
- checkout

详细流程

1. 先建立一个github账号
1. 创建一个自己的库
1. 本地init
1. touch 一个README
1. git status
1. add
1. git status
1. commit
1. git status
1. push（查一下-u是什么）
1. 看看github上变成了什么。
1. 查看.gitignore
1. 再体验一遍，创建一个文件readme吧，添点内容，看看status
1. add，看看status
1. 再commit，看看status，跟刚才有什么区别。理解local commit
1. push，这回没有了-u了
1. 去服务器改改readme
1. 然后本地也改改，push下，肯定失败。pull下来，严格要求怎么改，不能出现冲突。
1. 然后要求改同一行。pull，看看conflict，处理conflict。
1. 将readme改为readme.md

### 第二天～第三天


仿照Rails Guide完成一个简单Blog的搭建

具体流程：

- 先用genrator创建一个post
- 再用bootstrap重写页面
- 加入一个简单测试
- 加入用户登录，登录的用户才能看到添加按钮，才能进入添加页面，才能看到修改按钮，才能进入修改页面。
- 我省掉了任务划分部分。为了提高效率。


### 第四天

#### 上午

用Cucumber写测试，跑测试

- 创建一个测试，可以访问列表页面要求列表页面，只需要打开，看到某些要素即可。
- 创建一个测试，可以访问访问列表页面，从列表页面进入创建页面，从创建页面创建某标题的博客，然后确认回到列表页面，并找到刚才创建的标题的那一项。

### 下午


搭建一个持续集成环境，必要的话把测试环境，产品环境都部署好。

- 安装GO
- 创建一个测试环境。要有passenger，手动部署一次。
- 提交一个简单的对README的修改。
- 看看GO如何从下代码，跑测试，跑脚本：部署rails到passenger，drop数据库，运行migration，执行seed，跑cucumber测试


### 第五天

#### 上午

继续部署持续集成环境

#### 下午

开始搭建持续交付环境

### 第六天

装一个splunk
回顾



