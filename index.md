---
layout: default
title:  "Welcome to Jekyll!"
---
Pubblicazioni
-----
<ul>
  {% for post in site.posts %}
    <li>
    <p><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></p>
    <p>Pubblicato il {{ post.date | date: '%B %d, %Y' }} nelle categorie: {{ post.categories | join: ', ' }}.</p>
    </li>
  {% endfor %}
</ul>
