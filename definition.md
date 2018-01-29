# Définitions des concepts clés



## La différence entre un site statique et un site dynamique

Un site _statique_ est avec des pages identiques quelque soit l'utilisateur,
ex : recette sur marmiton
Un site _dynamique_, tout le contraire du site statique, est un site dont l'interface sera différente selon l'interaction avec l'utilisateur
ex : facebook, chaque utilisateur aura des messages différents, un mur différent etc..

## Le MVC

Le _MVC_ ou Model View Controller, est utilisé pour décrire presque tous les process de développement utilisant les langages Python, Javascript, Ruby, PHP.
Il y a trois éléments:
1. model: structure les données dans un form et les prépare en fonction des instructions du controller.
2. view: affiche les données dans un format accessible pour les utilisateurs, basés sur leurs instructions.
3. controller: envoie des ordres au model pour mettre à jour les données et envoie des ordres au view pour mettre à jour l'interface.
![schéma explicatif](https://cdn-images-1.medium.com/max/1000/1*4SxbmCrI5YVp1Uyj1Jstsg.png)


## Les routes

Les _routes_ interviennent au moment où on souhaite utiliser la fonctionnalité des articles, c'est le chemin pour y arriver.
On peut prendre l'image d'être sur la route et de prendre telle ou telle sortie pour telle ou telle ville.

## Les Bases de Données

Une _base de données_ est un grand tiroir dans lequel on peut trier, classer et ordonner les données.
Il n'y a pas de limite de taille.

## GET / POST

  GET           |    POST
------------    | -------------
Requête : SQL   | Requête : SQL
Méthode : HTTP  | Méthode : HTTP
Opération :Read | Opération : Create


## Le concept de migration

La _migration_ permet facilement d'altérer une base de données SQL. Chaque migration peut être vue comme une nouvelle version de la base de données. Cela fait penser à un commit sur ghitub.


## Les relations entre les models des BDD

##Les fonctions du CRUD

CRUD : Create, Read, Update, Delete
Ce sont les 4 opérations de base pour le stockage dans une base de données.
