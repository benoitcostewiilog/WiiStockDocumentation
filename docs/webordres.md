---
id: webordres
title: Les ordres de préparation, livraison, collecte, réception
sidebar_label: Ordres
---


## Les ordres

La fonctionnalité d'ordre regroupe les ordres de collecte et de livraison. Elle permet aussi de réceptionner des colis et d'incrémenter le stock grâce aux réceptions.  

## Ordre de préparation

Après une demande de livraison, l'ordre de préparation s'affiche dans le tableau. Dans la page des ordres de préparation vous y retrouverez aussi la possibilité de filtrer et d'exporter les informations du tableau au format CSV. 

Le tableau regroupe les colonnes suivantes : 

Informations | Description
------------ | -------------
Numéro | Permet de lier la demande à l'ordre
Statut | Permet de savoir si l'ordre est bien traité
Date de création | Permet de savoir quand a été créé l'ordre
Opérateur | Indique la personne qui a traité l'ordre
Type | Indique la typologie d'article concerné

Pour effectuer votre préparation, rendez-vous, dans l'ordre en cliquant sur la ligne de l'ordre souhaité. 

Après avoir cliqué dessus, vous serez redirigé vers le détail de l'ordre de préparation. Vous y retouverez le détail de l'ordre, mais aussi le tableau des articles et références demandés, et enfin la possibilité de lister les articles et références dont vous avez besoin. 

Puis vous pouvez valider ou bien supprimer l'ordre. 

Dans le tableau principal, votre préparation passera au statut de `à traiter` à `préparé`. 

### Picking sur référence

Le picking sur référence concerne les préparations qui ont une référence gérée par référence.  

Pour effectuer un picking sur référence, vous devez :

* Allez dans la fonctionnalité `Ordre`, puis `Préparation`. 
* Vous y retrouverez tous les ordres de préparations. 
* Cliquez sur la prépartion qui vous concerne. 
* Vous y retrouverez les articles qui concerne votre ordre.
* Cliquez sur les trois boutons. 
* Un formulaire s'ouvrira, vous allez devoir indiquer le nombre d'article que vous souhaitez. 
* Puis cliquez sur valider. 

### Picking sur articles

Le picking sur article concerne les préparations qui ont une référence gérée par article.

Pour effectuer un picking sur référence, vous devez :

* Aller dans la fonctionnalité `Ordre`, puis `Préparation`. 
* Vous y retrouverez tous les ordres de préparations. 
* Cliquez sur la prépartion qui vous concerne. 
* Puis cliquez sur les trois boutons, puis séléctionner, pour ouvrir le formulaire de séléction d'article
* Choisissez les quantités des articles que vous voulez préparer sans dépasser la limite demandée dans la demande de livraison 
* Enfin pour finir la préparation, vous pouvez cliquez sur "Valider" en haut à droite de votre écran.  

### Picking partiel

Lors de l'exécution de vos ordres, il est possible que les pièces ne soient pas disponibles en stock. Il est possible de traiter un ordre partiellement, un picking partiel créera un deuxième ordre pour finaliser l'action plus tard. 

## Ordre de livraison

Les ordres de livraisons sont liés aux [demandes de livraison](webdemandes.md). Chaque demande, impliquera un ordre de préparation. Lors de la validation de la préparation. Un ordre de livraison sera créé et il permettra de relier l'emplacement de préparation à l'emplacement de livraison. 

Pour traiter un ordre de livraison, il faut cliquer celui que vous devait faire. 

Vous allez vous retrouver sur l'ordre de livraison. Vous y retoruverai les articles liés. Vous retrouverez les informations qui concerne votre livraison en haut de la page. 

- Numéro de votre livraison, 
- Statut, `traité` ou `à traiter`,
- Opérateur,
- Demandeur, 
- Point de livraison, 
- Date de livraison.

Dans le tableau en dessous, vous y retrouverai la liste des articles. Avec les informations suivantes : 

Informations | Description
------------ | -------------
- Référence | Qui concerne votre article, 
- Libellé |Il s'agit du nom donné, 
- Emplacement | Le lieu ou est l'article
- Quantité |La quantité disponible en stock

Pour voir son statut, vous pouvez cliquer sur les articles. 

Grace au bouton en haut à doirte vous pouvez faire afficher les actions suivantes : 

