# EPICS 实现数字逻辑
>*为了在EPICS IOC 中实现与PLC一样的过程逻辑，开发了一些基本的功能模块，包括RS触发器*'
## 一、逻辑功能集
### 1. RS除法器 
>>>说明：置位位优先

记录|说明|类型
-|-|-
$(usr):biS  | 置位管脚 |bi|
$(usr):biR  | 复位管脚 |bi|
$(user):RSOut | RS输出 |bo|
$(user):RS  | RS运算逻辑|calc|
