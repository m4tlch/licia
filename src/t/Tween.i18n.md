## CN

JavaScript 补间动画库。

继承自 Emitter 类。

### constructor

|参数名|类型|说明|
|-----|----|---|
|obj|object|要补间的对象|

### to

|参数名|类型|说明|
|-----|----|---|
|destination|obj|目标属性值|
|duration|number|补间时长|
|ease|string function|缓动函数|

### play

开始播放。

### pause

暂停动画。

### paused

检查动画是否暂停。

### progress

设置或获取动画进度。

|参数名|类型|说明|
|-----|----|---|
|[progress]|number|介于 0 到 1 之间的数字|

