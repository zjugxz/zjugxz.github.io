---
layout: page
title: WIDE
description: Physical-level CTC via Digital Emulation.
img: assets/img/wide_figure.jpg
importance: 6
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/wide_figure.jpg" title="wide_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Recent works achieve physical-level CTC by emulating the standard time-domain waveform of the receiver. This method faces the challenges of inherent unreliability due to the imperfect emulation. Different from analog emulation, we propose a novel concept named digital emulation, which stems from the following insight: The receiver relies on the phase shift to decode symbols rather than the shape of analog time-domain waveform. There are lots of phase sequences which satisfy the requirement of phase shift. The distortions of these phase sequences after WiFi emulation are different. We have the opportunity to select an appropriate phase sequence with the relatively small emulation errors to achieve a reliable CTC. We implement our proposal as WIDE, a physical-level CTC via digital emulation from WiFi to ZigBee. Evaluation results show that WIDE significantly improves the Packet Reception Ratio (PRR) from 41.7% to 86.2%, which is 2× of WEBee’s, an existing representative physical-level CTC. This work appears in the proceedings of IEEE/ACM IPSN 2019.


