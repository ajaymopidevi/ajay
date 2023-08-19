---
layout: page
title: Situation Aware Object Tracking
description: 
img: assets/img/15.jpg
importance: 6
category: work
---

Over the course of tracking an object, the surrounding environmental conditions lighting, occlusion, scale etc might change, which often become challenging the Object tracker.

To address these changes in environment, we :
1. Detect the situational changes like illumination, occlusion and scale
2. Deploy the real-time object tracking algorithms which can adapt to these changes. Our proposed changes boosts the performance by 10% on VOT dataset


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Illumination.png" title="Illumination" caption="Object Tracking in multiple Illumination changes" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Occlusion.png" title="Occlusion" caption="Object Tracking in multiple Occlusion changes" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Scale.png" title="Scale" caption="Object Tracking in multiple Scale changes" class="img-fluid rounded z-depth-1" %}
    </div>
</div>