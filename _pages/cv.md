---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
</div>

* B.S.B.A. in Accounting, Economics, Bowling Green State University, 2016

Work experience
======
* 2022-Present: Assistant Professor of Accounting
  * Mississippi State University

* 2016-2018: Financial Analyst
  * Deloitte Consulting

  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
