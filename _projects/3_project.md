---
layout: page
title: Aloba
description: Rethinking ON-OFF Keying Modulation for Ambient LoRa Backscatter
img: assets/img/aloba_figure.jpg
importance: 2
category: work
giscus_comments: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/aloba_figure.jpg" title="aloba_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Backscatter communication holds potential for ubiquitous and low-cost connectivity among low-power IoT devices. To avoid interference between the carrier signal and the backscatter signal, recent works propose frequency-shifting technique to separate these two signals in frequency. Such proposals, however, have to occupy the precious wireless spectrum that is already overcrowded, and increase the power, cost, and complexity of tag design. We revisit the classic ON-OFF Keying (OOK) modulation and propose Aloba, a backscatter system that takes the ambient LoRa transmissions as the excitation and piggybacks the in-band OOK modulated signals over the LoRa transmissions. Our design enables the backsactter signal to work in the same frequency band of the carrier signal, meanwhile achieving good tradeoff between transmission range and link throughput. The key contributions of Aloba are: i) the design of a low-power backscatter tag that can pick up the ambient LoRa signals from other signals; ii) a novel decoding algorithm to demodulate both the carrier signal and the backscatter signal from their superposition. The design of ALoba completely unleashes the backscatter tag's ability in OOK modulation and achieves flexible data rate at different transmission range. Aloba can achieve 39.5--199.4 Kbps data rate at various distances. This work appears in the proceedings of ACM SenSys 2020.


