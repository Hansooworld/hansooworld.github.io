---
layout: archive
permalink: /settings-mac/
title: "Mac"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.settings-mac %}
{% for post in posts %}
  {% include archive-single.html type=entries_layout %}
{% endfor %}