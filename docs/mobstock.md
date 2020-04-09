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

La fonctionnalité livraison version mobile, est liée aux livraisons sur la partie web.

Après la préparation d'une livraison, il se crée sur l'application web et mobile un ordre de livraison. Cet ordre de livraison visible sur le mobile va permettre de déplacer les colis du point de préparation à son point de livraison finale. 

Pour effectuer cette action, rendez-vous dans le module stock de l’application mobile, puis cliquez sur la fonctionnalité livraison. Après avoir cliqué sur la fonctionnalité livraison, l'application affichera la totalité des ordres de livraison à traiter.

Pour les traiter, vous cliquez sur un des ordres. Une page s'ouvrira et affichera les informations suivantes : le numéro de la livraison, l'emplacement de destination, la référence de l'article, son emplacement, ainsi que sa quantité. Vous pouvez scanner l'article ou bien cliquez sur sa référence et puis valider. Une fois la livraison prête à être validée, vous cliquez sur le bouton en bas à gauche, validé. Pour finir le processus, il vous faudra scanner l'emplacement de livraison. 

Enfin, l'application mobile synchronisera ses données avec l'application web et permettra aux superviseurs de voir quels ordres de livraison sont traités et ceux qui ne le sont pas.  


## Collecte

La fonctionnalité collecte version mobile, est liée à une demande de collecte effectuée depuis la version web. 

Toutes les demandes de collectes ont une référence propre. 

Chaque demande de collecte, créera automatiquement un ordre de collecte visible pour tous vos opérateurs sur la version mobile. 

Pour effectuer votre collecte, il faut vous rendre sur la version mobile, dans le module stock, collecte. 
Si vous cliquez sur la fonctionnalité collecte, l'application ouvrira une page qui rassemble tous les ordres de collecte. 

Une fois que vous avez trouvé le bon ordre de collecte, vous cliquerez sur celle-ci. Vous serez dirigé dans le détail de l'ordre de collecte, avec les informations suivantes : le numéro de la collecte, le point de collecte (c'est à dire l'emplacement où se trouve les pièces que vous devez collecter), ainsi que la liste des articles à traiter. 

Pour valider votre collecte vous devez sélectionner les pièces à collecter. Pour cela vous pouvez scanner le code-barres de la pièce, ou bien valider la pièce à la main en cliquant sur la référence, et en sélectionnant la quantité souhaitée. 

Après validation, un petit bouton vert apparaît en bas à gauche de votre écran, il va vous permettre de valider la collecte. S’il s'agit d'une destruction, la collecte s'arrêtera ici. Mais si c’est une mise en stock, l'application vous redirigera vers la dépose. 

Pour faire la dépose vous pouvez choisir un emplacement à la main ou bien scanner une étiquette d’emplacement. Puis vous allez sélectionner les articles que vous voulez déposer. Encore une fois vous pouvez le faire manuellement ou bien en scannant le code barre de l'article. Une fois l'article ou les articles déposés, il vous faut cliquez sur le bouton valider. Ainsi la collecte est terminée et elle se synchronise avec la version web. Ainsi le superviseur pourra suivre les actions effectuées dans la journée.  

## Inventaire

La fonctionnalité inventaire version mobile, est liée aux inventaires créer sur la version web. 

En effet, l'application Wiistock mobile, permet d'effectuer les missions d'inventaire rapidement grâce au mobiles (ex : Mobile Zebra), qui peuvent lire les codes-barres. 

Pour retrouver les inventaires sur la partie mobile, vous vous rendrez dans le module stock, et vous cliquerez sur la fonctionnalité `inventaire`. Une page s'ouvrira avec la liste de tous les inventaires à effectuer et non finalisés. 

Commençons par traiter un inventaire. Chaque inventaire se voit attribuer une fourchette temporelle. Si vous n'êtes pas dans cette fourchette, l'inventaire ne s'affichera pas sur votre téléphone. 

Pour effectuer votre inventaire, scannez l'emplacement de l’article à inventorié. 

Vous devez scanner cet emplacement, pour ouvrir l'inventaire (Si votre téléphone n'est pas équipé de scan, vous pouvez utiliser votre appareil photo en cliquant sur le logo du code barre au milieu de votre écran). 

Après l'ouverture de l'inventaire, plusieurs données s'afficheront sur votre écran notamment l'emplacement de l'article de l'inventaire mais aussi l'article avec sa référence. 

Il vous faudra flasher le code barre de l'article ou bien le prendre en photo, pour incrémenter votre `inventaire`. Une fois le flash effectué, vous validerez le nombre d'article que vous trouverez sur cet emplacement. Si le nombre est bon, et que votre mission d'inventaire est terminée, l'inventaire sera noté comme rempli à 100 % sur la version web de la fonctionnalité [inventaire](webstocks.md). 

Il y’a aussi la possibilité de traiter une `anomalie` sur un inventaire. Si un inventaire ne regroupe pas la totalité des articles et références demandées. Alors, une anomalie se créra. 

Il vous suffira de scanner l'[emplacement](webreferentiels.md) concerant l'inventaire, pour pouvoir traiter cette erreur. 

La manipulation est similaire, une fois scanné, vous allez devoir séléctionner le nombre d'[articles/références](webstocks.md) qui sont signalées en anomalie. 