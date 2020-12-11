# Evaluation SQL
## L'ensemble des réponses sera à remettre sur un fichier avec votre nom et prénom.
### Bon courage ;)

## Partie 1: Pour cette évaluation, vous devrez écrire les requêtes correspondant aux énoncés suivants.
### Vous utiliserez la base de données classicmodels qui est jointe à ce dossier.

1. La liste des commandes(orderNumber, orderDate, status, productCode, productName, productLine) ayant au moins un avion dans les produits commandés et donc le statut est envoyé (shipped)
2. La liste des employés(employeeNumber, lastname, firstname) qui ont 10 ou plus clients.
3. La liste des paiements effectués en 2003 et dont le montant est supérieur à 10 000€.
4. La liste de chaque client (priceEach * quantityOrdered, country) par pays qui a passé la plus grande commande.
5. La liste des employés (nom, prenom, officeCode, adresse complète du bureau) qui ont leurs bureaux à Sydney ou au Japon
6. La liste des commandes de 2003 (orderNumber, orderDate, ShippedDate) dont le délai de livraison est inférieur à 4 jours.
7. Les motos des années 2000
8. La plus grosse vente (priceEach * quantityOrdered) rattachée à chaque bureau (officeCode, city, addressLine1, country)
9. La liste des produits (nom, vendeur et buyPrice) qui sont achetés au moins 90$ triés par nom du produit
10. La liste des produits (code, nom et prix d'achat) des produits achetés au moins 60$ au plus 90$ triés par prix d'achat
11. Le nombre d'employés pour chaque bureau
12. Le total du stock et la valeur du total du stock à la vente de chaque ligne de produit pour les produits vendus plus de 110$ trié par total de la valeur du stock à la vente
13. La liste des employés (nom, prénom et fonction) et des bureaux (adresse et ville) dans lequel ils travaillent
14. La liste des clients français ou américains (nom du client, nom, prénom du contact et pays) et de leur commercial dédié (nom et prénom) triés par nom et prénom du contact
15. La liste des lignes de commande (numéro de commande, code, nom et ligne de produit) et la remise appliquée aux voitures ou motos commandées triées par numéro de commande puis par remise décroissante
16. Le total des paiements effectués de chaque client (numéro, nom et pays) américain, allemand ou français de plus de 50000$ trié par pays puis par total des paiements décroissant
17. Le montant total de chaque commande (numéro et date) des clients New-Yorkais (nom) trié par nom du client puis par date de commande

## Partie 2: Pour une entreprise, vous devez créer une base de donnée nommée powersouffle et contenant les informations suivantes:

- les user(firstname, lastname, email, password, created_at),
- les products(name, description, buyPrice, sellPrice),
- les commandes(orders)(orderedAt, shippedAt, status),
- les notes des produits,
- les commentaires sur les produits (title, content, createdAt)

### Ecrivez les requêtes complètes de la création de la base de données à la création des tables et aux requêtes d'insertion, de données pour chaque table. (Attention toutes les tables ne sont pas précisées il faudra que vous réfléchissiez aux liens entre les tables.)(Pensez aux primary keys et foreign keys).

#### Le rendu se fait par mail alexandre.gaillot@jedy.com

Bon courage ;)
