---
layout: page
title: LWIR NLOS Imaging
description: nlos imaging in the lwir regime
img: assets/img/projects/lwir_overview.png
importance: 2
category: current research
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/lwir_example.PNG" title="lwir imaging" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Example of LWIR NLOS Imaging from Sasaki 2021
</div>

While most passive non-line-of-sight (NLOS) imaging methods are focused on the visible wavelength regime, there are several advantages to performing NLOS imaging in the long-wave infrared (LWIR) wavelength regime, otherwise known as the thermal domain. There are two main reasons: the first is that common materials are often much more "specular," or that the reflect light similar to a mirror. The other reason is that humans and other heated objects (such as cars) emit more LWIR radiance than their room temperature surroundings and therefore stand out much more in LWIR than they do in visible. However, there also are disadvantages, such as vastly decreased signal-to-noise ratio (SNR).

Since the visible passive NLOS imaging methods are not catered to LWIR, our goal in this project is to explore LWIR NLOS imaging and its limits. One of our works investigated the bi-directional reflectance distribution function (BRDF) of materials in LWIR and how to measure them quickly and effectively. The other work performs NLOS imaging using the light field NLOS imaging methods adapted to the LWIR regime.

The bottom of the page shows several papers that use light field NLOS imaging. Please email for PDFs of papers.


<div class="publications">

{% bibliography --file lwir_nlosimaging --style apa %}

</div>