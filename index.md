---
layout: page
title: Nerdwaukee
tagline: Nerd up with us
---
{% include JB/setup %}
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## We're working on this

Don't judge yet

