---
layout: page
title: RF-Transformer
description: A Unified Backscatter Radio Hardware Abstraction
img: assets/img/transformer_figure.png
importance: 1
category: work
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/transformer_figure.png" title="transformer_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

This paper presents RF-Transformer, a unified backscatter radio hardware abstraction that allows a low-power IoT device to directly communicate with heterogeneous wireless receivers at the minimum power consumption. Unlike existing backscatter systems that are tailored to a specific wireless communication protocol, RF-Transformer provides a programmable interface to the micro-controller, allowing IoT devices to synthesize different types of protocol-compliant backscatter signals sharing radically different PHY-layer designs. To show the efficacy of our design, we implement a PCB prototype of RF-Transformer on 2.4 GHz ISM band and showcase its capability on generating standard ZigBee, Bluetooth, LoRa, andWi-Fi 802.11b/g/n/ac packets. Our extensive field studies show that RF-Transformer achieves 23.8 Mbps, 247.1 Kbps, 986.5 Kbps, and 27.3 Kbps throughput when generating standard Wi-Fi, ZigBee, Bluetooth, and LoRa signals while consuming 23–177× less power than their active counterparts. Our ASIC simulation based on the 65-nm CMOS process shows that the power gain of RF-Transformer can further grow to 187–3165×. We further integrate RF-Transformer with pressure sensors and present a case study on detecting foot traffic density in hallways. Our 7-day case studies demonstrate RF-Transformer can reliably transmit sensor data to a commodity gateway by synthesizing LoRa packets on top of Wi-Fi signals. Code and hardware schematics can be found at: https://github.com/LeFsCC/RF-Transformer. This work appears in the proceedings of ACM MobiCom 2022.
