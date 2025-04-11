---
layout: page
title: Reverse-engineering neural code with ML
description:
img: assets/img/RWsetup.png
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
Reverse-engineering the cortical code for vision is key to building next-generation visual neuroprosthetics. Our work tackles this by understanding precisely how targeted optogenetic perturbations shape V1 network dynamics and causally drive visually-guided behavior. We propose a novel, biologically-constrained Spatiotemporal Graph Neural Network (STGNN) as the encoder (Jin et al., 2023 *IEEE TKDE*); taking visual and optogenetic stimuli as input, it learns realistic spatiotemporal dynamics by embedding V1's columnar structure and biological priors, predicting high-resolution neural activity while simultaneously unlocking interpretable insights into perturbed circuit function. To bridge these dynamics to perception, we propose an interpretable Transformer-based decoder processes the learned V1 representations (Kumar et al., 2024 *Nat Comms*). Leveraging self-attention, it dynamically integrates evidence over time, pinpointing precisely how specific V1 activity patterns and moments causally dictate behavioral outcomes like choice and reaction time. Together, this powerful encoder-decoder framework provides the foundation for intelligent, model-based design of closed-loop visual neuroprosthetics, accelerating the path toward meaningful sight restoration.
</p>
