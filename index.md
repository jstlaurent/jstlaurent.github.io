## The latest blog posts
{% for post in site.posts %}
* [{{ post.title }} ({{ post.date | date: "%b %Y" }})]({{ post.url }})
{% endfor %}