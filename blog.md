---
layout: blog
title: Blog
subtitle: Some thoughts...
---

{% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
{% endfor %}

