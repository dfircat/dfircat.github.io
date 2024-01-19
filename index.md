---
layout: default
title: Welcome to DFIR.CAT
---

![DFIRCAT Logo](assets/img/dfircat-logo.png)

# Welcome 

This is the main landing page for DFIR.CAT.

## About Me

I am a passionate web developer who loves to create static websites with Jekyll.

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
