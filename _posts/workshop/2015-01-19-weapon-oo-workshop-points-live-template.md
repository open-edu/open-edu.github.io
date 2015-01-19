---
layout: post
category : workshop
tagline: "Supporting tagline"
title: 武器进化与OO 教学重点 - live template
tags : [intro, beginner, tutorial]
---
{% include JB/setup %}



## 总览

### 要训练出的live template有

desc 用于生成describe

```
describe("$SECTION_DESC$", function(){
    $END$
});
```

test 用于生成it

```
it("$TEST_CASE$", function(){
    $END$
});
```

class 用于生成js的class

```
function $CLASS_NAME$($PARAMS$){
    $END$
}
```

ta

```
this.$FIELD_NAME$ = $FIELD_NAME$;
```
extend 用于生成js的extend

```
function $CLASS_NAME$($PARAMS$){
    $PARENT_NAME$.call(this, $PARAMS$$END$);
}
$CLASS_NAME$.prototype = Object.create($PARENT_NAME$.prototype);
$CLASS_NAME$.prototype.constructor = $CLASS_NAME$;

```

m 用于生成js的method
```
$CLASS_NAME$.prototype.$METHOD_NAME$ = function($PARAMS$){
    $END$
}
```

exp 用于生成js的module export

```
module.exports = $EXPORT$;$END
```

re
```
var $GLOBAL_NAME$ = require('$PATH$');$END$
```

each
```
for (var $INDEX$ = 0; $INDEX$ < $ARRAY$.length; $INDEX$++) {
  var $VAR$ = $ARRAY$[$INDEX$];
  $END$
}
```


