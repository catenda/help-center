# Intégration des modèles et documents Solibri

L'intégration de l'API Documents offre un moyen facile d'accéder à votre contenu stocké dans le cloud. Vous pouvez vous connecter à un environnement de données commun (CDE) et télécharger et charger des modèles depuis/vers le serveur.

## 1. **Connexion**

L'API Documents se trouve dans le menu des intégrations de l'onglet fichier dans Solibri. Pour commencer avec l'API Documents, vous devez d'abord donner accès à Solibri à votre compte Catenda. Pour ce faire, cliquez sur Connecter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/01-connecting.png)

La liste des serveurs auxquels vous pouvez vous connecter commencera maintenant à se charger.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/02-connecting.png)

La première fois que vous lancez Solibri, cette liste peut prendre du temps à se charger. Après le premier chargement, la liste est stockée et s'ouvrira plus rapidement. Dans le menu déroulant résultant, vous pouvez sélectionner Catenda ou Bimsync pour vous connecter à l'API Documents Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/03-connecting.png)

## 2. **Importation de documents ou de modèles**

Cliquez sur Ouvrir pour importer des documents ou des modèles auxquels vous avez accès dans Catenda Hub.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/04-importing-documents-or-models.png)

Après avoir cliqué sur Ouvrir, votre navigateur par défaut s'ouvrira.

