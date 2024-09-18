---
title: "CSRF"
layout: archive
permalink: categories/csrf
author_profile: true
types: posts
---

{% assign posts = site.categories['csrf']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}