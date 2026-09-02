# Dépannage du Bureau Connector

Les rubriques suivantes sont décrites dans cet article :

## 1. **Convention de nommage**

Si une convention de nommage est activée sur le dossier de téléchargement ou un dossier parent du dossier de téléchargement, le nom de fichier local doit respecter la convention pour que le téléchargement soit effectué. Si le nom de fichier ne respecte pas la convention, l'erreur suivante s'affiche.

**`<Nom de fichier> ne correspond pas à la convention de nommage`**

Veuillez télécharger le fichier manuellement via le navigateur pour voir quelles parties du nom de fichier manquent.

## 2. **Emplacement du projet serveur**

Plusieurs erreurs peuvent se produire lors de l'ouverture de l'emplacement du projet serveur.

### 2.1 **Emplacement du projet vide**

Pour synchroniser vos fichiers locaux avec un projet, vous devez avoir au moins un dossier dans la section Documents du projet sur Catenda Hub.

### 2.2 **Projet non trouvé**

Lorsque le Bureau Connector est ouvert pour la première fois, tous les projets auxquels l'utilisateur a accès sont chargés. Sans actualisation, ces mêmes projets s'affichent à la prochaine ouverture. Si l'utilisateur a perdu l'accès au projet, le message suivant s'affichera lors de la tentative de définir un emplacement serveur dans une tâche de téléchargement ou de chargement pour le projet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/01-project-not-found.png)

Veuillez demander à un administrateur de projet l'accès au projet. Pour savoir qui contacter pour accéder au projet, veuillez contacter le support Catenda.

## 3. **Apparence des documents**

Les rubriques suivantes sont décrites dans cette section :

### 3.1 **Emplacement du dossier**

Les noms de documents peuvent être limités par une convention de nommage dans Catenda. Les dossiers ne peuvent pas être limités. Sans l'utilisation d'une convention de nommage, les documents avec n'importe quel nom peuvent être téléchargés. Dans ce cas, Catenda n'a peut-être pas pu enregistrer l'extension de fichier du document. Les dossiers avec n'importe quel nom peuvent être créés. Il se peut donc que le Bureau Connector rencontre des problèmes avec les caractères dans les noms qui sont réservés à la fonctionnalité Windows.

Les problèmes typiques surviennent avec les caractères suivants : `/` - Barre oblique `\` - Barre oblique inversée Ces caractères sont utilisés dans la hiérarchie du chemin d'accès aux fichiers dans Windows, ce qui fait que le document se retrouve au mauvais endroit.

Pour trouver une liste complète de ce qui est réservé dans Windows, consultez : [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

### 3.2 **Nom de document ou de dossier incorrect**

Les noms de documents peuvent être limités par une convention de nommage dans Catenda. Les dossiers ne peuvent pas être limités. Sans l'utilisation d'une convention de nommage, les documents avec n'importe quel nom peuvent être téléchargés. Dans ce cas, Catenda n'a peut-être pas pu enregistrer l'extension de fichier du document. Les dossiers avec n'importe quel nom peuvent être créés.

Il se peut donc que le Bureau Connector rencontre des problèmes avec les caractères dans les noms qui sont réservés à la fonctionnalité Windows.

Les problèmes typiques surviennent avec les caractères suivants : `.` - Point

Étant donné que les dossiers et les fichiers se terminant par un point ne sont pas autorisés dans Windows, le point à la fin du dossier ou du fichier est supprimé dans le document créé à partir d'une tâche de téléchargement. Lors du chargement, le point est supprimé dans le processus de recherche du bon dossier vers lequel charger, de sorte que le document téléchargé se retrouvera au bon endroit lors de la synchronisation bidirectionnelle.

- Espace

Sur Catenda, il est possible d'ajouter manuellement un espace à la fin d'un nom de document ou de dossier tandis que les espaces à la fin des noms de documents et de dossiers sont supprimés dans Windows. Si un espace est inclus sur Catenda, le nom du dossier téléchargé est différent du nom du dossier dans Catenda qui peut inclure un espace. Lorsqu'une tâche de chargement est créée sur ce même dossier, un nouveau dossier sera créé car le nom de fichier ou de dossier sur Windows n'a pas d'espace à la fin.

## 4. **Aucun téléchargement ou chargement**

Les rubriques suivantes sont décrites dans cette section :

### 4.1 **Document déjà existant**

Lorsque le système d'importation ne peut pas traiter un élément qui a été créé précédemment, l'erreur suivante se produira.

Bureau Connector `Document déjà existant (code: 25)`

Fichier journal

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code Conflict reason: {"error":{"code":25,"message":"Document already exists"}}.url: https://api.bimsync.com/v2/projects/<ProjectGUID>/libraries/<LibraryGUID>/items? | Data: {"parentId":"<LibraryItemGUID>","name":"<Name>","document":{"type":"<Type>","filename":"<Filename>"}} 
```

