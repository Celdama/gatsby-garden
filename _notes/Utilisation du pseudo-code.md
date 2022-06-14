---
title: Utilisation du pseudo-code
tags: ['permanent-notes', 'programming', 'problem-solving']
---

Il s'agit d'écrire la logique de notre solution, à un défi de code spécifique, en utilisant un anglais/français simple.

> *"Pseudocode is an informal high-level description of the operating principle of a computer program or other algorithm. It uses the structural conventions of a programming language, but is intended for human reading rather than machine reading" Wikipedia*

Il faut bien comprendre que même si les langages de programmation peuvent semblaient compliqués, la grande majorité des composants de ces langages sont complètement interchangeables d'un langage à l'autre.

Que ce soit un [[langage fonctionnelle]] ou un [[langage orienté-objet]], il devra toujours utiliser des déclarations conditionnelles, des fonctions, des variables, des boucles et toutes sortes d'autres structures logiques communes. Seule la syntaxe réelle pour les mettre en oeuvre est différente.

Le pseudo-code est donc utile pour apprendre, parce qu'il se concentre sur les concepts fondamentaux des langages de programmation sans sans qu'on ait à se soucier de savoir si on utilise les 'bons' mots/syntaxes propres à chaque langage.

Par exemple, je souhaite expliquer le fonctionnement d'un programme de distributeur automatique à un public générale en pseudo-code, afin qu'on puisse le comprendre. Peu importe qu'on soit en Python, Ruby, JavaScript..

```
WHEN the user inputs money: 
	IF the bill is too crumpled to read, 
	  provide an error message, 
	  and return the bill. 
	ELSE, 
	  Add it to the balance 
WHEN the user selects an item: 
	IF they havent put in enough money,
	  ask for more. 
	IF the item is out of stock,
	  ask them to make a new selection. 
	ELSE,
	  determine change, 
	  dispense change, 
	  zero out the balance, 
	  and dispense the item. 
WHEN the user hits the "cancel" button: 
	IF the user has input money without making a purchase, 
	  return the money, and zero out the balance
```

Cela rend plutôt logique, les différentes étapes nécessaires pour notre programme.