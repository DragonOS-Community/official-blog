---
title: 关于DragonOS，你想了解的都在这儿
date: 2022-08-15 18:46:39
tags:
---

    DragonOS龙操作系统（以下简称“DragonOS”）是一个面向服务器领域的，从0开发内核及用户态环境，并提供Linux兼容性的64位操作系统。它使用Rust与C语言进行编写，并正在逐步淘汰原有的C代码，以在将来提供更好的安全性与可靠性。

    DragonOS的目标是，构建一个完全独立自主的、开源的、高性能及高可靠性的服务器操作系统，为国家数字基础设施建设提供完全独立自主的底层核心动力。

    作为一个社区驱动的开源操作系统，为了促进其发展，避免让其遭受一些不遵守开源协议的商业公司的侵权，我们决定使用GPLv2协议开放源代码，以严格的开源协议来保护DragonOS。

    我非常欢迎你参与到这个系统的开发之中，让我们共同构建完全独立自主的服务器操作系统！

    项目开源地址：[GitHub - fslongjin/DragonOS: 一个64位的操作系统。An x86_64 operating system.](https://github.com/fslongjin/dragonOS)

## 项目特点

- 从0开始构建的类Unix操作系统

- 提倡从0开始实现各项功能，而不是原封不动地搬运开源组件。

- 开放包容，欢迎任何感兴趣的同学参与开发，贡献代码。

## 如何运行？

    运行DragonOS并不是一件难事，我们有详细的运行教程，能帮助你在最短15分钟之内，在你的电脑上运行DragonOS。

    以下资料将对你有所帮助：

- [构建DragonOS &mdash; DragonOS dev 文档](https://docs.dragonos.org/zh_CN/latest/introduction/build_system.html#docker)

- [如何在电脑的虚拟机上运行DragonOS？ | | 龙进的博客](https://longjin666.cn/?p=1514)

- [教你在15分钟内运行DragonOS！- Bilibili](https://www.bilibili.com/video/BV1zF411w7s2?share_source=copy_web&vd_source=41ab4a1b73e6f65219a785923511517e)

## 如何阅读代码？

    DragonOS的代码具有详细的中文注释，能帮助你进行阅读。内核运行的第一个C语言程序为`kernel/main.c`，你可以从这里，开始你的内核代码阅读之旅。

    在阅读代码的时候，你可能会遇到许多疑惑，你可以尝试在[DragonOS文档](https://docs.dragonos.org/zh_CN/latest/index.html)中寻找答案。当问题仍未解决时，你可以在论坛[bbs.DragonOS.org](https://bbs.DragonOS.org)上的对应板块，使用正式的语言发帖讨论。

    我们也准备了一个代码搜索引擎[code.DragonOS.org](http://code.dragonos.org)，辅助你阅读DragonOS的代码，以及Linux的代码。尽管人们对于陌生的事物经常有畏惧感，但是，我真诚的建议你，花半个小时学会如何简单的使用这个搜索引擎，他能在将来为你节省不少时间。**这个搜索引擎能帮助你快速的查找代码交叉引用、定义以及符号关系等**。这能大大的加快你的代码阅读速度。

## 如何加入？

    你可以查看GitHub仓库的Project面板，选择近期已规划的功能，进行完善。或者，你也可以带着你的创意与想法，和社区的小伙伴一起讨论，为DragonOS创造一些新的功能。

### 如何与社区建立联系？

    你可以发邮件给我，我的邮件地址是longjin@RinGoTek.cn。

    或者是加入我们的开发交流QQ群：115763565

    对于正式问题的讨论，我们建议在论坛[bbs.DragonOS.org](https://bbs.DragonOS.org)上的对应板块，使用正式的语言发帖讨论。在发帖的同时，可以把帖子转发到交流QQ群，这样能使得问题的交流更加高效，也便于问题的归档。

### 如何参与开发？

    该部分的详细内容请转到文档：[参与开发 &mdash; DragonOS dev 文档](https://docs.dragonos.org/zh_CN/latest/community/code_contribution/index.html)

## 如何赞助本项目？

    本项目是一个不收费的开源项目，但是其日常维护仍需要一些资金，如果你愿意的话，可以通过以下页面，赞助DragonOS，这样也能促进这个项目的发展。所有的赞助者的名单都会被公示，我真诚的感谢每一位赞助者！

### 赞助页面

[赞助 - DragonOS](https://www.dragonos.org/donate/)

### 赞助的资金都会被用到哪里？

- 官网及社区论坛的服务器开支

- 代码搜索引擎服务器的开支（这不是一个小数目）

- 域名、CDN等服务的开支

- 任何有助于DragonOS发展建设的用途
