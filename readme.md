# README

## Introduction

Ce dépôt contient un script PHP pour gérer les contacts. Le script fournit une interface en ligne de commande (CLI) pour interagir avec une liste de contacts. Les commandes suivantes sont disponibles :

- `help` : Afficher les informations d'aide.
- `list` : Afficher tous les contacts.
- `create [name, email, phone number]` : Créer un nouveau contact.
- `modify [id]` : Modifier un contact existant.
- `delete [id]` : Supprimer un contact.
- `quit` : Quitter le programme.

## Démarrage

Pour utiliser le script, suivez ces étapes :

1. Clonez le dépôt sur votre machine locale.
2. Ouvrez un terminal et naviguez jusqu'au répertoire contenant le fichier `main.php`.
3. Exécutez le script en tapant `php main.php` et en appuyant sur Entrée.

## Utilisation

Une fois le script en cours d'exécution, vous pouvez utiliser les commandes listées ci-dessus pour gérer vos contacts. Par exemple :

- Pour créer un nouveau contact, tapez `create John Doe john@example.com 1234567890` et appuyez sur Entrée.
- Pour lister tous les contacts, tapez `list` et appuyez sur Entrée.
- Pour modifier un contact, tapez `modify 1` (où `1` est l'ID du contact que vous souhaitez modifier) et appuyez sur Entrée. Vous serez invité à saisir les nouvelles informations pour le contact.
- Pour supprimer un contact, tapez `delete 1` (où `1` est l'ID du contact que vous souhaitez supprimer) et appuyez sur Entrée.
- Pour quitter le programme, tapez `quit` et appuyez sur Entrée.