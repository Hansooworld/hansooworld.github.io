---
layout: archive
permalink: /settings-ubuntu
title: "Ubuntu"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.settings-ubuntu %}
{% for post in posts %}
  {% include archive-single.html type=entries_layout %}
{% endfor %}