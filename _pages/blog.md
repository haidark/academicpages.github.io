---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% include base_path %}

This is a test.

{% for post in site.blog reversed %}
  {% include archive-single-talk.html %}
{% endfor %}