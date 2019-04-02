---
layout: default
---

{% for post in site.posts %}
<time>{{ post.date | date: "%b %-d, %Y" }}</time>
<h2>{{ post.title }}</h2>
{{ post.excerpt }}
<hr>
{% endfor %}
