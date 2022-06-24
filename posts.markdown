---
layout: page
title: Posts
permalink: /posts/
nav_order: 2
title: Title test
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{post.url}}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
