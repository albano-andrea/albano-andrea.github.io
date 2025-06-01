---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

[1] A.A., M. Mazzotta and P. Stefanelli, _Reflections to set-theoretic solutions of the Yang--Baxter equation_, J. Algebra 676 (2025), 106-138.

Preprints
---
  * A. A., P. Stefanelli, _Generalized digroups, di-skew braces and solutions of the set-theoretic Yang--Baxter equation_, [[arXiv:2505.15387]](https://arxiv.org/abs/2505.15387).  
