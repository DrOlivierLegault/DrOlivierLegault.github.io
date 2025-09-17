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

<style>
.btn {
  display: inline-block;
  padding: 0.75em 1.5em;
  border-radius: 8px;
  font-weight: 600;
  text-decoration: none;
  transition: background-color 0.3s, color 0.3s, transform 0.2s, box-shadow 0.2s;
  font-family: inherit;
  text-align: center;
}

.btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.btn-primary { background-color: #005f73; color: #fff; }
.btn-primary:hover { background-color: #003d4a; color: #fff; }

.btn-secondary { background-color: #94bfa3; color: #00332b; }
.btn-secondary:hover { background-color: #78967d; color: #fff; }

.btn-outline {
  background-color: transparent;
  color: #005f73 !important;   /* forcer la couleur */
  border: 1px solid #005f73 !important;
}
.btn-outline:hover {
  background-color: #005f73;
  color: #fff !important;
}

.btn-full { display: block; width: 100%; max-width: 320px; margin: 1em auto; }
@media (max-width: 500px) { .btn-full { max-width: 90%; } }

.highlight-box {
  background-color: #f0ede9;
  border-left: 5px solid #005f73;
  padding: 1em 1.2em;
  margin: 1.5em 0;
  font-style: italic;
  color: #333;
  border-radius: 6px;
  max-width: 720px;
}
</style>

## Bienvenue sur mon site

Bonjour ! Je me présente, je suis **Olivier Legault**, pédiatre du développement au CHU Sainte-Justine et au Centre de réadaptation Marie Enfant.  

### *Comprendre et soutenir la diversité des trajectoires de développement*

<div class="highlight-box">
<strong>Je crois profondément à l’importance d’accompagner et d’outiller les familles dont les enfants et adolescent·e·s présentent des trajectoires de développement particulières.</strong>  
Mon approche se veut à la fois humaine, collaborative et attentive à la neurodiversité, ainsi qu’aux réalités vécues par chaque famille.
</div>

---

## Ressources clés et actualités

<div style="text-align: center; margin-bottom: 1.5em;">
<a href="ressources-cliniques" class="btn btn-primary">ℹ️ Chroniques</a>
<a href="recherche" class="btn btn-secondary">📂 Projets de recherche</a>
<a href="teaching" class="btn btn-outline">🎤 Conférences</a>
</div>

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

À travers ce site, j’ai pour objectif de partager des informations fiables et des ressources utiles sur le développement de l’enfant et de l’adolescent. Dans mon travail auprès des externes et résidents en médecine, je constate que ce domaine demeure parfois méconnu ou peu accessible.  

J’espère donc que ce contenu servira non seulement aux médecins, mais aussi aux autres professionnel·le·s de la santé et de l’éducation, aux étudiant·e·s, ainsi qu’aux familles. J’aimerais également contribuer à mieux faire connaître la spécialité de la **pédiatrie du développement**.

Pour consulter la liste de mes chroniques sur le développement de l’enfant, cliquez ci-dessous :
<a href="year-archive" class="btn btn-primary btn-full">
  Voir la liste de mes chroniques
</a>

Différentes sections de ce site présentent mes activités : pratique professionnelle, ressources cliniques, projets de recherche, formations et congrès, défense des droits des enfants, publications et CV.

---

## Pratique professionnelle

Je travaille auprès d’enfants et d’adolescent·e·s présentant des différences dans leur développement moteur, langagier, social ou cognitif, ou rencontrant des difficultés ayant un impact sur leur quotidien.  

Dans une approche interdisciplinaire, et lorsque cela est approprié et souhaité, nous posons des diagnostics cliniques afin de mieux comprendre leur profil, par exemple : autisme, déficience intellectuelle, TDAH, paralysie cérébrale ou troubles d’apprentissage.

Pour en savoir plus sur ma pratique professionnelle, cliquez ci-dessous :
<a href="pratique-professionnelle" class="btn btn-secondary btn-full">
  En savoir plus sur ma pratique
</a>

---

## Engagement et défense des droits

Je m’engage activement pour la **défense des droits et intérêts des enfants et adolescent·e·s à besoins particuliers**. J’ai à cœur de continuer à porter leur voix, et je demeure ouvert aux opportunités de collaboration ou de prise de parole.

À ce sujet, j’ai publié [plusieurs lettres ouvertes](./lettres_ouvertes/) dans des médias tels que *La Presse* et *Le Journal de Montréal*.

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

Je transmets mes connaissances à travers des **présentations scientifiques, formations cliniques et conférences publiques**, ainsi que par ce site. Je reste disponible pour des **collaborations, interventions médiatiques ou rôles d’expert** sur des sujets liés au développement de l’enfant.

Pour connaître mes prochaines conférences et interventions, cliquez ci-dessous :
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

Vous souhaitez collaborer, organiser une conférence, ou en savoir plus ?  

<a href="contact" class="btn btn-primary btn-full">
  Contactez-moi
</a>