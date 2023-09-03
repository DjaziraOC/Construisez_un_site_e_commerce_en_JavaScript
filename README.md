## Site e-commerce Kanap 

Projet n°4 du parcours [développeur web chez OpenClassrooms](https://openclassrooms.com/fr/paths185-developpeur-web#path-tabs)

L client Kanap, est une marque de canapés qui vend ses produits depuis sa boutique exclusivement. Aujourd’hui, celle-ci souhaiterait avoir une plateforme de e-commerce en plus de sa boutique physique pour vendre ses produits sur Internet.

## Objectif 
L'objectif étant d'implémenter de manière dynamique le site Kanap par :
● l'unification des travaux déjà réalisés par l’équipe en intégrant dynamiquement les éléments de l’API dans les différentes pages web avec JavaScript. Le code du front-end et de l’API est disponible [sur ce repo](https://github.com/OpenClassrooms-Student-Center/P5-Dev-Web-Kanap).

● Mettre en place un plan de [test d’acceptation](/docs/DW+P5+-+Modele+plan+tests+acceptation%20(3).xlsx) à partir de ce template que nous avons pour habitude d’utiliser.

![desktop ](/docs/maquette.png)

## Cahier des charges
Des spécifications [techniques et fonctionnelles du projet](https://course.oc-static.com/projects/DWJ_FR_P5/DW+P5+-+Specifications+fonctionnelles.pdf)

## Livrables attendus

- [x] Page Accueil

● Affiche (de manière dynamique) tous les articles disponibles à la vente. L’ensemble des produits sont retournés par l’API.

● Pour chaque produit, il faudra afficher l’image de celui-ci, ainsi que son nom et le début de sa description.

● En cliquant sur le produit, l’utilisateur sera redirigé sur la page du produit pour consulter celui-ci plus en détail.

- [x] Page Produit

● Cette page affiche (de manière dynamique) les détails du produit sur lequel l'utilisateur a cliqué depuis la page d’accueil.

● Depuis cette page, l’utilisateur peut sélectionner une quantité, une couleur, et ajouter le produit à son panier.

- [x] Page Panier

● Un résumé des produits dans le panier, le prix total et la possibilité de modifier la quantité d’un produit sélectionné ou bien de supprimer celui-ci.

● Les produits doivent toujours apparaître de manière regroupée par modèle et par couleur.

● Si un produit est ajouté dans le panier à plusieurs reprises, avec la même couleur, celui-ci ne doit apparaître qu’une seule fois, mais avec le nombre d’exemplaires ajusté.

● Si un produit est ajouté dans le panier à plusieurs reprises, mais avec des couleurs différentes, il doit apparaître en deux lignes distinctes avec la couleur et la quantité correspondantes indiquées à chaque fois.

● Un formulaire permettant de passer une commande. Les données du formulaire doivent être correctes et bien formatées avant d'être renvoyées au back-end. Par exemple, pas de chiffre dans un champ prénom.

● En cas de problème de saisie, un message d’erreur devra être affiché en dessous du champ correspondant.

● Attention à ne pas stocker le prix des articles en local. Les données stockées en local ne sont pas sécurisées et l’utilisateur pourrait alors modifier le prix lui-même.

- [x] Page Confirmation

● Un message de confirmation de commande, remerciant l'utilisateur pour sa commande, et indiquant l'identifiant de commande envoyé par l’API.

● Sur cette page, l'utilisateur doit voir s’afficher son numéro de commande. Il faudra veiller à ce que ce numéro ne soit stocké nulle part.

## Outils et languages pour la réalisation du projet

## Languages
- [x] Le projet à été réalisé en **HTML5/CSS3/JavaScript** ainsi que le framework frontend **Express**

## Outils         
- [x] [Visual Studio Code](https://code.visualstudio.com/)- Editeur de codes
- [x] [GitHub](https://github.com/)- Hébergeur de site web 
- [x] [RegExr](https://regexr.com/)- Testeur d'expressions régulières (Regex)

## Compétences évaluées

- [x] Interagir avec un web service avec JavaScript.
- [x] Valider des données issues de sources externes.
- [x] Créer un plan de test pour une application.
- [x] Gérer des événements JavaScript.

## Lien github & Plan test:

- [x] Lien de la page web de [projet 05:Construisez un site e-commerce en JavaScript](https://djaziraoc.github.io/NaitMessaoudDjazira_5_25022022/front/html/index.html) - Nécessité d'exécuter le serveur avec node server.
- [x] [Modèle de plan de test.](/docs/plan_test.xlsx) 

## Evaluation
-> Projet validé

