---
layout: page
title: Блог для думающих людей
tagline: Supporting tagline
---
{% include JB/setup %}

<div class="row">
  <div class="col-md-12">

## Список постов:

    <ul class="posts">
      {% for post in site.posts %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
    </ul>

    ## Далее

    Делать вывод о Джекилл и вести блог))

  </div>
</div>


