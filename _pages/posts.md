---
permalink: /posts/
title: "All Posts"
layout: single
sidebar:
  nav: "docs"
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
