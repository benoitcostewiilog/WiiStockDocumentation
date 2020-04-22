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

La demande de collecte permet de déplacer des références articles du stock vers une destination donnée. 
Une demande de livraison créeras un ordre de préparation. 

Les demandes sont crées sur l'application web. 
Les ordres peuvent être traités sur l'application web ou mobile. 

La page est sous forme de tableau avec les informations suivantes : 

Champs du tableau | Description
------------ | -------------
Action | Permet de voir la demande en détail
Date | Permet de voir la date de création de la demande
Demandeur | Permet de voir le demandeur 
Numéro | Permet de voir le numéro de la demande de livraison
Statut | Permet de savoir si la demande est à traiter, livré ou brouillon. 
Type | Permet de caractériser la typologie d'article à livré. 

### Créer une nouvelle demande  

La demande de livraison permet :
* D'envoyer des articles de votre stock à vos clients.
* D'envoyer des articles de votre stock à votre production/magasin.

Pour créer une demande de livraion, cliquez sur `Nouvelle demande`. 

Une fois cette action faite, un formulaire s'ouvrira. Vous y retrouverez les champs suivants :

Champs du tableau | Description
------------ | -------------
Demandeur | Champs déjà rempli, qui permet de connaitre la personne qui fait la demande 
Déstination | Permet de définir la destination de la livraison
Type |
Commentaire | Champ non obligatoire, qui permet de Laisser un commentaire

Puis cliquez sur `enregistrer`. 

Après avoir fait cette action, vous retrouverez dans la demande de livraison. Vous y retrouverez en haut de votre écran : 

Champs | Description
------------ | -------------
Demandeur | Permet de connaitre la personne qui a fait la demande de livraison 
Statut | Permet de savoir si la demande est à traiter, livré ou brouillon
Destination | Permet de définir la destination de la livraison
Commentaire | Permet de savoir divers informations laissé par le demandeur
Date de demander | Permet de connaitre quand le demandeur a fait la demande 
Date de validation | Permet de savoir quand la demande a était faite
Type | Permet de lui attribuer un type afin de selectionner certain champ libre. 

En haut à droite de votre page, les boutons `Supprimer`, `Modifier` et `Valider`.  

En bas de votre écran, vous trouverez le tableau qui regroupera toutes les [références](webstocks.md) et [articles](mobstock.md) de la demande. Il est constitué des colonnes :

Champs | Description
------------ | -------------
Actions | Le bouton en forme d'oeil, permet de voir l'article/référence.Le bouton en forme de stylo, permet de modifier, et le bouton en forme de corbeille, permet de supprmier. 
Référence | Permet de connaitre la référence liée
Libellé | Nous donne l'information sur le libellé donné
Emplacement | Permet de savoir ou se trouve l'emplacement des articles/références
Quantité disponible | Permet de conaitre la quantité disponible sur l'artcile/référence 
Quantité à prélever | Permet de savoir combien de référence/article sont à prélever

Pour rechercher une référence cliquez sur `chercher une référence`. Après cela, une liste de toutes les références appartenant à votre base de données apparaîtra. 

Cliquez sur le bouton `plus` pour ajouter cette référence à votre demande de livraison. Une page va s'ouvrir, et vous proposera de choisir une `livraison` ou une `collecte`. 

Cliquez sur `livraison`. Il vous faudra choisir la demande de livraison lié à cet ajout de référence. Puis d'autres champs vont s’afficher, il vous faudra les remplir : 

- Quantité à livrer
- Référence 
- Nom 
- Type 
- Emplacement

Vous cliquerez sur `ajouter`, cela permettra d'ajouter votre référence, mais de continuer sur la liste des références pour pouvoir en sélectionner d'autres.

Vous pouvez aussi cliquer sur `ajouter`. 
Ce qui vous fera retourner à votre demande. 

Pour ajouter un article cliquez sur `ajouter un article`, puis sélectionnez son nom dans le libellé référence. 

Sélectionnez les champs à remplir : 

- Quantité 
- Référence 
- Nom 
- Type
- Emplacement 

Cliquez sur `ajouter`. 

Enfin pour finaliser la création de la demande cliquez sur `valider`. Vous retrouverai votre demande dans la liste. De plus un [ordre de livraison](webordres.md) sera créé, lié à votre demande. 


## Demandes de manutention

La demande de manutention permet de générer une demande divers à une date attendue, par exemple cela peut être une demande de manutention d'un mobilier qui n'est pas présent dans votre stock.   

### Création d'une demande de manutention

Sur le menu demande de manuentention, cliquez sur le bouton `Nouvelle demande`, cela ouvrira un formulaire de création d'une nouvelle demande de manutention, vous devrez alors le remplir. Ci dessous la description des champs du formulaire de création :  

Champs de création d'une demande de manutention | Description
------------ | -------------
Objet | Renseignez un intitulé carartérisant la manutention
Demandeur| Indique le nom d'utilisateur du demandeur, ce champ est pré-rempli en fonction de l'utilisateur connecté sur l'application
Chargement | Emplacement de chargement de la manutention (peut être un emplacement non existant dans le référentiel)
Déchargement | Emplacement de déchargement de la manutention (peut être un emplacement non existant dans le référentiel)
Date attendue | Renseignez la date et l'heure souhaitée 
Commentaire | Vous pouvez remplir un commentaire au choix

Enfin cliquez sur `Enregistrer`, vous venez de créer une demande de manutention au statut "à traiter".

Toutes les demandes de service se trouve sur la même page.
Chaque demande est caractérisé par un statut selon l'état de traitement (traité ou à traiter). 

### Modification, traitement et suppression d'une demande de manutention

Afin de traiter une demande de manuentention, il faut d'abord cliquer sur le bouton crayon pour accèder à la fenêtre de modification, suite à cela vous pourrez modifier le statut de "à traiter" vers "traité" et renseigner la date de réalisation. 

Il est possible de modifier une demande de manutention au statut "à traiter" ou "traité". 

Il est possible de supprimer une demande de manutention uniquement au statut "à traiter"