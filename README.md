# Apprentissage de représentations d’images : approches auto-supervisées

Travaille dans le cadre d'un TP noté à partir d'un notebook source:
https://github.com/rll/deepul/blob/master/demos/lecture7_selfsupervised_demos.ipynb

Consignes :
1. Commencer par vous familiariser avec le code source proposé puis exécuter
chaque module de manière à observer les résultats offerts pour chaque démo
2. Différentes tâches prétextes sont implémentées dans les démos 1, 2, 3. Pour
chaque tâche une représentation est apprise puis évaluée sur une tâche de
classification sur CIFAR10.
3. Proposer et coder un script permettant de comparer les performances de
classification de l’ensemble des modèles sur un même tableau / ou graphique.
4. Effectuer la comparaison sur un autre jeu de données de votre choix (du
même ordre de grandeur que CIFAR10).
5. En vous appuyant sur la librairie existante, implémenter la tâche prétexte
consistant à apprendre au modèle à prédire la position relative d’un patch de
l’image relativement à un patch requête (diapo 18 du cours et figure page 2),
voir également : https://arxiv.org/pdf/1505.05192.pdf
6. Évaluer les performances relativement aux modèles entraînés via les autres
tâches prétextes sur CIFAR10 et un autre jeu de données de votre choix

### RODRIGUES Mathieu
