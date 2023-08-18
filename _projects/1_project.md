---
layout: page
title: Electron Tomography Segmentation
description: 
img: assets/img/RMap.png
importance: 2
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
        {% include figure.html path="assets/img/11.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Our Contributions:
1. Developed a Multi-UNet architecture to improve the performance of multi-class segmentation by 15%
2. Added different strategies to effectively train the deep learning U-Net architectures from a sparsely labelled tomogram images.
3. Achieved 92% accuracy in segmenting electron structures like ribosomes, membrane using <1% of the entire tomogram for training
4. Designed U-NeXt architectures, combining the ConvNeXt and U-Net, specifically tailored for tomograms captured at different scales, resulting in a f1 score of 85% for segmentation



