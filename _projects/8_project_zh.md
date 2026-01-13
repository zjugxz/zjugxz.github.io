---
layout: page
lang: zh
title: WiZig
description: 在噪声信道上联合时域与幅度维度的跨技术通信
img: assets/img/wizig_figure.jpg
importance: 8
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/wizig_figure.jpg" title="wizig_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

为实现跨技术通信（CTC），现有分组级方案通常利用“空闲的副信道”来承载信息。就无线介质而言，副信道通常存在于三个维度：频率、幅度和时间。通过利用频率、幅度或时间等副信道，这些工作能够实现 CTC，但在存在信道噪声时性能受限。本文提出 WiZig，这是一种新型 CTC 技术，在幅度和时间两个维度上联合设计调制方式，以在噪声信道上优化吞吐量。我们建立了能量通信信道的理论模型，以清晰刻画信道容量；并设计了在线速率自适应算法，根据信道状态动态调整调制策略。评估结果表明，在真实噪声环境中，WiZig 在符号错误率低于 1% 的情况下，可实现 153.85 bps 的吞吐量。该工作发表在 IEEE INFOCOM 2017。

