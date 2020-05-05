---
id: webtracabilites
title: Traçabilité des flux et des objets
sidebar_label: Traçabilité
---


## Flux - Identification des flux arrivage

L'application Wiistock propose en premier temps une réception, puis une mise en stock. 

La réception correspond à l'identification du flux d'arrivage. En effet faire la réception puis la mise en stock en même temps n'est pas possible. Grâce à la fonctionnalité arrivage il est possible pour vous de réceptionner vos colis et de les envoyer dans une zone en attente de mise en stock (réception).

La fonctionnalité arrivage se trouve dans le module traçabilité. Quand vous cliquez sur la fonctionnalité `arrivage`, vous arriverez sur un tableau qui regroupe tous les arrivages enregistrés. 

Ce tableau contient les informations suivantes :
- Date, 
- Numéro d' arrivage, 
- Transporteur, 
- Numéro de commande, 
- Fournisseur, 
- Destinataire

Les colonnes du tableau d'arrivage sont paramétrables, c'est-à-dire qu'elles peuvent être masquées du tableau si vous le désirez. 

Sur la page, vous verrez aussi, une liste de `filtres` permettant de trouver un arrivage plus facilement. 

Pour utiliser un filtre une fois la manipulation faite, il vous faudra cliquer sur le bouton `filtrer` en haut à droite de votre écran. 

Vous aurez la possibilité d'exporter votre tableau (pour faire un export il faut ajouter un ou plusieurs filtres) dans un tableau excel grâce au bouton `Exporter au format CSV`.  

Enfin, l'application est munie d'une barre de recherche au-dessus à droite du tableau afin de pouvoir rechercher directement un arrivage. 

### Création d'un arrivage 

Pour créer un arrivage il vous faudra cliquer sur le bouton `nouvel arrivage`. Cette fonctionnalité permettra d'ouvrir un formulaire de création d’arrivage. 

Champs | Description
------------ | -------------
Fournisseur | Permet de renseigner le fournisseur de l'arrivage
Transporteur | Permet de renseigner le transporteur des colis 
Numéro de commande BL | Correspond au numéro de commande attribué, par le bon de livraison
Destinataire | Nous indique le destinataire 
Statut | Conforme ou réservé 
Acheteur | Permet de savoir qui est l'acheteur 

De plus vous devez indiquer les colis que vous souhaitez recevoir. Bien sûr ils sont paramétrables en amont. Rendez-vous dans la partie [Paramétrage Global](parparametragesglobal.md).  

Certains champs sont obligatoires, ils sont munis d'une astérisque. [Vous pouvez paramétrer les champs que vous voulez voir obligatoires ou non](parparametragesglobal.md). Vous pouvez voir à côté de certains champs un `bouton plus`, il va permettre de créer un nouveau fournisseur, transporteur,… s'ils ne sont pas dans votre base de données.  

Pour valider la création, cliquez sur le bouton `enregistrer`. Une fois l'enregistrement créé, dans les [paramètres vous pourrez choisir si vous êtes redirigé dans l'arrivage ou bien si un formulaire d'arrivage se recrée automatiquement pour pouvoir en remplir un nouveau](parparametragesglobal.md). 

Lorsque vous avez créé votre arrivage et que vous vous rendez dans celui-ci, vous y retrouverez en haut de l'écran les informations concernant cet arrivage : 
- Fournisseur, 
- Transporteur, 
- Numéro de commande, 
- Statut,
- Destinataire, 
- Acheteur, 
- Plusieurs [champs libres que vous aurez paramétrés auparavant](parparametragesglobal.md). 
 
Vous y retrouverez `deux tableaux.`

L'un concernant les colis de votre arrivage et le second concernant les litiges qui pourraient être liés aux colis. 

Il vous sera possible après la création d'un arrivage, d'ajouter un colis ou plusieurs grâce au bouton `ajouter colis.` 

Vous pourrez imprimer le ou les colis, grâce au bouton `Imprimer colis.` 

Pour attribuer un `litige` à un `arrivage`, il vous faut cliquez sur `nouveau litige`. [Chaque litige est visible dans le module qualité, litiges.](webqualites.md)
Après avoir cliqué sur nouveau litige, un formulaire s'ouvrira, et vous permettra de créer votre propre litige. 

Il sera possible pour vous de définir : 
- Type, 
- Statut, 
- De laisser un commentaire,
- De choisir le colis concerné par le litige,
- Vous pouvez glisser une pièce jointe,
- Qualifier ce litige d’urgent ou non. 

