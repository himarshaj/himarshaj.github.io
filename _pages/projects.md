---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% assign projects = site.projects | sort: 'order' %}
{% for post in projects %}
  {% include archive-single.html %}
{% endfor %}
