---
layout: default
title: CS&SE
permalink: /cs/
---

# posts about computer science and software engineering

<ul>
  {% for post in site.posts %}
  {% if post.tag =="cs" %}
  <li><a href="{{ post.url }}" class="post-preview">{{ post.title }}</a></li>
  {% endif %}
  {% endfor %}
</ul>