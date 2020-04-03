---
id: webstocks
title: Visualisation et actions sur le stock
sidebar_label: Stock
---


## Références

La fonctionnalité référence permet de regrouper dans un tableau toutes les références concernant votre base de données. 

Cet outil se trouve dans le module stock, références. 

Vous y trouverez un tableau regroupant vos références, avec les champs suivants :  

Champ | Description
------------ | -------------
 Actions | Permet de modifier une référence grâce au bouton en forme de stylo, de la supprimer grâce au bouton corbeille, de voir les (mouvements de stock)[webordres.md] liée à cette référence et le bouton plus pour ajouter une référence (demande de collecte de livraison.)[webtracabilites.md] 
 Libellé | Correspond au nom que vous avez donné à votre référence. 
 Référence| Correspond à la référence donné. 
 Type | Permet de catégoriser vos références
 Statut | Permet de voir si votre référence est actif ou inactif.
 Quantité disponible | Correspond au qantité liée à votre référence.
 Emplacement | Correspond à l'emplacement où se trouve la référence.  

Afin d'imprimer les références, un bouton `Imprimer les étiquettes` est utilisable. Cella permettera d'imprimer des étiquettes de référence. Ce bouton est utilisable uniquement lorsque des filtres ont été affectés aux références. 

Vous pouvez créer manuellement une référence grâce au bouton `nouvel article de référence`. Après avoir effectué cette action, il vous faudra remplir les champs obligatoires : 

Champ | Description
------------ | -------------
Référence | Ce champ correpond à la référence que vous souhaitez créer. 
Nom | Il s'agit du nom que vous souhaitez attribuer à cette référence. 
Emplacement | Correponds à l'emplacement où se trouve votre référence. 
Type | Liste déroulente permettant de séléctionner le type lorsqu'une référence est gérée par référence. Selon le type séléctionné, certain champ libre s'afficheront.  
Quantité | La quantité affilié à cette référence.

De plus vous allez devoir sélectionner la gestion de quantité par référence OU par article

- Gestion de référence par article, 
- Gestion de référence par référence, 

Pour finaliser la création cliquez sur enregistrer. 

## Articles

La fonctionnalité article permet de regrouper tous les articles de votre base de données sur un seul tableau points.
Cet outil se trouve dans le module stock, article. 

Le tableau affichera les champs suivants :  

Champ | Description
------------ | -------------
 Actions | Permet de modifier une référence grâce au bouton en forme de stylo, de la supprimer grâce au bouton corbeille et d’imprimer l’étiquette de l’article. 
 Libellé | Correspond au nom que vous avez donné à votre référence. 
 Référence| Correspond à la référence de votre article. 
 Statut | Permet de voir si votre référence est actif ou inactif.
 Quantité disponible | Correspond au qantité liée à votre article.
 Emplacement | Correspond à l'emplacement où se trouve l’article.  

Afin d'imprimer les références, un bouton `Imprimer les étiquettes` est utilisable. Cella permettera d'imprimer des étiquettes d’article. Ce bouton est utilisable uniquement lorsque des filtres ont été affectés aux références. 

Vous pouvez créer manuellement une référence grâce au bouton `nouvel article de`. Après avoir effectué cette action, il vous faudra sélectionner une référence correspondante.  

(Référence gérée par article)[webstock.md] : 

Action | Description
------------ | -------------
Choisissez une référence | Cela permet d'attribuer une référence à votre article. 
Choisissez un fournisseur | Il s'agit du nom que vous souhaitez attribuer à cette référence. 
Puis remplissez les champs obligatoire. 
- Référence fournisseur
- Libellé*
- Quantité*
- Emplacement* 

Pour finaliser la création cliquez sur enregistrer.

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

Cette fonctionnalité permet de voir tous les inventaires qui ont une quantité saisit sur leur référence ou articles qui n'est pas la même qu'attendu. Les anomalies sont essuite traité par les logisticiens grâce a l'appliaction mobile. 

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