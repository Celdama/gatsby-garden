---
title: Résumé les importations
tags: ['permanent-notes', 'programming', 'clean code']
---

Meme si il est bien d'avoir des fichiers distincts pour importer d'autre langages, il ne faut pas en abuser. S'il y a trop de feuilles de style, elles peuvent probablement être résumées en une ou deux.

Cela permet de de rendre les choses plus propres, et aussi de gagner du temps de chargement. Chaque fichiers importé est une requête HTTP qui pèse sur les performances de l'application.

C'est donc une considèration pour la propreté mais aussi pour l'efficacite.

### Réference:
[[10 tips de clean code]]