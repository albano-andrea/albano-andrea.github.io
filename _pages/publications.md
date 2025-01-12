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

Preprints
---
  * A. Albano, M. Mazzotta, P. Stefanelli: Reflections to set-theoretic solutions of the Yang-Baxter equation, [[arXiv:2405.19105]](https://arxiv.org/abs/2405.19105).  
