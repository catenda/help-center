# Connecteur Catenda Desktop

> **Remarque :** Le fichier d'installation de cette application se trouve [ici](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

Avec le connecteur Catenda Desktop, vous pouvez planifier les téléchargements et les téléversements des dernières versions des Documents.

## 1. **Téléchargements et téléversements instantanés**

### 1.1 **Téléversement**

Sélectionnez un dossier sur un système local pour téléverser tout le contenu du dossier, y compris les fichiers dans les sous-dossiers du dossier sélectionné, avec le Connecteur Desktop vers un dossier spécifié sur Catenda Hub.

**Téléversements réussis** Si vous faites un glisser-déposer de plusieurs fichiers ou utilisez la fonction de téléversement de fichiers zippés sur Catenda Hub, vous téléversez un grand ensemble de données. Plus le téléversement est volumineux, plus longtemps vous devez attendre avant de pouvoir soumettre vos fichiers à la structure de Documents de Catenda Hub.

**Un fichier à la fois** En téléversant les fichiers à partir d'une structure de dossiers un fichier à la fois, le Connecteur Desktop vous permet de mettre en pause le téléversement et de le poursuivre ultérieurement.

**Réduisez le risque d'échecs de téléversement** Plus le téléversement est volumineux, plus élevé est le risque qu'il échoue également. Peut-être que votre alimentation s'arrête, peut-être que votre connexion Internet se coupe une fraction de seconde. Vous devrez alors recommencer le téléversement à zéro.

### 1.2 **Téléchargement**

Sélectionnez un ou plusieurs Documents individuels ou sélectionnez un dossier sur Catenda Hub pour télécharger la sélection, y compris les Documents dans les sous-dossiers des dossiers sélectionnés vers un emplacement sur votre machine locale.

### 1.3 **Vitesse de transfert**

Le téléchargement et le téléversement de fichiers avec le connecteur Desktop sont plus rapides en termes de transfert de fichiers que le processus de téléversement régulier, car les fichiers sont importés via l'API sans nécessiter les frais généraux d'un navigateur en cours d'exécution ou d'autres limitations du navigateur. Pour transférer un seul fichier, un glisser-déposer avec un navigateur est recommandé en raison de sa facilité d'utilisation, mais pour transférer de grandes quantités de données d'un seul coup ou pour ceux qui souhaitent économiser du temps lors des téléversements de fichiers volumineux, le Connecteur Desktop est le moyen recommandé de transférer.

### 1.4 **Accès**

Le contrôle d'accès configuré sur Catenda Hub est maintenu. Les utilisateurs peuvent téléverser vers des emplacements dans la structure de Documents Catenda où ils disposent au moins d'un accès en écriture et ne peuvent télécharger que les Documents auxquels ils ont au moins un accès en lecture.

## 2. **Synchronisation**

Les fichiers peuvent être planifiés pour être téléversés ou téléchargés à intervalles réguliers.

### 2.1 **Système local -> Catenda Hub**

Le Connecteur Desktop peut s'assurer que les fichiers d'un projet Catenda Hub sont maintenu à jour avec l'état de sauvegarde le plus récent d'un fichier sur le système local.

### 2.2 **Catenda Hub -> Système local**

Le Connecteur Desktop peut s'assurer que les fichiers sur un système local sont maintenu à jour avec la révision la plus récente d'un Document dans un projet Catenda Hub.

## 3. **Installation**

Quand le Connecteur Catenda Desktop est installé sur Windows, ses fichiers d'installation apparaîtront dans le dossier suivant.

`C:\Program Files\Catenda Hub Desktop Connector`

### 3.1 **Désinstallation**

Pour désinstaller le plugin, allez au menu Windows suivant :

`Paramètres Windows -> Applications -> Applications installées`

Trouvez Desktop Connector dans la liste et cliquez sur le menu d'action sur le côté droit pour désinstaller.

## 4. **Se connecter**

