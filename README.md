JSONPlaceholder API Testing

Présentation

Dans ce projet, j’ai réalisé des tests API avec Postman sur l’API JSONPlaceholder.

L’objectif était de pratiquer les principales méthodes HTTP et de vérifier les réponses de l’API.

Tests réalisés

J’ai testé les méthodes suivantes :

- GET – récupérer les données
- GET – récupérer un post par ID
- GET – tester un ID inexistant
- POST – créer un nouveau post
- PUT – modifier un post
- DELETE – supprimer un post

Vérifications

Pendant les tests, j’ai vérifié :

- les codes de statut HTTP
- les données retournées
- le comportement avec un ID inexistant

J’ai également utilisé quelques scripts simples dans Postman pour vérifier automatiquement les réponses.

 Résultats

- GET /posts → 200 OK
- GET /posts/1 → 200 OK
- GET /posts/9999 → 404 Not Found
- POST /posts → 201 Created
- PUT /posts/1 → 200 OK
- DELETE /posts/1 → 200 OK.


- Postman
