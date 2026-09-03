# Application Catenda SharePoint

> **Remarque :** Le fichier d'installation du plugin se trouve dans [cet article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Si l'application Catenda SharePoint est ajoutée à un site SharePoint, les fichiers peuvent être publiés de SharePoint vers Catenda et la structure des documents Catenda peut être affichée dans SharePoint. Une fois configurée, l'application peut ressembler à ceci : <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-628ad1424b68.png" width="300"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-910393724d2c.png" width="300"/> Cet article contient des informations sur le fonctionnement de cette application Voir [ici](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq) pour plus d'informations sur la façon dont cette application peut être utile. Voir [ici](https://support.catenda.com/en/articles/9453368-adding-and-removing-the-catendasp-app) pour savoir comment ajouter l'application SharePoint à un site.

## 1. **Publication vers Catenda avec la commande de liste**

Avec la commande de liste, il est possible de publier un ou plusieurs fichiers vers Catenda.

> **Remarque :** Il est uniquement possible de publier des fichiers. Les structures de dossiers peuvent être téléchargées depuis SharePoint et chargées vers Catenda via [chargement zip](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) ou [Connecteur de bureau](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector).

### 1.1 **Recherche de la commande de liste**

**Un fichier** Si vous souhaitez publier un fichier unique vers Catenda, le moyen le plus simple est de cliquer sur Publier vers Catenda dans le menu hamburger du fichier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/01-finding-the-list-command.png)

**Plusieurs fichiers** Si vous souhaitez publier plusieurs fichiers vers Catenda, vous devrez sélectionner les fichiers à publier. Après vos fichiers dans SharePoint, les utilisateurs pourront voir une commande de liste Publier vers Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/02-finding-the-list-command.png)

S'il n'y a pas assez d'espace dans la barre de commandes, vous pouvez voir la commande dans le menu hamburger.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/03-finding-the-list-command.png)

> **Remarque :** Les fichiers ne peuvent être publiés qu'à partir de l'affichage de liste, car la commande de liste n'est pas disponible en affichage grille.

### 1.2 **Publication du fichier**

Après avoir cliqué sur Publier vers Catenda, le menu suivant s'ouvre et peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/04-publishing-the-file.png)

Si vous n'avez pas accordé l'accès à SharePoint à votre compte Catenda, il vous sera demandé de l'autoriser. [Voir ci-dessous](#h_788fe15988) pour savoir comment autoriser votre compte.

**Sélection d'un dossier** Si vous avez accordé l'accès à votre compte Catenda, vous pouvez sélectionner le projet, la bibliothèque et le dossier de destination sur Catenda, puis publier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/05-publishing-the-file.png)

L'affichage de la structure des dossiers dans SharePoint est cohérent avec l'affichage dans Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/06-publishing-the-file.png)

Si un document portant le même nom que votre fichier n'existe pas encore dans le dossier où vous le publiez, il apparaîtra comme un nouveau document dans Catenda. Si le fichier que vous publiez porte le même nom qu'un document dans le dossier où vous le publiez, le fichier sera une nouvelle révision de ce document.

> **Remarque :** Il est uniquement possible de publier des documents et non de charger des brouillons

Une fois qu'un fichier est publié, les utilisateurs pourront le déplacer, le renommer et le supprimer. _Accès Catenda requis :_ Accès complet, généralement accordé aux utilisateurs comme l'éditeur ou un administrateur. La modification du fichier sur Catenda ne change rien dans SharePoint. De même, si le fichier change dans SharePoint, rien ne change dans Catenda.

## 2. **Composant WebPart Catenda**

Avec cette application, vous ajoutez [le composant WebPart Catenda](https://support.catenda.com/en/articles/10538168-catenda-sharepoint-application-webpart) à une page de votre site. Vous pouvez permettre aux utilisateurs de parcourir les zones auxquelles ils ont accès en lecture dans la section documents d'un projet Catenda. S'ils ont accès en écriture à une partie de la structure des documents, ils pourront également charger des fichiers à cet endroit.

Voici à quoi peut ressembler un composant WebPart configuré :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/07-catenda-webpart.png)

## 3. **Autorisation de votre compte Catenda**

Si vous accédez à une page SharePoint où le composant WebPart Catenda a été activé ou si vous tentez d'utiliser l'action de publication et que vous n'avez pas encore validé votre compte, vous obtiendrez la fenêtre contextuelle suivante :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/08-authorizing-your-catenda-account.png)

_Accès requis :_ Accès API lors de l'installation de l'application. Si un nouvel onglet de navigateur ne s'ouvre pas automatiquement, veuillez copier le lien de l'onglet de validation de compte ouvert et y accéder vous-même. Si vous n'êtes pas déjà connecté, il vous sera demandé de vous connecter à Catenda dans cette fenêtre. Si vous n'en avez pas déjà un, vous pouvez créer un compte Catenda [ici](https://hub.catenda.com/signup).

> **Remarque :** L'adresse e-mail associée au compte Catenda avec lequel vous vous connectez doit être identique à l'adresse associée au compte SharePoint avec lequel vous êtes connecté.

La fenêtre d'authentification peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/09-authorizing-your-catenda-account.png)

En autorisant l'application à accéder à votre compte, vous pourrez publier des documents de SharePoint vers n'importe quelle partie de votre ou vos projet(s) Catenda auquel vous avez accès en écriture dans la [section documents](https://support.catenda.com/en/articles/8204673-documents-page). Si un composant WebPart a été ajouté à une page de votre site, vous pourrez également voir tous les documents auxquels vous avez accès en lecture dans le projet Catenda configuré par la personne qui a ajouté le composant WebPart. Avec le composant WebPart, vous pourrez également publier des documents de votre système vers n'importe quelle partie du projet Catenda configuré auquel vous avez accès en écriture dans la [section documents](https://support.catenda.com/en/articles/8204673-documents-page).

> **Remarque :** Catenda n'aura pas accès à vos documents SharePoint. Si vous publiez un document vers Catenda, Catenda le reçoit en une transaction unidirectionnelle.

Si vous ne souhaitez plus donner à l'application l'accès à votre compte Catenda, vous pouvez toujours révoquer l'accès sur la [page des applications](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) de votre compte Catenda.
