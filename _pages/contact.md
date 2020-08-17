---
title: "Contact"
layout: page-sidebar
permalink: "/contact.html"
---

<form action="https://formspree.io/xknqezbp" method="POST">    
<p class="mb-4">Veuillez envoyer votre message à {{site.name}}. Nous vous répondrons aussi vite que possible !</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Nom*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-success" type="submit" value="Envoyer">
</form>