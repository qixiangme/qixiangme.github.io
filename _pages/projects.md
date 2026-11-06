---
layout: page
title: projects
permalink: /projects/
description:
nav: true
nav_order: 1
---

<div class="projects">
  {% assign main = site.projects | where: "category", "work" | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in main %}
      {% include projects.liquid %}
    {% endfor %}
  </div>

  <h2 class="mt-4 mb-3" style="font-size: 1.5rem;">side projects</h2>
  {% assign side = site.projects | where: "category", "side" | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in side %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
