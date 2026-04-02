---
title: "Contact"
layout: "page"
summary: "Contact"
searchHidden: true
---
### Vous avez une question, une remarque ?
---
*Utilisez le formulaire ci-dessous pour nous transmettre votre demande, nous vous répondrons dans les plus brefs délais.*
<form action="https://formspree.io/f/mykdalqj" method="POST" style="display: grid; gap: 20px; max-width: 600px; margin: 30px 0;">
  
  <input type="hidden" name="subject" value="Particulier">

  <div style="display: flex; flex-direction: column; gap: 8px;">
    <label style="font-weight: bold; font-size: 0.9rem;">Votre adresse email :</label>
    <input type="email" name="email" placeholder="exemple@mail.com" required 
      style="width: 100%; padding: 12px; border-radius: 8px; border: 1px solid var(--border); background: var(--code-bg); color: var(--content); outline: none;">
  </div>

  <div style="display: flex; flex-direction: column; gap: 8px;">
    <label style="font-weight: bold; font-size: 0.9rem;">Votre message :</label>
    <textarea name="message" placeholder="Décrivez votre projet d'ACV ici..." required 
      style="width: 100%; min-height: 150px; padding: 12px; border-radius: 8px; border: 1px solid var(--border); background: var(--code-bg); color: var(--content); outline: none; font-family: inherit;"></textarea>
  </div>

  <button type="submit" 
    style="background: var(--primary); color: var(--theme); padding: 12px 24px; border: none; border-radius: 8px; cursor: pointer; font-weight: bold; width: fit-content; transition: opacity 0.2s;">
    Envoyer le message
  </button>

</form>

---

*Vos données sont utilisées uniquement pour vous répondre et ne sont jamais partagées.*