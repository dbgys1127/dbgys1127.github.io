---
title: "Tip"
layout: archive
permalink: /tip
# author_profile: true
# sidebar_main: true
---
{% assign posts = site.categories.tip %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}