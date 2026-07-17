---
layout: page
title: 科研
permalink: /zh/research/
description: 当前研究方向与课题。
nav: false
---

临时入口：[English version]({{ '/research/' | relative_url }})

<div class="projects">

{% assign sorted_projects = site.zh_projects | sort: "importance" %}

<div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

</div>
