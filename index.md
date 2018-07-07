---
layout: home
title: Glossary
---

<div>
 {% for item in site.data.definitions %}
    <a href="definition/{{ item.url }}" alt="{{ item.term }}">{{ item.term }}</a>
 {% endfor %}
</div>

More coming soon!
