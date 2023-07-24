# 基本数据结构

两种基本的数据结构

**一维的 Series**  &  **二维的 DataFrame**

## Series

### 4个组成部分

1. data 序列的值  `.values`
2. index 索引 `.index`
3. dtype 存储类型 `.dtype`
4. name 序列名称 `.name`

### 创建方法

1. 数组 直接创建
2. 数组 + 索引
3. 字典创建
   可以通过自己想要的顺序传给构造函数，生成符合预期的Series索引

### 操作

1. `.`来获得属性
2. `.shape`来获得序列的长度
3. `[index_item]`来取出单个索引对应的值
4. `.to_dict`转为字典
5. `.isna()` `.notna()` 检测缺失数据



## DateFrame

### 5个组成部分

1. data 序列的值  `.values`
2. index 行索引 `.index`
3. columns 列索引 `.columns` 
4. dtype 存储类型 `.dtype  # 返回的是值为相应列数据类型的Series`
5. name 序列名称 `.name` df本身并没`name`属性，而是其`index` `columns`对应Series具有

### 构造

1. 由二维的data与行列索引来构造
2. 从列索引名到数据的映射来构造，再加上行索引

![img](http://upload-images.jianshu.io/upload_images/7178691-106835b28c0cea5a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 操作

1. `.`取出相应的属性
2. `.T`进行转置
3.  `df[col_name]`修改或新增一列，`df[col_list]`修改多列
4. `drop`删除某一行/列
5. `to_numpy()`将df以二维ndarray返回

## 索引对象

`Index`对象



# 基本功能

## 重建索引

`.reindex` 

## 删除指定轴上的项

`.drop()`

## 索引、选取和过滤

`loc` `iloc` 

## 算术运算和数据对齐

缺失值填充 `fill_value = ` 

广播机制

函数应用和映射

## 函数应用和映射

`apply` `applymap`

## 排序和排名

`sort_value()` `sort_index` 
缺失值处理`np_position = `  

`rank()` 
评级关系打破方法



# 描述性统计汇总和计算

约简方法
累计型方法
汇总统计

## 相关系数与协方差

`corr` `cov` `corrwith` 

## 唯一值、计数及成员属性

`unique` `value_counts` `isin` `match` 



