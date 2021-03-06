---
layout:     post
title:      Markdown学习笔记
subtitle:   Some syntax of Markdown
date:       2018-01-04
author:     hechangran
header-img:
catalog: true
tags:
    - Syntax
    - Markdown
---

## 基本信息
<https://hechangran.github.io/>

[本站地址](https://hechangran.github.io/ "Page")

本网站搭建参考资料：
<https://www.jianshu.com/p/e68fba58f75c>

Email address:
<hechangran@163.com>

---

第一次尝试用*Markdown*（斜体），感觉怪怪的。据说这样能很**突出**(加粗)。删除~~一段话~~，***加粗斜体***

插入网站：
1. B站[Bilibili](https://www.bilibili.com/ "FA♂")
2. Markdown语法介绍[资料](http://blog.leanote.com/post/freewalk/Markdown-%E8%AF%AD%E6%B3%95%E6%89%8B%E5%86%8C)


这样来**引用**(cross reference).
[Bilibili][1], [Markdown语法介绍][2] are useful sites.

[1]:https://www.bilibili.com/ "B站"

[2]:http://blog.leanote.com/post/freewalk/Markdown-%E8%AF%AD%E6%B3%95%E6%89%8B%E5%86%8C "Markdown语法介绍"

---

## 插图
方法一：
![pic1](https://ws1.sinaimg.cn/mw690/44ba9bf8gy1fnhnmhlfm6j23v92kyb2j.jpg "叉烧")


---
## 购物车

Item       | 价格      |备注
:---:  | :---:     | :---:
 土星5号    | $1000     | 价格稳定
 Creative建筑    | $1200 | 貌似停产

---
## To-do List
1.  Research Proposal:
    > 1. Review.
    > 2. Put EL in.

2. Slides for oral

---
## 使用技巧

> 1. Atom编辑器内置了git，可以直接commit和push。
> 2. 好像没发现快捷键push.

---
## 引入代码块
> 给出一些例子代码：
>
>      1st class Sample code;
>
> >     2nd class Sample code;
>
>     1st class Sample code;

插入代码：

    #include <stdio.h>
    int main(void)
    {
        printf("Hello world\n");
    }



---
>>> 请问 Markdwon 怎么用？ - 小白

>> 自己看教程！ - 愤青

> 教程在哪？ - 小白




## Definition

Markdown

:    轻量级文本标记语言，可以转换成html，pdf等格式（左侧有一个可见的冒号和四个不可见的空格）





## Footnote

使用 Markdown[^1]可以效率的书写文档。

[^1]:Markdown是一种纯文本标记语言

---
## Latex equation
$V=\frac{1}{2}x^{T}x$

$$ \frac{A}{B} \label{eq1}$$

Try cross reference \ref{eq1}.

How to set Latex support:
<http://csega.github.io/mypost/2017/03/28/how-to-set-up-mathjax-on-jekyll-and-github-properly.html>



A group of $N$ Euler Lagrange systems are described by the following dynamic equation
$$ M(q)\ddot{q}+C(q,\dot{q})\dot{q}+g(q)=\tau $$
