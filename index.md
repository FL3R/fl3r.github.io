---
layout: default
title: "I miei progetti"
---

# I miei progetti GitHub

{% for repository in site.github.public_repositories %}
  - [{{ repository.name }}]({{ repository.html_url }}): {{ repository.description }}
{% endfor %}
