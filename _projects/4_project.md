---
layout: page
title: Big-Data- and Optimization-Driven Sustainable Transport Infrastructure Asset Management
description: Funded by National Research Foundation of Korea 
img: assets/img/19.jpg
importance: 1
category: work
---

Project Description 

- Advanced a two-track program for pavement/transport assets: (1) system-level, multi-scale optimization that links budget allocation, group-level inspection, and facility-level maintenance to minimize discounted social costs; and (2) an autonomous, connected-vehicle–based condition-monitoring concept that feeds real-time data into decision models to cut life-cycle costs.

Role & Contributions

- Formulated a bottom-up optimization framework that couples system-, group-, and facility-level decisions; modeled facility dynamics with Markov decision processes and solved using function approximation and Lagrangian relaxation; validated on a real roadway network near Daejeon. 
 
- Specified inspection frequency and grouping logic to reflect heterogeneous deterioration/traffic environments, enabling adaptive group-specific inspection plans under budget limits. 

- Designed a connected-vehicle condition-monitoring concept: normal vehicles stream vibration/images/GPS to estimate current conditions, integrate data, and inform maintenance timing and policy. 
 
- Structured the social-cost objective and cost models balancing user and agency costs (and extensible to environmental externalities). 

- Implemented prototype analytics and scenario studies in Python to quantify network-level benefits under uncertainty (inspection accuracy, frequency, timing).

Methods & Tools 

- Life-cycle cost analysis; Markov decision processes; function approximation and Lagrangian relaxation; stochastic/dynamic optimization; scenario analysis; Python.

Results

- Published in Transportation Research Part C (2021) and Automation in Construction (2022); numerical experiments show the autonomous monitoring approach reduces social costs versus conventional periodic-inspection PMS.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/38.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Propose a condition monitoring-based road aseet management system 
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/37.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Propose a new road asset monitoring system using connected vehicles 
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
