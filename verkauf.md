---
layout: default
title: Verkauf
---

# Verkauf

<ul>
  {% for product in site.products %}
    <li>
      <h2><a href="{{ product.url }}">{{ product.title }}</a></h2>
      <p>{{ product.excerpt }}</p>
    </li>
  {% endfor %}
</ul>