- [Annulez votre session de navigateur](#h_e921d649ed) si vous souhaitez annuler ce processus et continuer à travailler avec Solibri
- Si vous ne l'avez pas déjà fait, [accordez l'accès à votre compte](#h_55ca1d4d10).
- Si vous n'avez pas encore sélectionné de projet, sélectionnez un projet sur la [page des projets](#h_343870704c).
- Après avoir sélectionné un projet, ou si vous avez précédemment sélectionné un projet, vous pouvez sélectionner la [page des documents](#h_b7ac757915) (_par défaut_) ou la [page des modèles](#h_617a3f8bf6).

## 3. **Export de la session Solibri vers Catenda**

Pour que le bouton Charger le modèle devienne disponible, vous devez avoir [connecté votre compte Catenda](#h_457cbf4e9d) et avoir au moins un fichier dans votre session Solibri. Cliquez sur Charger le modèle pour exporter votre session Solibri en tant que partie de votre projet Catenda auquel vous avez accès.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/05-exporting-solibri-session-to-catenda.png)

Si vous n'avez pas encore enregistré votre session Solibri ou apporté des modifications depuis votre dernier enregistrement, vous serez invité à enregistrer un fichier .smc pour qu'il puisse être chargé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/06-exporting-solibri-session-to-catenda.png)

Le .smc qui a été enregistré peut maintenant être exporté en tant que nouvelle révision vers Catenda et réimporté ultérieurement dans Solibri si vous souhaitez continuer votre session avec la dernière révision. Après avoir enregistré votre fichier .smc, cliquez à nouveau sur Charger le modèle.

Après avoir cliqué sur Charger le modèle, votre navigateur par défaut s'ouvrira.

- [Annulez votre session de navigateur](#h_e921d649ed) si vous souhaitez annuler ce processus et continuer à travailler avec Solibri
- Si vous ne l'avez pas déjà fait, [accordez l'accès à votre compte](#h_55ca1d4d10).
- Si vous n'avez pas encore sélectionné de projet, sélectionnez un projet sur la [page des projets](#h_343870704c).
- Après avoir sélectionné un projet, ou si vous avez précédemment sélectionné un projet, vous serez présenté avec la [page des documents](#h_b7ac757915).

## 4. **Intégration des documents Solibri -** Page des projets

Après avoir cliqué sur Ouvrir et vous être connecté, si vous venez d'autoriser l'accès ou si vous avez précédemment accordé l'accès, une page similaire à la page des projets de Catenda Hub s'ouvrira dans votre navigateur par défaut. La page des projets d'intégration des documents Solibri peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/07-solibri-document-integration-projects-page.png)

> **Note :** Cette page est créée par Solibri et n'est pas la même que la page des projets régulière dans Catenda Hub. Seules les sections modèles et documents de Catenda peuvent être consultées. Les fonctionnalités de Catenda Hub comme l'aperçu des documents et la configuration d'accès ne fonctionnent pas ici.

## 5. **Intégration des documents Solibri -** Page des documents

Consultez les documents auxquels vous avez accès avec votre compte Catenda sur la page des documents de l'intégration des documents Solibri. Ici, vous pouvez configurer les documents qui seront synchronisés avec Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/08-solibri-document-integration-documents-page.png)

### 5.1 **Navigation**

Cliquez sur le nom du projet si vous souhaitez naviguer vers un projet différent. Cliquez sur modèles dans le menu de gauche pour importer par modèle au lieu de par document.

> **Note :** La page des modèles n'est disponible que lors du téléchargement.

### 5.2 **Structure du document**

Pour chaque document, vous verrez :

- Icône de type de fichier
- Nom du document
- Numéro de révision
- Statut du document
- Étiquettes (cliquez sur les 3 points pour voir plus d'étiquettes)
- Taille du fichier
- Créateur de la dernière révision
- Date de publication de la dernière révision
- Bouton 3D (Aperçu du modèle avant l'importation)
- Liens d'objet (Sélectionnez les objets liés dans l'aperçu 3D en cliquant sur ce nombre)

Sélectionnez un ensemble de documents en cochant les cases ou cochez la case en haut pour sélectionner tous.

### 5.3 **Menu d'information à droite**

Après la sélection, le menu d'information apparaîtra en haut à droite. S'il est fermé, cliquez sur l'icône `i` pour l'agrandir.

### 5.4 **Menu d'information droit -** Télécharger

Lors de l'importation, vous pouvez configurer les documents qui seront importés dans Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/09-right-information-menu-download.png)

Cliquez sur Télécharger en bas pour importer la dernière révision partagée de chaque document sélectionné.

### 5.5 **Menu d'information droit -** Charger

Lors de l'export, vous pouvez configurer le fichier .smc qui sera chargé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/10-right-information-menu-upload.png)

**Mettre à jour le nom du document** Avec cette option activée, le nom du document sélectionné sera mis à jour avec le nom que vous avez donné à votre fichier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/11-right-information-menu-upload.png)

De cette façon, vous pouvez vous assurer que vous pouvez continuer à charger des révisions vers un document tout en vous assurant qu'il a toujours le même nom que ces révisions.

**Sélectionner automatiquement les documents similaires** Avec cette option activée, vous pourrez charger votre fichier vers un document ayant un nom similaire, même s'il n'est pas exactement le même. Notez que la révision chargée aura toujours le nom de fichier que vous avez spécifié.

**Nom de fichier** Ici, vous verrez le nom du fichier qui sera chargé vers Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/12-right-information-menu-upload.png)

Par défaut, le nom du fichier smc que vous avez enregistré sur votre système s'affichera. Le nom peut toujours être modifié à ce moment. Configurez le nom du fichier en cliquant sur le crayon à droite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/13-right-information-menu-upload.png)

**Document** Ici, vous verrez le nom du document sur Catenda qui recevra le fichier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/14-right-information-menu-upload.png)

Par défaut, il aura le même nom que le nom de fichier. S'il n'y a pas de document portant ce nom dans votre dossier actuel, ce champ sera vert, indiquant qu'un nouveau document sera créé. Le nom que votre document aura peut toujours être modifié à ce moment. S'il y a d'autres documents .smc dans ce dossier, vous pourrez cliquer sur le nom du document pour sélectionner l'un des autres documents vers lequel vous aimeriez que votre fichier .smc soit chargé en tant que révision. Si vous avez choisi un document ou s'il y a un document dans le dossier actuel avec le même nom, ce champ sera gris. Vous verrez alors un message d'avertissement indiquant qu'un document portant ce nom existe déjà et que votre fichier smc sera chargé en tant que nouvelle révision vers ce document.

**Statut** Si le flux de statut a été activé pour votre projet, vous verrez la liste déroulante de statut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/15-right-information-menu-upload.png)

Si vous créez un nouveau document, ou si votre document n'a pas encore de statut, vous ne verrez aucun statut. Si vous ajoutez une révision à un document existant, vous verrez le statut de ce document et pourrez modifier le statut du document lors du chargement. Si vous souhaitez modifier le statut du document lorsque votre révision est chargée, vous pouvez le sélectionner dans la liste des statuts disponibles dans le projet.

### 5.6 **Documents reçus**

Lorsque le téléchargement a démarré avec succès, vous verrez le message suivant dans le navigateur

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/16-documents-received.png)

