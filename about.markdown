---
layout: page
title: About
permalink: /about/
---

{% assign links = site.static_files | where: "webfinger", true %}
{% for link in links %}
  {{ link.path }}
{% endfor %}
