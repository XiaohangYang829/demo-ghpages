---
layout: page
title: Neural Rendering
description: Full-scene neural rendering for autonomous driving
img: assets/teaser/waymo2.gif
importance: 1
category: project
---

This is a research project, and my focus is on this at present.

The big goal of our group is to reconstruct the whole real-world scene with low computational complexity. We take autonomous driving task as the main dataset to reconstruct.

The whole scene can be split into foreground, background and other factors like illumination, and I mainly study the categorical neural representations for foreground objects, especially the dynamic vehicles and deformable pedestrians.

To represent the dynamic scenes, in my early experiments, scene flow is explicitly modeled, like other prior work. While these methods are more like interpolation and extrapolation of the original video. The result representation cannot render images with unseen views, and decomposing objects and background is hard.

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/teaser/waymo1.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/teaser/waymo2.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Two early results on WaymoDataset.
</div>

（New Update is in progress)
