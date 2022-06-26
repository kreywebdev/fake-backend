# Bienvenue sur fake-backend

Fake-backend est une api Rest toute simple ecrite avec le package npm [json-server](https://www.npmjs.com/package/json-server)

> L'api implémente deux listes. Une liste d'utilisateurs (10) et une liste de posts (100).

## Installation

Clonez le repository dans le dossier de votre choix. Rentrez dans le dossier nouvellement créé et faite :
```
npm install
```

## Lancer le serveur

```
npm run start
```
Le serveur par défaut s'écoute sur le port 3000 (http://localhost:3000).

### Routes
```
GET    /utilisateurs
GET    /utilisateurs/1
POST   /utilisateurs
PUT    /utilisateurs/1
PATCH  /utilisateurs/1
DELETE /utilisateurs/1
```
```
GET    /posts
GET    /posts/1
POST   /posts
PUT    /posts/1
PATCH  /posts/1
DELETE /posts/1
```
Pour connaitre la liste de toutes les options, je vous invite à vous rendre sur la [documentation officielle](https://github.com/typicode/json-server)

### Remise à zéro
Copier coller l'intégralité de db_backup.json dans db.json
