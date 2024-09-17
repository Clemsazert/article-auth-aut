# Contrôle d'accès dans un service numérique avec Keycloak

Ce dépôt contient le code de l'application web décrite dans la série d'articles sur le contrôle d'accès disponible
sur le blog [dev.to](https://dev.to/solona) de [Theodo GovTech](https://www.welcometothejungle.com/fr/companies/solona).

### Instructions de lancement

Prérequis :
- Docker

Toutes les applications (frontend, backend et authentification) sont conteneurisées et peuvent être lancées
via `docker-compose`

Lancer le service : `docker-compose up`

Arreter le service : `docker-compose down`

*Note: pour supprimer les volumes associés, utiliser le flag `-v` avec la commande ci-dessus.*

### Usage

Lien vers la console d'administration Keycloak : http://localhost:9081
