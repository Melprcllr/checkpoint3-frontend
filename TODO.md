## 1) Initialisation du projet : <br>
Initialisation d'un nouveau dépôt GitHub et clonage du repository du checkpoint https://github.com/WildCodeSchool/wns_13_05_2024 

## 2) Lancement de Docker : <br>
Dans le répertoire racine lancement de la commande ``npm start`` <br>
Cette commande démarre les 2 services principaux du projet : le __BACKEND__, en exécutant ``ts-node-dev`` sur le fichier ``src/index.ts`` (permettant de développer le backend avec TypeScript en mode "watch"),<br> 
Et le __FRONTEND__, avec ``next dev``, qui démarre un serveur ``Next.js`` pour l'interface utilisateur, disponible à l'URL http://localhost:3000 <br>
Ensuite dans les répertoires __BACKEND__ et __FRONTEND__ plusieurs commandes ont été exécutées : <br>
- ``npm i``  : Cette commande installe toutes les dépendances définies dans le fichier ``package.json``, garantissant que le projet dispose de toutes les bibliothèques nécessaires pour fonctionner.
- ``npm run dev`` : Elle permet de lancer l'application en mode développement. Pour le backend, cela démarre le serveur en écoutant les changements de fichiers, tandis que pour le frontend, elle active le serveur Next.js pour le rendu de l'interface.

## 3) Apollo Client : <br>
Après avoir lancé le projet, j'ai intitialisé __Apollo Client__ en configurant à la fois le __client__ et le __provider__ pour gérer la communication avec l'API GraphQL.<br>
__Apollo Client__ permet de récupérer, mettre en cache et gérer les données de l'API côté frontend.
<br>

## 4) Queries
Ensuite j'ai ajouté quelques requêtes GraphQL : <br> 
``getAllCountries``, qui permet de récupérer la liste de tous les pays depuis l'API backend, afin d'afficher ces données dans l'interface utilisateur. <br>
``getOneCountry``, permettant de récupérer les informations détaillées d'un pays spécifique. Cela permet à l'utilisateur de sélectionner un pays et de voir toutes les données associées, récupérées dynamiquement depuis l'API.


