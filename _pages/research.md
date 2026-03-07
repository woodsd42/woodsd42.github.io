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

* [Strategic Misrepresentation in Personality Testing: An Experimental Study using the Public Goods Game](https://woodsd42.github.io/files/PTPGG_JDM.pdf) - <i>forthcoming</i> in <i>Judgment and Decision Making</i>.
* [Examining Experimentation](https://dx.doi.org/10.2139/ssrn.5346974) (with [Stanton Hudja](http://stantonhudja.com)).
* [Stable Experimentation? An Analysis of Multi-Armed Bandit Problems with Bundling](https://dx.doi.org/10.2139/ssrn.5835062) (with [Stanton Hudja](http://stantonhudja.com) and [Jason Ralston](https://jasondralston.com/)).

Publications:
------

{% include base_path %}

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


