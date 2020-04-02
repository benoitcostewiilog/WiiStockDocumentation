---
id: webstocks
title: Visualisation et actions sur le stock
sidebar_label: Stock
---


## Références

Il s'agit des références de vos articles, produits,... que vous pouvez importer ou créer manuellement, en cliquant sur le bouton "Nouvel article de référence". Puis vous pouvez remplir le formulaire de création. 
Vous pouvez aussi modifier ou supprimer votre référence. 

Vous y retrouverez aussi toutes vos références. 

## Articles

Il s'agit de la liste des articles qui constitue votre stock. Vous pouvez importer une liste, ou bien créer à la main un article. Pour cela cliquez sur "Nouvelle article" et attribuez à cette article une référence. Enfin vous pourrez finaliser la création de l'article. 

Enfin vous pouvez imprimer l'étiquette de l'article. Vous pouvez aussi modifier ou supprimer l'article. 
Vous pouvez aussi choisir les colonnes visibles sur la liste des articles.  

## Articles fournisseur

Il s'agit de la liste des articles fournisseur. 
Lors d'une réception cela permet d'identifier d'une manière unique la référence article fournisseur réceptionnée. En effet un article de référence peut être liée à plusieurs fournisseurs, et pourrait donc avoir des codes de référence fournisseur diffèrents selon le ou les fournisseurs auquels il est lié. 

### Création d'un article fournisseur

Champs à renseigner | Description
------------ | -------------
Code fournisseur | Permet de sélectionner le code d'un fournisseur déjà existant dans le référentiel
Article de référence | Permet de sélectionner le code d'un article de référence déjà existant dans le référentiel
Référence | Permet de renseigner le code de l'article-fournisseur souhaité 

## Mouvement de stock

La fonctionnalité mouvement de stock, regroupe tous les mouvements de livraisons, de collectes et réceptions. Vous y retrouverez la date du mouvement, l'origine du mouvement, la référence, la quantité, l'opérateur de l'action, la destination et son type.

## Inventaire

La fonctionnalité inventaire, permet de créer un inventaire, avec les articles et références que vous souhaitez inventorier. 
Cela crée une mission, qui est effectuée par un logisticien sur site avec (l'application mobile) [mobstock.md]

Pour vous rendre sur #inventaire#, cliquez sur #stock#, puis sur #inventaire#. Après cette action, une page va s'ouvrir. Elle regroupera des filtres en haut de votre écran, afin d'affiner vos recherche. En dessous vous pourrez voir le tableau de tous les inventaires créés, avec la possibilité de voir, où de supprimer une mission. 

Enfin vous voyez juste au-dessus du tableau 3 boutons : 

-	Nouvelle mission,. 
-	Voir les saisies, 
-	Gérer les anomalies. 


1.	Nouvelle mission : 

Pour créer un inventaire, cliquez sur le bouton nouvelle mission. Un formulaire s'ouvrira et vous demandera de renseigner la date de début et la date de fin. Puis cliquez sur enregistrer. 

Vous venez de créer votre mission, il va falloir maintenant lui ajouter des articles ou des références. Pour cela cliquez sur le bouton en forme de d'oeil au niveau de l'inventaire. 

Une fois cette action faites, vous vous retrouverez sur la page qui concerne l'inventaire. Vous retrouverez les mêmes filtres en haut de l'écran mais aussi le bouton « Exporter au format csv ». Pour ajouter une référence ou un article cliquez sur « ajouter des références ou des articles ». Puis sélectionnez les articles ou les références que vous souhaitez en utilisant les barre de recherche. Après l'ajout de vos références ou de vos articles cliquez sur enregistrer. 

Enfin pour quitter cette page cliquer sur retour à la liste en bas à gauche. Vous venez de créer une mission d'inventaire qui sera visible par vos logisticiens. 

2.	Voir les saisies : 

Il s’agit d’une liste de tous les inventaires réalisés pour chaque article et références. 

3.	Gérer les anomalies :  

Cette fonctionnalité permet de voir tous les inventaires qui ont une quantité saisit sur leur référence ou articles qui n'est pas la même qu'attendu.

Il est possible de créer des fréquences d'inventaire, dans les (paramétrage global)[parametragesglobal.md]. 

## Alerte

Les alertes sont attribuées à des références. Il existe deux types de seuil de quantité minimum : 
* Seuil d'alerte
* Seuil de sécurité

Lorsque la quantité disponible de la référence sera inférieur au seuil d'alerte ou au seuil de sécurité cela générera une alerte. 

Ces seuils sont paramétrables dans le sous menu référentiel, cliquez sur le bouton crayon situé sur la ligne d'un référence puis renseignez le champ seuil d'alerte ou le champ seuil de sécurité. 

Sur le sous menu Alerte, vous pouvez visualiser la liste des alertes par référence : 

Champs liste des alertes | Description
------------ | -------------
Libellé | Indique le libellé de la référence
Article de référence | Indique le code référence
Quantité  | Indique la quantité en stock de la référence
Type quantité | Référence ou Article
Type | Type de la référence
Date d'alerte |
Seuil d'alerte |
Seuil de sécurité |
Alerte |