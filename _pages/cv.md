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
* B.S. in Mathematics, University of Chicago, 2020
* Ph.D Candidate in Medical Biophysics, University of Toronto, 2025 (expected)

Selected Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Selected Conference Presentations
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Selected Teaching Experiences
======
  <ul>{% for post in site.teaching reversed %}
  {% include archive-single.html %}
 {% endfor %}</ul>

For a full CV, please see [here](/assets/pdf/cv.pdf).
