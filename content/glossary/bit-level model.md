---
title: "bit-level model"
date: 2022-06-21T00:16:54+08:00

---

-   bit-level model表示对rtl电路设计的一种位级表示，一般来说，位级表示模型中会出现类似于input
    [信号位宽-1 ：0] 端口名，output [信号位宽-1 ：0] 端口名，reg [width-1 : 0]
    R变量，wire [width-1 : 0]
    W变量这种多bit位数据之间采用其各自的单个bit位如input[0]、input[1]、output[0]、output[1]等逐步进行位运算操作最后得出运算结果。

    ![图示 描述已自动生成](media/9.png)
    ![图示 描述已自动生成](media/9_1.png)