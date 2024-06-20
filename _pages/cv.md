---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

+ Sept 2022 – June 2026 (Expected), **PhD in Information Resources Management**, Nanjing University
+ Sept 2019 – June 2022, **MSc in Information Science**, Nanjing University
  + Thesis Title: "The Knowledge Structure and Intellectual Diversity of iSchools"
+ Sept 2015 – June 2019, **BSc in Information Management & Information System**, Nanjing University
  + Thesis Title: "A Comparative Study of Library and Information Science Curricula Between China and the USA"

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Conference Presentations

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
## Teaching & Mentoring Experience

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
