---
layout: archive
title: "Profile"
permalink: /profile/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


## Work and research journey
* Mar 2025 - _present_: **Research associate** @ Imperial College
  * Named co-investigator for EPSRC-funded grant ["Concurrent Learning and Control of Large-Scale Phenomena"](https://gtr.ukri.org/projects?ref=EP%2FZ533816%2F1)
  * Collaborating with prof. Eric Kerrigan and prof. Guillermo Rein
  * Methodological research on physics-informed machine learning and dual control

* Nov 2022 - Feb 2025: **Postdoctoral research fellow** @ Politecnico di Milano
  * Participation in projects on airborne wind energy and drone swarms
  * Methodological research on mathematical optimisation algorithms

* Nov 2016 - Oct 2019: **Research associate** @ University of the Philippines Diliman
  * Participation as a lead engineer in Philippine Microsatellite Program
  * Embedded software development for communications payload and experimental aspect sensor

## Educational profile
* **Ph.D.** (_cum laude_), Ingegneria dell'Informazione, Politecnico di Milano, Italy, 2023
* **M.Sc.**, Elektrotechnik, Informationstechnik, Technische Informatik, RWTH Aachen, Germany, 2016
* **B.Sc.**, Computer Engineering, University of the Philippines Diliman, Philippines, 2012

<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

## Recent Publications

  <ul>{% assign recent_publications = site.publications | sort: 'date' | reverse %}
  {% for post in recent_publications limit:3 %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  _More exhaustive list found [here](/publications)._

  
## Recent Talks
  <ul>{% assign recent_talks = site.talks | sort: 'date' | reverse %}
  {% for post in recent_talks limit:3 %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

  _More exhaustive list found [here](/talks)._
  
<!-- ## Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
## Service and leadership
* Currently signed in to 43 different slack teams
