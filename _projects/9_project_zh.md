---
layout: page
lang: zh
title: Stripcomm
description: 在共存环境下具备抗干扰能力的跨技术通信
img: assets/img/stripcomm_figure.jpg
importance: 9
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/stripcomm_figure.jpg" title="wstripcomm_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

现有基于幅度调制的分组级跨技术通信（CTC）在多种设备共存的环境中可靠性较差。尽管通过 RTS/CTS 预留信道可以在发送端通信范围内避免部分干扰，其他环境设备仍然容易引入严重的性能退化。结合物联网应用实践，“如何让 CTC 对干扰具有鲁棒性”仍然是一个开放问题。我们提出 StripComm，这是一种在共存环境下连接 WiFi 与 ZigBee 设备的新型 CTC 技术。我们设计了一种抗干扰调制机制，通过“是否有分组”的变化来编码符号，从而避免单一状态易出错的问题。同时提出了干扰感知的解码机制，利用 StripComm 信号自相似性在 RSS 模式上的可区分特征，剥离出干扰。在真实办公环境中，StripComm 在符号错误率（SER）低于 0.01 时可实现 1.1 Kbps 的吞吐量；即使在强干扰下，仍可达到 0.89 Kbps。该工作发表在 IEEE INFOCOM 2018。
