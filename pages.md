---
layout: page
title: 文章列表 
header: Pages
group: navigation
---
{% include JB/setup %}

<h2>标签列表</h2>

<ul class="tag_box inline">
  {% assign tags_list = site.tags %}  
  {% include JB/tags_list %}
</ul>


<h2>所有文章列表</h2>
<ul>
{% assign pages_list = site.pages %}
{% include JB/pages_list %}
</ul>
