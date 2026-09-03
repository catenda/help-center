# Activation de l'application Catenda SharePoint

> **Remarque :** Le fichier d'installation du plug-in se trouve dans [cet article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

L'application Catenda SharePoint peut être activée pour un environnement SharePoint par un administrateur système, puis ajoutée à un site par un propriétaire de site. Avec cette application, les utilisateurs SharePoint pourront afficher, gérer et collaborer sur les Documents dans Catenda avec les autres Membres du projet de construction.

Pour activer l'application dans votre environnement, vous pouvez trouver son entrée ici : [Microsoft AppSource](https://appsource.microsoft.com/en-us/marketplace/apps?search=Catenda&page=1), qui peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/01-intro.png)

Après avoir cliqué sur « Obtenir maintenant », vous devrez vous connecter à votre compte SharePoint si vous n'êtes pas déjà connecté. Vous serez ensuite redirigé vers l'entrée de la boutique SharePoint. La boutique SharePoint se trouve également en cliquant sur votre profil en haut à droite de SharePoint, puis en cliquant sur Ajouter une application

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/02-intro.png)

Dans la boutique SharePoint, vous pouvez également rechercher l'application Catenda SharePoint :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/03-intro.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/\_layouts/15/appStore.aspx/sharePointStore?entry=ClassicAppCatalog&sorting=7&search=catenda**

L'entrée de la boutique SharePoint peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/04-intro.png)

**https://\<Tenant>.sharepoint.com/\_layouts/15/appStore.aspx/appDetail/WA200005981**

## 1. **Utilisateurs SharePoint ordinaires**

Les utilisateurs SharePoint ordinaires pourront demander l'activation de l'application Catenda SharePoint en cliquant sur le bouton Ajouter à la application site. Vous verrez si votre demande a été approuvée sur la page Mes demandes de la boutique SharePoint. Si vous êtes administrateur, vous pourrez approuver la demande depuis le catalogue d'applications

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/05-regular-sharepoint-users.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/SitePages/Home.aspx**

## 2. **Administrateurs SharePoint**

En tant qu'administrateur dans un environnement SharePoint, vous pourrez activer l'application en cliquant sur Ajouter à la application site. Vous serez invité à confirmer l'accès aux données.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/06-sharepoint-administrators.png)

### 2.1 **Confirmer l'accès aux données**

L'application que vous êtes sur le point d'activer aura accès aux données en utilisant l'identité de la personne qui l'utilise. Activez cette application uniquement si vous faites confiance au développeur ou à l'éditeur. L'application a besoin de cette autorisation pour savoir quels fichiers d'utilisateurs publier lorsqu'ils choisissent de les publier. Le point de terminaison est : [https://sharepoint.plugins.catenda.com/1.0.0.0/](https://sharepoint.plugins.catenda.com/1.0.0.0/)

### 2.2 **Accès à l'API**

Si l'accès à l'API n'a pas été activé précédemment, il doit être activé pour que l'application fonctionne.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/07-api-access.png)

Pour approuver l'accès à l'API, accédez à la page Accès à l'API dans votre centre d'administration https://\<Tenant>.sharepoint.com/\_layouts/15/online/AdminHome.aspx#/webApiPermissionManagement

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/08-api-access.png)

L'accès à l'API est nécessaire pour que les administrateurs SharePoint doivent connecter leur compte Catenda pour activer la publication de Documents. Les utilisateurs seront également invités à se connecter avec leur compte Catenda lorsqu'ils essaient de publier quelque chose dans Catenda, car chaque utilisateur peut avoir des autorisations différentes dans Catenda.

Sans accès à l'API, l'application Catenda SharePoint peut être activée, après quoi l'action de liste et la webpart seront visibles mais non utilisables, car aucune donnée ne peut être échangée sans connecter votre compte Catenda. _Accès requis :_ Rôle administrateur global ou rôle administrateur d'application dans Microsoft 365.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/09-api-access.png)

