---
layout: post
title: NGS-pipeline相关平台
categories: NGS pipeline
tags: pipeline Next generation sequencing 
keywords: NGS pipeline
description: NGS分析平台介绍
author: chenx-bob
---

* content
{:toc}

随着人类科学技术进步和发展，精准医疗被比肩阿波罗计划、曼哈顿原子弹计划、人类基因组计划（20世纪人类自然科学史上的三大计划）成为21世纪最有划时代意义的人类第四大计划，引领者开始布道施法，越来越多的人关注到这个领域希望因此成就自己的梦想。

测序技术在其发展之初就受到了追捧，它为人类基因组计划顺利完成提供了核心技术支持。精准医疗计划让作为其核心层面的技术－NGS（Next generation sequencing ）又一次被推到伟大计划的风口浪尖。

NGS的发展以及与其相关的分析方法发展被认为是精准医疗的基石。当前存在很多方法、工具、评价标准对于NGS的发展都起到了至关重要的推动作用。有效的使用这些工具、方法、评级体系也是科学体系中的重要组成。

在此，介绍了几个NGS相关的生物信息学分析平台和框架，可以作为自己科学制定NGS数据分析策略的借鉴。

### GenomeSpace
#### GenomeSpace简介
[GenomeSapce](http://www.genomespace.org)是云基础的交互框架，支持web界面的整合的基因组学分析。框架支持不同维度的生物信息学工具集成，填补了工具之间的交互的空缺，更加容易的去利用分析和可视化的工具。事实上工具本身保持了原有的面貌和感觉，GenomeSpace只是通过轻量级的交互层提供工具之间交互的无摩擦的管道。框架本身没有执行任何分析，分析都是被无论是桌面、web、cloud、in-house的工具完成。此外GenomeSpace提供了工具的选择，它还扮演了数据自动格式化高速公路提供了数据从一个工具的输出到另一个工具的输入的功能。

![1](https://cl.ly/2U152g2B1i1i/Screen%20Recording%202016-10-15%20at%2009.50%20AM.gif)

**“** GenomeSpace started as a partnership between the Mesirov and Regev laboratories at the Broad Institute, the Chang laboratory at Stanford University, the Ideker laboratory at the University of California, San Diego, the Nekrutenko laboratory at Pennsylvania State University, the Segal laboratory at the Weizmann Institute of Science, and the Haussler and Kent laboratories at the University of California, Santa Cruz.  **”**

GenomeSpace集成工具能快速完成一个敏捷可用的框架，允许工具保有本身的特性并无缝衔接。当前框架下的[工具清单](http://www.genomespace.org/support/tools)。

#### GenomeSpace功能

1. GenomeSpace为在其框架下所有工具之间的交互提供服务。
2. GenomeSpace本身为个人用户提供30GB的数据存储，还提供包括Dropbox，Google Drive和Amazon S3云存储服务器的数据连接服务，此外GS-based一些工具本身就提供了数据都可以链接到GS框架下。
3. GenomeSpace最为重要的是提供了特定生物信息数据分析的配方，通过使用了GS-based的工具。这个配方还包括如何在GS框架下架设pipeline以及数据如何上下传。

#### GenomeSpace Recipes
GenomeSpace配方（[GenomeSpace Recipes](http://recipes.genomespace.org/home)）就是一个复杂的生物信息学分析的标准流程，也就是Best Practices for bioinformatics analysis。配方要回答的问题小到“如何从RNA－seq的数据中移除接头序列？”，大到“NGS数据分析的标准流程？”。

此外，配方使用来自GS框架下的工具，限制外部脚本或者其他计算过程，这对于完成一个简单的生物信息学分析是必不可少的。配方的目标是使生物信息分析的任务可以很容易的被生物学家、临床医生或者生物信息的初学者实现，还能扩展计算的技巧。

这个框架平台还提供了用户[接口](http://recipes.genomespace.org/recipes)，让用户自己提供Best Practices，从而实现社区驱动的Best Recipes更多的被挖掘和提高。GenomeSpace创建了[F1000 channel](https://f1000research.com/channels/genomespace)去host出版的配方，用户可以提交配方给GS团队评估，然后在F1000 channel发表这个配方。GenomeSpace说明了配方的的[提交标准和步骤](http://recipes.genomespace.org/page/best-practices-for-creating-recipes)。

![2](https://cl.ly/393I442A1d2H/Screen%20Recording%202016-10-15%20at%2012.14%20PM.gif)


### Galaxy




  
  
  

  
> 版权声明：本文为博主原创文章，未经博主允许不得转载。