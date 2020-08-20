---
layout: page
title: research
order: 2
---

### tags
[**all**](% link https://samstesmi.github.io/tag/tag/all.md %)
[algorithm](% link https://samstesmi.github.io/tag/tag/algorithm.md %)
[speech](% link https://samstesmi.github.io/tag/tag/speech.md %)

### projects
<ul style="list-style-type:none">
  {% for post in site.tags.all %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