Quand le Connecteur Desktop est ouvert pour la première fois, une demande de connexion s'affiche. Cliquez sur le bouton Se connecter pour ouvrir le navigateur par défaut du système sur la page de connexion Catenda. Après vous être connecté ou si vous êtes déjà connecté, cliquez sur autoriser l'accès pour accorder l'accès au compte Catenda qui est connecté. Après avoir cliqué sur autoriser l'accès, le navigateur demandera à l'utilisateur d'ouvrir l'application Connecteur Desktop. L'octroi de la permission d'ouverture de l'application redirige vers la [page d'accueil](#h_097078145d) du Connecteur Desktop.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Page d'accueil**

Voici à quoi le Connecteur Desktop peut ressembler au démarrage avec une connexion valide :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **Réveiller le PC**

Réveille le PC du mode veille si une tâche est programmée pour s'exécuter à ce moment.

### 5.2 **Exécuter au démarrage**

Pour exécuter le connecteur Desktop au démarrage, sélectionnez cette option

### 5.3 **Se déconnecter**

Cliquez sur le bouton Se déconnecter en bas à droite pour vous déconnecter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Liste des projets**

Un aperçu des projets auxquels le compte avait accès la dernière fois que la liste des projets a été chargée s'affiche. Pour chaque projet, le nombre de tâches de téléversement et de téléchargement configurées est indiqué.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Bouton Synchroniser**

Si un projet a été récemment rejoint, cliquez sur ce bouton de synchronisation pour charger la nouvelle liste des projets dont le compte connecté fait partie.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Nom**

Cliquez sur le nom d'un projet pour voir les tâches de téléversement et de téléchargement actuelles ou pour planifier une nouvelle tâche.

### 6.3 **Tâches de téléversement**

Le nombre de tâches de téléversement qui sont actives pour ce projet

### 6.4 **Tâches de téléchargement**

Le nombre de tâches de téléchargement qui sont actives pour ce projet

## 7. **Tâche de téléversement**

Planifiez un téléversement périodique de fichiers de votre système vers Catenda Hub avec cette tâche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Titre - Requis**

La tâche de téléversement doit au moins avoir un titre pour être enregistrée

### 7.2 **Calendrier de planification - Requis**

La tâche doit au moins avoir un jour sélectionné pour être enregistrée

### 7.3 **Emplacement du projet**

**Serveur** Cliquez sur parcourir pour sélectionner la destination sur la page Documents dans Catenda Hub où les fichiers doivent être synchronisés. Cliquez [ici](#h_4446f1b663) pour en savoir plus sur la sélection du chemin d'accès du répertoire du serveur

**Local** Sélectionnez l'emplacement sur le système local à partir duquel les fichiers doivent être synchronisés.

### 7.4 **Instantané**

Les tâches n'ont pas besoin d'être enregistrées pour démarrer le processus de téléversement. Cliquez sur le carré Téléverser maintenant pour démarrer cette tâche immédiatement. Les tâches enregistrées s'exécutent périodiquement à l'heure configurée.

## 8. **Tâche de téléchargement**

Planifiez un téléchargement périodique de fichiers de Catenda Hub vers le système local.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Titre - Requis**

La tâche de téléversement doit au moins avoir un titre pour être enregistrée

### 8.2 **Calendrier de planification - Requis**

La tâche doit au moins avoir un jour sélectionné pour être enregistrée

### 8.3 **Emplacement du projet**

**Serveur** Sélectionnez l'emplacement sur Catenda Hub à partir duquel les Documents doivent être téléchargés. Cliquez [ici](#h_4446f1b663) pour en savoir plus sur la sélection du chemin d'accès du répertoire du serveur

**Local** Sélectionnez la destination sur le système local où les fichiers doivent être téléchargés.

### 8.4 **Instantané**

Une tâche n'a pas besoin d'être enregistrée pour commencer le téléchargement. Cliquez sur le carré Télécharger maintenant pour démarrer cette tâche immédiatement. Enregistrez la tâche pour exécuter périodiquement le téléchargement à l'heure configurée. Les Documents téléchargés finiront sur votre système décompressés.

### 8.5 Bouton Retour

Cliquez sur le bouton flèche pour revenir à la [page d'accueil](#h_097078145d)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Emplacement du serveur**

Cliquez sur parcourir dans la zone d'emplacement du projet d'une tâche de téléversement ou de téléchargement pour commencer à parcourir le chemin du répertoire du projet Catenda. La boîte de dialogue Choisir le chemin du répertoire s'ouvrira. Une fois ouvert, il commencera à télécharger tous les noms de dossiers du projet et leur hiérarchie. Pour les tâches de téléchargement, les noms de Documents sont également téléchargés. Lors du téléchargement, la boîte de dialogue peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-server-location.png)

Surtout pour les tâches de téléchargement, s'il y a de nombreux dossiers et Documents, cela peut prendre quelques minutes pour que ce processus se termine. Veuillez vous assurer qu'il y a suffisamment de mémoire disponible sur le système local pour cette étape.

**Taille de la boîte de dialogue** Cliquez sur Min ou Max vers le haut à droite pour minimiser ou maximiser la boîte de dialogue Choisir le chemin du répertoire.

**Actions du répertoire** Après le chargement des dossiers, la boîte de dialogue peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/10-server-location.png)

Cliquez sur la flèche à côté d'un dossier pour le développer. Les Documents ne sont disponibles dans cette vue que pour les tâches de téléchargement.

**Sélection de dossier** Cliquez sur un dossier pour le sélectionner. Pour les tâches de téléchargement, plusieurs dossiers peuvent être sélectionnés, tandis que pour les tâches de téléversement, un seul dossier peut être sélectionné à la fois.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/11-server-location.png)

Après la sélection d'un dossier, il apparaît en blanc avec une coche. Tous les sous-dossiers du dossier sélectionné apparaîtront barrés car il n'est possible de sélectionner que les dossiers au même niveau. Vers le haut, le nombre d'éléments sélectionnés s'affiche.

**Tâche de téléchargement** S'il y a des Documents dans le dossier sélectionné ou ses sous-dossiers, tous les dossiers du chemin entre le dossier sélectionné et le Document seront créés. Le Document est alors téléchargé dans ce dossier. Si un sous-dossier ne contient pas de Documents, le sous-dossier ne sera pas créé même s'il peut être coché dans cette boîte de dialogue. Il n'est pas possible de décocher un sous-dossier pour ne pas télécharger une partie de la structure de dossiers. Pour télécharger uniquement certains dossiers, sélectionnez-les individuellement comme dans l'image ci-dessous :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/12-server-location.png)

