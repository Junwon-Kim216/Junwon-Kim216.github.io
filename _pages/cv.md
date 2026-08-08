---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- M.S. Student, Electrical and Electronic Engineering, Yonsei University

## Research Interests

- Machine learning for wireless communications
- 6G enabling technologies
- Learning-based routing and resource allocation
- Edge computing, LEO satellite networks, and UAV–edge systems

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
