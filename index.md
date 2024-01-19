---
layout: default
title: Welcome to My Website
---

# Welcome to My Website

This is the main landing page for my website. You can customize this page by editing the `index.md` file.

## About Me

I am a passionate web developer who loves to create static websites with Jekyll.

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
