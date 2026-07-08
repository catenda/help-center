# Connecteur de bureau Catenda

> **Remarque :** Le fichier d'installation de cette application se trouve [ici](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

Avec le connecteur de bureau Catenda, vous pouvez planifier les téléchargements et les envois des dernières versions de Documents.

## 1. **Envois/téléchargements instantanés**

### 1.1 **Envoi**

Sélectionnez un dossier sur un système local pour envoyer tout le contenu du dossier, y compris les fichiers dans les sous-dossiers du dossier sélectionné, avec le connecteur de bureau vers un dossier spécifié sur Catenda Hub.

**Envois réussis** Si vous faites glisser-déposer plusieurs fichiers ou utilisez la fonction d'envoi ZIP sur Catenda Hub, vous envoyez un grand ensemble de données. Plus l'envoi est volumineux, plus vous devez attendre avant de pouvoir soumettre vos fichiers dans la structure de Documents de Catenda Hub.

**Un fichier à la fois** En envoyant des fichiers à partir d'une structure de dossiers un fichier à la fois, le connecteur de bureau vous permet de suspendre l'envoi et de le continuer ultérieurement.

**Réduire le risque d'échecs d'envoi** Plus l'envoi est volumineux, plus le risque d'échec est élevé. Peut-être que votre alimentation s'arrête, peut-être que votre connexion Internet s'interrompt une fraction de seconde. Vous devriez alors recommencer l'envoi à zéro.

### 1.2 **Téléchargement**

Sélectionnez un ou plusieurs Documents individuels ou sélectionnez un dossier sur Catenda Hub pour télécharger la sélection, y compris les Documents dans les sous-dossiers des dossiers sélectionnés vers un emplacement sur votre machine locale.

### 1.3 **Vitesse de transfert**

L'envoi et le téléchargement de fichiers avec le connecteur de bureau est plus rapide au transfert de fichiers que le processus d'envoi régulier, car les fichiers sont importés via l'API sans nécessiter la surcharge d'exécution d'un navigateur ou d'autres limitations du navigateur. Pour transférer un seul fichier, le glisser-déposer avec un navigateur est recommandé en raison de sa facilité d'utilisation, mais pour transférer de grandes quantités de données d'un seul coup ou pour ceux qui souhaitent économiser du temps lors des envois de fichiers volumineux, le connecteur de bureau est le moyen recommandé de transférer.

### 1.4 **Accès**

Le contrôle d'accès configuré sur Catenda Hub est maintenu. Les utilisateurs peuvent envoyer vers des emplacements dans la structure de Documents de Catenda où ils disposent d'au moins l'accès en écriture et ne peuvent télécharger que les Documents auxquels ils ont au moins l'accès en lecture.

## 2. **Synchronisation**

Les fichiers peuvent être planifiés pour être envoyés ou téléchargés à intervalles réguliers.

### 2.1 **Système local -> Catenda Hub**

Le connecteur de bureau peut s'assurer que les fichiers d'un projet Catenda Hub restent à jour avec l'état d'enregistrement le plus récent d'un fichier sur le système local.

### 2.2 **Catenda Hub -> Système local**

Le connecteur de bureau peut s'assurer que les fichiers sur un système local restent à jour avec la dernière révision d'un Document dans un projet Catenda Hub.

## 3. **Installation**

Quand le connecteur de bureau Catenda est installé sur Windows, ses fichiers d'installation apparaîtront dans le dossier suivant.

`C:\\Program Files\\Catenda Hub Desktop Connector`

### 3.1 **Désinstallation**

Pour désinstaller le plug-in, allez au menu Windows suivant :

`Paramètres Windows -> Applications -> Applications installées`

Trouvez le connecteur de bureau dans la liste et cliquez sur le menu d'action sur le côté droit pour désinstaller.

## 4. **Se connecter**

