---
layout: page
title: Encoder-decoder model of V1
description:
img: assets/img/RWsetup.png
importance: 2
category: work
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/F1_edited.png" title="Read-write project overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<p>
To truly reverse-engineer the neural code for vision to build next-generation neuroprosthetics, we need to understand precisely how targeted optogenetic perturbations shape V1 network dynamics and causally lead to visually-guided behavior. 

Reverse-engineering how the brain's visual code under visual and optogenetic perturbation leads to behavior is key to building next-generation neuroprosthetics. Our work tackles this by understanding precisely how targeted optogenetic perturbations shape V1 network dynamics and causally drive visually-guided behavior. We employ a novel, biologically-constrained Spatiotemporal Graph Neural Network (STGNN) as the _encoder_; taking visual and optogenetic stimuli as input, it learns realistic spatiotemporal dynamics by embedding V1's columnar structure and biological priors, predicting high-resolution neural activity while simultaneously unlocking interpretable insights into perturbed circuit function. To bridge these dynamics to perception, an interpretable Transformer-based _decoder_ processes the learned V1 representations. Leveraging self-attention, it dynamically integrates evidence over time, pinpointing precisely how specific V1 activity patterns and moments causally dictate behavioral outcomes like choice and reaction time. Together, this powerful encoder-decoder framework provides the foundation for intelligent, model-based design of closed-loop visual neuroprosthetics, accelerating the path toward meaningful sight restoration.
</p>
