# Algorithme D'Ariane
- **Auteurs :** *Jean-Baptiste Sanchez*, *Marie Pellier*
- **Licence :** *MIT Licence*

Ce projet est le résultat d'un travail en binôme réalisé en 2019 par Jean-Baptiste Sanchez et Marie Pellier.
Le sujet a été donné en tant que Projet Tutoré de semestre 2 dans la matière APL (Algorithmie Programmation et Langage) dans le cadre de la formation du DUT Informatique.

## Table des matières
- Lancement de l'application
- Détails du projet
  - En quoi consiste l'algorithme ?
  - Fonctionnalités demandées
- Bibliothèque Graphique
  - Présentation
  - Installation
  - Utilisation

## Lancement de l'application
Téléchargez le dépôt puis dans un terminal depuis le dépôt Git allez dans `./src/` pour accéder aux fichiers sources de l'application. Vous y retrouverez un fichier `Makefile`. Il a été écrit pour permettre de compiler, de lancer l'application ainsi que de nettoyer les fichiers de l'application.

>**Commandes à inscrire au terminal pour utiliser le projet:**
- `make` permet de compiler les fichiers du jeu
- `make run` permet de lancer le jeu compilé
- `make clean` permet de supprimer tous les fichiers intermédiaires de l'application

## Détails du projet
L’algorithme d’Ariane est une application Java présentant un système de visualisation du comportement d’une intelligence artificielle à travers un labyrinthe. Il met en scène Thésée le personnage mythique grec essayant de trouver le fabuleux Minotaure.

### En quoi consiste l'Algorithme ?
C'est un algorithme permettant de sortir de manière déterministe d'un labyrinthe. En cas d'impossibilité l'algorithme est capable de savoir si il est bloqué.

### Fonctionnalités demandées
- Makefile
- Interface java permettant:
  - De créer une grille aléatoirement disposée
  - De créer une grille manuellement
  - De charger/sauvegarder une grille existante
  - De choisir la visualisation de l'Algorithme
  - De choisir le type d'Algorithme (Algorithme déterministe, Algorithme hasardeux)
