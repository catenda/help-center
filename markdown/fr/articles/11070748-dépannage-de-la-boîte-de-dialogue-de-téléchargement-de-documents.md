# Dépannage de la boîte de dialogue de téléchargement de documents

## 1. **Le document existe dans le dossier**

Si vous disposez d'un accès en écriture à un dossier, mais d'un accès en lecture à un document, vous ne pourrez pas ajouter de révisions à ce document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/01-document-exists-in-folder.png)

Veuillez créer un nouveau document avec cette révision ou télécharger la révision vers un document différent.

## 2. **Types de fichiers exécutables et scripts**

Lorsqu'un fichier a un type de fichier potentiellement nuisible, il ne sera pas téléchargé. Voici à quoi cela peut ressembler lorsque vous tentez de télécharger un type de fichier nuisible :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/02-executable-and-script-filetypes.png)

Les types de fichiers suivants, qui peuvent potentiellement être nuisibles, ne sont pas autorisés. Consultez les types de fichiers qui ne peuvent pas être téléchargés dans [cet](https://support.catenda.com/en/articles/4670320-previewing-file-types-on-catenda-hub) article.

## 3. **Nom de fichier tronqué**

Les fichiers sélectionnés pour téléchargement à partir d'un lecteur externe comme un disque dur USB/clé USB ou un lecteur réseau peuvent avoir une limitation d'environ 250 caractères dans la longueur de leur chemin. Si le chemin d'accès au fichier est trop long, la fin du nom de fichier (avant l'extension du fichier) est tronquée et remplacée par ~1. Voici à quoi cela ressemble lorsqu'un nom de fichier est tronqué.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/03-filename-cut-off.png)

Ce n'est pas une limitation de Catenda mais plutôt une limitation entre le navigateur et le système d'exploitation. Pour éviter ce problème, copiez les fichiers de l'emplacement externe vers votre machine locale et téléchargez-les vers Catenda à partir de là. Un bon endroit pour les placer est généralement le Tableau de bord où les fichiers temporaires peuvent être découverts et supprimés ultérieurement, ou à la racine C:// pour vous assurer qu'il y a autant de caractères que possible disponibles dans la longueur du chemin.
