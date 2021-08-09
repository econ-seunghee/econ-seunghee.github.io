---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Working Papers
======
* "An Empirical Investigation of Intergenerational Mobility in Korea" \ This version : 
* "A Trajectories-Based Approach toMeasuring IntergenerationalMobility" (with Yoosoon Chang, Steven N. Durlauf and Joon Y. Park)

{% for post in site.working reversed %}
  {% include archive-single.html %}
{% endfor %}


Publication
======

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

