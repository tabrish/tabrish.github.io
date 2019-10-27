---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

**Geometry of Graph Partitions via Optimal Transport**\
with Nestor Guillen, Parker Rule, Zachary Schutzman, Justin Solomon, Thomas Weighill, and Si Wu. \
Submitted, October 2019 \
[preprint](https://arxiv.org/abs/1910.09618)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
