---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
For a full CV, please see [here](/assets/pdf/cv.pdf).

Education
======
* B.S. in Mathematics, University of Chicago, 2020
* Ph.D Candidate in Medical Biophysics, University of Toronto, 2025 (expected)

Selected Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Selected Conference Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Selected Teaching Experiences
======
Please see [here](/teaching/).

