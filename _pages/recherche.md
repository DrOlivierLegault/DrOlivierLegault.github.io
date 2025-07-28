---
title: "Recherche"
permalink: /recherche/
layout: single
classes: wide
author_profile: true
---

{% include toc %}

{% include base_path %}

## Projets en cours et à venir

{% include projets.html %}


## Collaborateurs et collaboratrices<br>des projets

{% include lab_members.html %}

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

