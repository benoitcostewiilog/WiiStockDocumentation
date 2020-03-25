---
id: parroles
title: Paramétrage des rôles
sidebar_label: Rôles
---

## Avant de commencer - le principe des rôles

Un rôles permet de donner accés au fonctionnalités de l'application. Un rôle permet de manière générale et consulter / modifier / supprimer ou exporter une données liée à une fonctionnalité.

L'application permet de créer un rôle qui pourra être affecté à un ou plusieurs utilisateurs de l'application 

- Les cas d'utilisation des rôles : 
    - Rôle super admin : Rôle utilisé par les administrateurs de l'application de l'équipe Wiilog ou 1 ou 2 personne de l'équipe portant la responsabilité de key user dans l'application. 
    - Rôle opérateur : Rôle utilisé par les opérateurs permettant d'effectuer toutes les actions et traitements opérationnels dans l'application
    - Rôle client : Rôle utilisé par les demandeur de stock ou encore client acheteur permettant d'effectuer des demandes, création d'urgence et consulter l'avancement des ordres


>La bonne pratique est de créer un rôle ne disposant d'aucunes fonctionnalités, puis de les ouvrir à la demande des utilisateurs. 

Les points suivants décrivent ce que permettent les paramétrages de rôle.

### Creer un Nouveau rôle

Depuis le menu `Paramétrage / Rôle` la liste des rôles s'ouvre. Cliquer sur le bouton `+ Nouveau rôle`, le formulaire s'ouvre.
 - Saisir le libellé du rôle : exemple : Super Admin

Puis effectuer le paramétrage suivant

## Les menus de paramétrage
### Menu Paramétrage
Paramètre | Description
------------ | -------------
afficher paramétrage global | Permet de donner accès au sous menu paramétrage global
afficher rôles | Permet de donner accès au sous menu rôle
afficher utilisateurs | Permet de donner accès au sous menu utilisateurs
afficher champs libres | Permet de donner accès au sous menu champs libres
afficher exports | Permet de donner accès au sous menu exports
afficher types | Permet de donner accès au sous menu types
afficher statuts litiges | Permet de donner accès au sous menu statuts litiges
afficher nature colis | Permet de donner accès au sous menu nature colis
afficher champs fixes | Permet de donner accès au sous menu champs fixes
modifier | Permet de donner les droits en modifications sur toutes les foncionnalités du menu paramétrage
supprimer | Permet de donner les droits en suppression sur toutes les fonctionnalités du menu paramétrage
afficher inventaires | Permet de donner accès au sous menu inventaire
afficher import et mise à jour | Permet de donner accès au sous menu import et mise à jour

### Menu Stock
Paramètre | Description
------------ | -------------
afficher articles | Permet de donner accès au sous menu articles 
afficher références | Permet de donner accès au sous menu références
afficher articles fournisseurs | Permet de donner accès au sous menu articles fournisseurs
afficher mouvements de stock | Permet de donner accès au sous menu mouvements de stock 
afficher alertes | Permet de donner accès au sous menu alertes
créer | Permet de donner les droits de création sur toutes les fonctionnalités du menu stock
modifier | Permet de donner les droits de modification sur toutes les fonctionnalités du menu stock
gestionnaire d'inventaire | Permet de donner les droits de traitement des anomalies d'inventaire sur le menu stock et l'application mobile
supprimer | Permet de donner les droits de suppression sur toutes les fonctionnalités du menu stock
exporter | Permet de donner les droits d'export sur toutes les fonctionnalités du menu stock

### Menu Référentiel

Paramètre | Description
------------ | -------------
afficher fournisseurs | Permet de donner accès au sous menu fournisseurs
afficher emplacements | Permet de donner accès au sous menu emplacements
afficher chauffeurs | Permet de donner accès au sous menu chauffeurs
afficher transporteurs | Permet de donner accès au sous menu transporteurs 
créer | Permet de donner les droits de création sur le menu référentiel
modifier | Permet de donner les droits de modification sur le menu référentiel
supprimer | Permet de donner les droits de suppression sur le menu référentiel


### Menu Accueil

