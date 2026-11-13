---
layout: default
title: Issues
permalink: /issues/
---

# Issues

Inkwell articles collected by issue.

{% for issue in site.categories reversed %}
## Issue {{ issue[0] }}

{% assign issue_posts = issue[1] %}
{% include post_list.html posts=issue_posts %}

{% endfor %}
