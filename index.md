## Last posts
{% for post in site.posts limit:5 %}
- [{{post.title}}]({{post.url}}) at {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}
