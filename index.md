---
layout: page
title: anoopvalluthadam
---
{% include JB/setup %}

programmer, hardcore;
Heavy metal music listener, while coding;
traveller, by heart;
cricketer, by birth;
Nikonian, for ever.
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