Sélection du Document Cliquez sur un Document pour le sélectionner

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/13-server-location.png)

Quand des Documents individuels sont sélectionnés, les Documents seront téléchargés sous forme d'une liste plate directement vers le chemin local sélectionné sans la hiérarchie des dossiers dans lesquels ces Documents se trouvent.

**Tâche de téléversement** Les Documents sont téléversés dans le dossier sélectionné. Si le nom du dossier correspond, les Documents sont téléversés dans les sous-dossiers du dossier sélectionné.

## 10. **Liste des tâches**

Voici les tâches de téléversement et de téléchargement qui sont configurées dans cette installation pour l'utilisateur connecté.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/14-task-list.png)

### 10.1 **Nom**

Le nom de la tâche.

### 10.2 **Tâche**

L'heure programmée à laquelle la tâche s'exécutera.

### 10.3 **Projet**

Le nom du projet où cette tâche s'exécutera.

### 10.4 **Statut**

Le Statut de cette tâche.

### 10.5 **Bouton Retour**

Cliquez sur ce bouton pour revenir à la [page d'accueil](#h_097078145d)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 11. **Dossier Journaux**

Ce bouton ouvre l'emplacement du dossier des journaux du Connecteur Desktop sur le système local. L'emplacement par défaut de ces journaux est :

`C:\Users\<nom du compte Windows>\AppData\Local\User Name\2b92d867-496c-47d1-ac42-fbf8fa355177\Cache\BimsyncApp`
