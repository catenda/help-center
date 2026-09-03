# Dépannage du téléchargement de fichiers ZIP

## 1. **Le téléchargement a échoué**

Il est recommandé d'utiliser une connexion filaire pour télécharger les fichiers ZIP vers Catenda. De nombreux routeurs WiFi font un excellent travail en s'assurant qu'ils reçoivent les bonnes données, mais même les meilleurs routeurs peuvent avoir du mal avec un signal faible si vous êtes loin du routeur.

### 1.1 **Impossible de traiter le fichier**

Lors du processus de téléchargement du fichier ZIP, des paquets de données sont envoyés au serveur Catenda. S'il y a un problème avec l'un des paquets au cours du processus, le message suivant s'affiche : Le téléchargement a échoué ! Impossible de traiter le fichier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/01-unable-to-process-file.png)

Même lorsqu'on est juste à côté d'une antenne WiFi avec un appareil, il n'est jamais à 100 % certain que le paquet arrivera en toute sécurité par voie aérienne. Cet effet est amplifié en étant plus loin de l'antenne ou s'il y a des objets comme des murs entre l'appareil et l'antenne.

**Fichiers volumineux** Lorsque de grandes quantités de données sont téléchargées, de nombreux paquets sont envoyés. Si même l'un d'entre eux n'arrive pas correctement au routeur par voie aérienne, une erreur réseau peut apparaître. Quand cela se produit, l'intégralité du téléchargement sera invalide.

### 1.2 **Erreur réseau**

Certains logiciels limitent le nombre de caractères que les chemins d'accès aux fichiers dans un fichier ZIP peuvent contenir. S'il y a un problème avec la structure du chemin d'accès dans le fichier ZIP, l'erreur suivante s'affichera : Le téléchargement a échoué ! Erreur réseau.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/02-network-error.png)

**Décompresser/Recompresser** Si ce fichier ZIP a été reçu de quelqu'un d'autre, il peut être utile de le décompresser et de le recompresser.

**Limites connues (mise à jour décembre 2025)** Microsoft Windows 10/11 La limite dans Windows est de 260 caractères mais peut être augmentée. _Accès requis :_ Compte administrateur Windows

Utilisateurs de Windows Home : Cette limite peut être augmentée en allant au démarrage de Windows et en tapant REGEDIT Ouvrez l'Éditeur du Registre et naviguez vers :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem`

Double-cliquez sur `LongPathsEnabled` et changez la valeur à 1. Si ce n'est pas le cas, cliquez avec le bouton droit sur la clé `FileSystem` et choisissez

`Nouveau > Valeur DWORD (32 bits)`

Nommez la nouvelle valeur `LongPathsEnabled` avec une valeur de 1.

