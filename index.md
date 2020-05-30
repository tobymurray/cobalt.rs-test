---
layout: default.liquid
---
## Blog!

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}

A change has been made
![My helpful screenshot](/assets/images/20180505_140918.jpg)