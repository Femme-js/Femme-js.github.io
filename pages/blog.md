---
layout: page
title: Blog
permalink: /blog
---

<section class="post-list">
  <div class="container">
    {% for post in site.posts %}
      <article class="post-item">
        <span class="post-meta date-label">{{ post.date | date: "%b %d" }}</span>
        <div class="article-title"><a class="post-link" href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a></div>
      </article>
    {% endfor %}
  </div>

</section>
