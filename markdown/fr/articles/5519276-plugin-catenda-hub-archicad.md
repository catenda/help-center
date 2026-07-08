# Plugin Catenda Archicad

> test

> **Remarque :** Le fichier d'installation du plugin peut être trouvé dans [cet article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Le plugin Catenda Archicad est un plugin qui peut être installé pour Nemetchek Archicad. Avec ce plugin, vous pourrez collaborer sur des points de vue 3D, des sujets et des Documents avec les autres Membres du projet de construction.

## 1. **Installation**

Lorsque le plugin Catenda Archicad est installé sur Windows, ses fichiers d'installation apparaîtront dans le dossier suivant.

`C:\\Program Files\\Catenda\\Catenda Archicad Connection\\\<Archicad Version>\\Add-On`

Le plugin apparaîtra comme activé dans le gestionnaire de modules complémentaires la prochaine fois qu'Archicad sera ouvert. Notez que cela est différent du dossier de modules complémentaires par défaut qui se trouve à

`C:\\Program Files\\Graphisoft\\\<Archicad Version>\\Add-Ons`

### 1.1 **Désinstallation**

Pour désinstaller le plugin, accédez au menu Windows suivant :

`Paramètres Windows -> Applications -> Applications installées`

Trouvez Catenda Archicad Connection \<version> dans la liste et cliquez sur le menu d'action sur le côté droit pour désinstaller.

## 2. **Palette Catenda**

Après avoir installé le plugin, vous pourrez voir un onglet de menu Catenda dans la barre supérieure. Dans ce menu, vous trouverez la fenêtre « Gestionnaire de problèmes Catenda Hub » qui contient la « Palette du gestionnaire de problèmes Catenda Hub ». Pour commencer à utiliser cette palette, soit un plan d'étage, soit une vue 3D doit être ouvert. Dans la palette, vous pourrez :

- Accédez à votre projet Catenda Hub
- Voir et créer des problèmes
- Télécharger et charger des modèles et des révisions

## 3. **Connexion**

Lorsque vous ouvrez la palette Catenda, la première chose que vous verrez est la page de connexion. La page de connexion peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/01-sign-in.png)

Si vous n'avez pas de compte Catenda, vous pouvez vous inscrire gratuitement en haut à droite. Si vous avez déjà un compte Catenda, vous pouvez entrer votre adresse e-mail et votre mot de passe et cliquer sur connexion. Après votre connexion, vous serez invité à accorder l'accès à votre compte Catenda. Après avoir accordé cet accès, le plugin Archicad s'affichera comme une application sur la [page applications](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) de votre compte Catenda. Vous pouvez toujours révoquer l'accès si vous ne souhaitez plus l'accorder.

### 3.1 **Réinitialisation du mot de passe**

Si vous avez oublié votre mot de passe, vous pouvez cliquer sur J'ai oublié mon mot de passe pour le réinitialiser. La page de réinitialisation du mot de passe peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/02-password-reset.png)

Si vous entrez votre adresse e-mail et cliquez sur « envoyer un email de vérification », vous recevrez un e-mail qui vous guidera dans la réinitialisation de votre mot de passe. Assurez-vous d'avoir reçu cet e-mail dans les 5 minutes. Si vous ne le voyez pas dans votre boîte de réception, vous pouvez vérifier votre dossier Spam ou Indésirable. S'il faut plus de 5 minutes, veuillez contacter le support à [support@catenda.com](mailto:support@catenda.com)

Pour revenir à la connexion, cliquez sur connexion en haut à droite.

## 4. **Liste de projets**

Lorsque vous ouvrez le plugin Archicad, vous verrez votre liste de projets qui peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/03-project-list.png)

Dès que vous avez accepté l'invitation à un projet, votre projet s'affichera dans la liste de vos projets du plugin et sur la [page des projets](https://support.catenda.com/en/articles/8400797-projects-page).

**Menu d'action** Cliquez sur les trois points à côté de votre photo de profil pour ouvrir la liste déroulante du menu d'action :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/04-project-list.png)

**Modèles et révisions** Voici ce que la page des modèles et révisions peut ressembler. Ici, vous pourrez voir tous les modèles auxquels vous avez accès dans votre projet Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/05-project-list.png)

