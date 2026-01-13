---
layout: page
lang: zh
title: RF-Transformer
description: 统一的反向散射无线电硬件抽象
img: assets/img/transformer_figure.png
importance: 1
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/transformer_figure.png" title="transformer_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

本文提出 RF-Transformer，一种统一的反向散射无线电硬件抽象，使低功耗物联网设备能够以最低功耗直接与异构无线接收机通信。不同于为单一协议定制的传统反向散射系统，RF-Transformer 向微控制器提供可编程接口，让设备能够合成符合不同协议、但物理层设计完全不同的反向散射信号。我们在 2.4 GHz ISM 频段实现了 RF-Transformer 的 PCB 原型，并演示其生成标准 ZigBee、Bluetooth、LoRa、Wi-Fi 802.11b/g/n/ac 分组的能力。大量外场实验显示，在产生标准 Wi-Fi、ZigBee、Bluetooth、LoRa 信号时，RF-Transformer 的吞吐量分别达到 23.8 Mbps、247.1 Kbps、986.5 Kbps、27.3 Kbps，功耗仅为主动方案的 23–177× 之低。基于 65 nm CMOS 的 ASIC 仿真进一步表明其功耗优势可提升至 187–3165×。我们还将 RF-Transformer 与压力传感器集成，进行走廊人流监测案例研究，7 天的实验表明，通过在 Wi-Fi 信号上合成 LoRa 分组，RF-Transformer 能可靠地向普通网关传输传感数据。代码与硬件开源地址：https://github.com/LeFsCC/RF-Transformer。论文发表于 ACM MobiCom 2022。
