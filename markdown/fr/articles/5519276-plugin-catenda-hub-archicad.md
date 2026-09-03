# Plugin Catenda Archicad

> **Remarque :** Le fichier d'installation du plugin se trouve dans [cet article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Le plugin Catenda Archicad est un plugin qui peut être installé pour Nemetchek Archicad. Avec ce plugin, vous pourrez collaborer sur les points de vue 3D, les Sujets et les Documents avec les autres Membres du projet de construction.

## 1. **Installation**

Lorsque le plugin Catenda Archicad est installé sur Windows, ses fichiers d'installation apparaissent dans le dossier suivant.

`C:\Program Files\Catenda\Catenda Archicad Connection\<Archicad Version>\Add-On`

Le plugin apparaîtra comme activé dans le gestionnaire de modules complémentaires la prochaine fois qu'Archicad sera ouvert. Notez que ceci est différent du dossier de modules complémentaires par défaut, qui se trouve à

`C:\Program Files\Graphisoft\<Archicad Version>\Add-Ons`

### 1.1 **Désinstallation**

Pour désinstaller le plugin, allez au menu Windows suivant :

`Paramètres Windows -> Applications -> Applications installées`

Trouvez Catenda Archicad Connection \<version> dans la liste et cliquez sur le menu d'action sur le côté droit pour désinstaller.

## 2. **Palette Catenda**

Après l'installation du plugin, vous pourrez voir un onglet de menu Catenda dans la barre supérieure. Dans ce menu, vous trouverez la fenêtre « Gestionnaire de problèmes Catenda Hub » qui contient la « Palette du gestionnaire de problèmes Catenda Hub ». Pour commencer à utiliser cette palette, il faudra ouvrir soit un plan d'étage, soit une vue 3D. Dans la palette, vous pourrez :

- Accédez à votre projet Catenda Hub
- Voir et créer des problèmes
- Télécharger et charger les modèles et révisions

## 3. **Se connecter**

Lorsque vous ouvrez la palette Catenda, la première chose que vous verrez est la page de connexion. La page de connexion peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/01-sign-in.png)

Si vous n'avez pas de compte Catenda, vous pouvez vous inscrire gratuitement en haut à droite. Si vous avez déjà un compte Catenda, vous pouvez entrer votre adresse e-mail et votre mot de passe et cliquer sur se connecter. Après vous être connecté, il vous sera demandé d'accorder l'accès à votre compte Catenda. Après avoir accordé cet accès, le plugin Archicad s'affichera en tant qu'application sur la [page des applications](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) de votre compte Catenda. Ici, vous pouvez toujours révoquer l'accès si vous ne souhaitez plus l'accorder.

### 3.1 **Réinitialisation du mot de passe**

Si vous avez oublié votre mot de passe, vous pouvez cliquer sur J'ai oublié mon mot de passe pour le réinitialiser. La page de réinitialisation du mot de passe peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/02-password-reset.png)

Si vous entrez votre adresse e-mail et cliquez sur « envoyer un e-mail de vérification », vous recevrez un e-mail qui vous guidera dans la réinitialisation de votre mot de passe. Assurez-vous d'avoir reçu cet e-mail dans les 5 minutes. Si vous ne le voyez pas dans votre boîte de réception, vous pouvez essayer votre dossier de courrier indésirable ou de rebut. S'il faut plus de 5 minutes, veuillez contacter le support à [support@catenda.com](mailto:support@catenda.com)

Pour revenir à la connexion, cliquez sur se connecter en haut à droite.

## 4. **Liste de projets**

Lorsque vous ouvrez le plugin Archicad, vous verrez votre liste de projets qui peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/03-project-list.png)

Dès que vous avez accepté l'invitation à un projet, votre projet s'affichera dans la liste de vos projets dans le plugin et sur la [page des projets](https://support.catenda.com/en/articles/8400797-projects-page).

**Menu d'action** Cliquez sur les trois points à côté de votre photo de profil pour ouvrir la liste déroulante du menu d'action :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/04-project-list.png)

**Modèles et révisions** Voici ce que peut ressembler la page des modèles et révisions. Ici, vous pourrez voir tous les modèles auxquels vous avez accès dans votre projet Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/05-project-list.png)

Sur cette page, vous pourrez télécharger et importer des fichiers ifc de votre projet Catenda vers votre modèle Archicad. L'horodatage du modèle sera relatif. Survolez l'horodatage pour obtenir des informations précises sur le moment où la révision a été publiée. Cliquez sur le bouton fléché à côté de l'une des révisions du modèle pour importer le fichier IFC qui a été téléchargé en tant que révision. Si vous n'avez accès à aucun modèle dans votre projet Catenda, vous verrez les éléments suivants :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/06-project-list.png)

