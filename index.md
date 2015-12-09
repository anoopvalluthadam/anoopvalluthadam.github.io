---
layout: page
title: anoopvalluthadam
---
{% include JB/setup %}

programmer, hardcore; <br />
Heavy metal music listener, while coding; <br />
traveller, by heart; <br />
cricketer, by birth; <br />
Nikonian, for ever. <br />
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




