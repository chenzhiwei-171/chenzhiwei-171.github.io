---
layout: page
title: 科研
permalink: /zh/research/
description: 目前正在开展的研究课题主要为以下三部分：
nav: false
---

{% include site/language_switcher.liquid %}

<div class="projects">

{% assign sorted_projects = site.zh_projects | sort: "importance" %}

<div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

</div>
