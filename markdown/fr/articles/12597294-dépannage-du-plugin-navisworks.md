# Dépannage du plugin Navisworks

Les erreurs qui peuvent être rencontrées avec le plugin Navisworks et comment les résoudre sont expliquées dans cet article.

## 1. **AddTopic**

Lorsque le menu des sujets est ouvert sans être connecté, l'erreur suivante s'affiche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/01-addtopic.png)

Pour résoudre ce problème, veuillez accéder au menu des paramètres et cliquer sur connexion en haut à droite.

## 2. **PopulateIssueBoards**

Lorsqu'il n'y a pas de sujets dans l'un des projets dont un Membre fait partie, l'erreur suivante s'affichera.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/02-populateissueboards.png)

Une fois qu'un sujet est créé dans le projet, l'erreur n'apparaîtra plus.

## 3. **Réinitialisation du plugin**

Après la mise à jour de Navisworks, il pourrait y avoir des problèmes avec l'installation du plugin Navisworks de Catenda. Pour réinitialiser le plugin, veuillez suivre les étapes suivantes :

Veuillez d'abord modifier les options des dossiers Windows pour afficher les fichiers et dossiers cachés

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/03-resetting-the-plugin.jpg)

Ensuite, nous trouverons les paramètres d'application Navisworks dans le dossier C:\\Users\\_username\\_AppData\\Local. Ils peuvent se trouver dans les dossiers Autodesk\_Inc ou/et Autodesk\_Ltd

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/04-resetting-the-plugin.jpg)

Les paramètres Navisworks sont situés dans des dossiers qui commencent par "Roamer.exe\_Url…"

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/05-resetting-the-plugin.jpg)

Nous pouvons réinitialiser ces paramètres en supprimant le dossier Roamer.exe\_Url… y compris les sous-dossiers et les fichiers

Pour vérifier à quels plugins appartiennent les paramètres : le niveau suivant indique la version de Navisworks, par exemple 19 pour la version Navisworks 2022, 18 pour la version 2021, etc.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/06-resetting-the-plugin.jpg)

Sous ce dossier, nous pouvons trouver le fichier de configuration réel _user.config_ qui peut être ouvert avec un éditeur de texte. Veuillez noter ! Il est préférable de supprimer le chemin d'accès complet du niveau Roamer.exe\_Url plutôt que de tenter de supprimer des plugins individuels en utilisant l'éditeur de texte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/07-resetting-the-plugin.jpg)
