---
layout: archive
title: "信息可视化作品集"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature: 
  teaser:
---

- <a href="https://sylviatang.github.io/posts/%E6%9C%9F%E6%9C%AB%E9%A1%B9%E7%9B%AE/" target="_blank">![数据分析.png](https://i.loli.net/2018/01/07/5a51dae1bd0a2.png)</a>

其他作品
<div class="tiles">
{% for post in site.categories.visualization %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 visualization 的列出来-->