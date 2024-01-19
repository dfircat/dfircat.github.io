---
layout: default
title: Welcome to DFIR.CAT
permalink: /
---

![DFIRCAT Logo](assets/img/dfircat-logo.png)

# Welcome 

This is the main landing page for DFIR.CAT.

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