Actions | Description
------------ | -------------
Finir la livraion | Permet de valider la livraiosn
Supprimer | Pemret de supprimer l'ordre de livraison 
Lien vers la demande de livraion | Afin de pouvoir visualider la demande de livraion  
Lien vers l'ordre de préparation | Afin de pouvoir visualider l'ordre de préparation  

Pour finaliser l'ordre cliquez sur `Valider`. 

Vous pouvez retouver votre ordre, dans `ordre de livraion`. 

## Ordre de collecte

Un ordre de collecte est créé après une [demande de collecte](webdemandes.md). Il permet de traiter la demande, d'effectuer l'action. 

La page des ordres de collecte est constituée d'un tableau, de filtres et d'un bouton export CSV. 

Le tableau regroupe les colonnes suivantes :

Informations | Description
------------ | -------------
Numéro | Correspond à un numéro lier à la demande, permettant de lier l'ordre à la demande
Statut | Permet de voir si la collecte est `traité `ou `à traiter`
Date de création |Il s'agit de la date de création de l'ordre 	
Opérateur | Indique l'identité de la personne qui a traité l'ordre	
Type

Pour traiter la collecte, il faut cliquer sur la ligne de l'ordre à traiter qui vous aménera sur la page de l'ordre.
Vous trouverez le détail de la collecte en haut, avec les informations suivantes : 

- Statut
- Numéro de la collecte
- Demandeur
- Opérateur
- Date de collecte
- Point de collecte
- Destination
- Commentaire                                         
  

Vous trouvez aussi en bas la liste des articles/références liée à la demande sous forme de tableau. Vous y trouverez les informations suivantes :
* Référence	
* Libellé	
* Emplacement	
* Quantité	
* Actions, les actions permettent de modifier la quantité, de voir le détail de la référence, d'imprimer l'étiquette, et de valider la référence. 

Enfin pour traiter définitivement l'ordre, vous devez cliquer sur finir la collecte. 
Si la collecte doit être supprimée vous pouvez le faire grâce au bouton `supprimer`. 


## Ordre de réception

Quand vous venez de recevoir des colis, il faut ensuite les ajouter au stock. 
Pour cela vous pourrez utiliser la fonctionnalité : Réception. 
Celle-ci va vous permettre, de voir l'ensemble des réceptions que votre stock a enregistré.

La page est constituée d'un tableau : 

Informations | Description
------------ | -------------
Date de création de la réception | Permet de connaitre la date de création 
Date de fin | Permet de savoir quand la réception a été terminée 
Numéro de commande | Permet de voir si la réception est liée à un numéro de commande 
Fournisseur | Permet de voir le fournisseur
Numéro de réception | Permet de voir le numéro de réception 
Statut | Permet de voir si la réception est traitée ou non. Les deux statuts disponibles sont `en attente de réception` et `réception totale`
Commentaire | Possiblité de voir un commentaire laissé par le logisticien

De plus, un clic sur la ligne souhaitée permet de voir la réception en détail.

### Créer une réception

Pour créer une réception, cliquez sur le bouton, `nouvelle réception`, puis vous remplissez les champs dont vous avez besoin. 

Après avoir validé la création, vous arriverez dans le détail de la réception pour pouvoir y ajouter des pièces.

Pour les ajouter, il faut cliquer sur le bouton ajouter pièce. Si une ou plusieurs de vos pièces sont litigieuses, alors vous pouvez créer un litige associé à ces pièces.  Ensuite après avoir sélectionné une pièce, vous devrez cliquer sur le bouton réception, qui vous permettra de valider l'ajout d'une référence dans votre stock. 

Vous trouverez en haut de la page, les informations concernant votre réception 

* Numéro de réception
* Fournisseur
* Emplacement
* Date commande
* Numéro de commande
* Date de création 
* Date de fin d'une réception 
* Commentaire

Vous pouvez ensuite soit supprimer, modifier ou bien finir la réception grâce au bouton situé en haut à droite de votre écran. 

### Filtrer les réceptions

En haut de la liste de vos réceptions, vous trouverez tous les filtres. Vous pouvez combiner autant de filtres que vous souhaitez. Ensuite pour appliquer ces filtres, vous cliquez sur filtrer. 

Les filtres disponibles sont : 

Informations | Description
------------ | -------------
Date | Permet de sélectionner une période ou un jour précis dans vos filtres
Statut | Permet de sélectionner un statut précis 
Fournisseur |  Permet de sélectionner un fournisseur précis 
Urgent | Permet de sélectionner les réceptions urgentes

Pour activer les filtres, cliquez sur `Filtrer`