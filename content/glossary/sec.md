---
title: "AIGs"
date: 2022-06-21T00:16:54+08:00

---

-   SEC（sequential equivalence
    checking）是时序等价性检查的缩写，也即对两个电路中的时序逻辑是否等价进行验证。

-   SEC可以对两个时序逻辑设计进行比对，它可能使用BDD等symbolic算法来对设计的状态空间进行表述，这也就演变为了model
    checking问题，所以SEC通常会使用更高抽象层级的reference
    model，这个思想和验证RTL功能的model checking和theorem
    proving就有明显的共通之处了。

-   JasperGold
    SEC工具就是做时序等价性检查的工具。SEC主要就是针对RTL对RTL了。我们可以把SEC工具看做model
    checking的一个特例，这里model不是assertion，而是另一个design，甚至可以是一个周期精确的model。
