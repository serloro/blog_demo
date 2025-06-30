---
layout: default
title: "Inicio"
---

# Welcome to my blog

This is my personal blog where a share my thoughts, experiences and knoledge.

## Ultimas publicaciones

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%d/%m/%Y" }}
    </li>
  {% endfor %}
</ul>

## About me

I am a developer with a lot of passion.

---

*Gracias por visitar mi blog!*
