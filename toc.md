---
layout: page
title: Just all pages
parent: About
navigation: false
---

{% for p in site.pages %}
    {{ p.url  }}
{% endfor %}
