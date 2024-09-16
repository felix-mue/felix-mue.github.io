---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download my CV (file to be added).

Education
======
* currently: Ph.D student at Leipzig Institute for Meteorology, Leipzig University, Leipzig, Germany
* M.Sc. in Mathematics and Philosophy at Otto von Guericke University, Magdeburg, Germany, 2019
* B.Sc. in Mathematics and Philosophy at Otto von Guericke University, Magdeburg, Germany, 2015

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
