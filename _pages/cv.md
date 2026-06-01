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
* Ph.D. in Applied Mathematics, University of Southern California
  * Advisor: Prof. Jianfeng Zhang
* <!-- M.S. / B.S. — degree, institution, year -->

Work Experience
======
* Staff Research Engineer, DiDi Autonomous Driving
* Research Scientist / Engineer, Meta
* Research Scientist / Engineer, Google
<!-- Add dates and a short bullet of responsibilities for each role. -->

Skills
======
* <!-- e.g. Reinforcement learning, robotics, applied math -->

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
  
Service and Leadership
======
* <!-- Reviewing, organizing, mentoring, etc. -->
