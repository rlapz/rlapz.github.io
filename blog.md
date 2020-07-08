---
layout: default
title: Blog
---
### Daftar Postingan:

{% for post in site.posts %}
1.[{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}
