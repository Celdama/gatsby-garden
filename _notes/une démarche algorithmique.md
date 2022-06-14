---
title: Une démarche algorithmique
tags: ['permanent-notes', 'algorithme', 'programming']
---

Voici un exemple des différentes étapes pour la réalisation d'un algorithme qui demande à l'utilisateur 2 number et les ajoutes l'un à l'autre. 

#### 1er essai

```
# create an integer variable for x
# create an integer variable for y
# create an integer variable for sum
# ask the user "x: " and put answer in x
# ask the user "y: " and put answer in y
# put x + y in sum
# tell user "answer is " sum
``` 

Ensuite je convertis en code
```python
// create an integer variable for x
x = 0
// create an integer variable for y
y = 0
// create an integer variable for sum
sum = 0
// ask the user "x: " and put answer in x
x = input("x: ")
// ask the user "y: " and put answer in y
y = input("y: ")
// put x + y in sum
sum = x + y
// tell user "answer is " sum
print("answer is ")
print(sum)
```

Je teste ce code, et j'[[l'échec est merveilleux|échoue]], je rencontre des bugs, c'est normal.

Le problème dans mon algorithme est que j'ajoute 2 string ensemble. Je dois donc avoir une nouvelle étape dans mon algorithme: je souhaite convertir mes [[les inputs en algorithmie|inputs]] en integer.
- *oldVariable*: est au format non-integer
- *intVariable*: oldVariable to Integer

```
convert *oldVariable* en integer et la stocker dans *intVariable*
```

```python
// create an integer variable for x
x = 0
// create an integer variable for y
y = 0
// create an integer variable for sum
sum = 0
// ask the user "x: " and put answer in x
x = input("x: ")
// ask the user "y: " and put answer in y
y = input("y: ")
// convertir x en integer
// convertir y en integer
// put x + y in sum
sum = x + y
// tell user "answer is " sum
print("answer is ")
print(sum)
``` 

Voilà maintenant je peux chercher comment convertir une variable en integer, dans le langage de mon choix. C'est la beauté du [[Pseudo code]] et de l'algorithmie. Coder sans savoir coder, et ensuite remplacer les éléments du langage humain en code. 

Ici pour coder une nouvelle version de cet algorithme, il est préférable de mettre l'ancien code de coté et de repartir à zéro.