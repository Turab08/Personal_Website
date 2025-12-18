---
layout: page
title: Blog
permalink: /blog/
---

Welcome to my blog! Here you'll find my latest thoughts and posts.

{% for post in site.posts %}
  <article class="post-preview">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <time>{{ post.date | date: "%B %d, %Y" }}</time>
    <p>{{ post.excerpt }}</p>
  </article>
{% endfor %}