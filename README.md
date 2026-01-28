#  Blood Donation Management System

## Description
Le **Blood Donation Management System** est une application web conçue pour faciliter la gestion des dons de sang.  
Elle permet de centraliser les informations liées aux utilisateurs, aux annonces de dons et aux besoins en sang, tout en offrant une interface web moderne et une API robuste.

L’application est développée en utilisant la **stack MERN (MongoDB, Express.js, React, Node.js)** et repose sur une architecture **client–serveur** avec communication via une **API REST**.

Ce projet a été réalisé dans un cadre académique afin de mettre en pratique les concepts du développement web full-stack.


## Objectifs du projet
- Concevoir une application web complète (frontend + backend)
- Mettre en œuvre une architecture REST
- Appliquer les bonnes pratiques du développement JavaScript
- Gérer la persistance des données avec MongoDB
- Utiliser Git et GitHub pour la gestion du code source


## Technologies utilisées

### Frontend
- React
- JavaScript (ES6)
- HTML5
- CSS3

### Backend
- Node.js
- Express.js

### Base de données
- MongoDB

### Autres outils
- Git / GitHub
- REST API
- JSON

## Fonctionnalités principales
- Inscription et authentification des utilisateurs
- Gestion des utilisateurs (donneurs, bénéficiaires, administrateurs)
- Création et consultation d’annonces de dons de sang
- Gestion des besoins en sang
- Interface utilisateur interactive
- Communication sécurisée entre le client et le serveur via API REST

## Architecture
Le projet suit une architecture **MERN** classique :

- **Client** : application React responsable de l’interface utilisateur
- **Server** : API Node.js / Express qui gère la logique métier et l’accès aux données
- **Database** : MongoDB pour le stockage persistant des données

## Structure du projet

BLOOD_DONATION_MERN/
├── Client/
│ ├── public/
│ ├── src/
│ ├── .env
│ ├── .gitignore
│ ├── package-lock.json
│ ├── package.json
│ └── README.md
│
└── server/
├── config/
├── controllers/
├── middleware/
├── models/
├── routers/
├── upload/
├── validation/
├── .gitignore
├── package-lock.json
├── package.json
├── passportConfig.js
└── server.js


##  Installation et exécution du projet

### Prérequis
- Node.js
- MongoDB
- npm ou yarn

### Backend
```bash
cd server
npm install
npm start


Le serveur démarre par défaut sur :

http://localhost:5000

  Frontend
cd Client
npm install
npm start


L'application React sera accessible sur :

http://localhost:3000

  ### Tests

Les tests peuvent être ajoutés ultérieurement afin de valider les fonctionnalités du backend et du frontend.

### Auteurs

Azza Gatfa
