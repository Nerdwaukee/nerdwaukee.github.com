---
layout: page
title: Nerdwaukee
tagline: Nerd up with us
---
{% include JB/setup %}

## What is Nerdwaukee

Nerdwaukee simply aims to bring nerds together. We accept all kinds of nerds - young nerds, old nerds, student nerds, entrepreneur nerds, introverted nerds, extroverted nerds, and nerds-who-dont-know-they-are-nerds-yet nerds are a few groups we are looking at. Let’s make a networks of nerds.
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