Quand le connecteur de bureau est ouvert pour la première fois, une demande de connexion est affichée. Cliquez sur le bouton Se connecter pour ouvrir le navigateur par défaut du système sur la page de connexion de Catenda. Après vous être connecté ou si vous êtes déjà connecté, cliquez sur autoriser l'accès pour accorder l'accès au compte Catenda qui est connecté. Après avoir cliqué sur autoriser l'accès, le navigateur vous invitera à ouvrir l'application du connecteur de bureau. L'octroi de la permission d'ouvrir l'application vous redirige vers la [page d'accueil](#home-page) du connecteur de bureau.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Page d'accueil**

Voici ce à quoi le connecteur de bureau peut ressembler au démarrage avec une connexion valide :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **Réveiller le PC**

Réveille le PC du mode veille si une tâche est planifiée pour s'exécuter à ce moment.

### 5.2 **Exécuter au démarrage**

Pour exécuter le connecteur de bureau au démarrage, sélectionnez cette option

### 5.3 **Se déconnecter**

Cliquez sur le bouton de déconnexion en bas à droite pour vous déconnecter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Liste des projets**

Un aperçu des projets auxquels le compte avait accès la dernière fois que la liste des projets a été chargée s'affiche. Pour chaque projet, le nombre de tâches d'envoi et de téléchargement qui sont configurées s'affiche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Bouton Synchroniser**

Si un projet a été récemment rejoint, cliquez sur ce bouton de synchronisation pour charger la nouvelle liste des projets dont le compte connecté fait partie.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Nom**

Cliquez sur le nom d'un projet pour voir les tâches d'envoi et de téléchargement actuelles ou pour planifier une nouvelle tâche.

### 6.3 **Tâches d'envoi**

Le nombre de tâches d'envoi actives pour ce projet

### 6.4 **Tâches de téléchargement**

Le nombre de tâches de téléchargement actives pour ce projet

## 7. **Tâche d'envoi**

Planifiez un envoi périodique de fichiers de votre système vers Catenda Hub avec cette tâche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Titre - Obligatoire**

La tâche d'envoi doit avoir au moins un titre pour être sauvegardée

### 7.2 **Calendrier de planification - Obligatoire**

La tâche doit avoir au moins un jour sélectionné pour être sauvegardée

### 7.3 **Emplacement du projet**

**Serveur** Cliquez sur parcourir pour sélectionner la destination sur la page Documents de Catenda Hub où les fichiers doivent être synchronisés. Cliquez [ici](#server-location) pour en savoir plus sur la sélection du chemin d'accès du répertoire du serveur

**Local** Sélectionnez l'emplacement sur le système local à partir duquel les fichiers doivent être synchronisés.

### 7.4 **Instantané**

Les tâches n'ont pas besoin d'être enregistrées pour démarrer le processus d'envoi. Cliquez sur le carré d'envoi maintenant pour démarrer cette tâche immédiatement. Les tâches enregistrées s'exécutent périodiquement à l'heure configurée.

## 8. **Tâche de téléchargement**

Planifiez un téléchargement périodique de fichiers de Catenda Hub vers le système local.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Titre - Obligatoire**

La tâche d'envoi doit avoir au moins un titre pour être sauvegardée

### 8.2 **Calendrier de planification - Obligatoire**

La tâche doit avoir au moins un jour sélectionné pour être sauvegardée

### 8.3 **Emplacement du projet**

**Serveur** Sélectionnez l'emplacement sur Catenda Hub à partir duquel les Documents doivent être téléchargés. Cliquez [ici](#server-location) pour en savoir plus sur la sélection du chemin d'accès du répertoire du serveur

**Local** Sélectionnez la destination sur le système local où les fichiers doivent être téléchargés.

### 8.4 **Instantané**

Une tâche n'a pas besoin d'être enregistrée pour commencer à télécharger. Cliquez sur le carré Télécharger maintenant pour démarrer cette tâche immédiatement. Enregistrez la tâche pour exécuter périodiquement le téléchargement à l'heure configurée. Les Documents téléchargés se retrouveront sur votre système décompressés.

### 8.5 Bouton Retour

Cliquez sur le bouton de flèche pour retourner à la [page d'accueil](#home-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Emplacement du serveur**

Cliquez sur parcourir dans la zone d'emplacement du projet d'une tâche d'envoi ou de téléchargement pour commencer à parcourir le chemin d'accès du répertoire du projet Catenda. La boîte de dialogue Choisir le chemin d'accès du répertoire s'ouvrira. Une fois ouverte, elle commencera à télécharger tous les noms de dossiers du projet et leur hiérarchie. Pour les tâches de téléchargement, les noms de Documents sont également téléchargés. Pendant que le téléchargement est en cours, la boîte de dialogue peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-server-location.png)

Particulièrement pour les tâches de téléchargement, s'il y a de nombreux dossiers et Documents, cela peut prendre quelques minutes pour que ce processus se termine. Veuillez vous assurer que suffisamment de mémoire est disponible sur le système local pour cette étape.

**Taille de la boîte de dialogue** Cliquez sur Min ou Max vers le haut à droite pour réduire ou agrandir la boîte de dialogue Choisir le chemin d'accès du répertoire.

**Actions du répertoire** Une fois les dossiers chargés, la boîte de dialogue peut ressembler à quelque chose comme ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/10-server-location.png)

Cliquez sur la flèche en regard d'un dossier pour le développer. Les Documents ne sont disponibles que dans cette vue pour les tâches de téléchargement.

**Sélection de dossier** Cliquez sur un dossier pour le sélectionner. Pour les tâches de téléchargement, plusieurs dossiers peuvent être sélectionnés, tandis que pour les tâches d'envoi, un seul dossier peut être sélectionné à la fois.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/11-server-location.png)

Une fois qu'un dossier est sélectionné, il apparaît en blanc avec une coche. Tous les sous-dossiers du dossier sélectionné apparaîtront barrés car il n'est possible de sélectionner que des dossiers au même niveau. Vers le haut, le nombre d'éléments sélectionnés s'affiche.

**Tâche de téléchargement** S'il y a des Documents dans le dossier sélectionné ou ses sous-dossiers, tous les dossiers du chemin entre le dossier sélectionné et le Document seront créés. Le Document est alors téléchargé dans ce dossier. Si un sous-dossier ne contient pas de Documents, le sous-dossier ne sera pas créé même s'il peut être coché dans cette boîte de dialogue. Il n'est pas possible de décocher un sous-dossier pour ne pas télécharger une partie d'une structure de dossiers. Pour télécharger uniquement certains dossiers, sélectionnez-les individuellement comme dans l'image ci-dessous :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/12-server-location.png)

Sélection de Document Cliquez sur un Document pour le sélectionner

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/13-server-location.png)

