---
layout: default
title: Josh Sullivan
from_the_blog: 2
---

{% for post in site.posts %}
{% if forloop.index <= page.from_the_blog %}
<div class="post_container">
  <h1> {{ post.title }} </h1>
  <figure>
    <img src="/images/{{ post.image }}" />
  </figure>
  {{ post.content | truncatewords: 100 }}
  <div class="read_more">
    <a href="{{ post.url}}">Continue</a>
  </div>
</div>
{% endif %}
{% endfor %}
