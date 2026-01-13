---
layout: page
lang: zh
title: WIDE
description: 基于数字仿真的物理层跨技术通信
img: assets/img/wide_figure.jpg
importance: 6
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/wide_figure.jpg" title="wide_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

现有工作通常通过仿真接收端的标准时域波形来实现物理层跨技术通信（CTC）。这类方法由于仿真本身难以完美一致，固有存在可靠性问题。不同于模拟波形仿真，我们提出了一种新的概念——数字仿真，其核心思想是：接收端在解码符号时依赖的是相位跳变，而不是模拟时域波形的具体形状。满足相位跳变要求的相位序列有很多种，这些相位序列在经过 WiFi 发射链路仿真后的失真程度各不相同。我们可以选择失真相对较小的相位序列，从而实现更可靠的 CTC。基于这一思路，我们设计并实现了 WIDE，一个从 WiFi 到 ZigBee 的基于数字仿真的物理层 CTC 系统。评估结果表明，WIDE 将数据包接收率（Packet Reception Ratio, PRR）从 41.7% 显著提升至 86.2%，是代表性物理层 CTC 方案 WEBee 的 2 倍。该工作发表在 IEEE/ACM IPSN 2019。