Lorsque des Documents individuels sont sélectionnés, les Documents seront téléchargés sous forme de liste plate directement vers le chemin local sélectionné sans la hiérarchie des dossiers dans lesquels ces Documents se trouvent.

**Tâche d'envoi** Les Documents sont envoyés vers le dossier sélectionné. Si le nom du dossier correspond, les Documents sont envoyés aux sous-dossiers du dossier sélectionné.

## 10. **Liste des tâches**

Ici, les tâches d'envoi et de téléchargement qui sont configurées dans cette installation pour l'utilisateur connecté peuvent être vues.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/14-task-list.png)

### 10.1 **Nom**

Le nom de la tâche.

### 10.2 **Tâche**

L'heure planifiée à laquelle la tâche s'exécutera.

### 10.3 **Projet**

Le nom du projet où cette tâche s'exécutera.

### 10.4 **Statut**

Le Statut de cette tâche.

### 10.5 **Bouton Retour**

Cliquez sur ce bouton pour retourner à la [page d'accueil](#home-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 11. **Dossier de journaux**

Ce bouton ouvre l'emplacement du dossier des journaux du connecteur de bureau sur le système local. L'emplacement par défaut de ces journaux est :

`C:\\Users\\\<nom du compte Windows>\\AppData\\Local\\User Name\\2b92d867-496c-47d1-ac42-fbf8fa355177\\Cache\\BimsyncApp`
