# Reinforcement-Learning_TP-s-Correction

## Contexte :
Ce dépôt contient mes corrections des Travaux Pratiques (TPs) réalisés dans le cadre du cours de Machine Learning 2\ Reinforcement Learning. Chaque dossier correspond à un TP spécifique et contient les fichiers nécessaires pour comprendre et exécuter les solutions proposées.

## Objectif des TPs:

### devoir:
L'exercice consiste une première approche vers l’apprentissage par renforcement en utilisant une méthode classique de recherche de chemin en programmant un agent pour naviguer dans une grille pour atteindre un trésor 🏆 tout en évitant les pièges ☠️. L'agent doit explorer son environnement et trouver un chemin optimal en minimisant les déplacements inutiles.

### TP1:
L'objectif de ce TP est de se familiariser avec les outils essentiels du Reinforcement Learning (RL), notamment OpenAI Gym.
Explorer comment interagir avec un environnement RL (CartPole-v1) et exécuter des actions aléatoires ou manuelles avant d’implémenter un algorithme d’apprentissage.

### TP2:
L’objectif de ce TP est d’apprendre à un agent à traverser un lac gelé (FrozenLake) sans tomber dans un trou, en utilisant l'algorithme d’apprentissage par renforcement Q-Learning.

L’agent doit apprendre à se déplacer intelligemment sur une grille où :
- Certaines cases sont sécurisées (S, F, G)
- D’autres cases sont des pièges (H : trous où l’agent tombe)

Il doit maximiser sa récompense en atteignant l’objectif (G) sans tomber dans un trou.

### TP3: Optimisation des Feux de Circulation avec l'Apprentissage par Renforcement
L’objectif de ce TP est d’optimiser la gestion des feux de circulation à une intersection en utilisant les deux algorithmes d’apprentissage par renforcement Q-Learning et SARSA.
L’agent devra apprendre à prendre les bonnes décisions pour changer ou garder le feu en fonction du trafic, afin de :
- Minimiser les embouteillages
- Maximiser le nombre de voitures qui traversent l’intersection
Pour cela, il explorera différentes stratégies et mettra à jour une Q-Table en fonction des récompenses reçues, qui correspondent au nombre de voitures ayant réussi à passer, à la fin déterminer la meilleure stratégie pour fluidifier le trafic.

