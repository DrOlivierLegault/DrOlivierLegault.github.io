---
layout: archive
title: "Lettres ouvertes"
permalink: /lettres_ouvertes/
author_profile: true
---

<section class="lettres-ouvertes">
  <div class="header">
    <h1>Lettres d’intérêt</h1>
    <p class="intro">
      Cette section rassemble des lettres ouvertes d’intérêt public, sélectionnées et repostées depuis divers médias québécois ou canadiens. Les sources originales sont toujours citées.
    </p>
  </div>

  <ul class="lettres-list">
    {% for post in site.lettres_ouvertes reversed %}
      <li class="lettre-item">
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
        <div class="lettre-meta">
          <span class="date">{{ post.date | date: "%d %B %Y" }}</span>
          {% if post.source %}
            <span class="source">Publié dans {{ post.source }}</span>
          {% endif %}
        </div>
      </li>
    {% endfor %}
  </ul>
</section>