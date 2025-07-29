---
layout: archive
title: "Défense d'intérêts"
permalink: /engagement-public/
author_profile: true
---
Cette section rassemble des lettres d'opinions que j'ai publié à travers divers médias québécois. Les sources originales sont citées.

  <ul class="lettres-list">
    {% assign lettres = site.engagement-public | sort: "date" | reverse %}
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

