---
id: doc2
title: Démarer un dépot Git
---

Vous pouvez démarrer un dépôt Git de deux manières. La première consiste à prendre un projet ou un répertoire existant et à l'importer dans Git. La seconde consiste à cloner un dépôt Git existant sur un autre serveur.

## Initialisation d'un dépot Git dans un répertoire existant

Si vous commencez à suivre un projet existant dans Git, vous n'avez qu'à vous positionner dans le répertoire du projet et saisir :

```
git init
```

Cela crée un nouveau sous-répertoire nommé .git qui contient tous les fichiers nécessaires au dépôt (un squelette de dépôt Git). Pour l'instant, aucun fichier n'est encore versionné.

Si vous souhaitez commencer à suivre les versions des fichiers existants (contrairement à un répertoire vide), vous devriez probablement commencer par indexer ces fichiers (git add) et faire une validation initiale (git commit) :

```
git add *.c
git add README
git commit –m 'version initiale du projet'
```

Comme nous avons initialisé notre dépôt en utilisant git init, git ne saura pas quel serveur contacter lorsque vous utiliserez git push. Par conséquent, nous allons devoir ajouter un serveur (appelé remote dans la terminologie git) à notre repository :

```
git remote add origin git@github.com:yourusername/yourrepository.git
```

Ceci ajoute un serveur nommé origin avec l’URL git@github.com:yourusername/yourrepository.git

L’URL dépend du serveur que vous utilisez, pour GitHub, vous pouvez obtenir l’URL (HTTPS ou SSH) en cliquant sur le bouton vert "Clone or download".

Vous pouvez maintenant pusher vos données existantes vers le serveur. La commande git push par elle-même ne fonctionnera pas **<u>pour la première fois</u>**, parce que git ne sait pas automatiquement que nous voulons pusher à l’origine. Par conséquent, nous devons lui dire que les futures commandes git push se feront automatiquement à l’origine :

```
git push --set-upstream origin master
```

This is a link to [another document.](doc3.md)  
This is a link to an [external page.](http://www.example.com)
