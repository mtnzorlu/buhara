---
layout: default
title: Categories
---
<div class="box">
  <h4>{{ page.title }}</h4>
  <hr>
<ul class="ctg">
  {% for category in site.categories %}
    <li><a href="{{ site.baseurl }}/categories/{{ category[0] }}">{{ category[0] }}</a></li>
  {% endfor %}
</ul>
</div>