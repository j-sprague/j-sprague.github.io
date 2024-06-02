---
layout: page
title: SmashOverlayEditor
description: Editor for a tournament stream overlay
img: assets/img/soe.png
importance: 1
category: personal
---

Java program that allows you to easily edit a stream overlay for a Smash Ultimate tournament. 

This is the first side project I've worked on that was not for any class assignment. Originally developed in 2021, this program was designed for an event organizer in the Charlotte area that wanted a tool to easily modify a scoreboard that's displayed on a broadcast. There is no easy way to edit these fields natively in OBS. However, by linking the source files to the files output by this Java program, we can easily change what is displayed on the overlay without having to go into text settings every time a score or name needs to be changed.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/soe.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Screenshot of program next to OBS preview window, which contains text boxes + images that can be edited by the program.
</div>

