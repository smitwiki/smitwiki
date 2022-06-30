---
title: "AIGs"
date: 2022-06-21T00:16:54+08:00
author: "糸色先生"
---

-   BMC（bounded model checking）是有界模型检验的缩写。

-   针对前期的OBDD（ordered binary decision
    diagram）技术的模型检测的不足，有界模型检测BMC使用SAT（satisfiability）求解器来求解需要验证的问题。它通过设置界限阈值k，可以有效地克服状态爆炸问题。

-   BMC的主要过程是：使用有限状态自动机（finite state
    machine，FSM）来表示要验证的模型或系统，通过FSM状态间的转移来模拟系统或模型运行；用线性时序逻辑（linear-time
    temporal logic，LTL）来描述有限状态自动机；设定边界阈值k；FSM
    状态间的转移关系和LTL逻辑规范使用逻辑与来构成BMC转换公式；把BMC转换公式编码成SAT实例，借助SAT工具求解。若有解，则产生反例反之，若无解，则系统一直运行到阈值k阶段后停止，说明系统或模型是安全且没有错误的。