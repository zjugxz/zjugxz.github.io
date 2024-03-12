---
layout: page
title: Saiyan
description: Design and Implementation of a Low-power Demodulator for LoRa Backscatter Systems.
img: assets/img/saiyan_figure (1).png
importance: 2
category: work
giscus_comments: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/saiyan_figure (1).png" title="saiyan_figure (1)" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The radio range of backscatter systems continues growing as new wireless communication primitives are continuously invented. Nevertheless, both the bit error rate and the packet loss rate of backscatter signals increase rapidly with the radio range, thereby necessitating the cooperation between the access point and the backscatter tags through a feedback loop. Unfortunately, the low-power nature of backscatter tags limits their ability to demodulate feedback signals from a remote access point and scales down to such circumstances. This paper presents Saiyan, an ultra-low-power demodulator for long-range LoRa backscatter systems. With Saiyan, a backscatter tag can demodulate feedback signals from a remote access point with moderate power consumption and then perform an immediate packet re-transmission in the presence of packet loss. Moreover, Saiyan enables rate adaption and channel hopping – two PHY-layer operations that are important to channel efficiency yet unavailable on long-range backscatter systems.We prototype Saiyan on a two-layer PCB board and evaluate its performance in different environments. Results show that Saiyan achieves 3.5–5X gain on the demodulation range, compared with state-of-the-art systems. Our ASIC simulation shows that the power consumption of Saiyan is around 93.2 μW. Code and hardware schematics can be found at: https://github.com/ZangJac/Saiyan. This work appears in the proceedings of USENIX NSDI 2022.


