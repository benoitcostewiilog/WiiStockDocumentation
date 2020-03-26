---
id: mobgeneralites
title: Mobile - Généralités
sidebar_label: Généralités
---

## Avant de commencer

L'application Mobile/Nomade va de pair avec l'application web. Elle permet d'effectuer toutes les opérations d'entrée/de transfert/de sortie de stock via un mobile Android.

L'application a été développée pour fonctionner avec les terminaux Zebra TC dans le but de simplifier les flash laser 1D/2D. Il en résulte un gain de productivité important.

L'application est découpée en 3 blocs fonctionnels

## Application de traçabilité 

La traçabilité des objets et des oppérations consiste à prendre des objets dans un emplacement, puis de les déposer dans un autre emplacement.

Ainsi il est possible de tracer l'opération effectuée par un opérateur dans le temps et dans l'espace.

Il est surtout possible de savoir où a été identifié pour la dernière fois un objet flashé.

**Note importante** : L'application a été développée pour permettre le flash de n'importe quel code barre. Il est donc possible de scanner des objets : colis/articles/produit/numéro de tracking transporteur/ numéro d'ordre de transfert / tout autre numéro. De cette manière la traçabilité peut s'effectuer sur tous les systèmes existants du moment où un code barre existe.


## Application de Stock / WMS

Le bloc fonctionnel de gestion de stock est plus restrictif. Il permet d'opérer les ordres d'entrée de stock / transfert de stock / sortie de stock : à travers les préparations et livraison. 

Les mouvements de stock sont restrictifs et permettent aux opérateurs de leur donner toutes les indications pour effectuer leur travail. 

*Note : L'application a été pensée pour fonctionner à 100% sur les mobiles. Si les opérateurs travaillent sur l'application web pour exécuter des ordres, il se peut que vous utilisiez mal l'application. *

Les chapitres suivants décrivent avec précision le fonctionnement de l'application mobile.

## Connexion

L'application est disponible sur l'hébergement Wiilog [Répertoire DL](http://wiilog.fr/dl) . Sur cette espace, l'application compilée pour Android est disponible en téléchargement en version de production et en version de recette.

Cliquez sur un fichier .apk pour la télécharger et l'installer sur votre mobile.

Une fois effectué démarrez l'application.

### Paramétrage de l'url de l'application

Au premier lancement, si l'application n'a jamais été installée elle vous propose de saisir l'url : 
- Url de l'instance.
    - Ex : https://XXXX.follow-gt.fr
    - Ex : https://XXXX.wiilog.fr
    - Ex : https://XXXX.votrenomdedomaine.fr

Une fois l'url saisie, l'application vérifie que votre version mobile correspond à la version de votre instance.

*Si ce n'est pas le cas, l'application vous redirige vers le téléchargement de la version mobile adéquate.*

L'application vous propose ensuite de vous authentifier.

### Authentification

L'application vous propose de vous authentifier en saisissant : 

Champ | Description
--------- | ----------
Login | Correspond au nom d'utilisateur de votre compte utilisateur
Mot de passe | Correspond au mot de passe de votre utilisateur

Une fois connecté et en fonction de vos droits, vous entrez sur le menu principal de l'application mobile.

### 3 principaux menus

#### Menu Traçabilité

Permet d'aller vers le sous menu de traçabilité permettant de :
- Faire une prise
- Faire une dépose

#### Menu Stock

Permet d'aller vers le sous menu de stock permettant de : 
- Faire un transfert
- Faire une préparation
- Faire une livraison
- Faire une collecte
- Faire un inventaire

#### Menu Demande de service

Permet d'accéder directement au traitement des demandes de services (manutention)

Le clique sur le bouton ouvre directement la liste des demandes `A traiter`

Il est ensuite possible d'entrer sur les demandes pour les compléter et les traiter.

