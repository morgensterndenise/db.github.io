---
title: Index
layout: template
filename: index.md 
--- 
{% for page in site.pages %}
    <a href={{ page.filename }}>{{ page.title }}</a>
{% endfor %}

## Tips and good practices
