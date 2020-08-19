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

**[LEAF: A Faster Secure Search Algorithm via Localization, Extraction, and Reconstruction](http://wenruiustc.github.io/files/LEAF.pdf)**

**Rui Wen**, Yu Yu, Xiang Xie, Yang Zhang

*In ACM SIGSAC Conference on Computer and Communications Security (CCS 2020)*

&nbsp; 
  

**[Dynamic Backdoor Attacks Against Machine Learning Models](https://arxiv.org/abs/2003.03675)**

Ahmed Salem, **Rui Wen**, Michael Backes, Shiqing Ma, Yang Zhang

*Technical Report*
