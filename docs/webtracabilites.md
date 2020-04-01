---
id: webtracabilites
title: Traçabilité des flux et des objets
sidebar_label: Traçabilité
---


## Flux - Identification des flux arrivage

L'application Wiistock propose en premier temps une réception, puis une mise en stock. 

La réception correspond à l'identification du flux d'arrivage. En effet faire la réception puis la mise en stock en même temps n'est pas possible. Grâce à la fonctionnalité arrivage il est possible pour vous de réceptionner vos colis et de les envoyer dans une zone en attente de mise en stock (réception).

La fonctionnalité arrivage se trouve dans le module traçabilité. Quand vous cliquez sur la fonctionnalité arrivage, vous arriverez sur un tableau qui regroupe tous les arrivages enregistrés. Ce tableau contient différentes informations notamment la date, le numéro de arrivage, le transporteur, le numéro de commande, le fournisseur, le destinataire et beaucoup d'autres choses encore. Chaque colonne est paramétrable, c'est-à-dire qu'elles peuvent être enlevées du tableau si vous le désirez. 

Sur la page des vous verrez aussi, une liste de filtres permettant de trouver un arrivage plus facilement. Pour utiliser filtre une fois la manipulation faites, il vous faudra cliquer sur le bouton filtrer en haut à droite de votre écran. 

Vous aurez la possibilité d'exporter votre tableau (pour faire un export il faut ajouter un ou plusieurs filtres) dans un tableau exel grâce au bouton « Exporter au format CSV ».  
Enfin, l'application est muni d'une barre de recherche au-dessus à droite du tableau afin de pouvoir rechercher directement un arrivage. 

Pour créer un arrivage il vous faudra cliquer sur le bouton « nouvel arrivage ». Cette fonctionnalité permettra d'ouvrir un formulaire de création d’arrivage. Certains champs sont obligatoires, ils sont munis d'une astérix. #vous pouvez paramétrer les champs que vous voulez voir obligatoires ou non#. Vous pouvez voir à côté de certains champs un bouton plus, il va permettre de créer un nouveau fournisseur, transporteur, … s'ils ne sont pas dans votre base de données. 

Pour valider la création, cliquez sur le bouton enregistrer. #Une fois l'enregistrement créé, dans les paramètres vous pourrez choisir si vous êtes redirigé dans l'arrivage ou bien si un formulaire d'arrivage se recrée automatiquement pour pouvoir le remplir#. 

Lorsque vous avez créé votre arrivage et que vous vous rendez dans celui-ci, vous y retrouverez en haut de l'écran les informations concernant cet arrivage : le fournisseur, le transporteur, le numéro de commande, le statut, le destinataire, l'acheteur, et des champs libres que vous aurez paramétrés auparavant. Vous y retrouverez deux tableaux. Concernant les colis de votre arrivage, l'autre concernant les litiges. Il vous sera possible après la création d'un arrivage, d'ajouter un colis ou plusieurs grâce au bouton ajouter colis. Vous pourrez imprimer les ou le colis, grâce au bouton imprimer colis. 

Pour attribuer un litige a un arrivage il vous faut cliquer sur nouveau litige. #Chaque litige est visible dans le module qualité, litiges# 

Après avoir cliqué sur nouveau litige, un formulaire s'ouvrira, est vous permettra de créer votre propre litige. Il sera possible pour vous de définir le type, le statut, de laisser un commentaire et de choisir le colis concerné par le litige. De plus vous pouvez glisser une pièce jointe et qualifié ce litige d’urgent ou non. Puis vous cliquerez sur enregistrer. Votre litige sera visible dans le tableau à droite, celui qui renseigne tous les litiges. 

Vous venez de créer un arrivage, maintenant vous pouvez le mettre en stock, grâce à la fonctionnalité [Réception] (webordres.md). 


## Mouvement de traçabilité

