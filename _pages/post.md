---
layout: archive
title: "Posts"
permalink: /posts/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

Sharing my ideas on the things that I am learning :point_down:

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.post | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
