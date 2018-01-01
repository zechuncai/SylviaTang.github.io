---
layout: archive
title: "学习笔记"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "分为[网页设计笔记][https://sylviatang.github.io/notes/rwd/]和[信息可视化笔记][https://sylviatang.github.io/notes/infovis/]"
tags: []
image: 
  feature: notes.gif
  teaser:
---


<div class="tiles">
{% for post in site.categories.notes %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 notes 的列出来-->
[https://sylviatang.github.io/notes/rwd/]
[https://sylviatang.github.io/notes/infovis/]