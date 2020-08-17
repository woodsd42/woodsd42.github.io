---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Working Papers
------
* Behavioral Bandits: Analyzing the Exploration Versus Exploitation Trade-off in the Lab” (with Stanton Hudja).
* “Network Defense and Behavioral Biases:  An Experimental Study” (with Mustafa Abdallah, Saurabh Bagchi, Shreyas Sundaram, and Timothy Cason).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
