---
permalink: /posts/
title: "All Posts"
layout: single
sidebar:
  nav: "docs"
---
{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}
{% include paginator.html %}
