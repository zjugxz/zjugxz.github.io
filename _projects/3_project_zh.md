---
layout: page
lang: zh
title: Aloba
description: 重新思考面向环境 LoRa 反向散射的开关键控调制
img: assets/img/aloba_figure.jpg
importance: 3
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/aloba_figure.jpg" title="aloba_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

反向散射通信有望为低功耗物联网设备提供无处不在且低成本的连接。为了避免载波信号与反向散射信号的相互干扰，近期工作提出通过频移技术在频域将两者分离。然而，这类方案需要占用已然拥挤的无线频谱，并增加标签设计的功耗、成本与复杂度。我们重新审视经典的开关键控（OOK）调制，提出 Aloba：利用环境中的 LoRa 传输作为激励，在原有 LoRa 传输上叠加同频 OOK 调制信号的反向散射系统。该设计让反向散射信号在与载波相同的频段工作，同时在传输距离与链路吞吐之间取得良好权衡。Aloba 的核心贡献包括：i) 设计低功耗反向散射标签，使其能从其他信号中拾取环境 LoRa；ii) 提出解码算法，从叠加信号中同时解调载波与反向散射信号。Aloba 充分释放了标签在 OOK 调制下的能力，能在不同距离实现灵活的数据速率。在多种距离下可达 39.5–199.4 Kbps。本文发表在 ACM SenSys 2020。
