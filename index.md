---
layout: default
---

#Recent Posts ...

{% for post in site.posts limit: 8 %}
####  {{ post.date | date_to_long_string }} - [{{ post.title }}]( {{ post.url}})

{% endfor %}

<hr>
