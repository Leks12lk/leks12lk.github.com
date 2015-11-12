---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

Это скромная попытка создать свой блог.

## И вот всё получилось))

    
    return "Hello World!"


    
## Здесь список постов

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Далее

Делать вывод о Джекилл и вести блог))


