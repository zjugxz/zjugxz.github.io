---
layout: page
lang: zh
title: Saiyan
description: 低功耗 LoRa 反向散射系统解调器的设计与实现
img: assets/img/saiyan_figure (1).png
importance: 2
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/saiyan_figure (1).png" title="saiyan_figure (1)" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

随着新的无线通信原语不断涌现，反向散射系统的通信距离持续增长。然而，随着距离增大，反向散射信号的误码率和丢包率会迅速上升，需要接入点与反向散射标签通过反馈回路协同工作。不幸的是，反向散射标签的低功耗特性限制了其从远端接入点解调反馈信号的能力。本文提出 Saiyan，一种用于长距离 LoRa 反向散射系统的超低功耗解调器。借助 Saiyan，标签可以在可接受的功耗下解调远端接入点的反馈信号，并在检测到丢包时立即重传。同时，Saiyan 支持速率自适应和信道跳频——两种对提升信道效率重要但在长距离反向散射系统中缺失的物理层能力。我们在双层 PCB 上实现了 Saiyan，并在不同环境中进行性能评估。结果显示，与最先进系统相比，Saiyan 的解调距离提升 3.5–5 倍；ASIC 仿真表明其功耗约为 93.2 μW。代码和硬件开源地址：https://github.com/ZangJac/Saiyan。论文发表于 USENIX NSDI 2022。
