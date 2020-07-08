---
layout: pages
title: Blog
---
### Daftar Postingan:

{% for post in site.posts %}
1.[{{ post.title }}]({{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}
