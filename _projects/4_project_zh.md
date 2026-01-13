---
layout: page
lang: zh
title: Palantir
description: 基于 LoRa 反向散射信道的精确移动感知
img: assets/img/Palantir_figure.png
importance: 4
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Palantir_figure.png" title="Palantir_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

无线感知通过收集和分析无线信号来获取目标信息，是泛在物联网应用的关键使能技术。在过去十年中，我们见证了大量关于无线感知的研究。用于感知的无线技术从声学、RFID 和 WiFi 到 LoRa 和毫米波，而感知能力广泛涵盖运动和活动感知、移动性测量、环境感知和材料感知等。然而，如何远距离感知移动目标的状态仍然是一个缺失的部分。在这项工作中，我们提出了 Palantir，这是一个基于 LoRa 反向散射的首个远距离感知系统，面向公共自行车共享系统中的骑行者。为此，我们设计了一个完整的信号处理流程，特别处理多个相互耦合的挑战性问题，如幅度不稳定、频率偏移、时钟漂移、频谱泄漏和乘性噪声。我们通过全面的基准实验评估了 Palantir 的性能。我们还构建了一个原型，并在现实世界中进行了呼吸监测的案例研究。结果表明，Palantir 在 100 米范围内进行精确感知，运动周期的中位偏差低至 0.2%，并且对移动目标工作良好。这项工作发表在 ACM SenSys 2021 会议论文集中。
