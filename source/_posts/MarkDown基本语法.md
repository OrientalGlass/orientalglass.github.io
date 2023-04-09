---
title: MarkDown基本语法
date: 2023-4-8 22:16:00
description: 介绍一下MarkDown的基本语法
cover: /img/湖中初音.jpg
tags: 记录
categories: 日常学习
---


# 列表
## 有序列表
1. 有序列表1
2. 有序列表2
3. 有序列表3
## 无序列表
'*' '-' '+'可以创建无序列表
* 无序列表
- 无序列表
+ 无序列表


# 块引用
>'>'用于创建块引用
>>'>>'嵌套块引用
>>>'>>>'可以嵌套很多层


# 代码块
两个" \''' "之间可以写代码

```py
def fun():
    for i in range(6):
        print('hello,world')
print('this is code') #just a comment
```

# 图片和链接
"\!\[描述](address)"创建图片
![neko](../img/neko.jpeg)


"\[名称](url)"创建网页链接
[百度](https://www.baidu.com)

# 文字
在两个'\*'之间可以创建*斜体*

在两个'\*\*'之间可以创建 **加粗**

在两个'\*\*\*'之间可以创建
***加粗斜体***
markdown支持html语法,使用\<u>标签来创建
<u>下划线</u>

在文字后跟"\[^内容]"即可创建
脚注[^1]

[^1]:这是一个脚注