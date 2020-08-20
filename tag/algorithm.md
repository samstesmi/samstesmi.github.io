---
layout: page
title: research
exclude: true
---

### tags
[all](% link {{baseurl}}research.md %),
[**algorithm**](% link {{baseurl}}tag/algorithm.md %)
[speech](% link {{baseurl}}tag/speech.md %)

### projects
<ul style="list-style-type:none">
  {% for post in site.tags.algorithm %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
