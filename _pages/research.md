---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

An up-to-date list of my papers and preprints can be found on my [arXiv author page](https://arxiv.org/a/abrishami_t_1.html) or [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=6z6Pjt0AAAAJ). 

<img src="https://tabrish.github.io/files/central-bag-image.png" width="120" align = "left" /> My PhD focused on the relationship between induced subgraphs and treewidth. My coauthors and I developed a method called the central bag method to help study this problem. [Here](https://tabrish.github.io/files/central_bags.pdf) is a survey I wrote of the central bag method and some of the ways we applied it. <br/>



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
