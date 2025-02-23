---
layout: home
---

# {% t global.description %}

{% t global.tagline %}

## {% t global.latest_posts %}

{% for post in site.posts limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
