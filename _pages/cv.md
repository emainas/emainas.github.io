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
* B.S. in Chemistry, Athens University, Greece, 2017
* M.A. in Chemistry, Brown University, USA, 2019
* Ph.D in Chemistry, Brown University, USA, 2023 
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
