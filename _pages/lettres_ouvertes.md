---
layout: single
title: "Lettres ouvertes"
permalink: /lettres_ouvertes/
author_profile: true
---

<section class="lettres-ouvertes">
  <p class="intro">
    Cette section rassemble des lettres ouvertes d’intérêt public, sélectionnées et repostées depuis divers médias québécois ou canadiens. Les sources originales sont toujours citées.
  </p>

  <ul class="lettres-list">
    {% assign lettres = site.lettres_ouvertes | sort: "date" | reverse %}
    {% for post in lettres %}
      <li class="lettre-item">
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <div class="lettre-meta">
          <span class="date">{{ post.date | date: "%-d %B %Y" }}</span>
          {% if post.source %}
            <span class="source"> – Publié dans {{ post.source }}</span>
          {% endif %}
        </div>
      </li>
    {% endfor %}
  </ul>
</section>