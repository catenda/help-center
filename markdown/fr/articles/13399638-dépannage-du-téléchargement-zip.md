# Dépannage du téléchargement zip

Lorsqu'un dossier ou plusieurs éléments sont téléchargés dans la section Documents, une boîte de dialogue s'affiche vers le bas à gauche de l'écran. Dans cette boîte de dialogue, la progression de la préparation du fichier zip à télécharger est affichée.

## 1. **Caractères réservés dans le chemin**

Si un dossier contient le caractère `/` dans son nom, celui-ci est reconnu comme un chemin dans le fichier zip et le dossier sera divisé en plusieurs dossiers imbriqués les uns dans les autres. Tous les éléments contenus dans le dossier se retrouveront dans le dernier de ces dossiers. Par exemple, le dossier `This/is/a/folder` avec le document `This-is-a-document.pdf` sera téléchargé dans un zip avec la structure de dossiers suivante : This is a folder This-is-a-document.pdf

## 2. **Révisions non téléchargeables**

### 2.1 **Révisions brouillon (Legacy)**

Les révisions brouillon ne peuvent être téléchargées individuellement qu'à partir du menu de droite d'une révision. Si seules les révisions brouillon sont sélectionnées, un zip sera préparé mais il sera vide. Le nouveau type de révisions pour remplacer ceci est les révisions partagées qui, tout comme les révisions publiées régulières, peuvent être téléchargées avec l'action de téléchargement du tableau Documents sans problème.

### 2.2 **Révisions retirées**

Si la dernière révision de l'un des Documents de la sélection a été retirée, un avertissement peut s'afficher pour informer l'utilisateur que certains fichiers ne seront pas téléchargés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/01-withdrawn-revisions.png)

Appuyez sur Continuer pour poursuivre la préparation ou sur Annuler pour arrêter le téléchargement.

## 3. **Pas encore analysés pour les virus**

Si les fichiers qui ont été téléchargés récemment sont tentés d'être téléchargés, ils n'ont peut-être pas encore été analysés pour les virus.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/02-not-yet-scanned-for-virus.png)

Si un certain temps s'est écoulé depuis le téléchargement des fichiers à télécharger, veuillez contacter le support au sujet des fichiers non analysés. Appuyez sur Continuer pour poursuivre la préparation ou sur Annuler pour arrêter le téléchargement.

## 4. **Erreur de préparation du téléchargement**

Si quelque chose se passe mal lors de la préparation de ce fichier compressé, l'erreur suivante peut s'afficher :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/03-download-preparation-error.png)

Si vous voyez cet écran, veuillez contacter le support.
