---
title: "k3s"
layout: archive
permalink: categories/k3s
author_profile: true
sidebar:
  - nav: "mycat"
---
{% assign posts = site.categories.categories %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}