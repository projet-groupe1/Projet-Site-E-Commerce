# Projet-Site-E-Commerce (groupe 1)

        Sujet :
La conception d'un E-commerce(Vente d'appareil électronique) avec PHP/javascript avec les fonctionnalité suivante: Ajouter un produit dans une catégorie son prix et sa description en base de donné (administrateur connecté uniquement) Lister les produits dynamiquement depuis la base de données Ajouter un produit au panier dynamiquement des qu'on appui sur acheter filtrer et rechercher les produit par nom, date ajout, prix cliquer sur un produit pour consulter tout ces détails en suivant la commande pour paiement en se connectant ou en créant un compte client si simulation inexistante d'envoie de mail après achat (correctement formaté) NB : le FRONTEND sera fait avec du JAVASCRIPT et le BACKEND avec du PHP le design doit être très travaillé et convivial facile à manipuler et optimiser

  1.Présentation du Projet

•	Ce projet est un site de commerce électronique(Vente d'appareil électronique). Les clients pourront chercher les produits qu’ils désirent et les ajouter dans leur panier. S’ils souhaitent finaliser leurs achats, ils devront s’inscrire pour valider leur commande.
•	Le but de ce PROJET est de mettre en œuvre les notions de sessions pour affecter un panier à chaque visiteur, puis dans le cas d’un achat d’enregistrer la commande de l’utilisateur. Du côté du client web, nous tiendrons à faciliter la tâche de recherche, de sélection de produits et de validation de la commande.

 2. La conception de la Base de données

     Entités et règles de gestion : 🏷️

 Les entités utilisées dans  sont :
________________________________________
● Users, (id, nom, email, password) 
● Commandes, (id, nom, produits, quantité, total) 
● Produits, (id, nom, quantité, description, image) 
● Catégories (id, nom)

 Les règles et associations 🏷️

1. Un utilisateur (User) peut demander plusieurs commandes (Une commande est associée à un seul utilisateur).
2. Un utilisateur peut chercher un ou plusieurs produits.
3. un produit peut avoir une et une seule catégorie.
4. Une catégorie peut contenir un ou plusieurs produits.

   
   3.Les Technologies utilisées

 1.HTML5

•	Le HyperText Markup Langage, généralement abrégé HTML ou dans sa dernière version HTML5, est le langage de balisage conçu pour représenter les pages web.

voir également à propos HTML5 (https://developer.mozilla.org/fr/docs/Web/HTML)


 2.CSS3

•	Les feuilles de style en cascade, généralement appelées CSS de l'anglais Cascading Style Sheets, forment un langage informatique qui décrit la présentation des documents HTML et XML.

voir également à propos [HTML5] CSS3 (https://developer.mozilla.org/fr/docs/Web/CSS)


 3.BootsTrap

•	Bootstrap est une collection d'outils utiles à la création du design de sites et d'applications web.
•	C'est un ensemble qui contient des codes HTML et CSS, des formulaires, boutons, outils de navigation et autres éléments interactifs, ainsi que des extensions JavaScript en option.

voir également à propos Bootstrap (https://getbootstrap.com/)


 4.MySQL

•	Est un système de gestion de base de données relationnelle (SGBDR) open source. Son nom est une combinaison de "My", le nom de la fille du co-fondateur Michael Widenius, et de "SQL", l'abréviation de Structured Query Language. Une base de données relationnelle organise les données en une ou plusieurs tables de données dans lesquelles les types de données peuvent être liés les uns aux autres ; ces relations aident à structurer les données. SQL est un langage utilisé par les programmeurs pour créer, modifier et extraire des données de la base de données relationnelle, ainsi que pour contrôler l'accès des utilisateurs à la base de données.

Voir également à propos MySQL (https://www.oracle.com/fr/mysql/what-is-mysql/)


 5.JavaScript
 
•	JavaScript est un langage de programmation de scripts principalement employé dans les pages web interactives et à ce titre est une partie essentielle des applications web. Avec les technologies HTML et CSS, JavaScript est parfois considéré comme l'une des technologies cœur du World Wide Web.

Voir également à propos JavaScript (https://developer.mozilla.org/fr/docs/Web/JavaScript)


5.PHP

•	Hypertext Preprocessor, plus connu sous son sigle PHP, est un langage de programmation libre, principalement utilisé pour produire des pages Web dynamiques via un serveur HTTP, mais pouvant également fonctionner comme n'importe quel langage interprété de façon locale. PHP est un langage impératif orienté objet.

Voir également à propos PHP (https://www.php.net/)



        •	Enfin nous tenons à remercier le seul et unique, notre professeur
        Mr Robert DIASSE Ingerieur & professeur à ISI pour son soutien et son encouragement 
        envers nous, aussi pour nous avoir donné cette opportunité d'améliorer nos 
        compétences et de connaître les nouvelles technologies comme celles qui nous avons travaillé.







        
