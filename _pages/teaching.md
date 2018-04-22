---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

- [Machine Learning](https://ankitbit.github.io/Machine-Learning/) - Course notes for Machine Learning (MIRI-ML) 

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
