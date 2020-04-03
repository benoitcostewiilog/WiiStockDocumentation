---
id: parparametragesglobal
title: Paramétrage global
sidebar_label: Paramétrage global
---

## Avant de commencer

La paramétrage global est important d'être revu lors du démarrage sur l'application. Ce paramétrage permet de personnaliser l'application et ses fonctionnalités pour qu'elles puissent fonctionner suivant votre besoin.

Ces paramétrages ne sont pas des données en tant que tels. Il convient donc de les reporter sur vos environnements de recette et environnements de production pour retrouver le même comportement de l'application

>Note : Certains paramétrages s'enregistrent lors de leur modification, d'autres s'enregistrent au clique sur un bouton check vert.

## Paramétrage global

### Configuration des étiquettes

La configuration des étiquettes est commune aux étiquettes de traçabilité, de stock et d'emplacement.

Paramètre | Description
------------ | -------------
Hauteur mm | spécifie la hauteur en milimètre de l'étiquette (entier)
Largeur mm | spécifie la largeur en milimètre de l'étiquette (entier)
Champ libre présent sur étiquette | Permet d'ajouter un champ libre lié à un type de référence sur une étiquette d'article. Sert par exemple pour ajouter un part number ou bon de livraison à réception d'article
Champ libre sur étiquette | A définir
Type d'étiquette | Permet de spécifier le type de code barre généré sur les étiquettes. 2 choix possibles : QR Code [2D] ou CODE128 [1D]
Logo | Permet de charger une image de type .png ou .jpg qui sera superposée en haut à gauche de toutes les étiquettes générées. 


### Configuration des exports CSV

- Encodage des exports CSV.
Permet de choisir entre l'encodage : 1252 Europe de l'ouest Windows (Encodage compris par défaut par Excel version Française) ou UTF-8 (Encodage compris par le reste du monde)

Ce choix permet de limiter les effets d'accents "hiéroglyphe"

### Préfixage des nom de demandes

- Type de demande : Demande de livraison
Permet de choisir un préfixe des codes de demande générés. 
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

### Configuration demande de livraison

Paramètre | Description
------------ | -------------
Créer une demande de livraison après réception | Permet d'ajouter automatiquement les articles générés et réceptionnés dans une nouvelle demande de livraison lors de la réception d'un conditionnement. Ne fonctionne pas avec la réception de quantité sur référence.
Créer une préparation après demande de livraison | Permet de limiter la création automatique d'une préparation lors de la validation d'une demande de livraison
Emplacement de livraison par défaut | Permet d'indiquer un emplacement par défaut, cela permettra de pré-remplir le champ destination de livraison par un emplacement de livraison par défaut 


### Paramétrage réceptions

Paramètre | Description
------------ | -------------
Statut litige par défaut | Permet de spécifier le statut d'un litige lors de sa création sur une réception
Emplacement de réception par défaut | Permet de choisir l'emplacement vers lequel un mouvement de stock va être créé initialement

Il est ensuite possible de modifier les libellés des statuts de réceptions pour qu'ils correspondent à votre vocabulaire. 
1. En attente de réception
2. Réception partielle
3. Réception totale
4. Anomalie

Cliquer sur le bouton check vert pour valider la personnalisation des libellés


### Paramétrage arrivage

Paramètre | Description
------------ | -------------
Redirection vers l'arrivage créé | Permet de rediriger l'utilisateur vers le détail de l'arrivage une fois l'arrivage créé
Impression cochée par défaut | Permet l'impression systématique des étiquettes pdf colis d'arrivage
Envoyer un mail après nouvel arrivage | Permet l'envoi systématique d'un mail aux acheteurs renseignés dans l'arrivage
Statut arrivage par défaut | Permet choisir le statut par défaut lors de la création d'une arrivage
Staut litige par défaut | Permet de choisir le statut par défaut lors de la création d'un litige sur arrivage


### Paramétrage des heures travaillées

Le paramétrage des heures travaillées joue sur le calcul des en-cours et délais sur emplacement.

Ainsi le délais positionné sur les emplacements sera en heures ouvrées en fonction de ces plages horaires.

