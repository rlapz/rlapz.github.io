---
layout: pages
title: Blog
---
### Daftar Postingan:
[Bottom]({{ site.url }}/blog/#top).
#### Pencarian: Ctrl-F (Firefox/Chrome)

{% for post in site.posts %}
1.[{{ post.title }}]({{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}
[Top]({{ site.url }}/blog/#blog).
