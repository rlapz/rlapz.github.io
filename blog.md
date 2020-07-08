---
layout: default
title: Blog
---
{% include nav_default.md%}

### Daftar Postingan:

{% for post in site.posts %}
1.[{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}



