---
title: "k3s"
layout: category
permalink: categories/k3s
author_profile: true
toc: true
toc_sticky: true
sidebar:
    nav: "categories"

---
{% assign posts = site.categories.k3s %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}