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
* **Ph.D. in Computer Science**, University of Science and Technology of China (USTC), 2026.09–Present
* **B.S. in Computer Science and Technology**, Dalian Maritime University (211), 2022.09–2026.06 (GPA: 3.91/5.0)

Work experience
======
* **Algorithm Intern**, Neusoft Corporation (Commercial Software Division) (2025.10–Present)
  - Participated in the R&D of an Agent Loop-based automated mobile phone recovery system.
  - Designed and implemented an Adaptive RAG dynamic retrieval module.
  - Built a high-precision screen element recognition pipeline using YOLOv8 + EasyOCR.

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
    {% if post.published == false %}{% continue %}{% endif %}
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
