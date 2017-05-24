---
layout: default
title:  "Welcome to Jekyll!"
---
Pubblicazioni
-----
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> Published on {{ post.date | date: '%B %d, %Y' }} under categories {{ post.categories | join: ', ' }}
    </li>
  {% endfor %}
</ul>
