---
layout: page
lang: zh
title: ZigFi
description: 利用信道状态信息实现跨技术通信
img: assets/img/zigfi_figure.jpg
importance: 5
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/zigfi_figure.jpg" title="zigfi_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

在过去十年中，为满足不同环境下多样化的通信与服务需求，无线技术在种类（如 WiFi、ZigBee 和 Bluetooth）和密度上都呈现爆发式增长。在这样一个高度多样且密集的无线生态中，不同专用异构无线技术之间的互联为构建更高级的服务提供了巨大机会。为此，研究者提出了跨技术通信（Cross-Technology Communication, CTC）技术，只依赖商用设备即可在异构协议之间建立直接连接。本文提出 ZigFi，这是一种从 ZigBee 到 WiFi 的新型 CTC 方案。ZigFi 有意让 ZigBee 分组与 WiFi 分组在时间上重叠，并利用信道状态信息（Channel State Information, CSI）来承载数据。实验结果表明，ZigFi 可实现 215.9 bps 的吞吐量，比现有最先进方案快 18 倍。该工作发表在 IEEE/ACM ToN 2020 和 INFOCOM 2018。
