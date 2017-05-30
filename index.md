---
layout: default
title:  "Home"
---
# Ultime 10 pubblicazioni

<ul>
  {% for post in site.posts %}
    <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br/>
    <small>Data: [{{ post.date | date: '%B %d, %Y' }}] - Modulo: {{ post.category | remove: 'modulo' }}<br/>
    Argomenti: {{ post.tags | join: ' / ' }}</small>

    </li>
  {% endfor %}
</ul>