Plus précisément, cela peut se produire lors de la tentative de chargement d'un dossier portant le titre "`A`" une deuxième fois alors qu'un dossier avec ce titre existe déjà. Il est recommandé de changer chaque dossier local avec le nom "A" en quelque chose comme "A\_". De cette façon, la tâche ne rencontrera pas de problèmes. Après la fin de la tâche de chargement, changez la version synchronisée en "A" sur Catenda pour que les deux côtés restent identiques.

### 4.2 **Tous les dossiers n'ont pas été téléchargés**

Dans la tâche elle-même, les éléments suivants peuvent être visibles :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/02-not-all-folders-have-been-downloaded.png)

`Tous les dossiers n'ont pas été téléchargés, cliquez pour afficher les erreurs.`

Cliquez [ici](https://support.catenda.com/en/articles/13772277-desktop-connector-troubleshooting-not-all-folders-have-been-downloaded) pour en savoir plus sur le problème possible de cette erreur.

## 5. **Dernière révision retirée**

La dernière révision de l'un des documents a été retirée. Dans ce cas, aucun message d'erreur ne figure dans le fichier journal.

## 6. **Synchronisation simultanée**

Pour que le Bureau Connector soit capable d'extraire des données d'un document à télécharger ou de mettre à jour un document avec les données téléchargées, il a besoin d'accéder au document. Si le document est utilisé par un autre processus, il ne peut pas accéder au document. Si le document est en cours d'utilisation, l'erreur suivante peut s'afficher :

Bureau Connector `Le processus ne peut pas accéder au fichier '<Chemin d'accès au fichier>' car il est utilisé par un autre processus.`

Fichier journal

```
<Message number>|<Date/Time>|ERROR|1|ExceptionHandleExtension|Some error happen --> System.IO.IOException: The process cannot access the file '<File path>' because it is being used by another process.
```

Les processus qui peuvent avoir des fichiers en cours d'utilisation peuvent inclure : Une tâche différente du Bureau Connector lui-même Les services de synchronisation de fichiers tels que Dropbox, Onedrive ou Google Drive D'autres outils de synchronisation CDE. Les programmes qui ont le fichier ouvert pour édition.

Si le document est en cours d'utilisation, la tâche s'arrêtera et ne continuera pas si elle ne peut pas accéder à l'un des fichiers. Si plusieurs tâches ont été programmées, elle réessayera à l'heure programmée suivante.

## 7. **Suivi de l'activité**

Les rubriques suivantes sont décrites dans cette section :

### 7.1 **Tâche démarrée**

Les tâches, qui ont été démarrées manuellement en cliquant sur Charger/Télécharger maintenant dans la tâche, affichent un Statut de Chargement ou Téléchargement dès que la tâche a démarré. Pour les tâches qui ont été démarrées manuellement et les tâches qui ont été démarrées par programme, un message qui ressemble à ceci apparaît dans le fichier journal au démarrage d'une tâche :

Fichier journal `<Message number>|<Date/time>|INFO|1|LoggingExtension|start logging`

### 7.2 **Tâche en cours d'exécution**

Les tâches, qui ont été démarrées manuellement en cliquant sur Charger/Télécharger maintenant dans la tâche, affichent un Statut de Chargement ou Téléchargement tant que la tâche s'exécute toujours. Pour les tâches qui ont été démarrées manuellement et les tâches qui ont été démarrées par programme, l'état dans lequel les tâches en cours d'exécution peuvent être vues en surveillant l'utilisation du réseau de l'application.

**Phase de démarrage initial** Une tâche du Bureau Connector est dans sa phase de démarrage initial lorsqu'elle utilise entre 1 kilooctet par seconde et 1 mégaoctet par seconde. Pendant cette phase, l'utilisation du réseau de la tâche est minimale.

Tâche de téléchargement Pendant la phase de démarrage initial, les documents à l'emplacement du serveur sont comparés avec les fichiers locaux pour voir s'il y a des fichiers serveur qui ont changé et pour lesquels une nouvelle révision doit être téléchargée ou s'il y a de nouveaux fichiers côté serveur qui doivent être téléchargés vers le système local.

Tâche de chargement Pendant la phase de démarrage initial, les documents à l'emplacement du serveur sont comparés avec les fichiers locaux pour voir s'il y a des fichiers locaux qui ont changé et pour lesquels une nouvelle révision doit être chargée ou s'il y a de nouveaux fichiers locaux qui doivent être chargés sur Catenda.

**Phase active** Une tâche du Bureau Connector est dans sa phase active lorsqu'elle utilise plus de 1 mégaoctet par seconde. Pendant cette phase, l'utilisation du réseau de la tâche peut avoir un effet sur le reste du système.

Tâche de téléchargement Pendant la phase active, le Bureau Connector télécharge activement fichier par fichier de Catenda vers le système local.

Tâche de chargement Pendant la phase active, le Bureau Connector charge activement fichier par fichier du système local vers Catenda.

### 7.3 **Tâche arrêtée**

Les tâches, qui sont exécutées manuellement en cliquant sur Charger/Télécharger maintenant dans la tâche, affichent un message de Statut dans la tâche lorsque la tâche est arrêtée, soit lorsque la tâche est terminée, soit lorsqu'une erreur s'est produite.

**Tâche terminée** Le seul moyen de voir si les tâches ont été terminées avec succès est d'exécuter manuellement la tâche. Cliquez sur Charger/Télécharger maintenant dans la tâche pour ce faire. Lorsque la tâche a été completée avec succès, un message indiquant que tous les documents ont été chargés ou téléchargés s'affiche dans la tâche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/03-task-halted.png)

