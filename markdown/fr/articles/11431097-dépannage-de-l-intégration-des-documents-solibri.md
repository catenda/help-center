# Dépannage de l'intégration des documents Solibri

Les erreurs qui peuvent être rencontrées lors de l'intégration des documents Solibri et comment les résoudre sont expliquées dans cet article.

## 1. **Connexion et accès au compte**

### 1.1 **Déconnexion lors du téléchargement/non recommandé**

Il est possible de se déconnecter de votre compte dans le menu de sélection des documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/01-signing-out-during-up-download-not-recommended.png)

Si vous vous déconnectez ici et vous reconnectez, la page ressemblera plutôt à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/02-signing-out-during-up-download-not-recommended.png)

Bien que vous puissiez accéder à un compte Catenda différent de celui auquel vous avez accordé l'accès de cette manière, ce n'est pas recommandé. L'accès n'aura pas été accordé pour ce compte et les modèles ou documents que vous naviguerez ne seront pas importés dans Solibri.

### 1.2 **Téléchargement -** Pas d'accès au document

Si vous essayez de télécharger votre smc vers une révision à laquelle vous n'avez pas accès, vous verrez l'avertissement suivant.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/03-upload-no-access-to-document.png)

Dans cette situation, veuillez demander à un administrateur de projet s'il peut vous donner accès au document.

### 1.3 **Téléchargement -** Pas d'accès au dossier

Si vous essayez de créer un nouveau document dans un dossier auquel vous n'avez que l'accès en lecture, vous verrez le message suivant.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/04-upload-no-access-to-folder.png)

Dans cette situation, veuillez demander à un administrateur de projet s'il peut vous donner au moins l'accès en écriture au dossier.

### 1.4 **Révoquer l'accès à votre compte Catenda**

Accédez à la page des applications de votre compte Catenda Hub [paramètres du compte](https://intercom.help/bimsync-arena/en/articles/6880968-account-settings#:~:text=your%20notification%20settings.-,Applications,-In%20applications%20you), trouvez l'application Solibri et cliquez sur révoquer.

### 1.5 **Déconnexion du serveur Catenda**

Si vous ne souhaitez plus vous connecter au serveur Catenda, cliquez sur déconnecter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/05-disconnect-from-the-catenda-server.png)

Après la déconnexion, Solibri aura toujours accès à votre compte. Si vous souhaitez vous reconnecter ultérieurement, vous n'aurez pas à vous authentifier à nouveau.

### 1.6 **Se connecter avec un nouveau compte**

Dans les situations suivantes, il peut être utile de se connecter avec un nouveau compte :

- L'accès à votre compte a été révoqué.
- Donner accès à un compte différent.
- Réinitialiser la connexion si elle a cessé de fonctionner

L'ancien compte peut être déconnecté de la manière suivante :

### 1.7 **Révoquer l'accès sur Catenda**

Pour révoquer l'accès accordé à Solibri sur un compte, connectez-vous avec le compte sur Catenda. Après vous être connecté, accédez à la page des applications [https://hub.catenda.com/account/apps](https://hub.catenda.com/account/apps) Si l'accès Solibri a été accordé à ce compte, vous verrez Solibri dans la liste des applications avec accès au compte. Cliquez sur révoquer l'accès. Si Solibri était connecté avec ce compte, il demandera à l'utilisateur d'accorder l'accès à un nouveau compte.

### 1.8 **Supprimer le dossier .solibri**

Une autre façon de supprimer la connexion à un compte Catenda est de supprimer les données utilisateur dans Solibri. Pour ce faire, supprimez le dossier situé ici :

`C:\Users\<Username>\.solibri`

> **Remarque :** Par défaut, il s'agit d'un dossier masqué sur votre système. Tapez le chemin directement dans votre explorateur de fichiers ou découvrez comment afficher les dossiers masqués ici : [https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5)

Les données de connexion Solibri sont stockées dans ce dossier, de sorte que Solibri devra être connecté à nouveau la prochaine fois qu'il sera ouvert.

## 2. **Téléchargement**

### 2.1 **Document demandé non trouvé**

Si vous avez ouvert votre .smc à partir de Catenda, l'emplacement du projet à partir duquel vous l'avez ouvert sera mémorisé. Lorsque vous retéléchargez ultérieurement le .smc vers Catenda et que le document a été déplacé ou n'existe pas dans le projet que vous avez navigué, vous verrez le message suivant.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/06-requested-document-not-found.png)

### 2.2 **Pas de nouvelle révision**

Si vous avez ouvert un .smc de Catenda et le retéléchargez vers Catenda sans faire aucune modification, même si vous avez enregistré le smc quelque part, on ne vous demandera pas de l'enregistrer en premier et il semblera être téléchargé. Après le téléchargement, vous recevrez le message suivant comme prévu :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/07-no-new-revision.png)

Si votre fichier avait le même nom qu'un document dans le dossier, vous verrez qu'aucune nouvelle révision n'est ajoutée à ce document dans Catenda. Veuillez essayer de retélécharger votre .smc si c'est le cas.

### 2.3 **Nouveau document au lieu d'une nouvelle révision**

Si votre fichier avait un nom différent, mais que vous avez sélectionné un document pour lequel la révision devait être téléchargée, vous verrez qu'un nouveau document sera créé en fonction du nom de votre fichier et que votre fichier ne sera pas une nouvelle révision du document. Assurez-vous que votre fichier porte le même nom que le document si vous souhaitez qu'il devienne une nouvelle révision de ce document et non un nouveau document.

### 2.4 **Bouton non disponible**

Si vous essayez de télécharger des documents, vous pourriez voir le message indiquant qu'aucun fichier n'est sélectionné.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/08-button-not-available.png)

Cela peut être le cas lorsque vous avez accordé l'accès Solibri à Catenda avec un compte, mais que vous essayez de télécharger un fichier .smc avec un autre compte. Pour donner accès à un compte différent, voir [ici](#h_0ef63a37db).

## 3. **Télécharger**

### 3.1 **Erreur**

Si vous avez sélectionné un document, vous pourriez voir une erreur dans le menu de droite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/09-error.png)

Cela peut être le cas lorsque vous avez accordé l'accès Solibri à Catenda avec un compte, mais que vous essayez de télécharger le document avec un autre compte. Pour donner accès à un compte différent, voir [ici](#h_0ef63a37db).

### 3.2 **Type de fichier non supporté**

Avec l'intégration des documents, après avoir navigué et sélectionné un document non supporté sur la page des documents dans un projet, vous verrez le message suivant dans le menu d'informations de droite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/10-filetype-not-supported.png)

La tentative de téléchargement d'un document avec une extension différente n'aura aucun effet.

### 3.3 **Rien ne se passe**

Le compte auquel vous êtes connecté est différent du compte auquel vous avez accordé l'accès.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/11-nothing-happens.png)
