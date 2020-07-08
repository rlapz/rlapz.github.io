---
layout: default
---
{% include nav_post.html %}
<h2>{{ page.title }}</h2>
{{ page.date | date_to_string }} - {{ page.author }}

{{ content }}
