---
layout: pageNC
title: Archive
---

## Blog Posts

Other older posts can still be seen [at an older version of the blog](http://purplecrowlidar.blogspot.ca).

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
