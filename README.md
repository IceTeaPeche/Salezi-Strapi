# Salezi-Strapi



## Description

Ce projet utilise Strapi, Grafana et GraphQL pour créer une application [décrivez brièvement l'objectif de votre application].



## Prérequis

Assurez-vous d'avoir les éléments suivants installés avant de commencer :

- Node.js
- npm (Node Package Manager)
- Strapi
- Grafana
- Installation



## installation Strapi

```sh
npm install
```

Lancez Strapi : npm run develop 

Accédez à l'interface d'administration de Strapi à l'adresse http://localhost:1337/admin



## installation Grafana

Installez Grafana en suivant les instructions de la documentation officielle : https://grafana.com/docs/grafana/latest/setup-grafana/installation/

Démarrez Grafana et accédez à l'interface à l'adresse http://localhost:3000



## installion GraphQL

installez GraphQL, entré cette commande dans le terminal : npm install @strapi/plugin-graphql    



## Configuration

Pour accéder au panel, le mail et le mot de passe admin sont : ledoubleethan@gmail.com     /      Admin123

Pour les utilsateurs déjà créer, pour le fnace manager c'est son mail + manager123

pour les seller, c'est leur mail + Seller123

Dans Strapi, vous pouvez cr&er des roles pour limiter des accès ou en accorder. Vous pouvez aussi créer votre base de donnée



Dans grafana, installer SQlite, puis allez dans le projet pour copier le chemin d'acces de la base de donnée et allez le coller dans le SQlite et sauvegarder.


Créer un dashbord puis ajouter votre base de donnée. Apres ça vous pouvez faire des requêtes SQL pour avoir un graph de vos données séléctionné


## Base de donnée fournie

Pour utiliser la base de donnée fourni, supprimer celle qu'il y a dans le dossier .tmp et mettez celui là à la place.


## documentation technique

pour en savoir plus sur les routes de l'API, une fois le  serveur lancer copier coller ce lien : localhost:1337/documentation/v1.0.0

