---
id: webdemandes
title: Les demandes de livraison / collecte / service
sidebar_label: Demandes
---



## Demandes

L'application Wiistock permet de générer des demandes de collectes, de livraisons et de manutention. Chaqu'une des demandes créées dans l'application génère à son tour des ordres. Ces ordres permettent de réaliser les actions demandées, les opérateurs pourront les traiter avec l'application mobile.  

## Demandes de collecte

La demande de collecte permet de rapatrier des articles de votre production ou magasin à votre stock ou de les détruire.
Les demandes sont crées sur l'application web. 
Les ordres peuvent être traités sur l'application web ou mobile. 

### Création d'une demande de collecte

1. Création de l'entête de demande de collecte

Sur le menu demande de collecte, cliquez sur le bouton `Nouvelle collecte`, cela ouvrira une fenêtre de création d'une entête de demande de collecte : 

Champs de création d'une demande de collecte | Description
------------ | -------------
Objet | Renseignez un intitulé pour la collecte
Point de collecte | Liste déroulante des emplacements existants, sélectionnez un emplacement de collecte
Destination | Mise en stock si vous souhaitez que l'article soit intégré à votre stock ou destruction pour indiqué que l'article est destiné à la destruction
Type | Sélectionnez le type de pièce dans la liste déroulante
Commentaire | Vous pouvez renseigner un commentaire

Enfin cliquez sur `Enregistrer`, vous serez redirigé vers l'écran de détail de la demande de collecte. 
Vous venez de créer une entête de demande de collecte.
La demande de collecte est désormais au statut "brouillon". 

Vous pouvez aussi accéder à cet écran de détail en cliquant sur le bouton oeil situé dans la colonne action de la liste des demandes de collecte. 

2. Ajout d'article à une demande de collecte 

Il s'agit d'ajouter un ou plusieurs articles à la demande de collecte créée. 

Pour cela cliquez sur le bouton `Ajouter article`, cela ouvrira une fenêtre vous permettant de sélectionner le code de la référence à ajouter. 

Suite au clique sur le bouton `Ajouter`, une fenêtre de détail de la référence s'ouvrira vous permettant de renseigner la quantité à collecter. 

Dans le cas où vous ne connaissez le code de la référence, vous pouvez cliquer sur le bouton `Chercher une référence`, cela vous redirigera vers le référentiel des articles de référence. 

Lorsque vous aurez ajouter les articles à votre demande, cliquez sur le bouton `Valider` . 

Suite à la validation de la demande de collecte, un ordre de collecte sera généré

La demande est désormais au statut "à traiter" et on ne peut plus la modifier ou la supprimer. 
Un bouton `Aller vers la collecte` apparait, en cliquant sur ce dernier, vous serez redirigé vers l'ordre de collecte. 

La demande passera au statut "collecté" ue fois que l'ordre associé sera traité. 


### Modification et suppression d'une demande de collecte

On peut modifier ou supprimer une demande de collecte uniquement lorsqu'elle est au statut "Brouillon". 

### Liste des demandes de collecte

Sur le menu demande de collecte vous trouverez la liste des demandes de collecte, regroupant l'ensemble des demandes créées. 
Vous pouvez inspecter le détail d'une collecte avec le bouton en forme d'oeil. 

Vous retrouverez l'historique des demandes de collecte sous forme de tableau. Vous y retrouverez : 
* L'action oeil permettant de visualiser le détail d'une demande de collecte
* La date de création
* Le demandeur de la collecte
* Son numéro
* L'objet
* Le statut 
* Le type

## Demandes de livraison

La demande de livraison permet :
* D'envoyer des articles de votre stock à vos clients.
* D'envoyer des articles de votre stock à votre production/magasin.

Pour créer une demande de livraion, cliquez sur 
* Demande
* Livraison
* Nouvelle livraison
* Remplissez formulaire de livraison  

Vous venez de créer une demande de livraison. Vous aller pouvoir retrouver l'ordre associé dans Ordre de préparation. 

## Demandes de service

La demande de service permet de générer une demande divers à une date attendue, par exemple cela peut être une demande de manutention d'un mobilier qui n'est pas présent dans votre stock.   

Pour créer une demande de service, cliquez sur 
* Demande 
* Demande de service
* Nouvelle demande
* Remplissez le formulaire de demande de service

Vous venez de créer une demande de service. Toute les demandes de service se trouve sur la même page.
Chaque demande est caractérisé par un statut selon l'état de traitement (traité ou à traiter) 

Une barre de filtre est présente en en-tête de page de chaque fonctionnalité, cela permet de filtrer la liste des occurences selon diffèrents critères (dates, statut, demandeurs...) 