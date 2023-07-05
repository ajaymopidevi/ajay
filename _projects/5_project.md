---
layout: page
title: PersAR
description: Simple AR application
img: assets/img/3.png
importance: 5
category: fun
---

PersAR is an augmented reality software application that projects videos onto moving objects with smooth 30fps playback. It uses SVD and RANSAC algorithms to estimate the Projective Transformation Matrix, ensuring accurate alignment. Inverse warping methods are used to address holes in the projection caused by object motion. Gaussian blending reduces flickering and border artifacts for an immersive experience. 

<div class="row">
    <video src="assets/video/results_PersAR_30fps.mp4" controls>
        PersAR.
    </video>
</div>
