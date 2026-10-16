---
layout: default
title: SISSA Inkwell
---

<h1>Latest</h1>

{% for post in site.posts %}
<section>
  <div>
    {% for tag in post.tags %} <span class="tag">{{ tag }}</span> {% endfor %}
    {% if post.category %} <span class="tag">Issue {{ post.category }}</span> {% endif %}
  </div>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
  <div>
    <span class="author">{{ post.author }}</span> 
    <time class="date">{{ post.date | date: '%d %B %Y'}}</time>
  </div>
</section>
{% endfor %}