Puis vous cliquerez sur enregistrer. Votre litige sera visible dans le tableau à droite, celui qui renseigne tous les litiges. 

Vous venez de créer un arrivage, maintenant vous pouvez le mettre en stock, grâce à la fonctionnalité [Réception](webordres.md). 


## Mouvement de traçabilité

Les mouvements de traçabilité permettent de savoir où se trouvent les produits, colis, articles,… avant la mise en stock. Cela permet de déplacer d'un emplacement A à un emplacement B un ou plusieurs objets, tout en gardant les informations nécessaires de tracabilité liées aux colis, produits ou articles. Cette fonctionnalité est traitable sur l'application web et également sur l'application mobile.  

Pour se rendre sur la fonctionnalité `mouvement` il faut cliquer sur le module traçabilité puis mouvement. Vous arriverez sur le tableau de tous les mouvements. 

Ce tableau ne concerne pas uniquement les arrivages et les réceptions, il concerne aussi toutes les pièces qui ont été déplacées grâce à l'application. 

Il regroupe les informations suivantes : 

- Issu de 
- Date 
- Of et autres (colis et piéce) 
- Référence
- Libellé
- L’emplacement 
- Types (dépose où prise)

Vous allez retrouver en haut de l’écran, des filtres afin d'affiner vos recherches. Mais aussi une barre de recherche juste en dessous. 

Vous retrouverez aussi la possibilité d'exporter au format csv une liste de ce tableau. Nous allons ensuite voir comment on crée un mouvement. Il y a deux Type de mouvement : 

- Prise, 
- Dépose.

La prise permet de communiquer à l'application, « je prends cette référence à cet emplacement, à cette heure-ci ». La dépose elle, indique à l'application "je dépose cette référence à cet emplacement à cette heure-ci ». 

Pour créer un mouvement cliquez sur nouveau mouvement. Puis sélectionnez les champs obligatoires pour valider ce mouvement : 

- Emplacement de prise, 
- Of et autres, (Colis et pièces)  
- Emplacement de dépose. 

Vous avez aussi la possibilité de laisser un commentaire ainsi qu'une pièce jointe. Pour valider, cliquez sur enregistrer. Votre mouvement va automatiquement s'afficher dans votre tableau.


## Association BR

L'association BR est une fonctionnalité qui permet d'associer un arrivage à un bon de réception. 

Pour faire cette action, il faut vous rendre dans le module `Traçabilité`, puis sur la fonctionnalité `Association BR`. Cette fonctionnalité va vous rediriger vers la liste de toutes les associations BR déjà créées. Vous y retrouverez des filtres, en haut de votre écran, ce qui vous permettra de trier plus facilement. 

Vous y retrouverez aussi un tableau regroupant toutes les associations de Bons de Réception, regroupant les informations suivantes : 
-	Action 
-	Date 
-	Arrivage 
-	Réception 
-	Utilisateur 

Vous pouvez aussi retrouver juste au-dessus à droite du tableau, une barre de recherche.

Pour associer un bon de réception à un arrivage, il faut que vous cliquiez sur le bouton `Association BR`. Cette action va immédiatement ouvrir un formulaire de création. Il vous faudra remplir le numéro d’arrivage, s'il y en a plusieurs vous pouvez cliquer sur le bouton `plus` pour ajouter un nouvel arrivage. 

Puis vous devrez remplir le numéro de réception. Si vous voulez associer un bon de réception sans arrivage vous cliquez sur le bouton `sans arrivage`. Cette action fera disparaître le libellé des arrivages. 
Pour finaliser votre création, cliquez sur enregistrer. Une fois la création faite, vous aurez la possibilité de retrouver votre `Bon de Réception` dans votre tableau. 

Si vous le souhaitez vous pouvez exporter votre tableau sous forme de tableur Excel. 

## Acheminement

La fonctionnalité d'acheminement permet de déplacer une pièce qui ne se trouve pas dans votre stock et dont vous avez besoin. Il s'agit d'une fonctionnalité annexe à la gestion de stock. 

Pour vous rendre dans acheminement, il faut que vous cliquiez dans le module traçabilité, puis sur acheminement. 

Vous y retrouverez un tableau avec plusieurs informations pertinentes : 
- Date de la demande 
- Demandeur 
- Emplacements de prise et dépose
- Nombre de pièce
- Le statut
  
Pour créer un nouvel acheminement il faut cliquer sur `nouvel acheminement`.   

