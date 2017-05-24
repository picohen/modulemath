---
layout: default
title:  "Welcome to Jekyll!"
---
Pubblicazioni
-----
<ul>
  {% for post in site.posts %}
    <li>
      ({{post.date}}) - <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} - Categories: {{ post.categories }}</a>
    </li>
  {% endfor %}
</ul>
