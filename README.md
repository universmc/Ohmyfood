# OhMyFood - Projet 4

Ce projet consiste en la création d'un site web nommé OhMyFood, conçu en "desktop first". Il mettra en évidence des animations en CSS et l'utilisation de SASS (Syntactically Awesome Stylesheets). Ce fichier README fournit un aperçu du projet et de son architecture.

## Architecture du projet

Le projet est organisé de la manière suivante :

- Le fichier `index.html` à la racine du répertoire "Build" contient la page principale du site.
- Le répertoire "Assets" contient les composants, les images, et les fichiers de style.
- Dans le répertoire "Restaurants", vous trouverez les pages des différents restaurants du site.
- Le fichier `build/make-sass-index.csss` contient le fichier sass à compiler pour `assets/css/style.css`.

## Mise en route

Pour tester le projet localement, vous pouvez cloner ce dépôt GitHub et ouvrir le fichier `index.html` dans un navigateur web. Assurez-vous d'avoir Node.js installé pour compiler le SASS. Utilisez la commande `npm run compile-sass` pour générer le fichier CSS.

## Styles CSS

Le fichier `assets/css/style.css` contient les styles généraux du site. Il définit la mise en page, les polices, et les couleurs à l'aide de variables. De plus, il inclut des médias queries pour assurer la réactivité du site, suivant la méthode "mobile first".

## Contenu des pages

- `index.html` : Page d'accueil du site OhMyFood, contenant les sections "header," "hero banner," "fonctionnement," et "restaurant."
- `/restaurant` : Pages individuelles pour chaque restaurant avec des informations spécifiques.

## Contributeurs

- [Univers-mc] - Mickael Cauchon
