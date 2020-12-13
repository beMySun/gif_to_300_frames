## 背景

微信公众号对gif 有比较两大的限制： 
 
1. 单张不超过10M
2. 单张不能多于300帧

解决不超过10M， 比较简单， 也有非常多的在线工具， 比如：
```
https://www.yasuotu.com/
```

但是去帧就比较麻烦，只能用PhotoShop删除一部分帧。

但这样实在太慢了, 所以我找了个脚本, 可以将脚本同级目录下的 gif 图, 调整到不超过 300 帧, 并输出到同级目录。

脚本原地址：https://github.com/zhaoolee/cgf/blob/master/gifdir/to_300.py

## 如何使用这个脚本：

- 1. 安装 python3
- 2. 在 gifdir 目录下执行: 

``` py
python3 to_300.py

```

## 后续要增加的功能：
- 图片批量压缩