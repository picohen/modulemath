---
layout: default
title:  "Welcome to Jekyll!"
---
Pubblicazioni
-----
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> Published on {{ post.date.to_date }} under categories {{ post.categories.join(", ") }}
    </li>
  {% endfor %}
</ul>
