---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Works in Progress:
------
* Using QRE Simulations for Power Analysis and Improved Experimental Design.
* Competition in Information: An Experimental Investigation of Bayesian Persuasion in a Sequential Search Market.

Working Papers:
------
* [Behavioral Bandits: Analyzing the Exploration Versus Exploitation Trade-off in the Lab](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3484498) (with [Stanton Hudja](http://stantonhudja.com)).
* [Network Defense and Behavioral Biases:  An Experimental Study](https://www.krannert.purdue.edu/faculty/cason/papers/Network_defense_exp.pdf) (with Mustafa Abdallah, Saurabh Bagchi, Shreyas Sundaram, and Timothy Cason).

Publications:
------

{% include base_path %}

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
