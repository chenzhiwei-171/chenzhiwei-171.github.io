---
layout: page
title: 论文
permalink: /zh/publications/
description: 使用现有参考文献数据按时间倒序生成的论文列表。
nav: false
---

{% include site/language_switcher.liquid %}

<style>
.publications .author em {
  font-style: normal;
  font-weight: 700;
}
</style>

{% include bib_search.liquid %}

<p><sup>*</sup> 表示通讯作者。</p>

<div class="publications">

{% bibliography %}

</div>
