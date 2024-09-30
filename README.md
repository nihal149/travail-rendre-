Projet : Analyse de Scripts des Développeurs avec JDBC et MySQL

Ce projet est une application Java qui utilise JDBC pour interagir avec une base de données MySQL. L'application permet de suivre l'activité des développeurs, notamment en comptabilisant le nombre de scripts réalisés par jour et par développeur, et offre la possibilité d'exécuter des requêtes SQL personnalisées.

Fonctionnalités principales :
Requête du nombre maximum de scripts par jour : Cette fonctionnalité permet de déterminer le développeur ayant réalisé le nombre maximal de scripts pour chaque jour.

Nombre total de scripts par développeur : L'application permet de classer les développeurs en fonction du nombre total de scripts qu'ils ont réalisés.

Nombre total de scripts réalisés dans une semaine : Affiche la somme de tous les scripts produits durant une semaine.

Nombre total de scripts par développeur spécifique : Il est possible de spécifier un développeur et de voir combien de scripts il a produit au total.

Exécution de requêtes SQL personnalisées : L'utilisateur peut entrer une requête SQL libre, qui sera exécutée sur la base de données. Les résultats de la requête seront affichés, ainsi que les détails des colonnes retournées.

Description des classes :

Classe ExoJDBC :

Gère la connexion à la base de données MySQL et l'exécution des requêtes.
Fournit plusieurs méthodes pour récupérer des informations sur les développeurs et les scripts qu'ils ont réalisés.
Permet l'exécution de requêtes SQL définies par l'utilisateur.

Classe Developer :

Représente un développeur, avec des attributs comme le nom, le jour, et le nombre de scripts réalisés.

Classe Test :

Cette classe contient le point d'entrée du programme. Elle permet d'exécuter les différentes méthodes de la classe ExoJDBC pour tester les fonctionnalités et interagir avec l'utilisateur.
Pré-requis :

Un serveur MySQL avec une base de données et une table contenant les informations sur les développeurs et les scripts réalisés.
Une installation de Java pour exécuter le programme.
Exécution :

Le programme exécute diverses requêtes pour afficher les informations sur les scripts réalisés par les développeurs.
Il inclut également une fonctionnalité interactive permettant à l'utilisateur d'exécuter ses propres requêtes SQL sur la base de données.
