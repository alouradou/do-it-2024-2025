---
layout: layout/mon.njk

title: "Utiliser python dans une entreprise qui ne l'utilise pas ?"
authors:
  - Gordon Zola

date: 1971-03-01
temps: 3
tags:

résumé: "Ce MON permettra de répondre à deux questionnements principaux, nés d'observation réalisées dans différentes structures lors de différents stages :
1. Quels liens exist-t-il entre Pyhton, Excel et VBA ?
2. Comment peut-on utiliser Python sur des espaces de stockages Microsoft Sharepoint ?"
---

{% prerequis %}

Liste des prérequis du POK ET/OU MON

{% endprerequis %}
{% lien %}

Les lien utiles pour la compréhension de celui-ci.

{% endlien %}

Quelques phrases permettant de connaître, sans jargon ni blabla, le contenu de ce MON. On oubliera pas de donner :

- le niveau et les prérequis nécessaires en utilisant la balise [`prerequis`](/cs/contribuer-au-site/#prerequis)
- les autres POK & MON en rapport en utilisant la balise [`lien`](/cs/contribuer-au-site/#lien)

## Contenu

## Un peu de contexte
#### Questionnement 1 : Quels liens exist-t-il entre Pyhton, Excel et VBA ?
Python est un langage pratique et enseigné dès les classes de 2nd dans des cursus généraux. Il peut donc être utilisé par un grand nombre de personnes. Toutefois, lorsque le developpement web, logiciel etc... ne fait pas parti du socle de compétence ou de préocupation d'un personne, il est difficile de mettre en place des interfaces graphiques rapidement et simplement. Excel est un logiciel largement utilisé, permettant de répondre à cette dernièere problématique. De plus, le langage VBA (Visual basic for Application), permet de mettre en place certains programmes. Toutefois, ce dernier n'est pas forcément adapté à tous les usages. On peut citer par exemple l'absences d'objets tels que les listes et tableaux de python. Du moins, leur utilisation en VBA est bien moins facile et intuitive qu'en Python.

Je souhaite donc étudier les différentes possibilités qui pourraient permettre de lier python à Excel :
- Python vers Excel : 
  - Lecture et stocake de données : bibliothèque pandas.
  - Lancer une macro ?
- Excel vers Pyhton : 
  - Lancer un script python ?
  - Problématiques de droits d'accès ?