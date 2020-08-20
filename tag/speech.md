---
layout: page
title: research
exclude: true
---

### tags
[all](% link research.md %),
[**algorithm**](% link tag/algorithm.md %)

### projects
<ul style="list-style-type:none">
  {% for post in site.tags.algorithm %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
