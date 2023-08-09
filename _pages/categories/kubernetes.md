---
title: "k3s"
layout: categories
permalink: categories/kubernetes
author_profile: true
toc: true
toc_sticky: true
sidebar:
    nav: "categories"

---
{% assign posts = site.categories.kubernetes %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}