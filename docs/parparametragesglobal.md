---
id: parparametragesglobal
title: Paramétrage global
sidebar_label: Paramétrage global
---

## Avant de commencer

La paramétrage global est important d'être revu lors du démarrage sur l'application. Ce paramétrage permet de personnaliser l'application et ses fonctionnalités pour qu'elles puissent fonctionner suivant votre besoin.

Ces paramétrages ne sont pas des données en tant que tel. Il convient donc de les reporter sur vos environnent de recette et environnement de production pour retrouver le même comportement de l'application

>Note : Certains paramétrages s'enregistrent lors de leur modifications, d'autres s'enregistrent au clique sur un bouton check vert.

## Paramétrage global

### Configuration des etiquettes

La configuration des etiquettes est commune aux etiquettes de traçabilité, de stock et d'emplacement.

Paramètre | Description
------------ | -------------
Hauteur mm | spécifie la hauteur en milimetre de l'etiquette (entier)
Largeur mm | spécifie la largeur en milimetre de l'étiquette (entier)
Champ libre présent sur etiquette | Permet d'ajouter un champ libré lié à un type de référence sur une etiquette d'article. Sert par exemple pour ajouter un part number ou bon de livraison à réception d'article
Champ libre sur etiquette | A définir
Type d'étiquette | Permet de spécifier le type de code barré généré sur les etiquettes. 2 choix possibles : QR Code [2D] ou CODE128 [1D]
Logo | Permet de charger une image de type .png ou .jpg qui sera superposée en haut à gauche de toutes les etiquettes générées


### Configuration des exports CSV

- Encodage des exports CSV.
Permet de choisir entre l'encodage : 1252 Europe de l'ouest Windows (Encodage compris par défaut par Excel version Française) ou UTF-8 (Encodage compris par le reste du monde)

Ce choix permet de limiter les effets d'accents "hiéroglyphe"

### Préfixage des nom de demandes

- Type de demande : Demande de livraison
Permet de choisir un préfixe demande les code de demande générés. 
    ex : DL => pour demande de livraison / CDE pour commande / Autres suivant besoin


### Configuration du serveur mail

La configuration du serveur mail permet de renseigner les paramètres SMTP pour tous les envois des mails.

>Pour toutes les instances Follow-GT, merci de demander à Wiilog son paramétrage.

Le paramétrage comporte les champs suivants : 
- Adresse du serveur SMTP
- Nom d'utilisateur
- Mot de passe
- Port => A préciser à Wiilog si autre que 587 ou 25 pour ouverture du firewall sur l'infrasctructure
- Protocole
- Nom de l'expéditeur
- Adresse email de l'expéditeur

Une fois le paramétrage compléter, merci de valider avec le bouton check vert.


### Paramétrage réceptions

Paramètre | Description
------------ | -------------
Créer une demande de livraison après réception | Permet d'ajouter automatiquement les articles générés et réceptionnés dans une nouvelle demande de livraison lors de la réception d'un conditionnement. Ne fonctionne pas avec la réception de quantité sur référence.
Créer une préparation après demande de livraison | Permet de limiter la création automatique d'une préparation lors de la validation d'une demande de livraison
Statut litige par défaut | Permet de spécifier le statut d'un litige lors de sa création sur une réception
Emplacement de réception par défaut | Permet de choisir l'emplacement vers lequel une mouvement de stock va être créé initialement

Il est ensuite possible de modifier les libellés des statuts de réceptions pour collecter au vocabulaire de votre supply.
1. En attente de réception
2. Réception partielle
3. Réception totale
4. Anomalie

Cliquer sur le bouton check vert pour valider la personalisation des libellés


### Paramétrage arrivage

Paramètre | Description
------------ | -------------
Redirection vers l'arrivage créé | Permet de rediriger l'utilisateur vers le détail de l'arrivage une fois l'arrivage créé
Impression cochée par défaut | Permet l'impression systématique des etiquettes pdf colis d'arrivage
Envoyer un mail après nouvel arrivage | Permet l'envoi systématique d'un mail aux acheteurs renseignés dans l'arrivage
Statut arrivage par défaut | Permet choisir le statut par défaut lors de la création d'une arrivage
Staut litige par défaut | Permet de choisir le statut par défaut lors de la création d'un litige sur arrivage


### Paramétrage des heures travaillées

Le paramétrage des heures travaillées joue sur le calculs des en-cours et délais sur emplacement.

Ainsi le délais positionné sur les emplacements ser en heures ouvrés en fonction de ces plages horaires.

2 plages horaires sont à paramétrer par jours.
- 1 plage horaire le matin
- 1 plage horaire l'après midi

Ceci pour les 7 jours de la semaine

### Personnalisation des libellés

