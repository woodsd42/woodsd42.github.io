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
* [Behavioral Bandits: Analyzing the Exploration Versus Exploitation Trade-off in the Lab](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3484498) (with [Stanton Hudja](http://stantonhudja.com)).

Works in Progress:
------
* Using QRE Simulations for Power Analysis.
* Competition in Information: An Experimental Investigation of Bayesian Persuasion in a Sequential Search Market.


Publications:
------

{% include base_path %}

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
