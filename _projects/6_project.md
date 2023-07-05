---
layout: page
title: Ray Tracing with OpenCL
description:  Raytrace a complex scene and optimize the runtime using OPENCL.
img: assets/img/2.png
importance: 6
category: work
---

How many Spheres do you see in the scene?


<div class="row">
    <div class="col-sm mt-md-0">
        {% include figure.html path="assets/img/1.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

1. Added support for Raytracing a triangle. 
2. Added support for loading a obj file as set of triangles and Raytrace the scene with objects.
3. Added support for raytracing a scene with combination of spheres and triangles. If ray is defined as O+tD (O-origin, D-direction),   the least t of both spheres and triangles is considered as the intersected object.
4. Added OPENCL support to reduce the runtime.
5. Created a scene to display the mirror-like reflections.

Github Repo : <a href="https://github.com/ajaymopidevi/Ray-Tracing-using-OpenCL">Ray-Tracing-using-OpenCL</a>

Presentation: <a href="https://github.com/ajaymopidevi/Ray-Tracing-using-OpenCL/blob/master/Real-Time%20RayTracing%20using%20OpenCL.pdf">Real-time Raytracing using OpenCL</a>