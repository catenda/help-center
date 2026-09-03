# Code QR sur les PDF dans Catenda

Les codes QR peuvent être configurés par dossier dans la [configuration des dossiers](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) des [paramètres des documents](https://support.catenda.com/en/articles/7831371-document-settings).

Cette fonction fournit aux utilisateurs de Catenda une fonction pour vérifier si le document qu'ils utilisent est la dernière version, en scannant le code QR imprimé sur le PDF.

## 1. **Configuration du code QR sur Catenda Hub**

L'attribution du code QR se fait via les dossiers, ce qui signifie que chaque administrateur de projet peut décider d'un ensemble sélectionné de dossiers pour avoir cette fonction.

Voici les étapes pour attribuer la fonction de code QR aux dossiers de votre projet ;

1. Dans le document —> paramètres, accédez à **'configuration des dossiers'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. Cliquez sur le plus à côté de votre dossier souhaité pour ouvrir la configuration des dossiers et sous 'assigner un code QR' dites **'oui'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

Le scan des espaces réservés et le placement des codes QR ne se feront que sur les dossiers avec l'attribution du code QR ;

> **Remarque :** Une fois qu'un dossier parent est assigné, tous les sous-dossiers auront cette attribution Les codes QR peuvent être assignés à n'importe quel dossier une fois qu'un dossier parent n'a pas déjà été assigné.

## 2. Positionnement de l'espace réservé dans votre document

Pour utiliser cette fonction, vous devrez placer l'**[espace réservé du code QR](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**, fourni par Catenda, sur votre document, puis le télécharger sur Catenda Hub. _Exigence de dimension :_ Celui-ci doit avoir une taille minimale de 2 cm sur 2 cm.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

Le lien de téléchargement du code QR peut être trouvé ici :

_[Lien de téléchargement](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 Positionnement du code QR en tant qu'auteur du fichier

Étant donné que les Documents ne peuvent pas être modifiés après leur téléchargement vers Catenda, il est important que l'espace réservé du code QR soit placé sur le document avant son téléchargement vers Catenda. L'espace réservé peut être placé sur n'importe quelle couche sauf la couche d'annotation. Pour que Catenda reconnaisse le code QR, il doit être ajouté en tant qu'image. L'image du document publié doit être exactement la même image que l'image de l'espace réservé.

**Optimisation des PDF** De nombreux programmes effectuent des étapes d'optimisation pour une meilleure visualisation et une réduction de la taille des fichiers. Ces étapes peuvent modifier le nombre d'octets de l'image, ce qui fera que Catenda ne la reconnaît plus. Voici quelques informations sur l'espace réservé qui peuvent vous aider lors de l'optimisation. Densité de pixels : 144 dpi Compression d'image : ZIP L'image doit être une seule image complète. Certains optimiseurs peuvent diviser l'image lors de l'optimisation. Assurez-vous que l'image est complète après l'optimisation.

_Archicad_ Lors du placement du code qr, veuillez utiliser : Importer > interopérabilité > fusionner à partir du fichier > importer et ouvrir la feuille de travail > glisser-déposer Si vous ouvrez la feuille de travail et faites glisser-déposer le PNG, cela changera la résolution et ne fonctionnera pas.

### 2.2 Positionnement du code QR sur un document existant

Si vous avez un document que vous n'avez pas créé et que vous souhaitez ajouter l'espace réservé du code QR avant de le télécharger vers Catenda Hub, assurez-vous de modifier le document et d'ajouter l'espace réservé du code QR en tant qu'image.

### 2.3 Positionnement du code QR sur un document Catenda

Si votre document est déjà sur Catenda, vous devrez ajouter l'espace réservé du code QR et télécharger une nouvelle révision. Si vous n'avez pas accès à un programme d'édition PDF, vous pouvez utiliser l'[outil d'annotation de tampon d'image](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) pour ajouter l'espace réservé du code QR à votre document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

Pour enregistrer le document afin que l'espace réservé du code QR soit reconnu, imprimez le document avec [le bouton d'impression](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70) qui se trouve en haut à gauche de votre aperçu du document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

Cela ouvrira la boîte de dialogue d'impression de votre navigateur. Voici ce que cela peut ressembler pour Google Chrome :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

Dans la boîte de dialogue d'impression, imprimez le document en PDF.

> **Remarque 1 :** Le code QR ne se retrouvera sur la couche de contenu que si vous imprimez le document. Si vous téléchargez le document, il sera sur la couche d'annotation. **Remarque 2 :** En imprimant en PDF, vous rastérisez le contenu du document. Cela signifie que le texte ne sera pas consultable lorsque vous le téléchargerez en tant que révision vers Catenda.

Le PDF imprimé avec l'espace réservé peut maintenant être téléchargé en tant que nouvelle révision vers Catenda. Pour garder votre historique de révisions propre, vous pouvez souhaiter retirer la révision précédente sans le code QR.

## 3. **Publication avec codes QR**

1. Téléchargez une nouvelle révision d'un PDF avec l'espace réservé dans un dossier avec attribution du code QR
1. Lors de la publication, le PDF sera scanné à la recherche de l'espace réservé et remplacé par un code QR (généré pour cette révision)
1. Le code QR nouvellement généré deviendra partie du PDF, qui peut être visualisé/scanné sur Catenda Hub et/ou téléchargé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

Voici un exemple du positionnement de l'espace réservé du code QR et des résultats après le téléchargement vers Catenda Hub. 1\. Espace réservé dans le bloc titre d'un dessin. **Prêt pour le téléchargement.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. L'espace réservé dans le bloc titre est remplacé par le code QR généré. **Prêt pour la vérification.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **Historique des documents**

Après avoir téléchargé un document avec un espace réservé de code QR, vous pourrez voir qu'il a été traité avec succès dans l'historique du document du [menu d'informations de droite](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

Si la génération de votre code QR a échoué, cela peut être parce que votre code QR était plus petit que 2 cm x 2 cm ou qu'il a été placé en tant qu'annotation au lieu d'une image.

**Aplatissement des annotations** Certains logiciels vous permettent d'aplatir les annotations, ce qui permettra au placeholder d'être traité. Voici quelques exemples :

**PDF X-Change**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

**Adobe Acrobat**

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ Lorsque vous placez l'espace réservé dans BlueBeam Revu et enregistrez le document, il sera ajouté en tant qu'annotation. Il est possible d'aplatir le code QR pour en faire partie de la couche de contenu du document, mais même lors de l'enregistrement régulier ou à l'aide de l'option de taille de fichier réduite, le code QR sera modifié et ne fonctionnera pas avec Catenda. Pour que le code QR fonctionne avec Catenda, à la place : Imprimez le document avec le pilote BlueBeam :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

Dans la boîte de dialogue Enregistrer sous, sélectionnez Graphiques ZIP et activez le post-traitement. C'est parce que l'algorithme de compression utilisé pour l'espace réservé est ZIP.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

Dans le menu de post-traitement, choisissez l'option Combiner les images adjacentes. C'est parce que l'image est normalement divisée en deux, donc elle la recombine. Si votre taille de page n'existe pas en tant qu'option par défaut, vous pouvez en ajouter une personnalisée ici :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
