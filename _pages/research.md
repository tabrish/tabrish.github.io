---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My papers and preprints can also be accessed on my [arXiv author page](https://arxiv.org/a/abrishami_t_1.html) or [Google Scholar profile](https://scholar.google.com/citations?user=GvdjMbcAAAAJ&hl=en). 

**Published:** <br/>

1. **Induced subgraphs and tree decompositions IV. (Even hole, diamond, pyramid)-free graphs**]  [[journal](https://www.combinatorics.org/ojs/index.php/eljc/article/view/p30i2p42)] [[arxiv](https://arxiv.org/abs/2203.06775)] <br/>
with Maria Chudnovsky, Sepehr Hajebi, and Sophie Spirkl. <br/>
Electronic Journal of Combinatorics, Volume 30, Issue 2, 2023. <br/>

3. **Induced subgraphs and tree decompositions III. Three-path-configurations and logarithmic treewidth**]  [[journal](https://www.advancesincombinatorics.com/article/38089-induced-subgraphs-and-tree-decompositions-iii-three-path-configurations-and-logarithmic-treewidth)] [[arxiv](https://arxiv.org/abs/2109.01310)]<br/>
with Maria Chudnovsky, Sepehr Hajebi, and Sophie Spirkl. <br/>
Advances in Combinatorics, 2022. <br/>

4. **Polynomial-time algorithm for Maximum Independent Set in bounded-degree graphs with no long induced claws**  [[conference](https://epubs.siam.org/doi/10.1137/1.9781611977073.61)][[arxiv](https://arxiv.org/abs/2107.05434)]<br/>
with Maria Chudnovsky, Cemil Dibek, and Paweł Rzążewski. <br/>
Proceedings of the 2022 Annual ACM-SIAM Symposium on Discrete Algorithms (SODA), 1448-1470. <br/>

5. **Induced subgraphs and tree decompositions I. Even-hole-free graphs of bounded degree** [[journal](https://www.sciencedirect.com/science/article/pii/S0095895622000533)][[arxiv](https://arxiv.org/abs/2009.01297)]<br/>
with Maria Chudnovsky and Kristina Vušković. <br/>
Journal of Combinatorial Theory, Series B 157, November 2022, 144-175. <br/>

6. **Graphs with polynomially many minimal separators** [[journal](https://www.sciencedirect.com/science/article/pii/S0095895621000848)][[arxiv](https://arxiv.org/abs/2005.05042)]<br/>
with Maria Chudnovsky, Cemil Dibek, Stéphan Thomassé, Nicolas Trotignon, and Kristina Vušković. <br/>
Journal of Combinatorial Theory, Series B 152, January 2022, 248-280. <br/>

7. **Induced subgraphs of bounded treewidth and the container method** [[conference](https://epubs.siam.org/doi/10.1137/1.9781611976465.116)][[arxiv](https://arxiv.org/abs/2003.05185)]<br/>
with Maria Chudnovsky, Marcin Pilipczuk, Paweł Rzążewski, and Paul Seymour. <br/>
Proceedings of the 2021 ACM-SIAM Symposium on Discrete Algorithms (SODA). <br/>


8. **Geometry of Graph Partitions via Optimal Transport** [[journal](https://epubs.siam.org/doi/10.1137/19M1295258)][[arxiv](https://arxiv.org/abs/1910.09618)] <br/>
with Nestor Guillen, Parker Rule, Zachary Schutzman, Justin Solomon, Thomas Weighill, and Si Wu. <br/>
SIAM Journal on Scientific Computing 42 (5), A3340-A3366. <br/>

**Submitted:** 

1. **Induced subgraphs and tree decompositions VII. Basic obstructions in H-free graphs**  [[arxiv](https://arxiv.org/abs/2212.02737)]<br/>
with Bogdan Alecu, Maria Chudnovsky, Sepehr Hajebi, and Sophie Spirkl. <br/>
Manuscript, December 2022. <br/>

2. **Tree decompositions and many-sided separations**  [[arxiv](https://arxiv.org/abs/2207.10778)] <br/>
Manuscript, August 2022. <br/>

3. **Induced subgraphs and tree decompositions VI. Graphs with 2-cutsets**  [[arxiv](https://arxiv.org/abs/2207.05538)]<br/>
with Maria Chudnovsky, Sepehr Hajebi, and Sophie Spirkl. <br/>
Submitted, July 2022. <br/>

4. **Induced subgraphs and tree decompositions V. One neighbor in a hole** [[arxiv](https://arxiv.org/abs/2205.04420)]<br/>
with Bogdan Alecu, Maria Chudnovsky, Sepehr Hajebi, Sophie Spirkl, and Krinstina Vušković. <br/>
Submitted, May 2022. <br/>

5. **Submodular functions and perfect graphs** [[arxiv](https://arxiv.org/abs/2110.00108)] <br/>
with Maria Chudnovsky, Cemil Dibek, and Kristina Vušković. <br/>
Submitted, September 2021. <br/>

6. **Induced subgraphs and tree decompositions II. Toward walls and their line graphs in graphs of bounded degree**  [[arxiv](https://arxiv.org/abs/2108.01162)]<br/>
with Maria Chudnovsky, Cemil Dibek, Sepehr Hajebi, Paweł Rzążewski, Sophie Spirkl, and Kristina Vušković. <br/>
Submitted, August 2021. <br/>




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
