---
title: Technical Share
layout: default
permalink: /categories/tech_share/
---

# 🤖 Tech Share 工作技术分享
欢迎来到 Technical share 分类~ 在这里，**学习 思考 分享~**

{% for post in site.posts %}
  {% if post.categories contains "tech_share" %}
  - [{{ post.title }}]({{ site.url }}{{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
  {% endif %}
{% endfor %}

![HelloJune](../assets/images/HelloJune5.png)
