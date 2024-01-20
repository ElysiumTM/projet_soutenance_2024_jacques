# roadBuddy

RoadBuddy est une entreprise de covoiturage qui connecte les conducteurs avec des passagers pour des trajets partagés. Notre plateforme permet aux utilisateurs de trouver des trajets abordables, pratiques et respectueux de l'environnement.

# Information

Les techs utilisées pour ce projet sont : **ReactJS/ typescript - NodeJS - Express**.
La base de donnée : **mongoDb - mongoose**.
La version de node utilisée est : **v.18.13.0**.

# Lien vers les repositories

1. FRONT : [FRONT END](https://github.com/ElysiumTM/roadBuddy-front)
2. BACK : [BACK END](https://github.com/ElysiumTM/roadBuddy-server)

# Lancement du projet

- #### FRONT
  - Clonez le repository.
  - Lancez la commande `npm i` pour installer les dépandances.
  - Lancez le front avec cette commande `npm run dev`.

- #### BACK
  - Clonez le repository.
  - Lancez la commande `npm i` pour installer les dépandances.
  - Lancez le back avec cette commande `npm start`.
  - Pour interagir avec MongoDB, lancez cette commande afin de le démarrer `mongosh`.
  - #### STRIPE
    - Pour démarrer un paiement avec Stripe, il est primordial de lancez cette première commande : `stripe listen --forward-to localhost:3300/webhook --skip-verify`.
    - Ainsi que cette deuxième commande : `stripe trigger payment_intent.succeeded`.
  
# SCHEMA et DESIGN

### SCHEMA DE LA BASE DE DONNEE UML
  ![UML_roadBuddy](https://github.com/ElysiumTM/projet_soutenance_2024_jacques/assets/97950735/ba414c04-dbac-42ad-9741-f99b0b845c90)

### FIGMA
  - [DESKTOP](https://www.figma.com/file/XdtHXIRcvhLlI6DslvyCYW/Desktop?type=design&node-id=0-1&mode=design&t=7dL07JdFHkulTkbE-0)
  - [MOBILE](https://www.figma.com/file/kEaBQH2RhQVejAQDLhTv2l/Mobile?type=design&mode=design&t=AcwhYFWQKhJfK4c2-0)


# Très bonne journée à vous :)
