---
layout: page
title: WiZig
description: Harnessing Channel State Information for Cross-Technology Communication.
img: assets/img/wizig_figure.jpg
importance: 8
category: work
giscus_comments: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/wizig_figure.jpg" title="wizig_figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In order to achieve CTC, existing packet-level proposals try to exploit free side-channels as information carriers. Regarding the wireless medium, a side channel typically exists in the following three dimensions: frequency, amplitude, and time. By exploiting a side-channel like frequency, amplitude or time, the existing works enable CTC but have limited performance under channel noise. In this paper, we propose WiZig, a novel CTC technique that employs modulation techniques in both the amplitude and temporal dimensions to optimize the throughput over a noisy channel. We establish a theoretical model of the energy communication channel to clearly understand the channel capacity. We then devise an online rate adaptation algorithm to adjust the modulation strategy according to the channel condition. The evaluation results show that WiZig achieves a throughput of 153.85bps with less than 1% symbol error rate in a real noisy environment. This work appears in the proceedings of IEEE INFOCOM 2017.


