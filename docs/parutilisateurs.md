---
id: parutilisateurs
title: Paramétrage des utilisateurs
sidebar_label: Utilisateurs
---

## Avant de commencer

Pour donner accès aux managers ou opérateurs sur l'application, vous devez leur créer des comptes utilisateurs. Vous pouvez soit créer tous les comptes utilisateurs 1 à 1, soit demander aux utilisateurs de valider le fomulaire de création de compte disponible depuis l'écran d'authentification de l'application.

Le compte utilisateur est ensuite rattaché à un rôle lui permettant d'accéder à certaines fonctionnalités de l'application.

### Créer un utilisateur

Pour créer un utilisateur depuis l'interface de paramétrage, aller dans `Paramétrage / Utilisateurs` puis cliquer sur le bouton `+ Nouvel utilisateur`

Le formulaire de création s'ouvre et vous propose de saisir les informations suivantes : 
- **Nom d'utilisateur** : nom affiché dans la barre de menu de l'application, sert de login sur l'application nomade et doit donc être unique
- **Email** : doit correspondre à votre email pour recevoir les emails de notification sur les différentes actions de l'application, sert de login sur l'application web et doit donc être unique
- **Mot de passe** : la saisie de mot de passe doit respecter les contraintes suivantes
    - minimum 8 caractères
    - 1 caractère spécial
    - 1 chiffre
    - 1 majuscule
- **Confirmer mot de passe** : Permet de ressaisir le mot de passe pour valider qu'il n'y a pas eu d'erreur de saisie
- **Type** : Permet de préciser les `Type de demandes de livraison` visibles par l'utilisateur. Ainsi l'opérateur pourra traiter tous les types renseignés (Cela permet de cacher les autres types de demandes de livraison sur l'application mobile)
- **Rôle** : Permet d'affecter un rôle à l'utilisateur pour lui donner accès à certaines fonctionnalités de l'application
- **Dropzone** : Permet d'affecter un emplacement à un utilisateur. Cette fonctionnalité est utilisée sur les arrivages de traçabilité. Si l'utilisateur est positionné en acheteur, alors l'emplacement dropzone sera affiché sur l'étiquette d'unité de tracking

Une fois enregistré, le rôle est modifiable depuis la liste des utilisateurs. (Cela permet d'éviter d'entrer en modification pour chaque utilisateur).

### Création externe

Depuis l'écran d'authentification de l'application, un bouton `Créer un compte` redirige vers un formulaire de création de compte.

Ce formulaire est limité et permet seulement une saisie des champs suivants : 
- Nom d'utilisateur
- Adresse email 
- Mot de passe

Une fois créé, l'utilisateur pourra s'authentifier pour entrer dans l'application et sera rattaché au rôle automatique `Aucun accès`. Les administrateurs pourront ensuite affecter le bon rôle et compléter le paramétrage de l'utilisateur.

>Cette fonction de création externe permet d'inviter les utilisateurs demandeurs ou en consultation à créer directement leur compte ici. Cela limite la saisie en masse par les administrateurs de l'application

### Mot de passe oublié

Une fonction de mot de passe oublié permet à l'utilisateur de réinitialiser son mot de passe. 
1. Depuis l'écran d'authentification, l'utilisateur doit valider le formulaire de mot de passe oublié. 
*L'application envoit ensuite un lien temporaire chiffré sur la boite email de l'utilisateur comportant un lien redirigeant vers un formulaire de réinitialisation de mot de passe.*
2. L'utilisateur clique sur le lien se trouvant dans le mail qu'il a reçu puis valide le formulaire en saisissant un nouveau mot de passe.
3. le mot de passe est maintenant réinitialisé et l'utilisateur peut à nouveau se connecter sur l'application.

### Modifier un utilisateur

La modification d'un utilisateur est possible en clique sur le bouton `crayon` se trouvant dans la colonne action de la liste des utilisateurs.

Il n'est pas recommandé de modifier l'email d'un utilisateur. Tous les autres champs peuvent être modifiés.


La réinitialisation de mot de passe est possible depuis la modification de l'utilisateur.

### Supprimer ou désactiver un utilisateur

Un utilisateur peut être supprimé s'il n'a jamais créé d'informations liées à son profil (ex : arrivage / demandes / mouvements / autres )

Si l'utilisateur est lié à des données, il n'est plus possible de le supprimer. Dans ce cas il est possible de le désactiver en le modifiant.

La désactivation d'un utilisateur restreint : 
1. Sa sélection dans les champs destinataires / acheteurs
2. La possibilité de se connecter sur l'application