**Charger un IFC** Charger un IFC à partir de votre projet Archicad actuel Voici ce que peut ressembler la page de chargement d'un IFC :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/07-project-list.png)

Par défaut, le nom du fichier sera le nom du projet Archicad. Celui-ci deviendra le nom de la révision dans Catenda. Sélectionnez le modèle vers lequel vous souhaitez charger votre fichier. Cliquez sur les paramètres pour ouvrir la boîte de dialogue d'exportation Archicad IFC. Ici, vous pouvez configurer les paramètres que vous souhaitez utiliser pour exporter votre IFC vers Catenda. Lorsque vous êtes prêt, cliquez sur le bouton de chargement pour charger un modèle.

**Coordonnées** Survolez l'option des coordonnées pour développer le menu des coordonnées. Voici ce que peut ressembler le menu des coordonnées :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/08-project-list.png)

Dans le menu des coordonnées, les coordonnées peuvent être choisies pour être relatives à : Point d'arpentage - Origine du projet par défaut

**Version** Le numéro de version du plugin.

**Déconnexion** Déconnectez-vous de votre compte Catenda

## 5. **Liste de sujets**

Lorsque vous cliquez sur un projet pour l'ouvrir, la première liste de sujets du projet s'ouvre. Une liste de sujets peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/09-topic-board.png)

### 5.1 **Recherche**

Cliquez dans la barre de recherche pour la mettre en surbrillance. Voici ce que peut ressembler la barre de recherche mise en surbrillance :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/10-search.png)

Après avoir cliqué dans la barre de recherche, une liste déroulante avec des Filtres suggérés s'ouvre. Sélectionnez l'un des Filtres pour l'appliquer. Cliquez sur le x à côté du filtre pour le supprimer à nouveau. Commencez à taper pour affiner les Filtres suggérés ou effectuez une recherche textuelle.

### 5.2 **Afficher le filtre**

Cliquez sur le bouton Afficher le filtre pour ouvrir le menu des Filtres. Voici ce que peut ressembler le menu des Filtres :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/11-show-filter.png)

En fonction des paramètres configurés dans la liste de sujets et des Sujets soumis, différents Filtres peuvent être disponibles :

**Mes Sujets** Assigné à moi Demandé par moi Créé par moi

**Statut** Les différents statuts de la liste de sujets sont énumérés ici

**Type** Les différents types de la liste de sujets sont énumérés ici

**Échéance** En retard Moins d'un jour Moins d'une semaine Moins de deux semaines Moins d'un mois Tous avec une Échéance

**Assigné à** Les entrées commençant par un `@` sont des Équipes assignées qui sont énumérées en premier. Après cela, les Membres du projet assignés sont énumérés.

**Demandé par** Les entrées commençant par un `@` sont les Équipes demandant des Sujets qui sont énumérées en premier. Après cela, les Membres du projet qui demandent des Sujets sont énumérés.

**Milestone** Les milestones appliqués aux Sujets sont énumérés.

**Étiquette** Les Étiquettes appliquées aux Sujets sont énumérées ici.

**Filtres non mentionnés dans le menu des Filtres** Recherche textuelle Le texte peut être recherché en tapant dans la barre de recherche.

Contenu pouvant être recherché Titre du Sujet Description du Sujet Commentaire du Sujet

Capitalisation La recherche textuelle n'est pas sensible aux caractères majuscules ou minuscules.

Montants de caractères Un seul caractère - Pas de résultats. Au moins deux caractères sont requis pour une recherche textuelle Deux caractères - Les mots entiers, séparés par des espaces, qui correspondent à la phrase de recherche sont inclus dans les résultats.

### 5.3 **Tri**

Cliquez sur Tri pour ouvrir le menu de tri. Voici ce que peut ressembler le menu de tri :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/12-sort.png)

Cliquez sur l'une des options pour trier la liste des Sujets par : _Plus récent_ - Par défaut Sujets avec la date de création la plus récente

**Plus ancien** Sujets avec la date de création la plus ancienne

**Récemment mis à jour** Sujets les plus récemment mis à jour

**Moins récemment mis à jour** Sujets les moins récemment mis à jour

## 6. **Sujet**

Lorsque vous cliquez sur un Sujet dans la liste de sujets, vous l'ouvrez. Un Sujet peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/13-topic.png)
