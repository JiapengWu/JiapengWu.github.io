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
* B.A. in Computer Science, McGill University, 2019
* M.S. in Computer Science, McGill University, 2021

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Summer 2019: Research Intern
  * Nuance Communication, Montreal
  * Experiment with Multilingual BERT, a pretrained transformer model on multilingual datasets
  * Implemented transfer learning techniques including gradual unfreezing and layerwise discriminative learning rate training, integrated with tensorflow.bert repository
  *Further pretrained Multilingual using language-specific datasets, obtained about 3% accuracy gain averaged on multiple non-English intent classification tasks
  
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
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