Si vous revenez à Solibri, vous verrez que les documents ont commencé à être traités. Les documents téléchargés seront stockés dans un dossier temporaire pendant que votre session Solibri est active. Pensez à enregistrer votre session Solibri ou à charger une nouvelle révision sur Catenda si vous souhaitez enregistrer les modifications apportées à votre fichier. Les révisions de documents chargées seront stockées sur Catenda. La dernière révision peut être ouverte à nouveau dans Solibri ultérieurement.

## 6. **Intégration des documents Solibri -** Page des modèles

Consultez les modèles auxquels vous avez accès avec votre compte Catenda sur la page des modèles de l'intégration des documents Solibri. Ici, vous pouvez configurer les modèles qui seront synchronisés avec Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/17-solibri-document-integration-models-page.png)

Cliquez sur le nom du projet si vous souhaitez naviguer vers un projet différent. Pour chaque modèle, vous verrez :

- Nom du modèle
- Numéro de révision
- Type IFC
- Date de création de la dernière révision
- Créateur de la dernière révision

Sélectionnez un ensemble de modèles en cochant les cases ou cochez la case en haut pour sélectionner tous. Après la sélection, le menu d'information apparaîtra en haut à droite. S'il est fermé, cliquez sur l'icône `i` pour l'agrandir. Ici, vous pouvez modifier votre sélection de modèles à importer dans Solibri. Cliquez sur Télécharger en bas pour importer la dernière révision partagée de chaque modèle sélectionné.

## 7. **Annuler la session du navigateur**

Pendant que votre session de navigateur est active, vous verrez le message suivant dans Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/18-cancel-browser-session.png)

Appuyez sur Annuler si vous souhaitez terminer le processus d'importation.

## 8. **Octroyer l'accès à votre compte Catenda**

Si vous n'êtes pas encore connecté à Catenda, vous serez invité à [vous connecter](https://support.catenda.com/en/articles/7891486-sign-in-page). Après l'ouverture pour la première fois, après vous être connecté ou si vous étiez déjà connecté, vous serez invité à autoriser l'accès à votre compte Catenda :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/19-granting-access-to-your-catenda-account.png)

Si vous étiez déjà connecté, mais pas avec le bon compte, vous pouvez cliquer sur votre photo de profil pour vous déconnecter et vous connecter avec le bon compte. Lorsque vous êtes certain d'être connecté avec le bon compte, cliquez sur Autoriser l'accès pour continuer. Si vous attendez trop longtemps pour le faire, cela ne fonctionnera pas, alors assurez-vous d'avoir votre mot de passe prêt ! Après avoir accordé l'accès à votre compte avec succès, vous verrez le message suivant :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/20-granting-access-to-your-catenda-account.png)

## 9. **Gestion des documents liés**

Les documents qui ont été liés depuis Catenda dans Solibri peuvent différer des documents réguliers qui ont été ouverts à partir du système local. Voici à quoi ressemblent les documents lorsqu'ils ont été liés à des documents sur Catenda :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/21-managing-linked-documents.png)

### 9.1 **Colonne Nom**

