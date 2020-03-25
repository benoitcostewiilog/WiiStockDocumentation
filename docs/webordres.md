---
id: webordres
title: Les ordres de prération, livraison, collecte, réception
sidebar_label: Ordres
---

Check the [documentation](https://docusaurus.io) for how to use Docusaurus.

## Les ordres

La fonctionnalité d'ordre regroupe les ordres de collecte et de livraison. Elle permet aussi de récéptionner des colis et d'incrémenter le stock grace au récéption.  

![Premier pas](assets/premier.png)

## Ordre de préparation

Après une demande de livraiosn, l'ordre de prépartion s'affiche dans le tableau. Dans la page des ordres de livraison vous y retrouverez aussi la possibilité de filtrer et d'exporter les informations du tableau au format CSV. 

Le tableau regroupent les collones suivantes 
* Actions, permettant de rentrer dans l'ordre de livraison
* Numéro, qui permet de lier la dmeande a l'ordre
* Statut, qui permert de savoir si l'ordre est bien traité
* Date de création
* Opérateur, permettant de savoir qui c'est occupé de la prépartion
* Type

Pour éffèctuer votre prépartion, rendez-vous, dans l'ordre en passant par le bouton de l'oeil, dans la colonne action. 

Après avoir cliquez dessus, vous serez redirigé vers le détail de l'ordre de livraion. Vous y retouverez le détail de l'ordre, mais aussi le tableau des articles et réféernces demandé. Et enfin la possibilité de rassemblé ls articles et références dont vous avez besoins. 

Puis vous pouvez valider. Ou bien supprimer l'ordre. 

Dans le tableau principal, vorte préparation passera sont statut de "a trater" à "traité". De plus vous aurez aussi l'information de l'opérateur qui a efféctué l'action. 

### Picking sur référence

Pour une livraison :

Pour éfféctuer un picking sur référence, vous devez :
* Livraison 
* Nouvelle demande de livraion 
* Remplir le premier formulaire
* Chercher une référence, vous arriverez sur la liste de toutes les références de votre stock. Vous aller pouvoir modifier la référence, la supprimer, voir les mouvement de stock liée ou bien l'ajouter a votre ordre. Vous avez aussi la possiblité de créer un article de référence depuis cette page

### Picking sur articles

### Picking partiel

Lors de l'execution de vos ordres, il est possible que votre stock ne possédent pas les piece n'éssésaisre sur le moment. Il st possible de traiter un ordre partiellement, pour envoyer une partie de la demande. Pas de panique, un picking partiel créra un deuxieme ordre pour finaliser l'acion plus tard. 

## Ordre de livraison

Les ordres de livraiosns sont liées au demandes de livriaosns. Chaque demande, impliquera un ordre de préparartion. Lors de la validation de la prépartion. Un ordre de livraison se créra et il permettera de relier l'emplacement de prépartion à l'emplacemt de livraion. 

## Ordre de collecte

Un ordre de collecte est crée après une demande de collecte. Il permet de traité la demande, d'éfféctuer l'action. 

La page des ordres de collecte est constitué d'un tableau, de filtre et d'un bouton export CSV. 
Le tableau regroupent les collones suivantes :
* Actions, cella vous permet de traiter la demande
* Numéro, il s'agit d'un numéro lier a la demande, permettant de liée l'ordre a la demande
* Statut, permet de voir si la collecte est traité ou non
* Date de création	
* Opérateur, nous renseigne sur qui a traité la collecte 	
* Type

Pour traiter la collecte, il faut cliquez sur 
* Le bouton de l'oeil gris, dans la colonne action, qui vous aménera sur la page de l'ordre
* Vous trouverez le détail de la collectte en haut, avec les informations suivantes 
*     Statut
*     Numéro de la collecte
*     Demandeur
*     Opérateur
*     Date de collecte
*     Point de collecte
*     Destination
*     Commentaire                                                      

Vous trouvez aussi en bas la liste des articles/références liée a la demande sous forme de tableau. Vous y trouverez les informations suivantes 
* Référence	
* Libellé	
* Emplacement	
* Quantité	
* Actions, les actions permette de modifier la quantité, de voir le détail de la référneces, d'imprimer l'étiquette, et de valider la référence. 

Enfin pour traité déffinitivement l'ordre, vous cliquez sur finir la collecte. 
Si la collecte doit être supprimer, vous pouvez le faire grace au bouton supprimer. 


## Ordre de réception

Quand vous venez de recevoir des colis, il faut ensuite les ajouter au stock. 
Pour cella vous pourrez utiliser la fonctionnalité, récéption. 
Celle-ci vas vous permettre, de voir l'ensemble des récéptions que votre stock a enregistré.

### Créer une réception

Pour créer une récéption, cliquez sur le bouton, **nouvelle récéption**, puis vous remplissez les champs dont vous avez besoins. 

Après avoir validé la création, vous arriverez dans le détail de la récéption pour pouvoir y ajouter des piéces.
Pour les ajouter, il faut cliquer sur le bouton ajouter piéce. Si une ou plusieurs de vos piéces sont litigieuses, alors vous pouvez créer un litige sur c'est piéce la. Cella vas permettre d'alerter et qu'un logisticien s'occupe imédiatement de la ou les piéces concernées. Ensuite après avoir séléctionné une piéce, vous devrez cliquer sur le bouton récéption. Qui vous permettra de valider l'ajout d'une référence dns votre stock. 

Vous trouverez en haut de la page, les informations concernant votre récéption 

* Numero de réception
* Fournisseur
* Emplacement
* Date commande
* Numéro de commande
* Date de création 
* Date de fin d'une réception 
* Commentaire

Vous pouvez ensuite soit supprimer, modifier ou bien finnir la récéption grace au bouton situé en au a droite de votre écran. 

### Filtrer les réceptions

En haut de la liste de vos récéptions, vous toruverez, tous les filtres. Vous pouvez combiner autant de filtre que vous souhaitez. Ensuite pour appliquer c'est filtres, vous cliquez sur filtrer. 

### Réceptionner des articles ou références
