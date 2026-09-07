---
published: false # 暂时下线，日后大改后再打开
layout: page
permalink: /research/
title: research
description: Models that can be told what to make, agents that can tell whether they succeeded, and the representation learning both rest on.
nav: false
nav_order: 2
horizontal: false
---

<!-- _pages/projects.md -->
<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
</div>