2 plages horaires sont à paramétrer par jours.
- 1 plage horaire le matin
- 1 plage horaire l'après midi

Ceci pour les 7 jours de la semaine

### Personnalisation des libellés

La personnalisation des libellés ou aussi appelée module de traduction permet d'appliquer le vocabulaire utilisé par votre supply dans l'application sur les fonctionnalités suivantes : 

- Traçabilité / Arrivages
- Traçabilité / Urgences
- Stock / Ordre de réceptions

Pour détecter les libellés qui peuvent être renommés, il vous suffit de laisser quelques secondes votre pointeur de souris sur un libellé.

Si le libellé peut être renommé, un `tooltip` s'affiche comportant la clé de traduction que vous retrouverez dans ce menu.

### Configuration tableaux de bord

La configuration des tableau de bord est principalement faite pour les tableaux de bords suivants : 

1. Réception à quai
2. Réception administrative

Ces tableau de bord ont été réalisés pour les flux d'arrivages pour un site de Safran. Ces tableaux sont utilisables dans l'application ou en lien externe, en l'occurence pour une utilisation sur écran d'affichage sur quai d'entrepôt.

Voici les principaux diagrammes et indicateurs paramétrables : 

#### Réception à quai

Paramètre | Description
------------ | -------------
Suivi des transporteurs | Permet de sélectionner les transporteurs en affichage. Si des arrivages existent le jour J avec un transporteur présent dans cette liste, alors le transporteur est affiché dans la liste du dashboard
Emplacements colis restant à traiter | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)
Emplacements colis en attente dédouanement | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)
Emplacement colis dédouanés et dispo | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)
Emplacement colis à déposer en DropZones | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'une colis sur ces emplacements)

Le bouton Dashboard réception quai permet d'ouvrir le chemin chiffré vers le dashboard sans authentification pour affichage sur écran en temps réel.

#### Réception administrative