Les mouvements de traçabilité permettent de savoir où se trouve les produits, colis, articles,… avant la mise en stock. Cela permet de déplacer d'un emplacement A à un emplacement B un ou plusieurs objets, tout en gardant les informations nécessaires de tracabilité liées aux colis, produits ou articles. Cette fonctionnalité est traitable sur l'application web et également sur l'application mobile.  

## Association BR

L'association BR, est une fonctionnalité qui permet d'associer un arrivage à un bon de réception. 

Pour faire cette action, il faut vous rendre dans le module #Traçabilité#, puis sur la fonctionnalité #Association BR#. Cette fonctionnalité va vous rediriger vers la liste de toutes les Association BR déjà créée. Vous y retrouverez des filtres, en haut de votre écran, ce qui vous permettra de trier plus facilement. 

Vous y retrouverez aussi un tableau regroupant toutes les associations de Bon de Réception, regroupant les informations suivantes : 
-	Action 
-	Date 
-	Arrivage 
-	Réception 
-	Utilisateur 

Vous pouvez aussi retrouver juste au-dessus à droite du tableau, une barre de recherche.

Pour associer un bon de réception à un arrivage, il faut que vous cliquiez sur le bouton #association/BR#. Cette action va immédiatement ouvrir un formulaire de création. Il vous faudra remplir le numéro d’arrivage, s'il y en a plusieurs vous pouvez cliquer sur le bouton #plus# pour ajouter un nouvel arrivage. 

Puis vous devrez remplir le numéro de réception. Si vous voulez associer un bon de réception sans arrivage vous cliquez sur le bouton #sans arrivage#. Cette action fera disparaître le libellé des arrivages. 
Pour finaliser votre création, cliquez sur enregistrer. Une fois la création faites, vous aurez la possibilité de retrouver votre #Bon de Réception# dans votre tableau. 

Si vous le souhaitez-vous pouvez exporter votre tableau sous forme de tableur Excel. 


## Acheminement

La fonctionnalité d'acheminement permet de créer une demande de mouvement d'une pièce d'un emplacement de dépose. La particularité de cette fonctionnalité, c'est qu'il peut s'agir d'une pièce qui ne figure pas dans votr stock. 
Pour faire une demande, vous devez aller dans le module traçabilité, acheminement, puis vous cliquez sur le bouton faire une demande d'acheminement. Ensuite, le formulaire de votre demande va s’afficher. Et vous n’aurez plus qu’à le remplir. 

## En-cours

La fonctionnalité des encours permet de visualiser la durée d'un objet sur un emplacement. Les encours sont liés à des emplacements, qui sont eux-mêmes liés à des délais de traçabilité que vous pourrez paramétrer dans le référenciel des emplacements. 

Si les colis posés sur les emplacements d'encours dépassent le délais de tracabilité préalablement paramétré alors ils apparaîtront en rouge sur votre écran. 

Afin de fixer un délai de traçabilité et pour attribuer un emplacement à une zone d’encours, vous vous rendrez dans référentiel, emplacement. Vous pourrez soit modifier un emplacement déjà existant où et lui attribuer un délai de traçabilité ou bien créer un nouvel emplacement et lui ajouter un délai de traçabilité.  

## Urgences

IL est possible qu'un de vos collaborateurs ait besoin de colis en urgence. Pour cela il se rendra sur le module "Traçabilité", "Urgence". Puis il faudra cliquez sur "nouvelle urgence". Il vous faudra remplir les champs obligatoires qui sont essentiels pour l'activation de l'urgence : 
* La fourchette de livraison 
* Numero de commande
* Numéro de poste
* Acheteur
* Fournisseur 
* Transporteur

L'urgence pourra se déclencher lors de la réception d'un arrivage, lorsque vous remplirez les champs, 
* Fournisseur 
* Transporteur
* Numéro commande
* Destinataire  

Si la création de l'arrivage se fait lors de La fourchette de livraison, et que l'arrivage correspond au champ de l'urgence, alors l'urgence se déclenche. 