> **Remarque :** Il n'y a aucun message dans le fichier journal pour les tâches terminées. Le seul moyen de voir si les tâches qui ont été démarrées par programme ont été arrêtées est de vérifier l'utilisation du réseau de l'application.

**Une erreur s'est produite** Une description plus détaillée des erreurs qui se sont produites peut être vue en vérifiant le fichier journal pour toute erreur récente.

**Utilisation du réseau** Le seul moyen de voir si les tâches qui ont été démarrées par programme ont été arrêtées est de vérifier l'utilisation du réseau de l'application. Si le Bureau Connector a utilisé moins de 1 kilooctet par seconde pendant plus de 2 minutes, toute tâche en cours d'exécution a probablement été arrêtée et ne redémarrera pas. Pour les tâches programmées pour se reproduire, une nouvelle tâche sera démarrée si le Bureau Connector s'exécute à la prochaine date et heure programmées pour le début de la tâche.

## 8. **Connexion entre le Connector et Catenda**

Les rubriques suivantes sont décrites dans cette section :

### 8.1 **Connexion lors du démarrage d'une tâche**

S'il y a un problème de connexion Internet, la tâche de téléchargement ou de chargement ne redémarrera pas automatiquement et s'exécutera à nouveau à l'heure programmée suivante. Elle peut également être démarrée manuellement en allant à la tâche et en cliquant sur le bouton de téléchargement ou de chargement.

**Aucune connexion** S'il n'y a pas de connexion Internet disponible au démarrage d'une tâche de téléchargement ou de chargement, l'erreur suivante s'affichera dans la tâche de téléchargement ou de chargement.

`Aucun hôte de ce type n'est connu`

