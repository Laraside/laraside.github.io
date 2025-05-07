---
layout: default
title: Accueil
---

# Bienvenue sur mon blog

Voici mes derniers articles :

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y/%m/%d" }}
    </li>
  {% endfor %}
</ul>