La personnalisation des libellés ou aussi appelé module de traduction permet d'appliquer le vocabulaire utilisé par votre supply dans l'application sur les fonctionnalités suivantes : 

- Traçabilité / Arrivages
- Traçabilité / Urgences
- Stock / Ordre de réceptions

Pour détecter les libellés qui peuvent être renommé, il vous suffit de laisser quelques secondes votre pointeur de souris sur un libellé.

Si le libellé peut être renommé, un `tooltip` s'affiche comportant la clé de traduction que vous retrouverez dans ce menu.

### Configuration tableaux de bord

La configuration des tableau de bord est principalement faite pour les tableaux de bords suivants : 

1. Réception à quai
2. Réception administrative

Ces tableau de bord ont été réalisés pour les flux d'arrivages pour un site de Safran. Ces tableaux sont utilisables dans l'application ou en lien externe pour une utilisation sur écran sur quai d'entrepot.

Voici les prinipaux diagrammes et indicateurs paramétrables : 

#### Réception à quai

Paramètre | Description
------------ | -------------
Suivi des transporteurs | Permet de sélectionner les transporteurs en affichage. Si des arrivages existent le jour J avec un transporteur présent dans cette liste, alors le transporteur est affiché dans la liste du dashboard
Emplacements colis restant à traiter | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)
Emplacements colis en attente dédouanement | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)
Emplacement colis dédouanés et dispo | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)
Emplacement colis à déposer en DropZones | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)

Le bouton Dashboard réceptioni quai permet d'ouvrir le chemin chiffré vers le dashboard sans authentifications pour affichage sur écran temps réel.

#### Réception administrative

Paramètre | Description
------------ | -------------
Nature de colis 1er graphe | Permet de préciser 1 nature de colis a surveiller sur le premier graphe.
Natures de colis 2eme graphe | Permet de préciser 1 ou plusieurs natures de colis àsurveiller sur le deuxième graphe
Emplacement Urgence restant à traiter | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)
Emplacement Lignes en litiges | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)
Emplacement Colis en attente de dédouament | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)
Emplacement entrées à effectuer 1er graphe | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements) - Limité aux natures de colis paramétré plus haut
Emplacement entrées à effectuer 2eme graphe | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements) - Limité aux natures de colis paramétré plus haut

Toutes les statistiques sont basées sur les mouvements de traçabilités.

### Apparence du site

- Choix de la police du site : Permet de choisir la police de l'application pour la faire correspondre à la charte graphique de l'entreprise : Myriad / Montserrat / Tahoma 

### Paramétrage mouvements traça

- Vider et rester sur la modate de création de mouvement : Ce comportement permet une saisie en rafale des mouvements de traçabilité côté web. L'utilisateu n'a ainsi pas besoin de cliquer sur nouveau mouvement.

## Types

Une type est un regroupement ou une identification d'une entitée/catégorie principale de l'application.

Un type peut être visible (ex: sur les références) et permet d'activer le système de champ libre ou peut être invisible et sert uniquement de conteneur de champ libre (ex sur les arrivages et réceptions)

Un type peut identifié sur les entitées suivantes : 
- Articles : Pour typer les références et activer les champs libres en fonction. Pour activer les champs libres sur les articles liés aux types de références
- Réceptions : Pour activer les champs libres sur les réceptions (pas de typage en soit)
- Litige : Pour le typage des litiges
- Demande de livraison : Pour typer les demandes de livraisons et activer les champs libres
- Demandes de collecter : Pour typer les demandes de collecte et activer les champs libres
- Arrivage : Pour typer les arrivages et activer les champs libres

cliquer sur le bouton 

## Champs libres

Une application de gestion de stock et flux logistiques en entrepots pour facliter le métier des logisticiens/magazinier opérateurs en entrepotsqsdfqsdf

## Export des données

Une application de gestion de stock et flux logistiques en entrepots pour facliter le métier des logisticiens/magazinier opérateurs en entrepotsqsdfqsdf

## Inventaires

Une application de gestion de stock et flux logistiques en entrepots pour facliter le métier des logisticiens/magazinier opérateurs en entrepotsqsdfqsdf



## Status litiges

Une application de gestion de stock et flux logistiques en entrepots pour facliter le métier des logisticiens/magazinier opérateurs en entrepotsqsdfqsdf

## Nature des colis

Une application de gestion de stock et flux logistiques en entrepots pour facliter le métier des logisticiens/magazinier opérateurs en entrepotsqsdfqsdf

## Champ fixes

Une application de gestion de stock et flux logistiques en entrepots pour facliter le métier des logisticiens/magazinier opérateurs en entrepotsqsdfqsdf

## Import et mise à jour

Une application de gestion de stock et flux logistiques en entrepots pour facliter le métier des logisticiens/magazinier opérateurs en entrepotsqsdfqsdf
