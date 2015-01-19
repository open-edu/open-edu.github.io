---
layout: post
category : workshop
tagline: "Supporting tagline"
title: 武器进化与OO 教学重点 - live template
tags : [intro, beginner, tutorial]
---
{% include JB/setup %}



## 总览

live template是用于新建文本内容时的宏。抽取live template有利于发现我们工作中的重复。
当我们一次次的输入做同样的内容的时候，就意味着我们需要一个live template来减少我们的重复动作了。

live template等快捷输入方式的使用让我们在平时敲击键盘的时候都在思考我们哪里有重复，有利于工程师思维的建立和敏锐度的培养。

### 要训练出的live template有

desc 用于生成describe

    describe("$SECTION_DESC$", function(){
        $END$
    });

test 用于生成it

    it("$TEST_CASE$", function(){
        $END$
    });

class 用于生成js的class

    function $CLASS_NAME$($PARAMS$){
        $END$
    }

ta

    this.$FIELD_NAME$ = $FIELD_NAME$;

extend 用于生成js的extend


    function $CLASS_NAME$($PARAMS$){
       $PARENT_NAME$.call(this, $PARAMS$$END$);
    }
    $CLASS_NAME$.prototype = Object.create($PARENT_NAME$.prototype);
    $CLASS_NAME$.prototype.constructor = $CLASS_NAME$;


m 用于生成js的method

    $CLASS_NAME$.prototype.$METHOD_NAME$ = function($PARAMS$){
        $END$
    }

exp 用于生成js的module export

    module.exports = $EXPORT$;$END

re

    var $GLOBAL_NAME$ = require('$PATH$');$END$

each

    for (var $INDEX$ = 0; $INDEX$ < $ARRAY$.length; $INDEX$++) {
      var $VAR$ = $ARRAY$[$INDEX$];
      $END$
    }


