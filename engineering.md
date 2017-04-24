---
layout: page
title: Engineering
permalink: /engineering/
---

<p>Posts in category "engineering" are:</p>

<ul>
  {% for post in site.categories.engineering %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
