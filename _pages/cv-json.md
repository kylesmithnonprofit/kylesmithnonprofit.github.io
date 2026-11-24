---
layout: archive
title: "CV"
permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
  - /cv/
  - /resume
---

{% include base_path %}

{% comment %} The ?v= stamp changes on every site rebuild, so browsers fetch the latest CV instead of a saved copy. {% endcomment %}
{% capture cv_url %}{{ base_path }}/files/cv.pdf?v={{ site.time | date: '%s' }}{% endcapture %}

<div class="cv-download-links">
  <a href="{{ cv_url }}" class="btn btn--primary">Download CV as PDF</a>
</div>

<div class="cv-embed" style="margin-top:1rem;">
  <iframe src="{{ cv_url }}" width="100%" height="900" style="border:1px solid #ddd;" title="Curriculum Vitae"></iframe>
</div>
