---
layout: default
title: Building NewAlpha
---

![NewAlpha wordmark]({{ "/assets/img/newalpha-wordmark.png" | relative_url }})

A dev blog documenting the creation of **NewAlpha** — a personal virtual space, built slowly, from nothing.

## Posts

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>