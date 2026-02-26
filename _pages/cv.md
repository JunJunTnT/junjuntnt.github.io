---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Beijing Univeristy of Posts and Telecommunications, 2027 (expected)
* B.S. in Beijing Univeristy of Posts and Telecommunications, 2022


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards
======
  <ul>{% for post in site.awards reversed %}
    {% include archive-single-award.html %}
  {% endfor %}</ul>
  
