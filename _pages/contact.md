---
title: "Formulaire de contact"
sitemap: true
permalink: /contact/
layout: single
---
<br>
<div style="background-color: #fff3cd; border-left: 6px solid #856404; padding: 1em 1.2em; margin: 1.5em 0; color: #856404;">
  <strong>⚠️ Avis important :</strong><br>
Ce formulaire de contact est destiné aux questions générales et aux messages concernant le site ou les collaborations professionnelles.
Il n’est pas vérifié en continu et ne permet pas de demander une consultation médicale.
<br><br>
Pour toute question concernant la santé de votre enfant, veuillez consulter un·e professionnel·le de la santé qualifié·e ou suivre les <a href="https://www.chusj.org/fr/soins-services/N/CIRENE/PublicCible/Medecins-et-professionnels/Referencement" target="_blank">démarches officielles du CHU Sainte-Justine</a>  
</div>


<form
  action="https://www.formbackend.com/f/8a91098937d89f7f"
  method="POST"
>
  <label for="name">Nom:</label><br />
  <input type="text" id="name" name="name" required><br /><br />

  <label for="email">Adresse courriel:</label><br />
  <input type="email" id="email" name="email" required><br /><br />

  <label for="info">Commentaires:</label><br />
  <textarea id="info" name="info" rows="5" required></textarea><br /><br />

  <!-- reCAPTCHA v3 hidden token field -->
  <input type="hidden" id="g-recaptcha-response" name="g-recaptcha-response">

  <button type="submit">Envoyer</button>
</form>

<script src="https://www.google.com/recaptcha/api.js?render=6LeNYZcrAAAAALdcd351JiVg7vwZC0KFi35fweAA"></script>
<script>
  window.addEventListener('load', function () {
    grecaptcha.ready(function () {
      grecaptcha.execute('6LeNYZcrAAAAALdcd351JiVg7vwZC0KFi35fweAA', { action: 'contact' }).then(function (token) {
        document.getElementById('g-recaptcha-response').value = token;
      });
    });
  });
</script>
