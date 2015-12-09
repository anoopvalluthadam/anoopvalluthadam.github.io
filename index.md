---
layout: page
title: anoopvalluthadam
---
{% if site.twitter_username %}
  <li>
    <a href="https://twitter.com/{{ site.twitter }}">
      <i class="fa fa-twitter"></i> Twitter
    </a>
  </li>
{% endif %}
{% include JB/setup %}

Programmer, hardcore; <br />
Heavy metal music listener, while coding; <br />
Traveller, by heart; <br />
Cricketer, by birth; <br />
Nikonian, for ever. <br />
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




