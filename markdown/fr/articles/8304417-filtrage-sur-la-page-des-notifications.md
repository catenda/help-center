# Filtrage sur la page des notifications

Tant dans vos [paramètres de notification](https://support.catenda.com/en/articles/8272435-notification-settings) que dans vos [paramètres de notification spécifiques au projet](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings), vous pourrez configurer les notifications que vous souhaitez recevoir.

Les situations dans lesquelles une notification est envoyée pour les différents paramètres seront expliquées dans cet article. Une fois la notification envoyée, vous pourrez la retrouver sur la [page des notifications du compte](https://support.catenda.com/en/articles/7439223-account-notifications-page) et la [page des notifications du projet](https://support.catenda.com/en/articles/4670295-project-notifications-page) en ouvrant le bouton du menu de filtres sur la gauche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/810mbm4a/01-intro.png)

## 1. **Historique des notifications**

Les notifications commencent à être envoyées à un membre dès qu'il a rejoint un projet. L'historique des notifications dans un projet remonte donc au moment où le projet a été rejoint. Les membres qui font partie du projet depuis plus longtemps pourraient donc être en mesure de rattraper les événements passés que les nouveaux membres n'ont pas.

## 2. **Filtres**

Cliquez sur le bouton de filtre en haut à gauche pour qu'un panneau apparaisse sur le côté gauche. Lorsqu'un filtre est appliqué, l'URL visible dans le navigateur change en conséquence. Dans cet article, les filtres sont affichés comme suit :

### 2.1 **_Nom du filtre dans le menu_ - `Nom du filtre dans l'URL=Option de filtre dans l'URL`**

**Filtre par défaut** Le filtre par défaut n'est initialement pas visible dans l'URL. Lorsque la page est consultée pour la première fois, le filtre suivant est appliqué.

### 2.2 _Il y a un mois_ - `dateFrom=last-month`

### 2.3 **Enregistrer et partager le filtre actuel**

Accédez à l'URL d'une page filtrée pour charger cette page avec le filtre appliqué. Les filtres appliqués peuvent être enregistrés en haut du menu de filtres. Cliquez [ici](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) pour en savoir plus sur la façon d'enregistrer et de partager les filtres

### 2.4 **Masquer les filtres vides**

Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la limitation des résultats de filtre.

## 3. **Filtres de date**

Avec le filtre de date, vous pouvez sélectionner une période pour laquelle les notifications ont été envoyées.

### 3.1 **Il y a une semaine** - `dateFrom=last-week`

Notifications de la semaine dernière.

### 3.2 **Il y a un mois** - `dateFrom=last-month`

Si vous accédez à la page des notifications du compte, elle sera filtrée par les notifications du mois dernier par défaut.

### 3.3 **Il y a un an** - `dateFrom=last-year`

Notifications de l'année dernière.

### 3.4 **Choisir une date** - `date-from=<Epoch Unix Timestamp>&date-to=<Epoch Unix Timestamp>`

Lisez [cet](https://support.catenda.com/en/articles/6511685-date-filter) article pour apprendre à sélectionner facilement les dates sur la page.

### 3.5 **Toutes les notifications**

Pour voir toutes les notifications que vous avez jamais reçues, supprimez le filtre dateFrom de l'URL.

## 4. **Type**

Le menu de type inclut tous les types de notifications filtrables.

Les notifications sont divisées en les types suivants :

## 5. **Tous** - `type=all`

Toutes les notifications sont envoyées à la fois dans le navigateur et par e-mail par défaut. Si vous accédez à une page de notifications, elle sera filtrée par les notifications du mois dernier par défaut. Si vous supprimez le filtre dateFrom de l'URL et utilisez le filtre type=all, vous pourrez voir toutes les notifications que vous avez jamais reçues.

## 6. **Modèles** - `type=models`

_Nouveau modèle -_ `type=new-model` La notification affiche le nom du modèle qui a été créé.

**Un clic sur la notification vous mène à :** Page d'aperçu du modèle du projet dans lequel le modèle est créé.

**Option de paramètre de notification :** Un nouveau modèle est créé

### 6.1 **Envoyé même si toutes les cases à cocher ne sont pas cochées dans les paramètres**

_L'enregistrement a échoué_ - `type=checkin-failed` Si le formatage de votre fichier IFC n'est pas reconnu par notre système

_L'importation a échoué_ - `type=import-failed` Cela peut se produire si votre connexion a été interrompue lors du téléchargement.

_Importation terminée_ - `type=import-completed` Lorsqu'un modèle a fini de traiter

**Option de paramètre de notification :** Une nouvelle révision est importée

_Exportation réussie_ - `type=export-completed` Lorsque l'exportation de votre modèle a réussi à terminer la compression et est prête pour le téléchargement.

**Option de paramètre de notification :** Une nouvelle exportation est créée

## 7. **Sujets** - `type=issues`

### 7.1 **Nouveau sujet** - `type=new-issue`

C'est la seule notification que vous recevez à propos d'un sujet si vous ne [suivez](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) pas le sujet. Les assignés, les demandeurs et les membres mentionnés dans les sujets suivent automatiquement le sujet et recevront les notifications ci-dessous.

**Option de paramètre de notification :** Un nouveau sujet est créé

### 7.2 **Nouveau commentaire** - `type=new-comment`

Si vous n'êtes ni l'assigné ni le demandeur du sujet mais que vous [suivez](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) le sujet, vous recevrez cette notification.

Cela peut se produire si vous avez précédemment été [assigné](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [demandeur](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [mentionné](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) ou [suivi manuellement](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) le sujet. Si vous ne souhaitez pas recevoir de futures notifications sur ce sujet, vous pouvez arrêter de suivre le sujet dans son [panneau d'informations à droite](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Option de paramètre de notification : assigné à moi_ Un sujet vous est assigné

**Option de paramètre de notification : demandé par moi** Un sujet vous est demandé

**Option de paramètre de notification : suivi par moi** Un sujet est suivi par vous

### 7.3 **Assigné à moi** - `type=issue-assigned`

**Option de paramètre de notification :** Un sujet m'est assigné

### 7.4 **Équipe assignée** - `type=issue-team-assigned`

Lorsqu'une équipe est assignée à un sujet

**Option de paramètre de notification :** Un sujet m'est assigné

### 7.5 Me mentionnant - `type=issue-mentioned`

**Options de paramètre de notification :** Un sujet me mentionne ou mentionne l'une de mes équipes

### 7.6 **Équipe mentionnée** - `type=issue-team-mentioned `

**Options de paramètre de notification :** Un sujet me mentionne ou mentionne l'une de mes équipes

### 7.7 **Statut mis à jour** - `type=status-updated`

Si vous n'êtes ni l'assigné ni le demandeur du sujet mais que vous [suivez](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) le sujet, vous recevrez cette notification.

Cela peut se produire si vous avez précédemment été [assigné](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [demandeur](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [mentionné](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) ou [suivi manuellement](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) le sujet. Si vous ne souhaitez pas recevoir de futures notifications sur ce sujet, vous pouvez arrêter de suivre le sujet dans son [panneau d'informations à droite](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Option de paramètre de notification : assigné à moi_ Un statut est mis à jour dans un sujet qui vous est assigné

**Option de paramètre de notification : demandé par moi** Un statut est mis à jour dans un sujet qui vous est demandé

**Option de paramètre de notification : suivi par moi** Un statut est mis à jour dans un sujet suivi par vous

### 7.8 **Type mis à jour** - `type=type-updated`

Si vous n'êtes ni l'assigné ni le demandeur du sujet mais que vous [suivez](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) le sujet, vous recevrez cette notification.

Cela peut se produire si vous avez précédemment été [assigné](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [demandeur](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [mentionné](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) ou [suivi manuellement](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) le sujet. Si vous ne souhaitez pas recevoir de futures notifications sur ce sujet, vous pouvez arrêter de suivre le sujet dans son [panneau d'informations à droite](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Options de paramètre de notification :_

Assigné à moi - Un type est mis à jour dans un sujet qui vous est assigné

Demandé par moi - Un type est mis à jour dans un sujet qui vous est demandé

Suivi par moi - Un type est mis à jour dans un sujet suivi par vous

### 7.9 **Envoyé même si toutes les cases à cocher ne sont pas cochées dans les paramètres**

### 7.10 **Déplacement réussi** - `type=issues-move-success`

Affiche le nombre de sujets qui ont été déplacés et vers quelle Liste de sujets ils ont été déplacés.

### 7.11 **Déplacement échoué** - `type=issues-move-failed`

Affiche le nombre de sujets dont le déplacement a échoué et vers quelle Liste de sujets ils ont échoué à être déplacés.

### 7.12 **Importation échouée** - `type=issues-import-failed`

Affiche le type d'importation de sujet qui n'a pas pu être importé et sur quelle Liste de sujets il n'a pas pu être importé. _Types possibles d'importation de sujets :_ BCF

### 7.13 **Importation terminée** - `type=issues-import-success`

Affiche le type d'importation de sujet qui a été importé avec succès et sur quelle Liste de sujets il a été importé. _Types possibles d'importation de sujets :_ BCF

### 7.14 **Exportation échouée** - `type=issues-export-failed`

Affiche le type d'exportation de sujet qui a échoué et de quelle Liste de sujets elle a échoué à exporter. _Types possibles d'exportation de sujets :_ BCF 2.0, BCF 2.1, BCF 2.0, PDF, Excel

### 7.15 **Exportation réussie** - `type=issues-export-success`

Affiche le type d'exportation de sujet qui a été exporté avec succès et de quelle Liste de sujets elle a été exportée. _Types possibles d'exportation de sujets :_ BCF 2.0, BCF 2.1, BCF 2.0, PDF, Excel

## 8. **Documents** - `type=documents`

### 8.1 **Document ajouté** - `type=document-created`

_Option de paramètre de notification :_ Un document ou un dossier est créé

### 8.2 **Nouvelle révision de document** - `type=document-revision-uploaded`

_Option de paramètre de notification :_ Une nouvelle révision de document est téléchargée

### 8.3 **Virus détecté** - `type=document-file-infected`

Si un document est détecté comme étant infecté par un virus, vous recevrez une notification indépendamment du paramètre du résumé des e-mails. Une notification sera également envoyée aux administrateurs du projet du document infecté. La notification indiquera qui a téléchargé quel document et où.

Si vos notifications par e-mail sont complètement désactivées, cette notification ne sera pas envoyée en tant que notification par e-mail. Vous recevrez toujours la notification dans Catenda Hub même si les notifications de Catenda Hub sont désactivées.

> **Remarque :** Cette notification sera envoyée même si toutes les notifications ont été désactivées

### 8.4 **Document supprimé** - `type=document-deleted`

_Option de paramètre de notification :_ Un document ou un dossier est supprimé

### 8.5 **Documents supprimés** - `type=documents-deleted`

_Option de paramètre de notification :_ Un document ou un dossier est supprimé

### 8.6 **Documents téléchargés** - `type=documents-uploaded`

_Notification envoyée si :_ Un document a été téléchargé par un autre utilisateur

### 8.7 **Approbation de document**

**Options de paramètre de notification :** Je suis défini comme éditeur dans une demande d'approbation Une équipe dont je suis membre est définie comme éditeur dans une demande d'approbation Je suis défini comme relecteur pour une demande d'approbation Nouveau commentaire dans la demande d'approbation

### 8.8 **Extraction zip terminée**

_Notification envoyée si :_ Un dossier zip est importé avec succès.

> **Remarque :** Cette notification sera envoyée même si toutes les notifications ont été désactivées

### 8.9 **Votre téléchargement zip est prêt**

Si vous avez téléchargé plusieurs documents à la fois, un zip sera préparé. Ce zip peut être téléchargé à partir de la notification à tout moment, même si vous devez fermer le navigateur et le rouvrir.

Cliquez sur la partie de texte "_Cliquer pour télécharger (...MB)_" de la notification pour télécharger le fichier zip.

Si vous cliquez simplement sur la notification, elle actualisera simplement la page.

Le nom du zip téléchargé sera _\<Download GUID>.zip_ en contraste avec le nom du zip que vous obtenez automatiquement si vous attendez que le zip termine la compression après avoir cliqué sur télécharger, qui est \<Projectname>-\<Documents>-\<Timestamp>.zip Notification envoyée à : _L'utilisateur qui a téléchargé les documents._

> **Remarque :** Cette notification sera envoyée même si toutes les notifications ont été désactivées

## 9. **Collections** - `type=document-collections`

### 9.1 **Collection finalisée** - `type=library-item-collection-finalized`

**Notification envoyée si** Vous ou une équipe dont vous faites partie êtes défini comme suivi d'une collection et la collection est finalisée.

**Option de paramètre de notification** Collection finalisée

### 9.2 **Suivi d'une collection** - `type=library-item-collection-made-follower`

**Notification envoyée si** Vous ou une équipe dont vous faites partie avez été ajoutés en tant que suivi à une collection.

**Option de paramètre de notification** Suivi d'une collection

### 9.3 **Arrêt du suivi d'une collection** - `type=library-item-collection-removed-follower`

**Notification envoyée si** Vous ou une équipe dont vous faites partie avez été supprimés d'une collection.

**Option de paramètre de notification** Arrêt du suivi d'une collection

### 9.4 **Collection mise à jour** - `type=library-item-collection-updated`

**Notification envoyée si** Une collection est partagée avec le projet et vous ou une équipe dont vous faites partie avez été définis comme suivi.

**Option de paramètre de notification** Collection mise à jour

### 9.5 **Collection rendue privée** - `type=library-item-collection-made-private`

**Notification envoyée si** Vous, ou une équipe dont vous faites partie, êtes définis comme suivi d'une collection qui est partagée avec le projet et la collection est rendue privée.

**Option de paramètre de notification** Collection rendue privée

### 9.6 **Collection supprimée** - `type=library-item-collection-deleted`

**Notification envoyée si** Vous êtes administrateur et un autre administrateur supprime une collection dans le projet.

**Option de paramètre de notification** Collection supprimée

### 9.7 **Collection partagée en externe** - `type=library-item-collection-shared-externally`

**Notification envoyée si** Vous êtes administrateur et un autre administrateur partage une collection dans le projet en externe.

**Option de paramètre de notification** Collection partagée en externe

## 10. **Membres** - `type=members`

### 10.1 **Nouvelle invitation** - `type=invite`

**Notification envoyée si :** Un autre utilisateur vous envoie une invitation à un projet. La notification décrit qui vous a invité et à quel projet vous avez été invité. Si vous avez reçu cette notification, vous devriez également avoir reçu un e-mail avec un lien d'invitation que vous pouvez cliquer pour accepter l'invitation. Veuillez vérifier [ici](https://support.catenda.com/en/articles/8417802-why-am-i-not-receiving-emails) pour le dépannage des e-mails.

> **Remarque :** La notification dans Catenda Hub inclut également le lien d'invitation afin que vous puissiez également cliquer sur la notification pour accepter l'invitation. Si vous n'avez pas encore de compte, vous devrez peut-être en créer un et être invité à nouveau pour pouvoir cliquer sur la notification.

**Option de paramètre de notification** Une personne est invitée au projet.

### 10.2 **Nouveau membre** - `type=member-accept-invitation`

**Notification envoyée si** Si un utilisateur accepte une invitation envoyée par un autre membre, une notification est envoyée indiquant qu'un nouveau membre a rejoint le projet.

**Option de paramètre de notification** Un nouvel utilisateur a rejoint le projet

### 10.3 **Ajouté à l'équipe** - `type=member-added-to-team`

**Notification envoyée si** Vous avez été ajouté à une équipe.

### 10.4 **Nouveau membre de l'équipe** - `type=project-member-added-to-team`

**Option de paramètre de notification** Un membre est ajouté à une équipe

## 11. **Projet**

### 11.1 **Nom du projet** - `projects=<Project GUID>`

## 12. **Limite**

### 12.1 **Nombre de notifications par page** - `limit=<Notification amount>`

_Remarque :_ Le chargement de la page peut prendre plus de temps avec plus de notifications.

## 13. **Page**

### 13.1 **Page actuelle des notifications** - `page=<Page number>`

## 14. **Notifications obligatoires**

Il existe des notifications qui seront envoyées même si vous avez décoché toutes les cases dans les paramètres de notification.

### 14.1 **Envoyé même si toutes les cases à cocher ne sont pas cochées**

Tout type d'importation ou d'exportation qui s'exécute en arrière-plan produira une notification sur le résultat de l'importation, qu'elle ait été importée ou échouée. Si vous désactivez complètement les notifications avec le bouton marche/arrêt en haut à droite, ces notifications ne seront pas envoyées non plus.

### 14.2 **Envoyé même si toutes les notifications sont désactivées**

Les notifications concernant les liens partagés avec les utilisateurs via la fonction [sharelink](https://support.catenda.com/en/articles/4728886-sharelink-notify-people-about-catenda-hub-content) créeront toujours une notification pour l'utilisateur même si un utilisateur a complètement désactivé les notifications avec le bouton marche/arrêt en haut à droite de la page des paramètres de notification.
