# Code QR sur les fichiers PDF dans Catenda

Les codes QR peuvent être configurés par dossier dans la [configuration de dossier](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) des [paramètres de Documents](https://support.catenda.com/en/articles/7831371-document-settings).

Cette fonction fournit aux utilisateurs de Catenda la possibilité de vérifier si le Documents qu'ils utilisent est la version la plus récente, en scannant le code QR imprimé sur le fichier PDF.

## 1. **Configuration du code QR sur Catenda Hub**

L'assignation du code QR s'effectue via des dossiers, ce qui signifie que chaque administrateur de projet peut décider d'un ensemble sélectionné de dossiers pour activer cette fonction.

Voici les étapes pour assigné la fonction de code QR aux dossiers de votre projet ;

1. Sous le Documents —> paramètres, accédez à **'configuration de dossier'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. Cliquez sur le plus à côté de votre dossier souhaité pour ouvrir la configuration du dossier et sous 'assigné un code QR' dites **'oui'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

La numérisation des espaces réservés et le placement des codes QR ne s'effectueront que sur les dossiers avec assignation de code QR ;

> **Remarque :** Une fois qu'un dossier parent est assigné, tous les sous-dossiers auront cette assignation. Les codes QR peuvent être assignés à n'importe quel dossier une fois qu'un dossier parent n'a pas déjà été assigné.

## 2. Placement de l'espace réservé dans votre Documents

Pour utiliser cette fonction, vous devez placer l'**[espace réservé du code QR](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**, fourni par Catenda, sur votre Documents, puis le télécharger sur Catenda Hub. _Exigence de dimension :_ Cela doit avoir une taille minimale de 2 cm sur 2 cm.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

Le lien de téléchargement du code QR peut être trouvé ici :

_[Lien de téléchargement](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 Placement du code QR en tant qu'auteur de fichier

Comme les Documents ne peuvent pas être modifiés après leur téléchargement sur Catenda, il est important que l'espace réservé du code QR soit placé sur le Documents avant qu'il ne soit téléchargé sur Catenda. L'espace réservé peut être placé sur n'importe quelle couche sauf la couche d'annotation. Pour que Catenda reconnaisse le code QR, il doit être ajouté en tant qu'image. L'image dans le Documents publié doit être exactement la même image que l'image de l'espace réservé.

**Optimisation des fichiers PDF** De nombreux programmes effectuent des étapes d'optimisation pour une meilleure visualisation et une réduction de la taille des fichiers. Ces étapes pourraient modifier la quantité d'octets dans l'image, ce qui ferait que Catenda ne la reconnaîtrait plus. Voici quelques informations sur l'espace réservé qui peuvent aider à l'optimisation. Densité de pixels : 144 dpi Compression d'image : ZIP L'image doit être une seule image complète. Certains optimiseurs pourraient diviser l'image en tant qu'optimisation. Veuillez vous assurer que l'image est complète après optimisation.

_Archicad_ Lors du placement du code qr, veuillez utiliser : Importer > interopérabilité > fusionner à partir du fichier > importer et ouvrir feuille de calcul > glisser-déposer Si vous ouvrez la feuille de calcul et glissez-déposez le PNG, la résolution changera et ne fonctionnera pas.

### 2.2 Placement du code QR sur un Documents existant

Si vous avez un Documents que vous n'avez pas créé et que vous souhaitez ajouter l'espace réservé du code QR avant de le télécharger sur Catenda Hub, assurez-vous d'éditer le Documents et d'ajouter l'espace réservé du code QR en tant qu'image.

### 2.3 Placement du code QR sur un Documents Catenda

Si votre Documents est déjà sur Catenda, vous devrez ajouter l'espace réservé du code QR et télécharger une nouvelle révision. Si vous n'avez pas accès à un programme d'édition PDF, vous pouvez utiliser l'[outil d'annotation de tampon d'image](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) pour ajouter l'espace réservé du code QR à votre Documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

Pour enregistrer le Documents afin que l'espace réservé du code QR soit reconnu, imprimez le Documents avec [le bouton d'impression](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70) que vous pouvez trouver en haut à gauche de votre aperçu de Documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

Cela ouvrira la boîte de dialogue d'impression de votre navigateur. Voici à quoi cela peut ressembler pour Google Chrome :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

Dans la boîte de dialogue d'impression, imprimez le Documents au format PDF.

> **Remarque 1 :** Le code QR ne finira que sur la couche de contenu si vous imprimez le Documents. Si vous téléchargez le Documents, il sera sur la couche d'annotation. **Remarque 2 :** En imprimant au format PDF, vous rastérisez le contenu du Documents. Cela signifie que le texte ne sera pas consultable lorsque vous le téléchargez en tant que révision sur Catenda.

Le fichier PDF imprimé avec l'espace réservé peut maintenant être téléchargé en tant que nouvelle révision sur Catenda. Pour garder votre Historique des révisions propre, vous pourriez vouloir retirer la révision précédente sans le code QR.

## 3. **Publication avec codes QR**

1. Téléchargez une nouvelle révision d'un fichier PDF avec l'espace réservé dans un dossier avec assignation de code QR
2. Lors de la publication, le fichier PDF sera scanné pour l'espace réservé et remplacé par un code QR (généré pour cette révision)
3. Le code QR nouvellement généré fera partie du fichier PDF, qui peut être consulté/scanné sur Catenda Hub et/ou téléchargé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

Voici un exemple du placement de l'espace réservé du code QR et des résultats après le téléchargement sur Catenda Hub. 1\. Espace réservé dans le bloc titre d'un dessin. **Prêt pour le téléchargement.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. L'espace réservé dans le bloc titre est remplacé par le code QR généré. **Prêt pour la vérification.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **Historique du Documents**

Après avoir téléchargé un Documents avec un code QR d'espace réservé, vous pourrez le voir a été traité avec succès dans l'Historique du Documents du [menu d'informations de droite](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

Si la génération de votre code QR a échoué, cela peut être parce que votre code QR était plus petit que 2 cm x 2 cm ou qu'il a été placé en tant qu'annotation au lieu d'image.

**Aplatissement des annotations** Certains logiciels vous permettent d'aplatir les annotations ce qui permettra à l'espace réservé d'être traité. Voici quelques exemples :

**PDF X-change**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

**Adobe Acrobat**

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ Lorsque vous placez l'espace réservé dans BlueBeam Revu et enregistrez le Documents, il sera ajouté en tant qu'annotation. Il est possible d'aplatir le code QR pour en faire partie de la couche de contenu du Documents, mais même lors de son enregistrement régulièrement ou en utilisant l'option de taille de fichier réduite, le code QR sera modifié et ne fonctionnera pas avec Catenda. Pour que le code QR fonctionne avec catenda, à la place : Imprimez le Documents avec le pilote BlueBeam :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

Dans la boîte de dialogue Enregistrer sous, sélectionnez les graphiques ZIP et activez le post-traitement. C'est parce que l'algorithme de compression utilisé pour l'espace réservé est ZIP.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

Dans le menu post-traitement, choisissez l'option Combiner les images adjacentes. C'est parce que l'image sera normalement divisée en deux, elle les recombine ensemble. Si la taille de votre page n'existe pas en tant qu'option par défaut, vous pouvez en ajouter une personnalisée ici :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
