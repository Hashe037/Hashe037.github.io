---
layout: page
title: Light Field NLOS Imaging
description: using the angular and spatial information of scattered light to look around corners
img: assets/img/12.jpg
importance: 1
category: work
---

Passive non-line-of-sight (NLOS) imaging "looks" around corners at hidden scenes using just scattered light from rough surfaces. Since many scattering surfaces are highly diffusive and spread light out across all angles, passive NLOS imaging as an extremely difficult task. However, if it can be accomplished, it could greatly benefit many areas, such as search-and-rescue and autonomous vehicles.

Most previous attempts focused on using singular photographs which captures a 2D distribution of the scattered light. By combining multiple 2D photographs at different vantage angles, we can actually reconstruct a 4D distribution of the scattered light rays (2 angular and 2 spatial dimensions). This is called the light field, and our project explored how can we use the extra information in the light field to improve imaging reconstructions.

In our work we have found two main applications. The first "refocuses" scattered light to pinpoint the hidden scenes in a manner similar to typical refocusing algorithms in light field imaging. This allows for high 3D reconstruction precision and allows in-depth mathematical analysis on limits to the method. The second application is to improve occlusion-based NLOS imaging (i.e., using occluders already present in the scene to cast information-rich shadows) by allowing the additional angular information to discriminate against unwanted signals. This makes the imaging much more robust to real-world situations.

The bottom of the page shows several papers that use light field NLOS imaging.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}



<!-- _projects/lightfield_nlosimaging.md -->
<div class="publications">

{% bibliography --file lightfield_nlos --style apa %}

</div>
