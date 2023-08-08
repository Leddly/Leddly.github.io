---
title: "k3s"
layout: archive
permalink: categories/k3s
author_profile: true
sidebar:
  nav: "mycat"
---
{% assign posts = site.categories.k3s %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}