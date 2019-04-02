---
layout: default
---

{% for post in site.posts %}
<h2>{{ post.title }}</h2>
<center><time>{{ post.date | date: "%b %-d, %Y" }}</time></center>
{{ post.excerpt }}
<hr>
{% endfor %}
