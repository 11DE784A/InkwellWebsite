---
layout: default
title: SISSA Inkwell
---

<h1>Latest</h1>

{% for post in site.posts %}
<section>
  <div>{{ post.categories }}</div>
  <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
  <p>{{ post.excerpt }}</p>
  <div>{{ post.author }}</div>
  <div>{{ post.date | date: '%d %B %Y'}}</div>
</section>
{% endfor %}
