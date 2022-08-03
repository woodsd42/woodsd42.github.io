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
* [Strategies in the Multi-armed Bandit](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3942930) (with [Stanton Hudja](http://stantonhudja.com)).
* [Exploration Versus Exploitation: A Laboratory Test of the Single-Agent Exponential Bandit Model](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3484498) (with [Stanton Hudja](http://stantonhudja.com)).

Works in Progress:
------
* Using QRE Simulations for Power Analysis.

Publications:
------

{% include base_path %}

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
