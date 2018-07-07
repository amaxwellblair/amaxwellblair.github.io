---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Terms
<div>
 {% for item in site.data.definitions %}
    <a href="definition/{{ item.url }}" alt="{{ item.term }}">{{ item.term }}</a>
 {% endfor %}
</div>

More coming soon!
