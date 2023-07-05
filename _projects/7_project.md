---
layout: page
title: Autonomous car - 1/10 scale
description:  
img: assets/img/8.jpg
importance: 2
category: work
---

Designed an Autonomous car of 1/10 scale which is successful to :

- Detects a rolling ball in its track and avoids the collision. Then it again continues in the track.
<div class="row">
    <div class="caption">
        {% include video.html path="assets/video/avoid_ball.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>

- Detects a stop sign and waits for 3 sec

- Jump of the ramps placed 1m apart
<div class="row">
    <div class="caption">
        {% include video.html path="assets/video/jump.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>


- Generates the sparse map of the track using hector mapping ros package
<div class="row">
    <div class="col-sm mt-md-0">
        {% include figure.html path="assets/img/7.png" title="Track Sparse map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>




The following equipment was utilized for the project:
1. ODROID XU-4 with 2GB memory
2. Intel RealSense D435
3. 1/10 AMP MT 2WD Monster Truck RTR ECX03028T2
4. Mini Maestro 18-Channel USB Servo Controller
5. Adafruit IR Distance Sensor GP2Y0A710K0F (qty: 1)
6. PhidgetSpatial 3/3/3 Basic 1044/1 
7. 64GB eMMC 5.0 Module XU3/XU
8. 7.2V 1.8A Ni-MH battery
9. 11.1V (3S) LiPo Battery

<a href="assets/pdf/milk_final_report.pdf">Report
