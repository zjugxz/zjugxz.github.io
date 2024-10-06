---
layout: page
title: Stripcomm
description: Harnessing Channel State Information for Cross-Technology Communication.
img: assets/img/stripcomm_figure.jpg
importance: 9
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/stripcomm_figure.jpg" title="wstripcomm_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Existing packet-level CTCs based on amplitude modulation are not reliable in the coexisting environments. Although CTC can be free from the interference in the senders communication range by using RTS/CTS to reserve the channel, it is still easy for other ambient devices to introduce serious performance degradation of CTC. Considering the practice of IoT applications, how to make CTC resilient to interference is still an open problem. We propose StripComm, a novel CTC technique interconnecting WiFi and ZigBee devices in coexisting environments. We design a new interference-resilient modulation mechanism that encodes symbols by the changes of packet presence and absence to avoid the fallibility of the single state. We devise an interference-aware decoding mechanism that strips out the interference based on the distinguishable RSS patterns caused by the self-similarity of StripComm signals. The throughput of StripComm is 1.1Kbps with SER lower than 0.01 in a real office environment, and still 0.89Kbps even under strong interference.This work appears in the proceedings of IEEE INFOCOM 2018.
