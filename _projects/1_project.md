---
layout: page
title: Electron Tomography Segmentation
description: 
img: assets/img/10.jpg
importance: 1
category: work
---

Cryo-electron tomography (cryo-ET) is a powerful imaging technique used to study the three-dimensional (3D) cellular components and macromolecular complexes in their near-native state, providing insights into their organization and interactions. The data acquired can be noisy, and the sample may undergo distortions during the imaging process. 

Using Machine Learning techniques U-Net and Autoencoder, we are able to successly segment the cellular structures like <b>ribosome, membrane, microtubules, filament</b>.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/13.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/12.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</div>
<h2> Future Work</h2>
Extend the model to segment structures from different tomogram captured at different pixel size, without any additional annotations.


