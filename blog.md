---
layout: default
title: Blog
permalink: /blog/
---

<h1>Entradas del Blog</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>