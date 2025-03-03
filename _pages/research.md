---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=gQ-e6pEAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{{author.googlescholar}}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Working Papers:
------
* [Personality Testing and the Public Goods Game](https://woodsd42.github.io/files/PTPGG.pdf) 
* [Strategies in the Multi-armed Bandit](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3942930) (with [Stanton Hudja](http://stantonhudja.com)).
* [Forced Experimentation](https://dx.doi.org/10.2139/ssrn.5159357) (with [Stanton Hudja](http://stantonhudja.com) and [Braxton Gately](https://jbgatelyecon.wixsite.com/website)).


Publications:
------

{% include base_path %}

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  Works in Progress:
------
* Using QRE Simulations for Power Analysis.
