---
layout: page
title: The Archive
comments: false
---

Newer posts (after 2016-12): click on a post heading to enable comments (via [disqus](https://disqus.com)).

Other older posts can still be seen [at an older version of the blog](http://purplecrowlidar.blogspot.ca). For commenting let's start a conversation [on twitter @purplecrowlidar](http://twitter.com/purplecrowlidar). 

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
