---
title: "AIGs"
date: 2022-06-21T00:16:54+08:00
author: "糸色先生"
---

-   Theorem proving也是一种验证RTL功能和model是否match的手段，它使用的是推导的方法。不像model
    checking是工具自动给的激励来和assertion匹配，定理证明则是用纯数学方法了。它们之间有一点是共通的，就是都是和根据design
    specification写的model来比，model checking用assertion表达model，而theorem
    proving则是用某种中间语言来表达。用来进行theorem
    proving最有名的工具语言算是ACL2了。