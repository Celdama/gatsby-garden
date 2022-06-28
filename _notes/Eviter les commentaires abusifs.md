---
title: Eviter les commentaires abusifs
tags: ['permanent-notes', 'programming', 'clean code']
---

Les commentaires doivent être utilisés avec parcimonie. Quand on commente, l'objectif est d'expliquer en terme de variable et de résultats. Les commentaires ne sont pas fait pour :

-   écrire des instructions pour soi même : `/* *will finish this later... */*`
-   critiquer le travail des autres: `/* *john coded this. Ask him */*`
-   rédiger de vagues déclaration: `/* *This is another math function */*`
-   commenter à la place de supprimer. Si on est pas sûr de vouloir supprimer quelque chose, on peut le mettre en commentaire. Ce qui n'est pas bien, c'est de le laisser comme ca indefiniment. Cela peut être très confus.

Exemple de bons commentaires :

-   Création de spécification `/* *Coded by John,, Novembre 23th 2021 */*`
-   Détailler les étapes d'une fonctionnalité d'une méthode ou une procédure. `/* *this function validates the login form with the aid of the e-mail check function */*`
-   des notifications rapides ou des étiquettes indiquant l'endroit où une modification récente a été apportée. `/* *added email validation procedure* **/*`

### Réference:
[[10 tips de clean code]]