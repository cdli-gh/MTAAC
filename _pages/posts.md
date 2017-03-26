---
permalink: /posts/
title: "All Posts"
layout: single
sidebar:
  nav: "docs"
header:
  overlay_image: /assets/images/P248594.jpg
---
{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}
{% include paginator.html %}