Le nom du modèle peut prendre du temps à se mettre à jour, mais finira par changer pour refléter le nombre de révisions du document sur Catenda. Si votre organisation a défini une préférence pour le nom de téléchargement de votre document, vous pourriez trouver un nom différent ici. Par exemple, il est possible de demander le nom du document sans l'option de révision. Notez que cela doit être demandé par l'organisation pour tous les fichiers téléchargés dans leurs projets. Vous pouvez voir les différentes options de nom de téléchargement pour les organisations [ici](https://support.catenda.com/en/articles/8224886-organization-options).

### 9.2 **Colonne Version**

La colonne Version vous aidera à suivre la révision actuellement chargée. Si la publication de révision a été activée sur votre projet Catenda, vous verrez peut-être des numéros de révision majeurs (1.0, 2.0, 3.0, etc...) et mineurs (1.1, 1.2, 2.1, etc...) ici.

### 9.3 **Colonne Lien**

Après l'importation d'un modèle depuis Catenda Hub, une icône de chaîne s'affichera dans la troisième colonne pour montrer qu'il est lié.

### 9.4 **Survol du modèle**

Si vous survolez un document qui a été lié depuis Catenda, vous verrez `[API Documents] Catenda` suivi du nom du document.

### 9.5 **Menu contextuel -** Mises à jour

Cliquez avec le bouton droit sur un document pour ouvrir le menu contextuel. Ici, les préférences de mise à jour du document peuvent être configurées.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/22-context-menu-updates.png)

**Mettre à jour les modèles** Voici à quoi pourrait ressembler la boîte de dialogue de mise à jour des modèles si vous avez sélectionné plusieurs documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/23-context-menu-updates.png)

Dossier - Cliquez sur le dossier si vous souhaitez choisir un fichier local pour ce modèle à la place.

Version - Ici, vous verrez le numéro de version dans Catenda avec une coche qui montre si vous travaillez actuellement avec la dernière révision ou non. Mise à jour - Cochez la case de mise à jour pour chaque modèle ou pour tous les modèles en cochant la case en haut et cliquez sur Mettre à jour les modèles pour les mettre à jour.

Paramètres - Cliquez sur Paramètres pour ouvrir les paramètres de mise à jour du modèle pour vos documents sélectionnés.

Relier à nouveau les modèles - Relier à nouveau les modèles ne fonctionne que si vous avez sélectionné les modèles locaux dans cette boîte de dialogue et non les modèles Catenda.

**Paramètres de mise à jour du modèle**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/24-context-menu-updates.png)

Automatique - Lorsqu'une nouvelle révision est disponible dans Catenda Hub, le modèle se met à jour automatiquement.

Invite - Une invite s'affichera lorsqu'une nouvelle révision est disponible sur Catenda. La mise à jour vers la nouvelle révision commencera à votre convenance.

Relier à nouveau les modèles - Relier à nouveau les modèles ne fonctionne que si vous avez sélectionné les modèles locaux dans cette boîte de dialogue et non les modèles Catenda.

### 9.6 **Menu contextuel -** Hyperliens

Vers le bas du menu contextuel du document, vous verrez les hyperliens.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/25-context-menu-hyperlinks.png)

Pour chacun des documents sélectionnés qui a un lien vers Catenda, vous verrez "Catenda" lorsque vous ouvrirez chacun des menus hyperliens. Voici à quoi pourrait ressembler le menu hyperliens développé :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/26-context-menu-hyperlinks.png)

Nouvel hyperlien - Cliquer sur Nouvel hyperlien ouvre le menu Ajouter un hyperlien qui peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/27-context-menu-hyperlinks.png)

Afficher - Cliquez sur "Catenda" pour ouvrir ce document lié sur Catenda.

Modifier - Cliquez sur "Catenda" pour modifier le lien pour ce document sélectionné. Le menu Modifier l'hyperlien s'ouvrira maintenant et peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/28-context-menu-hyperlinks.png)

L'adresse devrait ressembler à ceci : [https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx](https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)

Le sujet sera Catenda par défaut, mais peut être renommé en n'importe quoi d'autre.

Les liens Catenda sont toujours Absolus, ce qui signifie qu'ils ne sont pas relatifs à l'endroit où se trouve votre fichier .smc sur votre système.

Supprimer - Cliquez sur "Catenda" pour supprimer le lien pour ce document sélectionné.
