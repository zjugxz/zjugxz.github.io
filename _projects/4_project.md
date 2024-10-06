---
layout: page
title: Palantir
description: Accurate Mobile Sensing over a LoRa Backscatter Channel.
img: assets/img/Palantir_figure.png
importance: 4
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Palantir_figure.png" title="Palantir_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Wireless sensing, which acquires the information of a target by collecting and analyzing wireless signals, is a key enabling technology for ubiquitous Internet of Things applications. In the past decade, we have witnessed a large body of studies on wireless sensing. The wireless technologies for sensing range from acoustic, RFID and WiFi to LoRa and mmWave, while the sensing capabilities extensively cover motion and activity sensing, mobility measurement, environmental sensing, and material sensing, etc. However, how to sense the condition of a mobile target in a long range is still a missing piece. In this work, we present Palantir, a first-of-its-kind long-range sensing system based on the LoRa backscatter, for cyclists in the public bicycle sharing systems. For this purpose, we design a complete signal processing flow to particularly deal with multiple challenging problems that are coupled with each other, such as amplitude instability, frequency offset, clock drift, spectrum leakage, and multiplicative noise. We evaluate the performance of Palantir by performing comprehensive benchmark experiments. We also build a prototype and conduct a case study of respiration monitoring in the real world. The results demonstrate that Palantir performs accurate sensing at the range of 100 m with a median deviation of motion period to as low as 0.2%, and works well for mobile targets. This work appears in the proceedings of ACM SenSys 2021.
