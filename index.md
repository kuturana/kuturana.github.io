---
layout: default
---

{% for post in site.posts %}
<center><time>{{ post.date | date: "%b %-d, %Y" }}</time></center>
<h2>{{ post.title }}</h2>
{{ post.excerpt }}
<hr>
{% endfor %}
