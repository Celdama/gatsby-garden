---
title: Exposer clairement la structure de la page
tags: ['permanent-notes', 'programming', 'clean code']
---

En HTML travailler avec des containers c'est bien, mais travailler avec des containes qui ont un `id` représentatif c'est encore mieux.

```html
<div id="main-container">
----<div id="header">
-------<div id="logo">...</div>
-------<div id="main-menu">...</div>
----</div>
----<div id="content">
-------<div id="left-column">...</div>
-------<div id="center-column">...</div>
-------<div id="right-column">...</div>
----</div>
----<div id="footer">
-------<div id="footer-menu">...</div>
-------<div id="disclaimer">...</div>
----</div>
</div>
```

La structure est ici évidente, c'est grâce à l'utilisation des `id` représentatif. C'est maintenant beaucoup plus facile d'ajouter du code, ou de supprimer des parties de ton site.

### Référence:
[[10 tips de clean code]]