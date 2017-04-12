#this is the home page

{% for post in site.posts %}
1.[{{ post.Test Post}}] ({{ post.url }})
{% endfor %}