Après cette action, un formulaire s'ouvrira. Il vous faut remplir les champs colis, demandeur, destinataire, emplacement de prise, et emplacement de dépose. Pour finaliser la création, cliquez sur enregistrer. Après la création, vous pourrez voir votre acheminement dans le tableau. 

Si vous souhaitez voir quel acheminement a été fait ou pas, il faut regarder dans la colonne statut. Il y à deux statut possible. `à traiter` et `traité`.  

Si vous souhaitez rechercher votre acheminement, vous pouvez le faire de manière simple, en utilisant les filtres en haut de votre écran ou bien la barre de recherche juste en dessous du bouton filtrer. Si vous souhaitez imprimer, modifier ou supprimer votre d'acheminement, vous pourrez utiliser les 3 boutons dans la colonne action. Le premier sert à imprimer, le deuxième à modifier et le troisième à supprimer.


## Encours

La fonctionnalité des encours permet de visualiser la durée d'un objet sur un emplacement. Les encours sont liés à des emplacements, qui sont eux-mêmes liés à des délais de traçabilité que vous pourrez paramétrer dans le référentiel des emplacements. 

Si les colis déposés sur les emplacements d'encours dépassent le délai de tracabilité préalablement paramétré alors la ou les lignes de colis apparaîtront en rouge sur votre écran. 

Afin de fixer un délai de traçabilité et pour attribuer un emplacement à une zone d’encours, vous vous rendrez dans référentiel, emplacement. Vous pourrez soit modifier un emplacement déjà existant et lui attribuer un délai de traçabilité ou bien créer un nouvel emplacement et lui ajouter un délai de traçabilité.   

Sur l'écran des encours, vous allez pouvoir visualiser plusieurs tableaux selon le nombre d'emplacements d'encours, autrement dit un tableau par emplacement d'encours, ci dessous le détail des champs disponibles sur ces tableaux : 

Champs Emplacement d'encours | Description
------------ | -------------
Colis | Indique le ou les numéros de colis présents sur l'emplacement
Date de dépose  | Indique la date de dépose du colis sur l'emplacement
Délai | Indique le temps passé du colis sur l'emplacement

## Urgences

### Concept des urgences

Il est possible qu'un acheteur ou des acheteurs aient besoin d'une commande en urgence, ils pourront identifier des commandes urgentes dans cette fonction. Dès l'arrivage de la commande en urgence, l'opérateur sera informé que la commande est en urgence et pourra donc la traiter en priorité, aussi les acheteurs seront informés par mail de l'arrivage de leur commande. 

### Création d'une urgence

Sur l'application Web, l'acheteur devra se rendre sur le module `Traçabilité`, `Urgence`. Puis il faudra cliquer sur `nouvelle urgence`. Il vous faudra remplir les champs obligatoires qui sont essentiels pour l'activation de l'urgence : 

Champs de création d'une urgence | Description
------------ | -------------
Fourchette de livraison entre le et le | L'urgence sera active uniquement entre la date de début indiquée et la date de fin
N°de commande | Renseignez le numéro de commande
Numéro de poste | Renseignez le numéro de poste en urgence figurant sur la commande ou sur le BL
Fournisseur | Sélectionnez l'intitulé du fournisseur lié à la commande, il doit préalablement figurer dans le référentiel fournisseur
Transporteur | Sélectionnez l'intitulé du transporteur lié à la commande, il doit préalablement figurer dans le référentiel transporteur
Numéro de tracking transporteur | Champ textuel libre non obligatoire,si disponible vous pouvez renseigner le numéro de tracking transporteur de la commande

L'urgence se déclenchera lors de la création d'un arrivage lors de la fourchette de livraison et si les champs renseignés ci-dessous correspondent à l'urgence :    
* Fournisseur 
* Transporteur
* Numéro commande
* Destinataire  

Suite à cela l'opérateur visualisera un message l'informant du caractère urgent de l'arrivage et du numéro de poste en urgence, aussi le ou les acheteurs recevront un mail les informant de l'arrivage de la commande urgente.  

### Urgence sur référence gérée à l'article

Il est aussi possible de paramétrer un caractère urgent sur une référence gérée à l'article. Lors de la réception , l'opérateur sera alors averti de l'urgence et l'utilisateur sera averti de la réception de la référence en urgence. 

Afin d'indiquer une urgence sur une référence gérée à l'article, dans le sous menu "Référence", cliquez sur le bouton crayon pour accéder à la fenêtre de modification de la référence et activez le bouton `Urgence`.

Suite à la réception de cette référence en urgence, l'urgence sera désactivée.  