Paramètre | Description
------------ | -------------
Nature de colis 1er graphe | Permet de préciser 1 nature de colis à surveiller sur le premier graphe.
Natures de colis 2eme graphe | Permet de préciser 1 ou plusieurs natures de colis à surveiller sur le deuxième graphe
Emplacement Urgence restant à traiter | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'un colis sur ces emplacements)
Emplacement Lignes en litiges | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'un colis sur ces emplacements)
Emplacement Colis en attente de dédouament | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'un colis sur ces emplacements)
Emplacement entrées à effectuer 1er graphe | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'un colis sur ces emplacements) - Limité aux natures de colis paramétré plus haut
Emplacement entrées à effectuer 2eme graphe | Permet de voir le nombre de colis restant sur les emplacements paramétrés (dernier mouvement de dépose d'un colis sur ces emplacements) - Limité aux natures de colis paramétré plus haut

Toutes les statistiques sont basées sur les mouvements de traçabilités.

### Apparence du site

- Choix de la police du site : Permet de choisir la police de l'application pour la faire correspondre à la charte graphique de l'entreprise : Myriad / Montserrat / Tahoma 

### Paramétrage mouvements traça

- Vider et rester sur la modale de création de mouvement : Ce comportement permet une saisie en rafale des mouvements de traçabilité côté web. L'utilisateur n'a ainsi pas besoin de cliquer sur nouveau mouvement.

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

Le système de champs libre est un fort outil de personnalisation. Ce dernier permet aux administrateurs de l'application d'enrichir des données typées sur des entitées typées le permettant.

Ainsi il est possible d'enrichir des données sur : 
- Les types de références de stock
- Les articles liés aux types de références
- Les types de demandes de livraison
- Les types de demandes de collecte
- Les arrivages
- Les réceptions

#### Les types de données

Les types de données disponibles sont : 

Type | Format | Exemple et détail
------------ | ------------- | -------------
Date | JJ/MM/AA | 25/03/20 : l'année peut être reprise facilement sous excel
Texte | texte de 250 caractères | le texte peut être limité en affichage sur la taille des champs
Oui/Non | Coche | les imports et export se font avec les caractères "Oui" et "Non"
Date et heure | JJ/MM/AA HH:MM | 25/03/20 17:53
Liste | Choix unique | La données se sélectionne dans une liste et est disponible en import ou export via une valeur de la liste : "Valeur"
Liste multiple | Choix multiple | la donnée se sélectionne dans une liste multiple et est disponible en import et export via une chaine avec séparateur point virgul : "Valeur1;Valeur2"
Nombre | NNNN | Exemple : 12345

#### Ajouter un champ libre

Pour ajouter un champ libre sur un type, aller dans le menu `Paramétrage / Champ libre` : la liste des types disponible s'ouvre.
-  Ouvrir un type existant via le bouton avec l'oeil
ou 
-  Cliquer sur le bouton `Aller vers la création d'un type`

Une fois dans la liste des champs libres, 
2. Cliquer sur le bouton `+ Nouveau Champ Libre` le formulaire de création s'ouvre et vous demande de : 
- Choisir le nom : Il doit être unique
- Choisir l'entitée sur laquelle s'applique le champ libre
- Typage : choisir le type de donnée
- Oligatoire à la création : Choisir si l'utilisateur est obligé de saisir cette donnée à la création de l'entitée
- Obligatoire à la modification : Choisir si l'utilisateur est obligé de saisir cette donnée à la modification de l'entitée.

Le champ est ensuite visible dans la liste des champs et une prévisualisation permet d'avoir un aperçu. 

> Note : Il n'est pas possible de muter un typage de champ, ex : un champ typé en texte ne pourra pas être modifié en date ou autre type



#### Supprimer un champ libre

**Attention : Un champ peut être supprimé via ce paramétrage. Il est très important de savoir que la suppression d'un champ est irréversible, les données saisies seront perdues.**

Penser à exporter vos données avant d'effectuer une éventuelle suppression de champ.

Pour effectuer la suppression, cliquer sur le bouton avec la corbeille dans la liste des champs.


## Export des données

Les exports de données se trouvent en général sur les listes des demandes/ordres/mouvements ou autres entitées de données.
Pour procéder à un export sur les listes de données, il faut préalablement saisir des dates dans la barre de filtre située en-tête de page.
Enfin il faut lancer l'export en cliquant sur le bouton `Exporter au format CSV`, cela permettra de télécharger un fichier de données au format CSV. 


Le sous menu d'export des données comporte l'export des données liées aux références et articles présents dans le stock, cela inclu également les champs libres associés. Afin de lancer l'export des articles ou références, il faut cliquer sur le bouton `Exporter au format CSV` et ne pas quitter la page tant que l'export n'est pas terminé, car le fait de quitter ou de rafraichir la page annulera l'export. 
Le système de champ libre multiplie les requêtes dans la base de données, c'est pourquoi l'export total de la base peut prendre un certain temps.


## Inventaires

La paramétrage des inventaires a été placé dans le menu paramétrage car il génèrent des automatismes de calculs et peut comme l'export des données multiplier les requetes sur la base de données.

L'inventaire fonctionne via un système de génération automatiques de missions suivant une cathégorisation ABC.

Les cathégories sont associés aux fréquences et permettent de générer automatiquement les mission toutes les semaines suivant la date de dernier inventaire positionnée sur une référence ou sur un article (suivant la gestion de quantitée retenue).

#### Nouvelle fréquence

Via le bouton `+Nouvelle fréquence`, il est possible de créer une nouvelle fréquence en nombre de mois.

Cela permet de déterminer qu'une catégorie de référence sera à inventorier au plus rapide, 1 fois par mois et au plus tard, 1 fois tous les XX mois (illimité).

#### Nouvelle catégorie

Via le bouton `+Nouvelle catégorie`, il est possible de créer une catégorie et de l'associer à une fréquence.

> Cette catégorisation peut se faire en dehors de l'application suivant vos règles : Valeur produit / nombre mouvement / nombre de réappo / nombre de régularisation / autre

Une fois vos catégorie créée, il est possible d'importer et mettre à jour les références pour leur affecter une catégorie.

#### Import pour mise à jour

Vous pourrez télécharger le modèle d'import attendu en cliquant sur le bouton `Modèle d'import`.

Ce dernier attend 2 colonnes : 
1. Référence
2. Catégorie

l'outil d'import attend un fichier d'import au format csv encodé en UTF-8. Une fois votre fichier pret, vous pouvez le charger via le bouton `Import excel`.

En cas de problème, l'outil d'import vous informera du déroulé de la mise à jour des catégories.


## Statuts litiges

Les status des litiges sont paramétrables via le menu `Paramétrage / Statuts litiges`.

Un statut de litige est à différencier d'une type de litige.
Exemple de type : *Manque BL*, *Problème Quantité*

Le statut est fait pour paramétrer un workflow, soit les étapes succésivent permettant d'aller vers la résolution d'un litige. Ces statuts peuvent être différents suivant les litiges d'arrivage et réception.

Il est possible de créer un statut en cliquant sur `+Nouveau statut`, voici les fonctionnalités disponibles : 

Champ paramétrage litige | Description
------------ | -------------
Catégorie | Permet se sélectionner arrivage ou réception
Label | Permet de choisir le nom :ex : "en attente fournisseur", "En attente contrôle qualité"
Commentaire | Champ texte qui sera ajouté automatiquement dans l'historique du litige lors du passage sur ce statut.
Statut de type "litige traité" | Permet d'identifier que le statut de requiert plus d'actions utilisateurs (filtre disponible sur les liste des litiges)
Envoi de mails aux acheteurs | Permet de spécifier que le passage sur ce statut envoi directement un mail d'information d'avancement aux acheteurs associés au litige
Ordre | Permet de spécifier l'ordre dans la liste des statut pour assister les utilisateurs sur le changement de statut

## Nature des colis

La nature des colis permet de caractériser les colis lors de l'arrivage. 

### Création d'une nature de colis

Via le bouton `+Nouvelle nature`, il est possible de créer une nouvelle nature de colis, ci dessous les diffèrents champs à paramétrer :
Champ paramétrage nature des colis | Description
------------ | -------------
Label | Permet de renseigner le nom de la nature de colis, ex : "Congelé"
Code | Permet de renseigner le code de la nature de colis, ex : "STD"
Quantité par défaut | Permet de renseigner le nombre de colis par défaut qui sera pré-remplie lors de la création d'un nouvel arrivage. 
Couleur | Permet d'identifier la couleur de cette nature sur les graphes des tableaux de bord. 
Préfixe | Permet de spécifier le préfixe qui figurera sur le numéro de colis généré lors de l'arrivage de cette nature, ex : **MRO**200331175615-00001

### Suppression et modification d'une nature de colis

#### Suppression d'une nature de colis

On ne peut pas supprimer une nature de colis si elle est déjà associée à un colis réceptionné 

#### Modification d'une nature de colis 

On peut modifier tous les champs de paramétrages d'une nature. La modification de préfixe n'aura pas d'impact sur le préfixe d'un numéro de colis réceptionné avant la modification. 

## Champs fixes

Ce menu liste les diffèrents champs fixes liés à la fonction arrivage et à la fonction réception. 
Contrairement aux champs libres, les champs fixes ne peuvent ni être supprimés, ni en créer de nouveaux.  

Cependant on peut modifier le paramétrage d'un champ fixe, pour cela vous devez cliquer sur l'icone crayon pou chaque champ fixe que vous souhaitez paramétrer, ci dessous les diffèrentes possibilités de paramétrage : 

Champ paramétrage champs fixes | Description
------------ | -------------
Agit sur | Permet de connaitre la fonction sur laquelle figure le champ fixe, ce paramètre n'est pas modifiable. 
Champ fixe | Indique le libellé du champ fixe, ce paramètre n'est pas modifiable. 
Obligatoire à la création ?  | Lorsque ce bouton est activé, le champ aura un caractère obligatoire lors de la création d'un arrivage ou d'une réception
Obligatoire à la modification ?  | Lorsque ce bouton est activé, le champ aura un caractère obligatoire lors de la modification d'un arrivage ou d'une réception
Affiché  | Lorsque ce bouton est activé le champ fixe apparaitra dans la fenêtre de création d'un arrivage ou d'une réception. 

## Import et mise à jour

### Introduction

La fonction d'import et de mise à jour permet soit d'importer de nouvelles données dans l'application ou mettre à jour des données existantes.
L'interêt de cette fonction est un gain de temps important, en l'occurence la création unitaire d'une importante base de données dans l'application peut être trsè chronophage. 

Pour l'instant, les types de données concernées par cette fonction sont les suivants : 
- Articles
- Références
- Fournisseurs
- Articles fournisseurs

### Création d'un nouvel import ou maj

Commencez par cliquer sur le bouton `+Nouvel import`, cela ouvrira la fenêtre *Import d'un fichier*. 
Sur cette fenêtre : 
1. Renseignez le nom de l'import souhaité 
2. Puis sélectionnez le type de données à importer dans la liste tel ci dessous  : 
- Articles
- Références
- Fournisseurs
- Articles fournisseurs
3. Enfin ajoutez le fichier au format CSV (délimiteur point virgule, encodage UTF-8 et <2 Mo) contenant les données à importer ou à mettre à jour. 
4. Suite à la validation de l'import, une nouvel fenêtre s'ouvre contenant un tableau avec 3 colonnes, cette étape nous permet d'associer les champs du fichier importé et les champs Follow GT : 

Colonnes du tableau de correspondance des champs Follow GT | Description
------------ | -------------
Titre de colonne de fichier | Libellé de chaque colonne, cela correspond aux valeurs de la première ligne de votre fichier d'import, qui pourraient correspondre à des titres de colonnes. 
Apercu (ligne 1 ) | Correspond aux valeurs de chaque colonne de la deuxième ligne de votre fichier d'import. 
Champs Follow GT | Liste déroulante, qui contient tous les champs (champs libres et fixes) liées au type de données à importer.

**Afin d'associer les champs du fichier importé et des champs Follow GT, en s'aidant de l'aperçu, il faut associer chaque champs du fichier importé avec un champ Follow GT. Les champs Follow GT avec une astérisque sont des champs obligatoires à la création de l'import ou de la mise à jour.** 

5. Enfin cliquez sur validation pour lancer l'import ou la mise à jour, si l'import est trop volumineux (voir "règles de planification des imports" ci dessous), il passera au staut "planifié" et sera exécuter plus tard, sinon il sera au statut "en cours", puis passera au statut "terminé"  lorsqu'il sera finalisé.

>**Règle de planification des imports** :Pour les imports de moins de 100 lignes, lancement immédiat. Pour les imports entre 100 et 500 lignes, lancement dans les 30 prochaines minutes. Pour les imports entre 500 et + lignes, lancement à minuit.


### Liste des imports et mise à jour 

Les détails de l'import seront visibles sur le tableau de l'historique des imports, il comporte des informations sur les imports ainsi que certaines actions que l'on pourra exéctuer : 

Champs liste imports et MAJ | Description
------------ | -------------
Actions | Bouton flèche circulaire : permet de créer un import en dupliquant les paramètres renseignés sur un import précédemment exécuté. Bouton loupe :  Lorsqu'un import est au statut "Terminé", le bouton permet  de télécharger le fichier de traces au format CSV. En cas d'erreurs d'import le fichier de trace contient le détail des erreurs par ligne. 
Statut | Indique le statut de l'import ou de la mise à jour , soit il peut être "en cours", "planifié", "annulé" ou "terminé"   
Date début | Indique la date et l'heure du lancement de l'import ou de la mise à jour
Date fin | Indique la date et l'heure de fin de l'import ou de la mise à jour
Nom import | Indique le nom de l'import renseigné lors de la création de l'import
Nvx enreg. | Indique le nombre de type de données crées
Mises à jour | Indique le nombre de type de données mises à jour
Nombre d'erreurs | Indique le nombre d'erreurs suite à l'import ou à la mise à jour
Utilisateur | Indique le nom de l'utilisateur qui a exécuté l'import ou la mise à jour





