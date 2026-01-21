---
layout: page
title: Documentos
permalink: /documentos/
---

<ul>
  {% for post in site.categories.documentos %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
