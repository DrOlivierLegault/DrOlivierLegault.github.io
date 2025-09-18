---
permalink: /
title: "Pédiatrie du développement : ressources cliniques, engagement et recherche"
og_image: og_image.jpg
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /accueil/
---

## Bienvenue sur mon site
### *Comprendre et soutenir la diversité des trajectoires de développement*

Bonjour ! Je me présente, je suis **Olivier Legault**, pédiatre du développement au CHU Sainte-Justine et au Centre de réadaptation Marie Enfant.  

<div class="highlight-box">
<strong>Je crois profondément à l’importance d’accompagner et d’outiller les familles dont les enfants et adolescent·e·s présentent des trajectoires de développement particulières.</strong>  
Mon approche se veut à la fois humaine, collaborative et attentive à la neurodiversité, ainsi qu’aux réalités vécues par chaque famille.
</div>

---

## Ressources clés

<div style="text-align: center; margin-bottom: 1.5em;">
<a href="ressources-cliniques" class="btn btn-primary">ℹ️ Chroniques</a>
<a href="recherche" class="btn btn-secondary">📂 Projets de recherche</a>
<a href="teaching" class="btn btn-outline">🎤 Conférences</a>
</div>

## Actualités

- ℹ️ Dernière chronique : *[{{ site.posts.first.title }}]({{ site.posts.first.url }})*  

{% assign next_talk = site.teaching | where_exp:"item","item.date >= site.time" | sort: "date" | first %}
{% if next_talk %}
- 🎤 Prochaine conférence : *[{{ next_talk.title }}]({{ next_talk.url }})*  
{% endif %}

{% assign latest_engagement = site.engagement-public | sort: "date" | reverse | first %}
{% if latest_engagement %}
- 📰 Dernière intervention publique : *[{{ latest_engagement.title }}]({{ latest_engagement.url }})*
{% endif %}

---

## Mon approche

À travers ce site, je souhaite partager des informations fiables et accessibles sur le développement de l’enfant et de l’adolescent.  

Ce contenu s’adresse autant aux médecins qu’aux autres professionnel·le·s de la santé et de l’éducation, aux étudiant·e·s et aux familles.  

Mon objectif est aussi de mieux faire connaître la spécialité de la **pédiatrie du développement**.

Pour consulter la liste de mes chroniques, cliquez ci-dessous :  
<a href="year-archive" class="btn btn-primary btn-full">
  Voir la liste de mes chroniques
</a>

### Explorer le site

Différentes sections de ce site présentent mes activités : pratique professionnelle, ressources cliniques, projets de recherche, formations et congrès, défense des droits des enfants, publications et CV.

---

## Pratique professionnelle

Je travaille auprès d’enfants et d’adolescent·e·s présentant des différences dans leur développement moteur, langagier, social ou cognitif, ou rencontrant des difficultés ayant un impact sur leur quotidien.  

### Approche interdisciplinaire

Dans une approche interdisciplinaire, et lorsque cela est approprié et souhaité, nous posons des diagnostics cliniques afin de mieux comprendre leur profil, par exemple :  
- autisme  
- déficience intellectuelle  
- TDAH  
- paralysie cérébrale  
- troubles d’apprentissage  
- etc.

Pour en savoir plus sur ma pratique professionnelle, cliquez ci-dessous :
<a href="pratique-professionnelle" class="btn btn-secondary btn-full">
  En savoir plus sur ma pratique
</a>

---

## Engagement et défense des droits

Je m’engage activement pour la **défense des droits et intérêts des enfants et adolescent·e·s à besoins particuliers**.  

J’ai à cœur de continuer à porter leur voix et je demeure ouvert aux opportunités de collaboration ou de prise de parole.

### Publication de lettres ouvertes

À ce sujet, j’ai publié [plusieurs lettres ouvertes](./engagement-public/) dans des médias tels que *La Presse* et *Le Journal de Montréal*.  

Pour consulter mes interventions publiques, cliquez ci-dessous :
<a href="engagement-public" class="btn btn-outline btn-full">
  Lire mes lettres ouvertes
</a>

---

## Recherche

Mes projets de recherche visent à mieux comprendre l’influence des vulnérabilités et des déterminants sociaux sur le développement des enfants et adolescent·e·s, en collaboration avec d’autres chercheur·e·s et équipes.  

Pour découvrir mes projets de recherche, cliquez ci-dessous :
<a href="recherche" class="btn btn-primary btn-full">
  Découvrir mes projets de recherche
</a>

---

## Transmission des connaissances

Je partage mon expertise par des **présentations scientifiques, formations cliniques et conférences publiques**, ainsi que sur ce site.  

Je suis aussi disponible pour des **collaborations, interventions médiatiques ou rôles d’expert** sur le développement de l’enfant.  

<a href="teaching" class="btn btn-secondary btn-full">
  Voir mes conférences à venir
</a>

---

## CV (en bref)

Voici un aperçu de mon parcours et de mes engagements professionnels.  

**Formation**  
- Doctorat en médecine (MD), Université de Montréal  
- Résidence en pédiatrie générale : années 1 à 3, Université de la Saskatchewan ; année 4, Université de Montréal  
- Fellowship (surspécialité) en pédiatrie du développement, Université de Montréal  
- Maîtrise en santé publique, École de santé publique de l’Université de Montréal  

**Rôles actuels**  
- Pédiatre du développement, clinicien-enseignant au CHU Sainte-Justine  
- Chercheur-investigateur au Centre de recherche du CHU Sainte-Justine  
- Professeur adjoint de clinique, Département de pédiatrie, Université de Montréal  
- Membre du GRIP (Groupe de recherche sur l’inadaptation psychosociale chez l’enfant)  

**Intérêts professionnels**  
- Développement de l’enfant et trajectoires de santé  
- Déterminants sociaux de la santé et leur influence sur le développement  
- Impact des environnements précoces (tabagisme, pauvreté, stress parental)  
- Défense des enfants vulnérables ou à besoins particuliers  

Pour consulter mon CV complet, cliquez ci-dessous :
<a href="cv" class="btn btn-outline btn-full">
  Consulter mon CV complet
</a>

---

## Me contacter

Vous souhaitez collaborer, organiser une conférence ou en savoir plus ?  

<a href="contact" class="btn btn-primary btn-full">
  Contactez-moi
</a>