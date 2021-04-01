---
layout: pages
title: Blog
---
##### [[Bottom]]({{ site.url }}/blog.html#top). Ctrl-F (Firefox/Chrome) untuk melakukan pencarian
### Daftar Postingan:
{% for post in site.posts %}
1.[{{ post.title }}]({{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}
##### [[Top]]({{ site.url }}/blog.html#blog).
