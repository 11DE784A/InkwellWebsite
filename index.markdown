---
layout: default
title: Home
---

# Welcome to SISSA Inkwell!

SISSA Inkwell is a shared community publication in which everyone is free to
speak out about _anything_. Our first issue is out now!

{% assign letter = site.posts | where: "slug", "the-worlds-we-carry" | first %}
{% include post_card.html post=letter %}

## Browse by category

{% assign sorted_tags = site.tags | sort %}
{% for tag in sorted_tags %}
{% if tag[0] == "Letter from the Editor" %} {% continue %} {% endif %}
### {{ tag[0] }}

{% assign tag_posts = tag[1] %}
{% include post_list.html posts=tag_posts %}

{% endfor %}

## Credits

__Editorial Team.__ 
Mohamed Aliouane, 
Anindita Basu, 
Aliza Mustafa,
Camilla Perna,
Valentin Pomakov,
Ayush Singh,
Rubio Gunawan The, and
Enrico Veraldi.

__Design & Layout.__ Camilla Perna.

__Web Design.__ [Ayush Singh](https://www.11de784a.com/).

