---
id: mobstock
title: Transfert de stock
sidebar_label: Stock
---

## Avant de commencer

Les opérations liés aux stock sont essentielles au block fonctionnel de stock. Elles permettent aux opérateurs d'effectuer tous les traitements d'entrée et sortie de stock sans se retrouver "Devant l'ordinateur" et ainsi permet une grande autonomie sur le terrain.

Les grandes fonctionnalités sont les suivantes
- Transfert de stock
- Préparation
- Livraison
- Collecte
- Inventaire

Ces fonctionnalités sont décrites ci-après.

## Transfert de stock

> Le transfert de stock permet de modifier l'adressage d'un article ou d'une référence suivant sa gestion Quantité. Il n'est pas possible décontitionner un article depuis l'application mobile.

La fonctionnalité de transfert de stock reprend le principe de prise et dépose. Il est ainsi possible de prendre 1 ou plusieurs références/articles d'un emplacement, puis de les déposer sur les emplacements au choix.

Depuis le menu `Stock` de l'application Mobile, tapper sur le menu `transfert`, l'application vous propose d'effectuer une prise ou une dépose. L'application vous indique aussi le nombre de produit[article ou référence] actuellement en prise.

1. Prise - Sélection de l'emplacement : Une fois dans la prise, l'application vous propose de: 
- Soit flasher l'emplacement de prise via le flahs intégré des Zebra TC
- Soit de flasher l'emplacement de prise via l'appareil photo du téléphone
- Soit de sélectionner un emplacement de prise via la loupe

2. Prise - Flash du produi : Vous pouvez ensuite soit
- Flasher le produit avec le flash intégré ou via l'appareil photo de votre mobile.
>Si vous flashez une référence qui ne doit pas se trouver sur cet emplacement, un message d'erreur s'affiche sur votre application, cela permet de bloquer les mauvaises utilisations

3. Prise - Valider la prise : 
- Toucher le bouton vert une fois votre produit scannés, la prise est terminée.

Les produits sont à présent sur vous et aucun mouvement de stock n'est encore créé dans l'application.

Pour terminer un mouvement, vous devez effectuer la dépose des produits en prise.
1. Dépose - Sélection de l'emplacement.
- Flasher l'emplacement sur lequel vous souhaitez déposer les produits en prise
2. Dépose - Sélection des produits à déposer : 
- l'application vous affiche les produits [références ou articles] étant en prise.

> Il n'est pas possible de flasher un produit n'étant pas en prise.
3. Dépose - Valider la dépose : 
- Toucher le bouton vert une fois vos produits en prise scannés.
La dépose est terminée.

A ce moment, l'application créé un mouvement de transfert pour tracer le changement d'un adressage sur un produit par un opérateur sans changement de quantitité.

2 mouvements de traçabilité sont aussi créés.
Le mouvemnt de stock est donc composé d'une mouvement de traçabilité de type prise et d'un mouvement de traçabilité de type dépose horodatés.


## Préparation

Les ordres de préparation sont générés à la validation d'une demande de validation.

L'ordre de préparation indique à un opérateur qu'il doit effectuer une préparation liée à une demande de livraison. l'opérateur peut donc effectuer la préparation avec le mobile.

Il existe plusieurs types de préparations : 
Type | Description
---------- | -----------
Préparation total sur référence | Le consommable n'a pas exemple pas besoin d'une traçabilité rapprochée. Dans ce cas, le type de gestion quantité se fait à la référence. Si tout le stock est demandé en livraison, l'opérateur pourra se diriger dans le stock et flasher les étiquettes puis valider la préparation
Préparation partielle sur référence | Toujours avec l'exemple du consommable en type de gestion quantité par référence, un demandeur demande une quantité partielle. Cette fois-ci **il sera important d'imprimer les etiquettes de références sur l'application web avant d'opérer sur le mobile**. Une fois avoir imprimé les etiquettes depuis l'ordre de préparation web, l'opérateur peut effectuer son prélèvement partiel de quantité sur référence puis valider sa préparation.
Préparation de qte globale sur articles sans prélèvements | Ce cas est très rare mais peut arrivé, dans ce cas le picking des articles peut se faire depuis l'application Nomade, il n'y pas d'impression d'étiquettes supplémentaires
Préparation de qte globale sur articles avec prélèvements partiels | **Il sera important d'effectuer le picking depuis l'application web et d'imprimer les etiquettes** avant de passer sur les opérations mobiles. 
Préparation d'article avec prélèvement partiel | **Il sera important d'effectuer le picking depuis l'application web et d'imprimer les etiquettes** avant de passer sur les opérations mobiles
Préparation d'article | Dans ce cas, l'opérateur peut aller directement dans le stock pour effectuer l'opération de préparation

### Processus de préparation mobile

>Note : L'utilisateur doit disposer des droits pour traiter les types de demandes et accéder au menu de stock

1. Depuis le menu stock, cliquer sur le bouton des préparations, la liste des préparations s'affiche.
- On dans la liste des préparations l'emplacement de livraison cible, le type de demande de livraison ainsi sur l'identifiant de la préparation

2. Tapper sur une préparation pour entrer dedans et la traiter
- On retrouve plusieurs informations d'entête qu'on retrouvait précédement sur la liste des préparation.
- On retrouve la liste des produits à prélever pour valider la préparation.

    1. 

## Livraison

## Collecte

## Inventaire
