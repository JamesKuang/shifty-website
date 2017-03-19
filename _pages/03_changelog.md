---
layout: page
title: Changelog
permalink: /changelog/
---

{% for post in site.posts %}
#### {{ post.date | date: "%b %-d, %Y" }}
### {{ post.title }}
{{ post.content }}
***
{% endfor %}

<!--<p>subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>-->