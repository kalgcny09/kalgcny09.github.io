#this is the home page

{% for post in site.posts %}
1.[{{ post.testpost }}] ({{ post.url }})
{% endfor %}
