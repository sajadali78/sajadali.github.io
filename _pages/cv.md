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
* MS / PhD in Electrical Engineering, Sukkur IBA University, [Year]
* BS in [Field], [University], [Year]

Work experience
======
* [Year] - Present: Graduate Researcher
  * Sukkur IBA University
  * Focus: Electrical Machine Design & Optimization

Skills
======
* **Core:** Synchronous Machines, Finite Element Analysis (FEA), Machine Learning Surrogate Models
* **Tools:** [Software 1], [Software 2]

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
