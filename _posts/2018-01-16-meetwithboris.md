---
layout:     post
title:      After meeting with Boris
subtitle:   2018's resolution
date:       2018-01-16
author:     Mingcan
header-img: img/post-bg-2015.jpg
catalog: true
tags:
    - Life
---

# 一些遗留工作

2018在不知不觉中已经降临，这也更加剧了我对于光阴的恐慌，原来时间才是这个世界上最毒的致死剂。

我们首先讨论了一些2017年上一篇投出去的paper的一些遗留问题，当然，这些工作都是边边角角。比如Simulator里Cache coherence protocol的正确性验证，形式化的验证方法暂时不用去考虑，只能通过不断的simulation去测试。紧接着就是state-of-art的DRAM Cache的一些结果分析了，假期那段时间，重新配置了DRAM Cache的参数然后生成Checkpoints然后simulation，漫长的simulation之后总会有点结果的。

# Boris的建议
Boris 是个很nice的guy，总会在你感到迷茫时候给你一些inspiration。在我们探讨一些新的idea的时候，他总是强调首要的事情就是opportunity，那么多idea，那么多想法，真正有opportunity的会有多少呢？他顺便告诉我一个好习惯，早晨来首先thinking，然后去reading然后再利用接下来的时间去analysis，这样不仅踏实做事也知道自己要奋斗的目标。

#接下来的三个工作要点
1. 优化coherence directory
2. TLB的一些idea
3. 去跑一些simualtion从而看看我们是否有机会再sharing的优化上做文章




