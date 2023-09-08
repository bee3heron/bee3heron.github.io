---
layout: default
title: "Bird Adventures"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Adventures" %}
{% endif %}
