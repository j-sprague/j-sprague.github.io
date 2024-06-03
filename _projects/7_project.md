---
layout: page
title: Smash Match Analyzer
description: Program that analyzes fighting game match with YOLOv8 Model Detection 
img: assets/img/computervision-icon.PNG
importance: 5
category: coursework
---

Proof of concept for a tool that keeps track of what is happening in a video game match based on what can be scanned on screen. The program scans the screen every 0.2 seconds to detect any changes on what's happened on screen. This could help automate the process of keeping score in Smash Ultimate game matches. This project contains a model that was trained on 159 images showing different characters, costumes, and backgrounds, to make sure the data is as accurate as possible. This project served as a thorough demonstration of everything I had previously learned about YOLOv8 model detection.

<a href="https://github.com/j-sprague/computervision-project-ssbu">Repository Link</a>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/computervision.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Both output windows from the object-detection model on the left side. Gameplay preview on the right side.
</div>

