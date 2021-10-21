---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My papers and preprints can also be accessed on [arxiv](https://arxiv.org/search/?query=Abrishami%2C+Tara&searchtype=author&abstracts=show&order=-announced_date_first&size=100) or [Google Scholar](https://scholar.google.com/citations?user=GvdjMbcAAAAJ&hl=en). 

[**Submodular functions and perfect graphs**](https://arxiv.org/abs/2110.00108)<br/>
with Maria Chudnovsky, Cemil Dibek, and Kristina Vušković. <br/>
Manuscript, September 2021. <br/>

[**Induced subgraphs and tree decompositions III. Three-path-configurations and logarithmic treewidth**](https://arxiv.org/abs/2109.01310)<br/>
with Maria Chudnovsky, Sepehr Hajebi, and Sophie Spirkl. <br/>
Submitted, August 2021. <br/>

[**Induced subgraphs and tree decompositions II. Toward walls and their line graphs in graphs of bounded degree**](https://arxiv.org/abs/2108.01162)<br/>
with Maria Chudnovsky, Cemil Dibek, Sepehr Hajebi, Paweł Rzążewski, Sophie Spirkl, and Kristina Vušković. <br/>
Submitted, August 2021. <br/>

[**Polynomial-time algorithm for Maximum Independent Set in bounded-degree graphs with no long induced claws**](https://arxiv.org/abs/2107.05434)<br/>
with Maria Chudnovsky, Cemil Dibek, and Paweł Rzążewski. <br/>
To appear. <br/>

[**Induced subgraphs and tree decompositions I. Even-hole-free graphs of bounded degree**](https://arxiv.org/abs/2009.01297)<br/>
with Maria Chudnovsky and Kristina Vušković. <br/>
Submitted, September 2020. <br/>

[**Graphs with polynomially many minimal separators**](https://www.sciencedirect.com/science/article/pii/S0095895621000848?dgcid=coauthor)<br/>
with Maria Chudnovsky, Cemil Dibek, Stéphan Thomassé, Nicolas Trotignon, and Kristina Vušković. <br/>
Journal of Combinatorial Theory, Series B 152, January 2022, Pages 248-280. <br/>

[**Induced subgraphs of bounded treewidth and the container method**](https://epubs.siam.org/doi/10.1137/1.9781611976465.116)<br/>
with Maria Chudnovsky, Marcin Pilipczuk, Paweł Rzążewski, and Paul Seymour. <br/>
Proceedings of the 2021 ACM-SIAM Symposium on Discrete Algorithms (SODA). <br/>


[**Geometry of Graph Partitions via Optimal Transport**](https://epubs.siam.org/doi/10.1137/19M1295258)<br/>
with Nestor Guillen, Parker Rule, Zachary Schutzman, Justin Solomon, Thomas Weighill, and Si Wu. <br/>
SIAM Journal on Scientific Computing 42 (5), A3340-A3366. <br/>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
