---
layout: page
title: Research
permalink: /research/
description: Current research interests and projects.
nav: true
nav_order: 3
horizontal: false
---

{% include site/language_switcher.liquid %}

<div class="projects">

{% assign sorted_projects = site.projects | sort: "importance" %}

<div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

</div>
