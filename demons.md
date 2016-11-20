---
layout: page
title: Członkowie
permalink: /czlonkowie/
---

<ul>
{% for item in site.data.demonsfromheaven %}
  <li style="{% if item.active %}color: green {% endif %}">
    {{ item.name }} (<em>{{
      item.level}}</em>) {{ item.ilvl }}
  </li>
{% endfor %}
</ul>
