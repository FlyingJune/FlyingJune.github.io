---
title: Just Fun
layout: default
permalink: /categories/just_fun/
---

# 🪂 Just Fun 轻松一刻
欢迎来到 Just Fun 分类~ 在这里，**追求 开心 舒服 自在~**

{% for post in site.posts %}
  {% if post.categories contains "just_fun" %}
  - [{{ post.title }}]({{ site.url }}{{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
  {% endif %}
{% endfor %}

![HelloJune](../assets/images/HelloJune.png)
