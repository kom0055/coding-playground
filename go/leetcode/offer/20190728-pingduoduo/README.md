# CREATED AT
28, July, 2019

# 拼多多20届学霸批服务端研发工程师笔试题
- [参考答案](https://www.nowcoder.com/discuss/212363)

## 1. 严格升序
### 输入
两行数字，第一行数字是数组A，第二行数字是数组B，数组A几乎升序（只需要替换数组中的一个元素就可以转换为严格升序（严格升序不能有邻近的元素相等））

### 要求
从B中选择一个元素与A中元素交换，该元素必须是可以使A升序的值最大的元素。

### 输出
字符串，严格排序后数组A各元素以空格间隔（如果失败返回NO）

## 2. 判断是否首尾相接形成圆环
### 输入
一组字符串，每个字符串的所有字符全部大写

### 要求
经过有限次字符串顺序交换是否能够收尾相接形成圆环，如：ABD、DCE、EGDA

### 输出
true或false

## 3. 最短平均等待时间
### 输入
先输入N、M，分别代表程序个数（N）和依赖个数（M）；再输入N个数字，代表每个程序的执行时间；再输入M组数，分别代表M个依赖关系，每组数据的第二个数字代表的进程依赖第一个数字代表的进程

### 要求
求出符合依赖规则（被依赖的先执行），并且程序平均等待时间最短的程序执行序列

### 输出
程序执行顺序


## 4. 搭积木
### 输入
首先输入N，代表总共有N个积木；再输入N个数字，分别代表N个积木的长宽；再输入N个数字，分别代表N个积木的重量

### 要求
每个积木高1米；把积木搭起来，下面的积木一定要比上面积木的长宽大；下面的积木的承重最大是自己重量的7倍；求积木的最大高度

### 输出
积木高度