Paramètre | Description
------------ | -------------
afficher indicateurs | Permet d'afficher ou non les tableau de bord et autres indicateurs présents sur l'accueil
afficher indicateur fiabilité monétaire | Permet d'afficher ou masquer le diagramme  de fiabilité monétaire présent sur le premier tableau de bord de l'accueil
afficher indicateur fiabililité par référence | Permet de consulter l'indicateur de fiabilité dans le menu + du premier tableau de bord

### Menu Traçabilité

Paramètre | Description
------------ | -------------
afficher arrivages | Permet de donner accès au sous menu flux. arrivages
afficher mouvements | Permet de donner accès au sous menu mouvements de traçabilités
afficher acheminements | Permet de donner accès au sous menu acheminements 
afficher associations BR | Permet de donner accès au sous menu acheminements
afficher encours | Permet de donner accès au sous menu encours
afficher urgences | Permet de donner accès au sous menu urgences
créer | Permet de donner les droits de création sur le menu traçabilité
modifier | Permet de donner les droits de modification sur le menu traçabilité
supprimer | Permet de donner les droits de modification sur le menu traçabilité
exporter | Permet de donner les droits d'export de données sur le menu traçabilité
lister tous les arrivages | Le droit d'affichage par défaut limite l'accès aux arrivages sur lesquel une utilisateur est positionné comme acheteur. Ce droit permet de rendre visible tous les arrivages de la base (même si votre utilisateur n'est pas acheteur).

### Menu Qualité
Paramètre | Description
------------ | -------------
afficher litiges | Permet de donner accès au sous menu litige
créer | Permet de donner les droits de création des litiges se trouvant sur un arrivage ou une réception 
modifier | Permet de donner les droits de modification des litiges se tranvant sur un arrivage ou une réception. Attention, le passage au statut traité n'est pas possible
supprimer | Permet de donner les droits de suppression des litiges se trouvant sur un arrivage ou une réception.
traiter les litiges | Permet à l'utilisateur de modifier le statut d'un litige sur un statut "traité", soit la clôture du litige

### Menu Demande

Paramètre | Description
------------ | -------------
afficher collectes | Permet de donner accès au sous menu collecte
afficher livraisons | Permet de donner accès au sous menu livraisons
afficher manutentions | Permet de donner accès au sous menu manutention (services)
créer | Permet de donner les droits de création sur tout le menu demande
modifier | Permet de donner les droits de modification sur tout le menu demande
supprimer | Permet de donner les droits de suppression sur tout le menu demande
exporter | Permet de donner les droits d'export sur tout le menu demande

### Menu Ordre
Paramètre | Description
------------ | -------------
afficher collectes | Permet de donner accès au sous menu collectes. Permet l'accès aux ordres de collectes depuis les demandes
afficher livraisons | Permet de donner accès au sous menu livraisons. Permet l'accès aux ordres de livraison depuis les ordres de préparations
afficher préparations | Permet de donners accès au sous menu préparations. Permet l'accès aux ordres de préparation depuis les demandes de livraison
afficher réceptions | Permet l'accès aux ordres de réceptions
création référence depuis réception | Permet à l'utilisateur d'afficher un formulaire rapide de création de référence depuis la réception
créer | Permet de donner les droits de création sur tout le menu ordre
modifier | Permet de donner les droits de modification sur tout le menu ordre
supprimer | Permet de donner les droits de suppression sur tout le menu ordre
exporter | Permet de donner les droits d'export sur tout le menu ordre
### Menu Nomade
Paramètre | Description
------------ | -------------
Accès stock | Permet d'accéder aux traitements liés au stock depuis l'application mobile / transfert / préparation / livraison / collecte / inventaire
Accès Traçabilité | Permet d'accéder aux traitements liés à la traçabilité depuis l'application mobile / Prise / Dépose.
Accès Demande | Permet d'accéder aux traitements liés au demandes de manutention et services depuis l'application mobile.

### Autre

#### Ajout quantité

`L'ajout quantité` permet de simplifier l'ajout d'une quantité sur une demande de livraison.

#### Libellé

Permet de donner un nom au rôle qui sera créé ou modifié.

L'étape suivante du paramétrage consiste à créer vos utilisateurs.