---
title: Life Canvas
layout: default
permalink: /categories/life_canvas/
---

# 🎨 Life Canvas 生活画布
欢迎来到Life Canvas分类~ 在这里，**有分享 有收获~**

{% for post in site.posts %}
  {% if post.categories contains "life_canvas" %}
  - [{{ post.title }}]({{ site.url }}{{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
  {% endif %}
{% endfor %}

![HelloJune](../assets/images/HelloJune3.png)
