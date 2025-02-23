---
layout: home
title: Welcome to Random Stuff
---

# Welcome to Random Stuff

Here you'll find my thoughts, experiences, and tutorials on various topics including:

- Technology trends and insights
- Travel adventures and tips
- Cooking recipes and techniques
- Software development tutorials and best practices

## Latest Posts

{% for post in site.posts limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
