---
layout: page
permalink: /teaching/
title: Teaching
description: Teaching materials I plan to use in future courses
nav: true
nav_order: 5
display_categories: [Undergraduate, Graduate]
---

<div class="projects">
{% if page.display_categories %}
  <!-- 카테고리별 렌더 -->
  {% for category in page.display_categories %}
    <a id="{{ category }}" href=".#{{ category }}">
      <h2 class="category">{{ category }}</h2>
    </a>
    {% assign categorized_items = site.teaching | where: "category", category %}
    {% assign sorted_items = categorized_items | sort: "importance" %}
    {% if page.horizontal %}
      <div class="container">
        <div class="row row-cols-1 row-cols-md-2">
          {% for project in sorted_items %}
            {% include teaching_horizontal.liquid %}
          {% endfor %}
        </div>
      </div>
    {% else %}
      <div class="row row-cols-1 row-cols-md-3">
        {% for project in sorted_items %}
          {% include teaching_card.liquid %}
        {% endfor %}
      </div>
    {% endif %}
  {% endfor %}
{% else %}
  <!-- 전체 렌더 (카테고리 안 씀) -->
  {% assign sorted_items = site.teaching | sort: "importance" %}
  {% if page.horizontal %}
    <div class="container">
      <div class="row row-cols-1 row-cols-md-2">
        {% for project in sorted_items %}
          {% include teaching_horizontal.liquid %}
        {% endfor %}
      </div>
    </div>
  {% else %}
    <div class="row row-cols-1 row-cols-md-3">
      {% for project in sorted_items %}
        {% include teaching_card.liquid %}
      {% endfor %}
    </div>
  {% endif %}
{% endif %}
</div>
