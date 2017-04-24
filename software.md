---
layout: page
title: Software
permalink: /software/
---

<p>Posts in category "software" are:</p>

<ul>
  {% for post in site.categories.software %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
