---
id: webordres
title: Les ordres de préparation, livraison, collecte, réception
sidebar_label: Ordres
---

Check the [documentation](https://docusaurus.io) for how to use Docusaurus.

## Les ordres

La fonctionnalité d'ordre regroupe les ordres de collecte et de livraison. Elle permet aussi de réceptionner des colis et d'incrémenter le stock grâce aux réceptions.  

![Premier pas](assets/premier.png)

## Ordre de préparation

Après une demande de livraiosn, l'ordre de préparation s'affiche dans le tableau. Dans la page des ordres de livraison vous y retrouverez aussi la possibilité de filtrer et d'exporter les informations du tableau au format CSV. 

Le tableau regroupe les colonnes suivantes 
* Actions, permettant de rentrer dans l'ordre de livraison
* Numéro, qui permet de lier la demande à l'ordre
* Statut, qui permet de savoir si l'ordre est bien traité
* Date de création
* Opérateur, identité de la personne qui a traité l'ordre
* Type

Pour effectuer votre préparation, rendez-vous, dans l'ordre en passant par le bouton de l'oeil, dans la colonne action. 

Après avoir cliquez dessus, vous serez redirigé vers le détail de l'ordre de livraison. Vous y retouverez le détail de l'ordre, mais aussi le tableau des articles et références demandés. Et enfin la possibilité de lister les articles et références dont vous avez besoin. 

Puis vous pouvez valider ou bien supprimer l'ordre. 

Dans le tableau principal, votre préparation passera au statut de "à traiter" à "traité". De plus vous aurez aussi l'information de l'opérateur qui a effectué l'action. 

### Picking sur référence

Pour une livraison :

Pour effectuer un picking sur référence, vous devez :
* Livraison 
* Nouvelle demande de livraion 
* Remplir le premier formulaire
* Chercher une référence, vous arriverez sur la liste de toutes les références de votre stock. Vous aller pouvoir modifier la référence, la supprimer, voir les mouvements de stock liés ou bien l'ajouter à votre ordre. Vous avez aussi la possiblité de créer un article de référence depuis cette page

### Picking sur articles

### Picking partiel

Lors de l'exécution de vos ordres, il est possible que les pièces ne soit pas disponibles en stock. Il est possible de traiter un ordre partiellement, un picking partiel créera un deuxième ordre pour finaliser l'action plus tard. 

## Ordre de livraison

Les ordres de livraisons sont liés aux demandes de livraisons. Chaque demande, impliquera un ordre de préparation. Lors de la validation de la préparation. Un ordre de livraison sera créer et il permettra de relier l'emplacement de préparation à l'emplacement de livraison. 

## Ordre de collecte

Un ordre de collecte est créé après une demande de collecte. Il permet de traiter la demande, d'effectuer l'action. 

La page des ordres de collecte est constitué d'un tableau, de filtres et d'un bouton export CSV. 
Le tableau regroupe les colonnes suivantes :
* Actions, cela vous permet de traiter la demande
* Numéro, il s'agit d'un numéro lier à la demande, permettant de lié l'ordre à la demande
* Statut, permet de voir si la collecte est traitée ou non
* Date de création	
* Opérateur, identité de la personne qui a traité l'ordre	
* Type

Pour traiter la collecte, il faut cliquer sur 
* Le bouton de l'oeil gris, dans la colonne action, qui vous aménera sur la page de l'ordre
* Vous trouverez le détail de la collecte en haut, avec les informations suivantes 
*     Statut
*     Numéro de la collecte
*     Demandeur
*     Opérateur
*     Date de collecte
*     Point de collecte
*     Destination
*     Commentaire                                                      

Vous trouvez aussi en bas la liste des articles/références liée à la demande sous forme de tableau. Vous y trouverez les informations suivantes 
* Référence	
* Libellé	
* Emplacement	
* Quantité	
* Actions, les actions permettent de modifier la quantité, de voir le détail de la références, d'imprimer l'étiquette, et de valider la référence. 

Enfin pour traité définitivement l'ordre, vous devez cliquer sur finir la collecte. 
Si la collecte doit être supprimer, vous pouvez le faire grâce au bouton supprimer. 


## Ordre de réception

Quand vous venez de recevoir des colis, il faut ensuite les ajouter au stock. 
Pour cela vous pourrez utiliser la fonctionnalité, réception. 
Celle-ci va vous permettre, de voir l'ensemble des réceptions que votre stock a enregistré.

### Créer une réception

Pour créer une réception, cliquez sur le bouton, **nouvelle récéption**, puis vous remplissez les champs dont vous avez besoin. 

Après avoir validé la création, vous arriverez dans le détail de la réception pour pouvoir y ajouter des pièces.
Pour les ajouter, il faut cliquer sur le bouton ajouter pièce. Si une ou plusieurs de vos pièces sont litigieuses, alors vous pouvez créer un litige associé à ces pièces.  Ensuite après avoir sélectionneè une piéce, vous devrez cliquer sur le bouton réception , qui vous permettra de valider l'ajout d'une référence dans votre stock. 

Vous trouverez en haut de la page, les informations concernant votre réception 

* Numero de réception
* Fournisseur
* Emplacement
* Date commande
* Numéro de commande
* Date de création 
* Date de fin d'une réception 
* Commentaire

Vous pouvez ensuite soit supprimer, modifier ou bien finir la réception grâce au bouton situé en haut à droite de votre écran. 

### Filtrer les réceptions

En haut de la liste de vos réceptions, vous toruverez, tous les filtres. Vous pouvez combiner autant de filtres que vous souhaitez. Ensuite pour appliquer ces filtres, vous cliquez sur filtrer. 

### Réceptionner des articles ou références