**Connexion perdue lors du démarrage de la tâche** Si la connexion à Internet a été perdue ou a expiré lors de la tentative de connexion aux serveurs Catenda, l'erreur suivante s'affiche :

`La connexion SSL n'a pas pu être établie`

**La méthode de connexion utilisée dépend de la méthode préférée disponible au démarrage de la tâche** Lorsqu'une tâche est démarrée, une connexion est établie avec la méthode de connexion Internet préférée. Par exemple, si une connexion filaire et une connexion WiFi sont disponibles lors de l'exécution d'une tâche, la connexion filaire est souvent préférée. Si seule une connexion WiFi est disponible au démarrage d'une tâche et qu'une connexion filaire est connectée pendant son exécution, le connecteur continue d'utiliser la connexion initiale tant qu'elle est disponible et ne bascule pas vers une connexion préférée qui devient disponible ultérieurement.

### 8.2 **Connexion pendant la tâche - Connexion à Internet**

**Connexion Internet non disponible sans solution de secours** S'il n'y avait qu'une seule connexion disponible lors du début de la tâche ou s'il n'y avait aucune connexion disponible du tout (par exemple, Mode Avion), l'erreur suivante peut s'afficher.

`Une erreur s'est produite lors de l'envoi de la demande.`

**Connexion Internet non disponible avec solution de secours** S'il y avait plusieurs connexions disponibles lors du début de la tâche et que la connexion utilisée a été perdue, le connecteur tentera de basculer vers l'une des autres connexions disponibles. Pendant ce basculement, l'erreur suivante peut s'afficher :

`Erreur lors de la copie du contenu dans un flux`

### 8.3 **Connexion pendant la tâche - Délai d'expiration de la session du Bureau Connector**

Le Bureau Connector Catenda a une limite de session codée en dur de 10 minutes. Cela ne signifie pas qu'une tâche expirera après 10 minutes car le Bureau Connector fonctionne souvent avec plusieurs courtes sessions à la fois. Les gros fichiers comme les nuages de points où jusqu'à 25 Go à la fois peuvent être acceptés peuvent faire durer une session plus longtemps que d'habitude et peuvent expirer s'ils ne sont pas chargés dans les 10 minutes.

`Délai d'expiration de 600 secondes`

Veuillez contacter le support dans cette situation. Une version Bêta est disponible sur demande pour vous aider avec ceci. Avec la version Bêta, cette limite est légèrement augmentée, mais même avec la version bêta, elle peut expirer mais après 15 minutes.

`Délai d'expiration de 900 secondes`

### 8.4 **Connexion pendant la tâche - Connexion à Catenda**

Selon la vitesse de la connexion des deux côtés du téléchargement/chargement ou du côté Catenda, le chargement des fichiers peut prendre plus ou moins de temps. Si la tâche prend trop de temps, la connexion peut expirer.

**Délai d'expiration de Catenda** Si le transfert a pris trop de temps, il expirera et l'erreur suivante s'affichera :

`Une tentative de connexion a échoué car la partie connectée n'a pas répondu correctement après une période de temps, ou la connexion établie a échoué car l'hôte connecté n'a pas répondu. (api.bimsync.com:443)`

Veuillez contacter le support dans cette situation. Une version Bêta est disponible sur demande pour vous aider avec ceci.

**Service Catenda indisponible** Si l'API Catenda est temporairement incapable de recevoir des demandes à la fraction de seconde où le Bureau Connector tente de la contacter, le message suivant s'affiche.

Bureau Connector `ERREUR HTTP 503 Service indisponible`

