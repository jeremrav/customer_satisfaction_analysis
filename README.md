# customer_satisfaction_analysis

## Description du projet :
La supply chain représente les étapes d'approvisionnement, du processus productif et de distribution de la marchandise.
En aval de ce processus, il peut être intéressant d’évaluer la satisfaction client pour :

- Étude de qualité sur la supply chain : problème de conception, livraison, prix non adapté, durabilité...
- Étudier si le produit/service correspond bien à l’attente du marché.
- Synthétiser les feedback, améliorations des clients.
- Aider à la réponse ou à la redirection des clients insatisfaits...

Pour de nombreux produits/services, la satisfaction des clients se mesure sur les commentaires, avis de sites dédiés (Trustpilot, site distributeur, twitter...).
Il peut être long, fastidieux mais important de lire et analyser les verbatim* qui sont essentiels à la compréhension de la satisfaction client, mais en l’absence d’outils qui permettent de synthétiser ces avis, les procédés sont généralement par échantillonnage.

L’objectif de ce projet est d’extraire de l’information de commentaires. Voici quelques axes de travails :
- Prédire la satisfaction d’un client : problème de régression (prédire le nombre d'étoiles).
- Identifier les entités importantes d’un message : localisation, nom d’entreprise...
- Extraire les propos du commentaire (problème de livraison, article défectueux...) : approche non supervisé
- Extraire de la réponse du fournisseur les propos du commentaire dans but d’essayer de les prédire uniquement avec le commentaire.

### Ressources à consulter :
#### Données :
- Le jeu de données peut se construire en scrapant (extraire) des sites d’avis de consommation :
  - Trustpilot : https://www.trustpilot.com/
  - Site du distributeur : Amazon, CDiscount...
  - Réseaux sociaux : Twitter, Facebook...
- Deux jeux de données sont disponibles pour le site Trusted shops :
  - venant de Trusted shops : les avis sont vérifiés, c’est-à-dire qu’ils font suite à une commande client.
  - venant de Trustpilot : avis d'internautes.

#### Conditions de validation du projet :
- un rapport d’exploration, de data visualisation et de pre-processing des données ;
- un rapport de modélisation ;
- un rapport final et le GitHub associé.
 
