---
layout: default
title:  "Welcome to Jekyll!"
---
Pubblicazioni
-----
<ul>
  {% for post in site.posts %}
    <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br/>
    Data: [{{ post.date | date: '%B %d, %Y' }}] - Categorie: {{ post.categories | join: ', ' }}.
    </li>
  {% endfor %}
</ul>