Utilisateurs de Windows Pro Cette limite peut être augmentée en allant au démarrage de Windows et en tapant gpedit.msc Ouvrez Modifier la stratégie de groupe et naviguez vers :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem`

Double-cliquez sur `Activer les chemins longs Win32` et activez-le.

OneDrive et SharePoint 400 unités de code Unicode

### 1.3 **Téléchargements robustes**

**Fichiers ZIP plus petits** Si le fichier ZIP se compose de plusieurs fichiers, le fichier ZIP peut être divisé en fichiers ZIP plus petits. Chaque fichier ZIP séparé peut être téléchargé individuellement, mais il y aura toujours un risque d'erreur réseau ou de connexion.

**Fichiers individuels** Le [connecteur de bureau Catenda](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) est un moyen plus sûr de télécharger car il télécharge des documents fichier par fichier. C'est aussi plus rapide car les fichiers sont téléchargés directement sur notre backend plutôt que par l'interface du navigateur. Même si l'un des fichiers échoue, ceux téléchargés jusqu'à présent apparaîtront déjà sur Catenda. Le reste des fichiers continuera à se télécharger la prochaine fois que la tâche de téléchargement s'exécutera.

## 2. **Téléchargements ZIP avec caractères spéciaux**

Catenda détecte l'encodage du fichier ZIP lors de son extraction, donc si le fichier ZIP contient des caractères spéciaux, ils seront interprétés correctement lors de l'extraction. Si les caractères spéciaux n'ont pas été encodés correctement, ils ne pourront pas être extraits par Catenda et finiront par ressembler à du charabia. Selon le service que vous utilisez pour créer votre fichier ZIP, vos caractères peuvent être correctement encodés ou non. Si vos caractères spéciaux sont brouillés, veuillez regarder dans le fichier ZIP pour voir s'ils semblent corrects là. Si vous pensez que vos caractères ont été encodés correctement et ne sont pas correctement extraits par Catenda, nous serions heureux de jeter un œil à votre fichier ZIP et de voir si nous pouvons faire quelque chose. Dans ce cas, veuillez contacter [support@catenda.com](mailto:support@catenda.com) avec les détails de la façon dont vous avez créé votre fichier ZIP.

### 2.1 **Encodage ZIP sur Windows**

Différentes versions de Windows utilisent différents encodages ZIP. Par exemple, la version anglaise utilise la norme d'encodage IBM-437 et la version pt-BR utilise IBM-850. Si votre installation Windows n'encode pas correctement vos fichiers ZIP, vous pourriez avoir plus de chance en utilisant un service tiers comme [7zip](https://7-zip.org/download.html) ou [WinRAR](https://www.win-rar.com/download.html?&L=0) pour créer vos fichiers ZIP avec le bon encodage.

## 3. **Terminé mais rien ne s'est passé**

Bien qu'une importation ZIP se termine, il peut y avoir plusieurs raisons pour lesquelles aucun changement n'est visible dans le tableau des documents. Voici à quoi cela peut ressembler quand une importation ZIP s'est terminée sans que des changements n'aient été apportés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/03-completed-but-nothing-happened.png)

Voici à quoi le menu de droite de la page d'importation ZIP peut ressembler dans cette situation :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/04-completed-but-nothing-happened.png)

### 3.1 **Dossiers ignorés**

Si un dossier portant le même nom qu'un dossier dans le fichier ZIP existe déjà à l'emplacement où un dossier est tenté d'être extrait, la création du dossier sera ignorée et aucun nouveau dossier ne sera créé. Tous les documents dans le dossier portant le même nom que sur Catenda seront téléchargés dans le dossier existant du projet Catenda.

### 3.2 **Fichiers ignorés**

Si l'option d'ignorer et de continuer a été choisie dans la boîte de dialogue de téléchargement ZIP et qu'un document portant le même nom que le fichier qui est tenté d'être téléchargé depuis le fichier ZIP existe déjà, il sera ignoré et l'extraction du fichier suivant commencera.

### 3.3 **Documents manquants**

Si des documents sont répertoriés sous documents manquants, cela signifie que les documents ont été créés avec succès mais ne peuvent pas être consultés. Les documents dans lesquels les fichiers ont été téléchargés peuvent depuis avoir été supprimés. Il est également possible que la personne qui a effectué le téléchargement n'ait plus accès aux documents dans lesquels les fichiers ont été téléchargés. _Accès requis :_ Accès en lecture

## 4. **Types de fichiers nuisibles**

Lorsqu'un fichier dans le fichier ZIP a un type de fichier potentiellement nuisible, il ne sera pas téléchargé. Voici à quoi la page d'importation ZIP peut ressembler lorsqu'on tente de télécharger des types de fichiers nuisibles :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/05-harmful-filetypes.png)

Voici à quoi le menu de droite de la page d'importation ZIP peut ressembler lorsqu'on tente de télécharger un fichier nuisible :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/06-harmful-filetypes.png)

Les types de fichiers suivants qui peuvent être potentiellement nuisibles ne sont pas autorisés.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa; width: 229px; padding: 8px;"><h1 id="h_711fb2a104"><b>Formats nuisibles</b></h1></td><td style="background-color: #e3e7fa; width: 142px; border-left: 1px solid #c6c9c0; padding: 8px;"><h1 id="h_581e5e19b4">Extensions</h1></td><td style="background-color: #e3e7fa; border-left: 1px solid #c6c9c0; padding: 8px;"><h1 id="h_766841ac5d">Commentaires</h1></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Scripts</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>php</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Exécutables Windows</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>exe</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Packages d'installation Windows</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>msi</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Scripts batch</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>bat</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Scripts de commande</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>cmd</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Exécutables DOS</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>com</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Exécutables de sauvegarde d'écran</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>scr</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Scripts PowerShell</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ps1</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Raccourcis Windows</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>lnk</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Cliquer sur un lien téléchargé pourrait établir un lien vers un exécutable sans ressembler à un exécutable.</p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Fichiers exécutables Java</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>jar</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr></tbody></table></div>

## 5. **Accès insuffisant**

L'accès approprié est requis pour que le contenu du fichier ZIP soit extrait. _Accès requis :_ Accès en écriture

Voici à quoi la page d'importation ZIP peut ressembler lorsqu'il n'y a pas assez d'accès :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/07-insufficient-access.png)

Voici à quoi le menu de droite de la page d'importation ZIP peut ressembler lorsqu'il n'y a pas assez d'accès :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/08-insufficient-access.png)