Sur cette page, vous pourrez télécharger et importer des fichiers ifc de votre projet Catenda vers votre modèle Archicad. L'horodatage du modèle sera relatif. Passez la souris sur l'horodatage pour obtenir des informations précises sur le moment où la révision a été publiée. Cliquez sur le bouton fléché à côté de l'une des révisions de modèle pour importer le fichier IFC qui a été chargé en tant que révision. Si vous n'avez accès à aucun modèle dans votre projet Catenda, vous verrez ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/06-project-list.png)

**Charger IFC** Charger un IFC depuis votre projet Archicad actuel Voici ce que la page de chargement IFC peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/07-project-list.png)

Par défaut, le nom du fichier sera le nom du projet Archicad. Cela deviendra le nom de la révision dans Catenda Sélectionnez le modèle sur lequel vous souhaitez charger votre fichier. Cliquez sur les paramètres pour ouvrir la boîte de dialogue d'export IFC d'Archicad. Ici, vous pouvez configurer les paramètres que vous souhaitez utiliser pour exporter votre IFC vers Catenda. Lorsque vous êtes prêt, cliquez sur le bouton de chargement pour charger un modèle.

**Coordonnées** Passez la souris sur l'option de coordonnées pour développer le menu des coordonnées. Voici ce que le menu des coordonnées peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/08-project-list.png)

Dans le menu des coordonnées, les coordonnées peuvent être choisies pour être relatives à : Point d'arpentage - Origine du projet par défaut

**Version** Le numéro de version du plugin.

**Déconnexion** Déconnectez-vous de votre compte Catenda

## 5. **Tableau de sujets**

Lorsque vous cliquez sur un projet pour l'ouvrir, le premier tableau de sujets du projet s'ouvre. Un tableau de sujets peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/09-topic-board.png)

### 5.1 **Recherche**

Cliquez dans la barre de recherche pour la mettre en évidence. Voici ce que la barre de recherche en surbrillance peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/10-search.png)

Après avoir cliqué dans la barre de recherche, une liste déroulante avec les Filtres suggérés s'ouvre. Sélectionnez l'un des Filtres pour les appliquer. Cliquez sur le x à côté du filtre pour le supprimer à nouveau. Commencez à taper pour réduire les Filtres suggérés ou effectuez une recherche de texte.

### 5.2 **Afficher le filtre**

Cliquez sur le bouton Afficher le filtre pour ouvrir le menu du filtre. Voici ce que le menu du filtre peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/11-show-filter.png)

Selon les paramètres configurés dans le tableau de sujets et les sujets soumis, différents Filtres peuvent être disponibles :

**Mes sujets** Assigné à moi Demandé par moi Créé par moi

**Statut** Les différents statuts du tableau de sujets sont répertoriés ici

**Type** Les différents types du tableau de sujets sont répertoriés ici

**Echéance** En retard Moins d'un jour Moins d'une semaine Moins de deux semaines Moins d'un mois Tous avec une Echéance

**Assigné à** Les entrées commençant par un `@` sont des Équipes assignées qui sont répertoriées en premier. Après cela, les Membres du projet assignés sont répertoriés.

**Demandé par** Les entrées commençant par un `@` sont des Équipes demandant des sujets qui sont répertoriées en premier. Après cela, les Membres du projet demandant des sujets sont répertoriés.

**Milestone** Tous les jalons appliqués aux sujets sont répertoriés.

**Étiquette** Les Étiquettes appliquées aux sujets sont répertoriées ici.

**Filtres non mentionnés dans le menu du filtre** Recherche de texte Le texte peut être recherché en tapant dans la barre de recherche.

Contenu qui peut être recherché Titre du sujet Description du sujet Commentaire du sujet

Capitalisation La recherche de texte est insensible à la casse.

Quantité de caractères Un seul caractère - Aucun résultat. Au moins deux caractères sont requis pour une recherche de texte Deux caractères - Les mots complets, séparés par des espaces, qui correspondent à la phrase de recherche sont inclus dans les résultats.

### 5.3 **Trier**

Cliquez sur Trier pour ouvrir le menu de tri. Voici ce que le menu de tri peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/12-sort.png)

Cliquez sur l'une des options pour trier la liste des sujets par : _Plus récent_ - Par défaut Sujets avec la date de création la plus récente

**Plus ancien** Sujets avec la date de création la plus ancienne

**Récemment mis à jour** Sujets qui sont les plus récemment mis à jour

**Le moins récemment mis à jour** Sujets qui sont le moins récemment mis à jour

## 6. **Sujet**

Lorsque vous cliquez sur un sujet dans le tableau de sujets, vous l'ouvrez. Un sujet peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/13-topic.png)
