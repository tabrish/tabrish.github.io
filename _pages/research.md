---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My papers and preprints can also be accessed on [arxiv](https://arxiv.org/search/?query=Abrishami%2C+Tara&searchtype=author&abstracts=show&order=-announced_date_first&size=100) or [Google Scholar](https://scholar.google.com/citations?user=GvdjMbcAAAAJ&hl=en). 

[**Induced subgraphs and tree decomposisions V. One neighbor in a hole**](https://arxiv.org/abs/2205.04420)<br/>
with Bogdan Alecu, Maria Chudnovsky, Sepehr Hajebi, Sophie Spirkl, and Krinstina Vušković. <br/>
Submitted, May 2022. <br/>

[**Induced subgraphs and tree decompositions IV. (Even hole, diamond, pyramid)-free graphs**](https://arxiv.org/abs/2203.06775)<br/>
with Maria Chudnovsky, Sepehr Hajebi, and Sophie Spirkl. <br/>
Submitted, March 2022. <br/>

[**Submodular functions and perfect graphs**](https://arxiv.org/abs/2110.00108)<br/>
with Maria Chudnovsky, Cemil Dibek, and Kristina Vušković. <br/>
Submitted, September 2021. <br/>

[**Induced subgraphs and tree decompositions III. Three-path-configurations and logarithmic treewidth**](https://arxiv.org/abs/2109.01310)<br/>
with Maria Chudnovsky, Sepehr Hajebi, and Sophie Spirkl. <br/>
Submitted, August 2021. <br/>

[**Induced subgraphs and tree decompositions II. Toward walls and their line graphs in graphs of bounded degree**](https://arxiv.org/abs/2108.01162)<br/>
with Maria Chudnovsky, Cemil Dibek, Sepehr Hajebi, Paweł Rzążewski, Sophie Spirkl, and Kristina Vušković. <br/>
Submitted, August 2021. <br/>

[**Polynomial-time algorithm for Maximum Independent Set in bounded-degree graphs with no long induced claws**](https://arxiv.org/abs/2107.05434)<br/>
with Maria Chudnovsky, Cemil Dibek, and Paweł Rzążewski. <br/>
Proceedings of the 2022 Annual ACM-SIAM Symposium on Discrete Algorithms (SODA), 1448-1470. <br/>

[**Induced subgraphs and tree decompositions I. Even-hole-free graphs of bounded degree**](https://arxiv.org/abs/2009.01297)<br/>
with Maria Chudnovsky and Kristina Vušković. <br/>
Journal of Combinatorial Theory, Series B 157, November 2022, 144-175. <br/>

[**Graphs with polynomially many minimal separators**](https://www.sciencedirect.com/science/article/pii/S0095895621000848?dgcid=coauthor)<br/>
with Maria Chudnovsky, Cemil Dibek, Stéphan Thomassé, Nicolas Trotignon, and Kristina Vušković. <br/>
Journal of Combinatorial Theory, Series B 152, January 2022, 248-280. <br/>

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
