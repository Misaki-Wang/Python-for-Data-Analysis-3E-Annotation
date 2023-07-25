# ndarray(gyw)

ndarray:通用的同构数据多维容器（同构即其中元素必须是相同类型的）

- 含有两种属性：
  - shape:表示各维度大小的tuple
  - dtype:说明数据的类型

## 创建方法：

![表4-1 数组创建函数](http://upload-images.jianshu.io/upload_images/7178691-78ab11f67e7077a6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 数据类型的转换：

`ndarray.astype("dtype")`

## Numpy数组的运算：

广播机制

## 切片和索引

基本索引：

- 切片是原数组的一个视图，任何更改将反应在原数组上
- `.copy()`来获得数组的副本
- 高维数组的切片

布尔型索引：

- 用逻辑表达式来进行索引，达到筛选的目的
- `and` `or` ,不能使用，用 `&` `|`

花式(fancy)索引：

- 花式索引赋值会修改原数组的值

## 转置和轴变换

`.T`  对矩阵进行简单转置

`.swapaxes( , )` 接受一对轴编号后进行轴变换

- 返回原数据视图，不进行复制

# 随机数生成

![img](http://upload-images.jianshu.io/upload_images/7178691-97ba09c96dab93a2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![img](http://upload-images.jianshu.io/upload_images/7178691-6ed04fae3d1178e2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 函数

![](http://upload-images.jianshu.io/upload_images/7178691-1d494e73b61c7ced.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/7178691-2be79faf68ab6ff8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/7178691-4e38d02a66481530.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/7178691-eff1e61e5464159f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/7178691-236dba83b6a420cc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/7178691-a6c6df3ca8e0b98e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/7178691-866fcde885b1d357.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/7178691-80e85ae6b9c89ada.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/7178691-dcdb66e49e5f70ea.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
