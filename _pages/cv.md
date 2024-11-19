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
* Ph.D in CV/ML, Marine Robotics group, Australian Centre for Robotics, University of Sydney, 2020 - present
* M.S. in Information and Communication Engineering, Shanghai Jiao Tong University, 2022
* B.S. in Electronic Science and Technology, Southeast University, 2017


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
  
