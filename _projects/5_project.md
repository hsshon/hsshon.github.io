---
layout: page
title: Urban Mobility Network Analysis & Forecasting with Attention Mechanisms and Graph Neural Networks
description: Funded by National Research Foundation of Korea 
img: assets/img/1.jpg
importance: 2
category: work
---

Project Description

- Developed a graph-based forecasting model that learns taxi-flow–driven, time-varying spatial correlations and predicts short-term and long-term traffic speeds. The study used large-scale DTG taxi data from Seoul (≈10-s sampling aggregated to 10-min intervals; two study sites with 451/863 segments; ~40k taxis and ~14M GPS records per day) and applied hidden Markov model map matching before modeling.
 
Role & Contributions 

- Designed a graph attention + diffusion architecture that propagates traffic states along the network to capture directional effects and dynamic neighborhood influence; added a recurrent temporal encoder for multi-step speed forecasting.

- Built the data pipeline: Taxi DTG GPS → hidden-Markov map matching → network sparsification and segment-level speed aggregation → training/validation splits and normalization. 
 
- Established evaluation protocol and baselines (historical average, support-vector regression, graph convolution, recurrent models) with root-mean-squared error and mean-absolute error as primary metrics.

Methods & Tools

- Graph neural networks with attention and diffusion, recurrent encoder, DTG trajectories, hidden-Markov map matching, Python.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/61.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Dynamic Graph Diffusion Convolutional Network for Traffic Speed prediction 
</div>
