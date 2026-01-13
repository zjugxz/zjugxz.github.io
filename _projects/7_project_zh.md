---
layout: page
lang: zh
title: LEGO-Fi
description: 面向低端发射端的跨技术通信
img: assets/img/legofi_figure.jpg
importance: 7
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/legofi_figure.jpg" title="legofi_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

现有物理层跨技术通信（CTC）方案通常需要在发射端进行复杂的信号处理，这对从低端发射端到高端接收端的场景（例如从 ZigBee 到 WiFi）并不适用。本文提出了一种**发射端透明**的跨技术通信机制，将计算复杂度完全留在接收端，从而向双向高吞吐 CTC 迈出了关键一步。我们将该方案实现为 LEGO-Fi，实现从 ZigBee 到 WiFi 的通信。其核心技术是跨解映射（cross-demapping），基于两个关键洞见：（1）ZigBee 分组在通过 WiFi 模块时会留下可区分的特征；（2）与 ZigBee 简单的编码与调制方案相比，WiFi 丰富的处理能力为处理 ZigBee 分组提供了额外的灵活性。评估结果表明，LEGO-Fi 可实现 213.6 Kbps 的吞吐量，分别比现有的两个 ZigBee-to-WiFi CTC 方案 FreeBee 和 ZigFi 快 13000 倍和 1200 倍。该工作发表在 IEEE INFOCOM 2019。

