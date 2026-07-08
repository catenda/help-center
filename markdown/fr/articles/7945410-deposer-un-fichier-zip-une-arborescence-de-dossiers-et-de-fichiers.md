# Télécharger un fichier zip / structure de fichiers

Contrairement au téléchargement d'un fichier zip ordinaire, la fonction de téléchargement de fichier zip décompressera un fichier zip. De cette façon, vous pouvez importer une structure de fichiers dans la [page Documents](https://support.catenda.com/en/articles/8204673-documents-page#h_28610e1d21) sans avoir à créer manuellement des dossiers.

La fonction Télécharger un fichier zip se trouve dans le menu d'actions à droite du bouton + vert en haut à droite de la page Documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/01-intro.png)

## 1. **Sélection d'un fichier zip**

Après avoir cliqué sur l'élément de menu Télécharger un fichier zip, la boîte de dialogue suivante s'ouvrira :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/02-selecting-a-zip-file.png)

L'explorateur de fichiers de votre système doit s'ouvrir automatiquement. Si l'explorateur de fichiers ne s'est pas ouvert ou s'il a été fermé sans sélectionner de fichier zip, vous pouvez l'ouvrir à nouveau en cliquant sur le bouton Sélectionner un fichier zip.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/03-selecting-a-zip-file.png)

Après avoir sélectionné avec succès un fichier zip sur votre système local, vous devriez voir le nom du fichier zip ci-dessous et le bouton de téléchargement du fichier zip sera surligné en vert foncé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/04-selecting-a-zip-file.png)

Si vous n'avez pas entré de dossier dans la section des documents, il indiquera que le contenu sera extrait au dossier Racine. Cela signifie que vous verrez le contenu dès que vous entrerez dans la section Documents. Il est également possible de naviguer vers un dossier dans Catenda et de télécharger votre fichier zip là-bas si vous souhaitez que la structure de fichiers y apparaisse.

## 2. **Configuration du téléchargement**

Les paramètres peuvent être configurés pour les éléments dont les noms dans le fichier zip existent déjà à l'emplacement où l'extraction du fichier zip tente de les placer dans le projet Catenda.

### 2.1 **Dossiers**

Les nouveaux dossiers ne seront créés que si un dossier portant ce nom n'existe pas encore à l'emplacement où le fichier zip tente d'extraire un dossier. Tous les éléments contenus dans un dossier où un dossier portant le même nom existe déjà seront placés dans le dossier existant portant le même nom dans le projet Catenda.

### 2.2 **Documents**

Différents comportements peuvent être configurés pour la façon dont l'extraction du fichier zip se comporte lorsqu'un document portant le même nom que le fichier dans le fichier zip existe déjà au même emplacement où le fichier zip tente de l'extraire dans le projet Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/05-documents.png)

**Créer une nouvelle révision - Par défaut** Si un document portant le même nom existe au même emplacement où le fichier zip tente d'extraire un fichier, une nouvelle révision sera créée dans ce document.

**Ignorer et continuer** Si un document portant le même nom existe au même emplacement où le fichier zip tente d'extraire un fichier, le fichier sera ignoré et aucune nouvelle révision ne sera créée dans le document.

### 2.3 **Appliquer le statut**

Si le flux de statut a été activé dans votre projet, vous serez en mesure de configurer le statut que les nouveaux documents auront. Si vous avez choisi l'option de création d'une nouvelle révision, le statut des documents qui recevront une nouvelle révision sera automatiquement modifié.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/06-apply-status.png)

Il n'est possible de choisir que parmi les statuts de révisions partagées. Après le téléchargement, les révisions partagées peuvent être trouvées dans l'onglet espace de travail et peuvent être publiées ultérieurement.

## 3. **Téléchargement**

Après avoir cliqué sur télécharger un fichier zip, votre fichier zip commencera à être téléchargé

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/07-uploading.png)

Vous pouvez continuer à travailler avec Catenda dans un autre onglet pendant que vous attendez la fin du téléchargement.

**Accès requis :** Accès en écriture à chacun des emplacements où les dossiers et les documents seront créés Accès en écriture aux révisions de documents qui seront ajoutées.

## 4. **Extraction**

Après le téléchargement de votre fichier zip, Catenda commencera à extraire votre fichier zip. Lors de l'extraction, vous verrez le menu suivant en bas à gauche :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/08-extracting.png)

Vous pouvez garder ce menu ouvert en explorant Catenda, ou le fermer si vous le souhaitez. Vous pouviez même fermer complètement le navigateur pendant le processus d'extraction. Le fichier zip continuera à s'extraire en arrière-plan. Si vous avez utilisé Catenda dans un onglet différent pendant que le fichier zip s'extrayait, vous verrez les dossiers, documents et révisions commencer à apparaître à l'emplacement où vous avez extrait en actualisant la page.

### 4.1 **Extraction terminée**

Lorsque le fichier zip aura fini d'être extrait, il affichera "terminé" dans la boîte de dialogue.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/09-extraction-completed.png)

Cliquez sur afficher les détails pour voir les fichiers qui ont été extraits. Vous pourrez trouver ces détails ultérieurement dans "Mes téléchargements de fichiers zip" comme expliqué ci-dessous. Actualisez la page pour voir tous les fichiers qui ont été téléchargés.

### 4.2 **Notification d'importation de fichier zip terminée**

Si vous avez fermé la boîte de dialogue, le navigateur ou actualisé la page, vous ne verrez plus la boîte de dialogue. Vous recevrez également une notification indiquant que votre extraction de fichier zip est terminée. De cette façon, vous saurez quand votre téléchargement de fichier zip est terminé, même si vous ne voyez plus la boîte de dialogue d'extraction.

## 5. **Contourner la limite de taille de fichier**

Le téléchargement d'un fichier zip vous permettra de télécharger des fichiers plus volumineux que 7 Go, car le fichier zip compresse le fichier.

## 6. **Mes téléchargements de fichiers zip**

L'option sous le téléchargement du fichier zip dans le menu d'actions vous permettra de voir un aperçu de vos téléchargements de fichiers zip précédents. Voici à quoi peuvent ressembler les importations de fichiers zip avec les différents statuts possibles :

### 6.1 **Extraction**

Pendant que le fichier zip s'extrait, les fichiers extraits commencent à apparaître sous forme de lignes dans le tableau des Documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/10-extracting.png)

**Terminé** Lorsque l'importation du fichier zip est terminée, tous les fichiers sont extraits.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/11-extracting.png)

### 6.2 **Page d'importation de fichier zip**

Cliquez sur une importation de fichier zip pour voir plus d'informations sur le processus d'importation. Voici à quoi peut ressembler la page d'importation de fichier zip d'une importation de fichier zip terminée :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/12-zip-import-page.png)

Voici à quoi peut ressembler le menu droit de la page d'importation de fichier zip d'une importation de fichier zip terminée :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/13-zip-import-page.png)

## 7. **Connecteur de bureau**

Avec le [Connecteur de bureau Catenda](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector), vous pouvez automatiquement et périodiquement télécharger les dernières versions de documents de votre système local vers Catenda Hub. Le Connecteur de bureau est à la fois plus rapide que le processus de téléchargement régulier et minimise le risque d'échec en téléchargeant les documents fichier par fichier au lieu d'un lot de téléchargement ou de fichier zip unique volumineux.
