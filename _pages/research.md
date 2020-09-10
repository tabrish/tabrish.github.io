---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My papers and preprints can also be accessed on [arxiv](https://arxiv.org/search/?query=Abrishami%2C+Tara&searchtype=author&abstracts=show&order=-announced_date_first&size=100).

[**Even-hole-free graphs with bounded degree have bounded treewidth**](https://arxiv.org/abs/2009.01297)<br/>
with Maria Chudnovsky and Kristina Vušković. <br/>
Submitted, September 2020 <br/>

[**Graphs with polynomially many minimal separators**](https://arxiv.org/abs/2005.05042)<br/>
with Maria Chudnovsky, Cemil Dibek, Stéphan Thomassé, Nicolas Trotignon, and Kristina Vušković. <br/>
Submitted, May 2020 <br/>

[**Induced subgraphs of bounded treewidth and the container method**](https://arxiv.org/abs/2003.05185)<br/>
with Maria Chudnovsky, Marcin Pilipczuk, Paweł Rzążewski, and Paul Seymour. <br/>
Submitted, March 2020 <br/>


[**Geometry of Graph Partitions via Optimal Transport**](https://arxiv.org/abs/1910.09618)<br/>
with Nestor Guillen, Parker Rule, Zachary Schutzman, Justin Solomon, Thomas Weighill, and Si Wu. <br/>
To appear in *SIAM Journal of Scientific Computing* <br/>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
