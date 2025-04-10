---
layout: page
title: project 1
description: with background image
img: assets/img/F1_edited.png
importance: 1
category: work
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/F1_edited.png" title="Read-write project overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<p>
Our research aims to understand how the brain sees, with the long-term goal of developing technologies to restore vision. We focused on the primary visual cortex (V1), where specific groups of brain cells, called "columns," represent visual features like the orientation of lines. To test if activating these columns directly affects perception, we first built a sophisticated "read-write" system. This involved using genetic tools and precisely targeted light (optogenetics) to both <em>read</em> brain activity by watching columns light up, and <em>write</em> activity by selectively stimulating specific columns associated with different orientations (like horizontal or vertical). We meticulously optimized these tools and developed a pipeline to ensure we could reliably target the correct columns in awake macaques.
</p>
<p>
With our read-write system established, we investigated whether artificially activating orientation columns could influence what the macaques perceived. Macaques performed a task judging line orientation while we occasionally used light to stimulate either the "horizontal" or "vertical" columns in their V1. Our key finding was that activating specific columns <em>biased</em> the animals' choices towards the orientation represented by those columns. For instance, stimulating "horizontal" columns made them more likely to report seeing horizontal, even if the actual image was different. This provides strong evidence that the brain uses the activity patterns across these columns as part of its code for vision and helps pave the way for future visual neuroprosthetics.
</p>
