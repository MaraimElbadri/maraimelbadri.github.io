---
layout: archive
permalink: /blog/
title: "Blog Posts"
author_profile: true
---

{% include base_path %}

{% for post in site.posts %}
  {% if post.categories contains 'Tutorial' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}