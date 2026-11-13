---
layout: default
title: Categories
permalink: /categories/
---

# Categories

Inkwell articles collected by category.

{% for tag in site.tags %}
## {{ tag[0] }}

{% assign tag_posts = tag[1] %}
{% include post_list.html posts=tag_posts %}

{% endfor %}

