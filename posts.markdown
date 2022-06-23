---
layout: page
title: Posts
permalink: /posts/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/posts{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
