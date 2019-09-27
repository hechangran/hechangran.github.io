---
layout:     post
title:      在Matlab画数据点很多的图无法正确导出.eps矢量文件
subtitle:   解决方案
date:       2019-09-26
author:     hechangran
header-img:
catalog: true
tags:
    - Matlab r2019b

--- 

遇到Matlab一个'feature',表现为:一旦Matlab觉得你图片数据过多,导出.eps文件时,它会导出一个伪矢量图. 要正确导出矢量图,必须手动选择render为painters. 这样做的缺点是.eps图片会比较大.

解决方案是:如果图太复杂,就每隔10个数据点采一个样来画图,并手动选择render为painters.

 
---



