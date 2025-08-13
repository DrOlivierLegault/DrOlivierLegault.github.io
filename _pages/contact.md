---
title: "Formulaire de contact"
sitemap: true
permalink: /contact/
layout: single
---

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
