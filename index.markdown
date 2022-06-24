---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Weelcome
nav_order: 1
---

# Welcome!

Welcome to my personal blog. My name is Dominik and I am an iOS developer localed in the Czech Republic. On this page, you can find my [posts](https://dominikgrodl.github.io/posts/) as well as some information about me like my [current projects]() and my [resume]()

## Latest posts

<ul>
  {% for post in site.posts limit:2 %}
   <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
</ul>
