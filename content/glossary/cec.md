---
title: "CEC"
date: 2022-06-21T00:16:54+08:00
author: "糸色先生"
---

-   CEC（combinational equivalence
    checking）是组合等价性检查的缩写，也即对两个电路中的组合逻辑是否等价进行验证。

-   我们常用的Synopsys的formality或者Cadence的Conformal
    LEC都有个步骤叫match，用于match两个design里的参考点，这些参考点和STA里使用的类似，为flip-flop和IO，然后再进行verify。这可以理解为工具把整个等价性检查工具拆分为一系列两个参考点之间的组合逻辑的等价性验证，可以让整个工作高效完成。