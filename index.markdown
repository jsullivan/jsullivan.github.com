---
layout: default
title: Josh Sullivan
from_the_blog: 5
---

{% for post in site.posts %}
{% if forloop.index <= page.from_the_blog %}
<div class="post_container">
  <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
  <figure>
    <a href="{{ post.url}}">
      <img src="/images/{{ post.image }}" />
    </a>
  </figure>
  {{ post.content | truncatewords: 32 }}
  <div class="read_more">
    <a href="{{ post.url}}">Continue reading</a>
  </div>
  <div class="clearfix"></div>
</div>
{% endif %}
{% endfor %}