**Approuver l'accès** Sélectionnez Catenda dans la liste des demandes en attente et cliquez sur approuver en haut. Pour que l'application Catenda fonctionne, elle a besoin de l'autorisation : accès

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/10-api-access.png)

**Supprimer l'accès** Sélectionnez Catenda sur la page Accès à l'API et cliquez sur supprimer en haut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/11-api-access.png)

Dans le menu suivant, cliquez sur Supprimer

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/12-api-access.png)

Bien que l'application Catenda puisse être activée, les utilisateurs ne pourront pas se connecter à Catenda après la suppression de cet accès.

## 3. **Disponibilité de l'application**

### 3.1 **Activer uniquement cette application**

Cette option active l'application pour l'environnement SharePoint, ce qui permet aux propriétaires de sites de votre environnement d'ajouter l'application à partir de la page Mes applications. L'application ne fait rien jusqu'à ce qu'elle soit ajoutée à un site. Bien que cette option soit excellente, si vous souhaitez avoir un meilleur contrôle sur les sites à partir desquels les utilisateurs peuvent publier des Documents dans Catenda, cela peut prêter à confusion pour les utilisateurs si certains sites ont l'option de publication tandis que d'autres ne l'ont pas. Pour encore plus de contrôle, vous pouvez activer le [catalogue d'applications au niveau du regroupement de sites](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog), qui vous permet de choisir les applications que le propriétaire du site peut installer. Avec cette option, l'application ne sera pas activée par défaut sur les nouveaux sites, ce qui signifie qu'il y a plus de travail pour configurer un nouveau site lors de sa création.

### 3.2 **Activer cette application et l'ajouter à tous les sites**

Avec cette option, l'application sera automatiquement ajoutée à tous les sites. La seule différence visuelle que l'utilisateur verra lorsque l'application sera ajoutée à son site est qu'il aura la commande de liste dans sa liste et le menu hamburger lors de la sélection d'un Document. Les webparts et les pages complètes devront être ajoutées ultérieurement. Cela peut également être fait à partir de la page gérer les applications ultérieurement.

### 3.3 **Ajouter aux Équipes**

Avec cette option, l'application sera également ajoutée aux Équipes. Cela permettra aux utilisateurs de voir l'onglet Équipes. Cela peut également être fait à partir de la page gérer les applications ultérieurement.

## 4. **Gérer les applications**

Après avoir activé l'application, les administrateurs SharePoint pourront voir votre application dans la zone Gérer les applications. https://\<Tenant>.sharepoint.com/sites/appcatalog/AppCatalog/Forms/AllItems.aspx

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/13-manage-apps.png)

Après avoir sélectionné l'application, celle-ci peut être ajoutée à différentes parties de SharePoint.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/14-manage-apps.png)

### 4.1 **Ajouter à tous les sites :**

Cela ajoutera l'application à tous les sites et à tous les nouveaux sites créés. Si l'application est activée, les propriétaires de sites pourront également ajouter individuellement l'application à un site. Si vous ne souhaitez pas continuer à ajouter l'application aux nouveaux sites, vous pouvez arrêter en cliquant sur arrêter l'ajout aux nouveaux sites.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/15-add-to-all-sites.png)

La fonctionnalité fournie par l'application continuera à être disponible sur tous les sites où elle a été ajoutée, et le propriétaire du site pourra toujours ajouter cette application à ses sites.

### 4.2 **Ajouter aux Équipes :**

Cela active l'onglet Équipes pour l'application.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/16-add-to-teams.png)

Pour que l'application soit ajoutée aux Équipes, elle doit d'abord être ajoutée à tous les sites.

## 5. **Lectures complémentaires**

Consultez [ici](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application) pour obtenir des informations sur le fonctionnement de cette application après son installation Consultez [ici](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq) pour plus d'informations sur la manière dont cette application peut être utile.
