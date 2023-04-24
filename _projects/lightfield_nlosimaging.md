---
layout: page
title: Light Field NLOS Imaging
description: using the angular and spatial information of scattered light to look around corners
img: assets/img/projects/lightfield_nlosimaging.png
importance: 1
category: current research
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/lightfield_nlosimaging.png" title="lfieldnlos" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Light field NLOS imaging setup
</div>

Passive non-line-of-sight (NLOS) imaging "looks" around corners at hidden scenes using just scattered light from rough surfaces. Since many scattering surfaces are highly diffusive and spread light out across all angles, passive NLOS imaging as an extremely difficult task. However, if it can be accomplished, it could greatly benefit many areas, such as search-and-rescue and autonomous vehicles.

Most previous attempts focused on using singular photographs which captures a 2D distribution of the scattered light. By combining multiple 2D photographs at different vantage angles, we can actually reconstruct a 4D distribution of the scattered light rays (2 angular and 2 spatial dimensions). This is called the light field, and our project explored how can we use the extra information in the light field to improve imaging reconstructions.

In our work we have found two main applications. The first "refocuses" scattered light to pinpoint the hidden scenes in a manner similar to typical refocusing algorithms in light field imaging. This allows for high 3D reconstruction precision and allows in-depth mathematical analysis on limits to the method. The second application is to improve occlusion-based NLOS imaging (i.e., using occluders already present in the scene to cast information-rich shadows) by allowing the additional angular information to discriminate against unwanted signals. This makes the imaging much more robust to real-world situations.

The bottom of the page shows several papers that use light field NLOS imaging. Please email for PDFs of papers.



<!-- _projects/lightfield_nlosimaging.md -->
<div class="publications">

{% bibliography --file lightfield_nlos --style apa %}

</div>
