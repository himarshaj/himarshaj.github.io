---
layout: archive
title: "Presentations"
permalink: /presentations/
author_profile: true
---

{% include base_path %}

{% for post in site.presentations reversed %}
  {% if post.type == "year" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
