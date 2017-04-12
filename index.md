#this is the home page

{% for post in site.posts %}
1.[{{ post.test.post }}] ({{ post.url }})
{% endfor %}
