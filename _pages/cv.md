---
layout: archive
title: "My Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.pdfobject-container { width: 800; height: 1000px; border: 1px solid #ccc; }
</style>
<div id="my-pdf"></div>
<script src="https://unpkg.com/pdfobject"></script>
<script>PDFObject.embed("../images/RockyResume.pdf", "#my-pdf");</script>
<br>

<!-- Education
======
* Kang Chiao International School High School Deploma
* Purdue University Robotics Engineering Technology, Minor in CS
* Purdue University Certificate in certificate in Entrepreneurship and Innovation

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

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
 -->

