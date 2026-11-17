
# Projet final : Jeu de mémoire

**Membres de l'équipe :**
- Jose Luis Branco
- Yassine Ani

---

## 1. Objectif du projet

L'objectif de ce projet est de développer un jeu de mémoire interactif à l'aide d'un Arduino Nano ESP32.

Le jeu consiste à mémoriser et à reproduire des séquences de directions affichées sur une matrice LED 8×8. Chaque direction correspond à une couleur et à un bouton physique situé dans l'un des quatre coins du dispositif : rouge, vert, bleu et blanc.

Le joueur doit observer la séquence affichée, la mémoriser, puis appuyer sur les quatre boutons correspondants dans le bon ordre.

Le jeu comprend également trois niveaux de difficulté, des indications lumineuses et des confirmations sonores.

---

## 2. Matériel et composants

| Composant | Quantité | Statut |
|:---|:---:|:---:|
| Arduino Nano ESP32 | 1 | Prêt |
| Breadboard | 1 | Prêt |
| Fils de connexion | Plusieurs | Prêt |
| Boutons-poussoirs (rouge, vert, bleu, blanc) | 4 | À obtenir |
| Bouton ON/OFF (2 broches) | 1 | À obtenir |
| LED blanche | 1 | Prêt |
| Module LED RGB | 1 | À obtenir |
| Buzzer actif | 1 | À obtenir |
| Matrice LED 8×8 | 1 | À obtenir |
| Potentiomètre | 1 | À obtenir |

---

## 3. Livrables du projet

### Livrable 1 – Configuration initiale

- Créer la structure de base du code.
- Préparer l'environnement de développement Arduino et les instructions d'installation.
- Faire approuver la proposition de projet.

### Livrable 2 – À déterminer

Les objectifs et les tâches de ce livrable seront définis au fur et à mesure de l'avancement du projet.

### Livrable 3 – À déterminer

Les objectifs et les tâches de ce livrable seront définis en fonction de l'évolution du projet et des exigences finales.

---

## Design

![Design du projet](Deuxieme_Designe.png)

---

## 4. Idées et fonctionnalités

### Fonctionnement du jeu

- La matrice LED 8×8 affiche des flèches indiquant les directions à mémoriser.
- Chaque direction correspond à l'un des quatre boutons colorés situés dans les coins du dispositif.
- Les couleurs utilisées sont rouge, vert, bleu et blanc.
- Le joueur doit mémoriser la séquence affichée et reproduire celle-ci en appuyant sur les boutons dans le bon ordre.
- Une erreur entraîne un signal sonore indiquant que la séquence est incorrecte.

### Système de difficulté

Le jeu proposera trois niveaux de difficulté sélectionnables à l'aide d'un potentiomètre.

| Niveau | Couleur de la LED RGB |
|:---|:---:|
| Facile | Vert |
| Moyen | Jaune |
| Difficile | Rouge |

La difficulté pourra varier selon deux paramètres :

#### Mode vitesse
- Réduire le temps d'affichage entre chaque direction.
- Donner moins de temps au joueur pour mémoriser la séquence.

#### Mode séquence
- Augmenter progressivement le nombre de directions à mémoriser.
- Rendre les séquences de plus en plus longues selon le niveau choisi.

### Indications lumineuses et sonores

**LED RGB :**
- Vert : niveau facile sélectionné.
- Jaune : niveau moyen sélectionné.
- Rouge : niveau difficile sélectionné.

**Buzzer actif :**
- Confirmer la sélection du niveau de difficulté.
- Confirmer une séquence correctement reproduite.
- Signaler une erreur lorsque le joueur appuie sur le mauvais bouton.

### Bouton ON/OFF

Un petit bouton à deux broches sera installé sur le côté du dispositif.

Il permettra d'allumer et d'éteindre le système.

---

## 5. Objectif final

Créer un jeu de mémoire physique, amusant et interactif qui combine programmation, électronique et design.

Le joueur devra observer, mémoriser et reproduire des séquences de directions et de couleurs tout en progressant à travers trois niveaux de difficulté.

---

## 6. Développement

Cette section sera utilisée pour documenter le code, les modifications et les différentes étapes du développement du projet.

### Structure du projet

```text
On n'a pas encore décidé
```
