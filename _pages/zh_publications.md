---
layout: page
title: 论文
permalink: /zh/publications/
description: 使用现有参考文献数据按时间倒序生成的论文列表。
nav: false
---

临时入口：[English version]({{ '/publications/' | relative_url }})

<style>
.publications .author em {
  font-style: normal;
  font-weight: 700;
}
</style>

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
