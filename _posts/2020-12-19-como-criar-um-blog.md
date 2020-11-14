---
title: "Como criar um blog"
date: 2020-11-12 04:08:10 -0300
categories: Tutoriais
---

Acrecentando Imagem no Jekyll
![Imagem do personagem Jekyll e Hyde](/assets/img/exemplo.jpg)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
