---
layout: page
title: Road Asset Management System (RAMS) Strategy for the Dominican Republic
description: Funded by The Export-Import Bank of Korea
img: assets/img/7.jpg
importance: 3
category: work
---

Project Description 

- Delivered a country-tailored strategy for a national road asset management system: carried out a local diagnostic and institutional review; benchmarked Korean best practices; and produced a master plan, data model, condition indices, prioritization/budgeting processes, training for officials, and a phased implementation roadmap with a trial application concept.

Role & Contributions 

- Led the field diagnostic and stakeholder consultations; compared Korea–Dominican approaches to derive improvement tasks and roadmap items. 
- Designed the framework: specified modules for condition survey/evaluation, repair-method determination, repair-priority setting, and budget allocation; defined the supporting web-based database and annual update workflow. 
- Defined data collection schemas for the inventory and condition layers (e.g., segment attributes, ancillary structures, drainage, climate/land-use), ensuring compatibility with operations and planning. 
- Proposed prioritization principles that account for Dominican climate and disaster frequency (rainy-season flooding, hurricanes/earthquakes), emphasizing preventive maintenance to reduce long-run social costs. 
- Organized and delivered capacity-building: initiation/interim/final briefings and online training for public officials; consolidated feedback into the final strategy. 
- Authored the phased implementation roadmap and trial-application plan to move from detailed design to deployment and monitoring.

Methods & Tools 

- Policy and institutional analysis; asset inventory and pavement-condition index design; maintenance prioritization and budgeting logic; preventive-maintenance economics; GIS-based data modeling; technical writing and stakeholder facilitation.

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

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
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
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
