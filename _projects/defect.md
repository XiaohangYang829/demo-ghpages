---
layout: page
title: Defect Detection and Segmentation
description: Defect detection and segmentation on assembly line
img: assets/teaser/defect.jpg
importance: 3
category: project
---

This is a project for a company.

On the assembly line, the rate of defective products is often very low, which makes the cost of manual inspection very high.

Quality inspection can be done quickly with the help of computer vision. For a general defect detection task, the focus of the task is to build a dataset of related categories of defects and label them. However, in this project, there are some challenging defects, for example, screws need to be screwed into specific holes, while other holes need to be left empty. So we design our methods based on comparison. Homography matrix is estimated to align detected image with template image, then stack them together for later defect detection and segmentation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/teaser/motor_crop.jpg" title="homography estimation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
    </div>
</div>
<div class="caption">
    Image alignment before detection.
</div>
