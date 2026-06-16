# QR-Code sur les PDF dans Catenda

Les codes QR peuvent être configurés par dossier dans la [configuration des dossiers](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) des [paramètres du document](https://support.catenda.com/en/articles/7831371-document-settings).

Cette fonction permet aux utilisateurs de Catenda de vérifier si le document qu'ils utilisent est la dernière version, en scannant le code QR imprimé sur le PDF.

Cet article contient des informations sur les sujets suivants :

**[Placement](#h_ea221d5cae) - [Configuration](#h_e66cc03a0e) - [Publication](#h_c7f0685c1c) - [Vérification](#h_8e9c27030b)**

## Placer le Placeholder dans votre document

Pour utiliser cette fonction, vous devez placer le **[code QR](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)** fourni par Catenda dans votre document et le télécharger ensuite dans Catenda Hub.

_Dimensions requises :_ Le code doit avoir une taille minimale de 2 cm sur 2 cm.

![](https://downloads.intercomcdn.com/i/o/1129210747/3afe134405c9c151b8ed9936/image.png?expires=1781092800&signature=c2ea1933f269989980b29fa6c815f2115ec45196d7a904078bb197360e86fddf&req=dSElH8t%2FnYZbXvMW3nq%2BgZCIR8olrrgqRy31Ne2%2BudU3rI2Jb6gXfXlYW6X%2F%0AXNTNl9vBqIGhWJFcubOVyA7Cdis%3D%0A)

Le lien de téléchargement du QR-Code se trouve ici :

**[Lien de téléchargement](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**

### Placer le code QR en tant qu'auteur du fichier

Comme les documents ne peuvent pas être modifiés après avoir été téléchargés sur Catenda, il est important que le QR-Code soit placé sur le document avant qu'il ne soit téléchargé sur Catenda.

Le placeholder peut être placé sur n'importe quelle couche, à l'exception de la couche d'annotation.

Pour que Catenda reconnaisse le QR-Code, il doit être ajouté en tant qu'image. L'image dans le document publié doit être exactement la même que celle de l'espace réservé.

**Optimisation des PDF**

De nombreux programmes effectuent des étapes d'optimisation afin d'améliorer l'affichage et de réduire la taille du fichier. Ces étapes peuvent modifier le nombre d'octets de l'image, ce qui fait que Catenda ne la reconnaît plus.

Voici quelques informations sur l'image de remplacement qui peuvent aider à l'optimisation.

Densité de pixels : 144 dpi

Compression de l'image : ZIP

L'image doit être une image entière. Certains optimiseurs peuvent diviser l'image pour l'optimiser. Veuillez vous assurer que l'image est entière après l'optimisation. _Archicad_ Lorsque vous placez le code qr, veuillez utiliser :

Importation > interpolation > fusion à partir d'un fichier > importation et ouverture d'une feuille de calcul > glisser-déposer

Si vous ouvrez la feuille de travail et que vous glissez-déposez le PNG, la résolution changera et cela ne fonctionnera pas.

### Placer le QR-code sur un document existant

Si vous avez un document que vous n'avez pas créé et que vous souhaitez ajouter le QR-Placeholder avant de le télécharger sur Catenda Hub, assurez-vous d'éditer le document et d'ajouter le QR-Placeholder en tant qu'image.

### Placer le QR-code sur un document Catenda

Si votre document est déjà sur Catenda, vous devrez ajouter le QR-Placeholder et télécharger une nouvelle révision. Si vous n'avez pas accès à un programme d'édition de PDF, vous pouvez utiliser l'[outil d'annotation de timbre-image](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) pour ajouter le QR-placeholder à votre document.

![](https://downloads.intercomcdn.com/i/o/1165885061/ae025a55c35d673b26d3b3ec/image.png?expires=1781092800&signature=f469acea7eb841bcc95627902b16ee5ed109ab644f6afc371231b6d465916809&req=dSEhE8F2mIFZWPMW3nq%2Bga02mppt6hBCA90R4m71PN0kw8C4zyvbvgGu9rh3%0ADTOcjhPIJS2btWeIeuUssChmLaY%3D%0A)

Pour enregistrer le document de manière à ce que le marqueur QR soit reconnu, imprimez le document à l'aide du [bouton d'impression](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70) qui se trouve en haut à gauche de l'aperçu du document.

![](https://downloads.intercomcdn.com/i/o/1165883068/4a74577bed69bc1c9d03fb70/image.png?expires=1781092800&signature=6bed605d6f4023da5dd176c37e0bcb02c2260da48b745b166ca9180ffd2634be&req=dSEhE8F2noFZUfMW3nq%2BgbP8OSnIbWHHuDUSH4RtEiAwcPStemLi4y8ICBXM%0AnUVMJVgMAm3izg74YLei43u1ZF8%3D%0A)

Cela ouvrira la boîte de dialogue d'impression de votre navigateur.

Voici à quoi cela peut ressembler pour Google Chrome :

![](https://downloads.intercomcdn.com/i/o/1165888827/f660b2af47c24e1514b73c70/image.png?expires=1781092800&signature=3244fada036415f24b00afb5bf9f81dbc5115b934b4f3afcede9a8e30a446fb5&req=dSEhE8F2lYldXvMW3nq%2BgUlKoXiLbDdj4BFNUGbByCq8Sapme9Px1qV28zGd%0AMlM6KNMxS%2B0SwM2qf7lUMNxvA60%3D%0A)

Dans la boîte de dialogue d'impression, imprimez le document au format PDF.

> **Note:** **Note 1 :** Le code QR n'apparaîtra sur la couche de contenu que si vous imprimez le document. Si vous téléchargez le document, il se trouvera sur la couche d'annotation. **note 2 :** En imprimant au format PDF, vous rastérisez le contenu du document. Cela signifie que le texte ne pourra pas être recherché lorsque vous le téléchargerez en tant que révision dans Catenda.

Le PDF imprimé avec l'espace réservé peut maintenant être téléchargé en tant que nouvelle révision dans Catenda.

Pour garder votre historique de révision propre, vous pouvez retirer la révision précédente sans le code QR.

## Configuration du QR-Code sur Catenda Hub

L'attribution du code QR se fait par le biais des dossiers, ce qui signifie que chaque administrateur de projet peut décider d'un ensemble de dossiers sélectionnés pour cette fonction.

Voici les étapes pour assigner la fonction QR-code aux dossiers de votre projet ;

1. Dans le document -> paramètres, allez à **"configuration des dossiers"**

![](https://downloads.intercomcdn.com/i/o/1058260520/dddd82c067f7b46accb5b32c/image.png?expires=1781092800&signature=e7941acca8aedcea4e848c67e0007a4e09578fab49b5e5c9a824b181ac99454a&req=dSAiHst4nYRdWfMW3nq%2BgRkR2h4rS0XQNc9lbtEQewqJ6NZ6VLakXmSCbXYB%0AVxWNDann97ZsWaqAzYsRKbOcTVk%3D%0A)

2. Cliquez sur le plus à côté du dossier souhaité pour ouvrir la configuration du dossier et sous "assigner le code QR", dites **"oui** "

![](https://downloads.intercomcdn.com/i/o/1058261375/a52f5da19606885304d919f1/image.png?expires=1781092800&signature=4c64a3d24c6c5463ebe93bbe1059a2dbb1bb4338b4ad72cfa53803d88d531b46&req=dSAiHst4nIJYXPMW3nq%2BgSrY7yhARKJj3Bos80hgsCYYWj1IyWqj837ROIDg%0ADGVbmygamuvFA2FrHAL5c1SXMPw%3D%0A)

La numérisation des espaces réservés et le placement des codes QR n'auront lieu que dans les dossiers auxquels un code QR a été attribué ;

> **Note:** **Remarque :** une fois qu'un dossier parent est attribué, tous les sous-dossiers recevront cette attribution Les codes QR peuvent être attribués à n'importe quel dossier dès lors qu'un dossier parent n'a pas encore été attribué.

### Publication avec des codes QR

1. Téléchargez une nouvelle révision d'un PDF avec le caractère générique dans un dossier auquel un code QR a été attribué
1. Lors de la publication, le PDF sera scanné à la recherche de l'espace réservé et remplacé par un code QR (généré pour cette révision)
1. Le code QR nouvellement généré fera partie du PDF, qui pourra être visualisé/scanné sur Catenda Hub et/ou téléchargé.

![](https://downloads.intercomcdn.com/i/o/1058270845/bbf3025f7cf4ce2c44e5ff3a/image.png?expires=1781092800&signature=87316e36cd478d482c98ab3fde729320404c1178d31708e40ca8cb797844e67a&req=dSAiHst5nYlbXPMW3nq%2BgcetveFGeYCsO6kaiNDTAeDsrR86FZzvPBsliNcU%0AoJizxECcx70jjX9lsLKDjBubHOo%3D%0A)

Voici un exemple de l'emplacement du code QR et des résultats après le téléchargement sur Catenda Hub. 1. Placeholder dans le bloc de titre d'un dessin. **Prêt à être téléchargé.**

![](https://downloads.intercomcdn.com/i/o/1128898386/b042fd79d7595f8d12a0159c/image.png?expires=1781092800&signature=7b305493e3afeef99f797c6bde7577f9ee147be9259ffd5234d136ceb18b19a5&req=dSElHsF3lYJXX%2FMW3nq%2BgcCYNHtVa2O6MpBCTIpzHdyIjlAArQsK42e3eW8C%0ARJ8ENFmJfkyirg6BcnLQ%2FlGVRgM%3D%0A)

2. L'espace réservé dans le cartouche est remplacé par le code QR généré. **Prêt pour la vérification.**

![](https://downloads.intercomcdn.com/i/o/1129687828/6fba8f5b78f9f26b6c0e5b25/image.png?expires=1781092800&signature=55a085321bf04009ffc5682bedfb937e1a8a745978110ea5fa2e653c230c60eb&req=dSElH892moldUfMW3nq%2BgZOaMeorej4wNegl5eWFN3XW6bJCLqd8omIpfqDg%0AO6V0qLi3tjmDOiAbb2n%2BOrLzNCo%3D%0A)

### Historique du document

Après avoir téléchargé un document avec un code QR, vous pourrez voir qu'il a été traité avec succès dans l'historique du document dans le [menu d'information de droite](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://downloads.intercomcdn.com/i/o/1158296344/8501b8c6f0f7482ddb0c7197/image.png?expires=1781092800&signature=1e5deaa95185367a07c23d5631171b26024e8b89c794c5efe22feaa680d9b0ca&req=dSEiHst3m4JbXfMW3nq%2BgewPTFkD53NGqyS8JRv2yXNIp5f6r7f4i1A6fjMn%0A%2Fz4hmqzWLABpzCZJ%2Fg6mvXrdJyI%3D%0A)

Si la génération de votre code QR a échoué, cela peut être dû au fait que votre code QR était plus petit que 2cm x 2cm ou qu'il a été placé en tant qu'annotation au lieu d'une image.

**Aplatir les annotations**

Certains logiciels permettent d'aplatir les annotations, ce qui permet de traiter l'espace réservé.

Voici quelques exemples :

**PDF X-change**

![](https://downloads.intercomcdn.com/i/o/1158320081/b9774d23bf69244a53c6677c/image.png?expires=1781092800&signature=aee14a2b2de51226325ef2fd47deac0b6a7e31a185455f7ef6732fb438418455&req=dSEiHsp8nYFXWPMW3nq%2Bga6WZ0m2TsLc5vpEJEy3apY1DWFS5YUEXwWcGHrD%0A%2FRUu%2FVy7gDNxref2%2FtxTh835Rgc%3D%0A)

**Adobe Acrobat**

![](https://downloads.intercomcdn.com/i/o/1158321222/a0ef6a62a1446027ae555371/image.png?expires=1781092800&signature=170ea2c989478be21e642c31ce3b024172f2a85fa046b32d8f6dd48d0e4d0059&req=dSEiHsp8nINdW%2FMW3nq%2BgYbe1cpY6%2B%2Bqbx2jeLpWOp5WQ1EnJG8EKT3zgybU%0A2cuw3Hj3W2xHQJaGmkv81Ac9Dno%3D%0A)

![](https://downloads.intercomcdn.com/i/o/1158321809/3012a1e60769cac4c4c66927/image.png?expires=1781092800&signature=fa12a072f48bb25045331ec0b732be3aa4733327bd1314825f4b019de5b7cac2&req=dSEiHsp8nIlfUPMW3nq%2Bgae%2B94TJ3Blas4eGR7qsCoN1m7TVPYwpQiH4X1RA%0AK7557p4HpFp%2Bo8CSDc2fx%2BOlpI0%3D%0A)

_BlueBeam Revu_ Lorsque vous placez l'espace réservé dans BlueBeam Revu et que vous enregistrez le document, il est ajouté en tant qu'annotation. Il est possible d'aplatir le code QR pour qu'il fasse partie de la couche de contenu du document, mais même en l'enregistrant régulièrement ou en utilisant l'option de réduction de la taille du fichier, le code QR sera modifié et ne fonctionnera pas avec Catenda.

Pour que le QR-code fonctionne avec Catenda, il faut plutôt

Imprimez le document avec le pilote BlueBeam :

![](https://downloads.intercomcdn.com/i/o/1158701866/cdb3dad8520ad9922fc83b80/image.png?expires=1781092800&signature=bf9fc4876c441d15de14a343431d2b87d940fefb32fce6972e65c9c0a97eb752&req=dSEiHs5%2BnIlZX%2FMW3nq%2BgbggalZVq%2BITFpjjrTB1u9B%2F%2Bh4zRLT%2Fobt7Jze1%0AAkpOYt1kSbjWdyiPq%2F3wh6fKumU%3D%0A)

Dans la boîte de dialogue Enregistrer sous, sélectionnez ZIP graphics et activez le post-traitement. En effet, l'algorithme de compression utilisé pour l'espace réservé est ZIP.

![](https://downloads.intercomcdn.com/i/o/1158706510/20d6307f60ff541da3591698/image.png?expires=1781092800&signature=6c9c52da176e71d33a937ceb3e0b18b277326f1841bd7079ba5431be7b196bb5&req=dSEiHs5%2Bm4ReWfMW3nq%2BgZ2NDBVmQLRv8ONaLnaJJ5qkQIAKJ9MF%2FTOhkUY6%0Afi0WqOywf3njxKsmY6mHN7yBEWk%3D%0A)

Dans le menu de post-traitement, choisissez l'option Combiner les images adjacentes. En effet, l'image est normalement divisée en deux et le post-traitement la combine à nouveau. Si votre taille de page n'existe pas en tant qu'option par défaut, vous pouvez en ajouter une personnalisée ici :

![](https://downloads.intercomcdn.com/i/o/1159572236/695f90c63c88bc45e6be27ae/image.png?expires=1781092800&signature=fbf5d6383e17d8ddbea0e397999413fdc10e4ab2b1096f998c4003bad5c37afd&req=dSEiH8x5n4NcX%2FMW3nq%2BgW32aqFEwBD2XBCw3n0xGmY%2FjAhzSZOKeLycCrcG%0AdOGFYSZ3RWYwpj4SYUPInsxn1Mg%3D%0A)

## Vérification de la dernière révision

En scannant le code QR avec votre smartphone, vous accéderez à une page de vérification où les résultats suivants apparaîtront en fonction de la version du PDF ;

1. Votre révision est la dernière version du PDF : **Document valide**
1. Votre révision est une ancienne version du PDF : **Document non valide**
1. Vous avez numérisé un espace réservé : **Vous avez numérisé un espace réservé, ce document n'est pas publié**

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1128836302/b5ed664002c909cad1388c1c/image.png?expires=1781092800&amp;signature=e32a0bc159c2fe53c0580cf78540908f18b726e36d6e988f6fd07bba7b2f7069&amp;req=dSElHsF9m4JfW%2FMW3nq%2BgRAbWSa0uwekHXdmw0dniPvD%2F48H6GJmWGPMPCrC%0AngeKuBJW%2FPMavpOc%2Btwvf9PFqVY%3D%0A"/></div>