Fichier journal

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code ServiceUnavailable reason: <html><head><meta http-equiv="Content-Type" content="text/html;charset=ISO-8859-1"/><title>Error 503 Service Unavailable</title></head><body><h2>HTTP ERROR 503 Service Unavailable</h2><table><tr><th>URI:</th><td>/v2/projects/10005fce182e49cb91342571746cf1fc/libraries/9a90887d954a444c8ed45695707b2fbd/items</td></tr><tr><th>STATUS:</th><td>503</td></tr><tr><th>MESSAGE:</th><td>Service Unavailable</td></tr><tr><th>SERVLET:</th><td>-</td></tr></table>
```

Ceci est souvent dû à des serveurs surchargés et de nombreux utilisateurs tentant d'envoyer des demandes en même temps.

**Délai d'expiration de la passerelle** Un délai d'expiration de la passerelle signifie souvent que l'API Catenda fonctionne correctement et que la demande initiale a été correctement reçue. Le service qui devait traiter cette demande n'a cependant pas répondu à temps.

Bureau Connector `Délai d'expiration de la passerelle 504` Fichier journal

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code GatewayTimeout reason: <html><head><title>504 Gateway Time-out</title></head><body><center><h1>504 Gateway Time-out</h1></center></body></html>
```

Cela peut indiquer que Catenda reçoit correctement les demandes mais que le serveur qui traite les demandes est temporairement indisponible. Cela peut parfois arriver quand il n'y a pas assez de machines disponibles après lesquelles d'autres démarre automatiquement mais cela peut prendre un peu de temps.

**Jeton d'accès expiré** Les jetons d'accès Catenda doivent être actualisés après une heure. Lorsque le Bureau Connector est navigué, ce n'est généralement pas un problème car le jeton est actualisé automatiquement, mais quand une tâche est démarrée et qu'elle prend plus d'une heure, le jeton d'accès qui a été utilisé pour la tâche peut expirer pendant que la tâche est en cours. Lorsque cela se produit, l'erreur suivante s'affiche dans le Bureau Connector. Pour les tâches qui prennent plus d'une heure, redémarrez la tâche ou attendez la prochaine tâche programmée pour faire le travail restant.

Bureau Connector `L'exception de type 'BimsyncApp.Exceptions.BimAuthenticatorException' a été levée.`

Fichier journal

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code Unauthorized reason: {"error":{"code":12,"message":"Access token has expired"}}.url: 
```

## 9. **Cet appareil est actuellement en cours d'utilisation**

Lors du téléchargement depuis ou du chargement vers un disque dur externe, Windows donnera une erreur indiquant que l'appareil est actuellement en cours d'utilisation s'il est tenté d'être débranché.

## 10. **Autorisations de dossier**

Pour les dossiers qui se trouvent sur le lecteur où Windows est installé, les autorisations de dossier appropriées sont requises. Cliquez avec le bouton droit sur le dossier vers lequel vous essayez de télécharger et accordez les autorisations appropriées.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/04-folder-permissions.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/05-folder-permissions.png)

Dans ce cas, le fichier journal donnera l'erreur suivante :

`L'accès au chemin '<Chemin du dossier local sélectionné> sous-dossier <Chemin dans le dossier local>' est refusé`

### 10.1 **Permission refusée**

Bien qu'un dossier sur Windows puisse être ouvert, Windows peut appliquer une politique "Pas d'écriture vers le haut". Le Bureau Connector vous permettra de sélectionner ce dossier, mais lorsque la tâche s'exécute, le message suivant s'affiche :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/06-permission-denied.png)

Dans ce cas, le Bureau Connector est bloqué de l'écriture, indépendamment des droits "Contrôle total" de l'utilisateur.

La suppression de ce dossier nécessitera que l'utilisateur accorde des privilèges d'administrateur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/07-permission-denied.png)

Dans certaines situations, le dossier peut toujours être ouvert tandis que dans d'autres, le message suivant peut s'afficher :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/08-permission-denied.png)

Même en continuant, le message suivant peut s'afficher :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/09-permission-denied.png)

En cliquant sur Télécharger de toute façon, les fichiers seront téléchargés, mais ils ne pourront pas être téléchargés vers le dossier spécifié car ce dossier est restreint.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/10-permission-denied.png)

Bureau Connector `Statut: Redirection, cliquez pour afficher les fichiers téléchargés`

Fichier journal `L'accès au chemin '<Chemin>' est refusé`

Cliquez sur Afficher les fichiers téléchargés pour ouvrir l'emplacement où les fichiers ont été téléchargés.
