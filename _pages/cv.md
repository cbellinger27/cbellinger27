---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Machine Learning, University of Ottawa, 2016
* Master of Computer Science, Carleton University, 2010
* Bachelor of Computer Science, Minor in Mathematics, Carleton University, 2007

Work experience
======
* Staff Scientist: Oct. 2018 - Aug 2025
  * National Research Council of Canada
  * Machine Learning and Reinforcement Learning Research

* Donald Hill Fellow: July 2018 - Oct. 2018
  * Dalhousie University, Computer Science
  * Machine Learning research

* Postdoctoral Fellow: May 2016 - July 2018: 
  * University of Alberta, AMII
  * Machine Learning research
  


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
  
