# 稀疏多项式计算器

HUST CSE CSE2004 熊睿

[toc]

---

### 1.项目基本介绍

#### 项目理论

链表

#### 项目功能

实现稀疏多项式的简单运算（稀疏多项式的加法和减法）稀疏多项式的各项系数和指数为任意的实数，两个多项式相加时，要实现相同指数的项进行合并，不同的项要列出在输出多项式中。

#### 项目环境

visual studio2019



### 2.项目模块具体功能

#### 构造链表

将多项式的系数和指数分别存储在结构体中，并用`malloc`来为每个新输入的内容开辟空间,同时完成顺序的排列，最后将每个结构体链接起来。

#### 返回链表长度

除去coef为0的节点，实现对多项式项数的统计。

#### 操作链表

实现对两个相同expn的节点进行相加或相减，剩下的部分进行链接。

#### 选择加法或减法

对输入字符的一个简单判断，拥有操作链表。

#### 升序输出系数

直接输出操作后的链表的每一项系数

#### 降序输出多项式

利用堆栈进行倒序，并输出每一项的具体内容。






