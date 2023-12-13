# Projet de Gestion de Commandes pour un Restaurant

## Description

Ce projet a pour objectif de créer une application web de gestion des commandes pour un restaurant, en utilisant HTML, CSS, JavaScript pour le frontend et PHP pour le backend. La base de données est gérée avec PHPMyAdmin. 

### Fonctionnalités

#### 1. Clients
   - Consulter le menu du restaurant.
   - Ajouter des plats au panier.
   - Passer des commandes avec des instructions spécifiques.
   - Suivre l'état des commandes en cours.

#### 2. Administrateurs
   - Gérer le menu : ajout, mise à jour, suppression de plats.
   - Suivre les commandes en cours.
   - Marquer les commandes comme traitées/livrées.
   - Visualiser l'historique des commandes.

### Technologies Utilisées

- **HTML** : Structure de la page web.
- **CSS** : Style et mise en page.
- **JavaScript** : Logique côté client.
- **PHP** : Logique côté serveur et gestion des bases de données avec PHPMyAdmin.
- **MySQL** : Système de gestion de base de données relationnelle.

### Base de Données

La base de données est gérée avec PHPMyAdmin et suit une structure adaptée aux besoins du projet. Les tables incluent :
- **users** : Utilisateurs (id, nom, prenom, login, mdp, type).
- **plats** : Plats du menu (id, nom, description, prix, created_at, updated_at).
- **commandes** : Commandes passées par les clients (id, user_id, statut, created_at, updated_at).
- **commande_plat** : Association des plats à une commande (commande_id, plat_id, quantite).

### Installation

1. Clonez le dépôt : `git clone https://github.com/votre-utilisateur/ProjetGestionCommandes.git`
2. Configurez PHPMyAdmin avec la structure de la base de données fournie.
3. Ouvrez le projet dans un serveur local compatible avec PHP (ex: Apache).
4. Accédez à l'application via le navigateur.

## Remarques

- Ce projet utilise un stack technologique basique avec PHP, JavaScript, HTML, CSS, et PHPMyAdmin pour la gestion de la base de données.
- Les utilisateurs peuvent ajouter des plats au panier et passer des commandes.
- Les administrateurs peuvent gérer le menu et suivre les commandes en cours.

  ![image2](https://github.com/shyamsubrun/shyamsubrun-Conception-site-restaurant-commande/assets/113545721/be46b632-ff7a-462f-9411-2fa483e43619)

![image](https://github.com/shyamsubrun/shyamsubrun-Conception-site-restaurant-commande/assets/113545721/81c19b57-3942-4a9e-8672-1ac9bceb1713)

