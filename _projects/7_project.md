---
layout: page
title: LEGO-Fi
description: Harnessing Channel State Information for Cross-Technology Communication.
img: assets/img/legofi_figure.jpg
importance: 7
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/legofi_figure.jpg" title="legofi_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Existing physical-level CTC means considerable processing complexity at the transmitter, which doesn't apply to the communication from a low-end transmitter to a high-end receiver, e.g. from ZigBee to WiFi. This paper presents transmitter-transparent cross-technology communication, which leaves the processing complexity solely at the receiver side and therefore makes a critical advance toward bidirectional high-throughput CTC. We implement our proposal as LEGO-Fi, the communication from ZigBee to WiFi. The key technique inside is cross-demapping, which stems from two key technical insights: (1) A ZigBee packet leaves distinguishable features when passing the WiFi modules. (2) Compared to ZigBee’s simple encoding and modulation schemes, the rich processing capacity of WiFi offers extra flexibility to process a ZigBee packet. The evaluation results show that LEGO-Fi achieves a throughput of 213.6Kbps, which is respectively 13000× and 1200× faster than FreeBee and ZigFi, the two existing ZigBee-to-WiFi CTC approaches. This work appears in the proceedings of IEEE INFOCOM 2019.
