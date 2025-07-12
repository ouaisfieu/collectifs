---
title: Goodies
nav_order: 3
layout: default
---

# Goodies

Logos, icônes et gifs libres à réutiliser.

{% for file in site.static_files %}
{% if file.path contains '/goodies/' %}
- [{{ file.name }}]({{ file.path | relative_url }})
{% endif %}
{% endfor %}
