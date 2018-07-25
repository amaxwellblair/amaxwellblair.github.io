---
layout: home
title: "Measure, analyze and evaluate user growth"
---
Our mission is to provide definitions of the most used growth metrics as well as practical applications of how they are used across the industry.

## Metrics
<ul>
 {% for item in site.data.definitions %}
    <li><a href="definition/{{ item.url }}" alt="{{ item.term }}">{{ item.term }}</a></li>
 {% endfor %}
</ul>
