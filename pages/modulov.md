---
layout: default
title: "Modulo v"
---
# Sinossi propedeutica del modulo v

### Calcolo di integrali indefiniti

<ul>
  {% for post in site.posts %}
  {% if post.category == 'modulov' and post.tags contains "integrali indefiniti" %}
    <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br/>
    <small>Data: [{{ post.date | date: '%B %d, %Y' }}]<br/>
    Argomenti: {{ post.tags | join: ' / ' }}</small>
    </li>
    {% endif %}
  {% endfor %}
</ul>

### Volume di solidi di rotazione

<ul>
  {% for post in site.posts %}
  {% if post.category == 'modulov' and post.tags contains "volume solidi di rotazione" %}
    <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br/>
    <small>Data: [{{ post.date | date: '%B %d, %Y' }}]<br/>
    Argomenti: {{ post.tags | join: ' / ' }}</small>
    </li>
    {% endif %}
  {% endfor %}
</ul>
