# Models comme Documents

Auparavant, il était possible de télécharger des fichiers IFC à deux endroits différents sur Catenda Hub. Avec la fonction _models comme documents_, ces deux emplacements pour les fichiers de model seront fusionnés en une fonction transparente. Si vous créez un model dans la section models, un Document sera lié et créé dans la section Documents. Si vous téléchargez un Document IFC, vous pouvez utiliser le bouton d'action "make model" pour lier et créer un model dans la section models. Avec cette fonction, les models de la section models peuvent être traités comme des Documents tandis que les models de la section Documents peuvent être traités comme des models.

## 1. **Avant/Après migration - Différences principales**

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e8e8e880; width: 126px;"><h1 id="h_3632d3cc1b"></h1></td><td style="background-color: #e8e8e880; width: 262px;"><h2 class="intercom-align-center" id="h_2093155130"><b>Avant</b></h2></td><td style="background-color: #e8e8e880; width: 248px;"><h2 class="intercom-align-center" id="h_d5cfcbcb2d"><b>Après</b></h2></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Comportement principal</b></p></td><td style="width: 262px;"><p>Les models existaient uniquement dans la section Model. L'utilisateur devait télécharger le même fichier IFC dans les sections Document et Model.</p></td><td style="width: 248px;"><p>Les models sont créés à partir de fichiers IFC téléchargés dans la section Document, sur demande de l'utilisateur. Le fichier IFC et son model associé sont ensuite liés.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Interface utilisateur</b></p></td><td style="width: 262px;"><p><b>Différente</b> de la section Document et affichant moins d'informations, essentiellement juste une liste de models.</p></td><td style="width: 248px;"><p><b>Identique</b> à la section Document : un tableau personnalisable avec les métadonnées associées.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Droits d'accès</b></p></td><td style="width: 262px;"><p><b>Impossible à appliquer</b> aux models</p></td><td style="width: 248px;"><p><b>Peut être appliqué</b> aux models à partir de leur Document associé dans la section Document</p></td></tr></tbody></table></div>

## 2. **Familier mais différent**

Maintenant que les deux sections ont été liées, il est important de noter qu'il existe toujours des différences clés entre les sections models et Documents. Dans la section models, vous pourrez voir tous les model-Documents rassemblés dans une liste. Ici, vous verrez vos model-Documents d'une manière similaire à la façon dont ils seront utilisés dans la Visionneuse 3D. Dans la section Documents, vous pourrez voir les Document-models dans votre structure de Document. Ici, vous verrez vos Document-models d'une manière similaire à la façon dont ils seront utilisés dans votre environnement commun de données. Tous les models sont liés à chacun de leurs propres Documents et les fonctionnalités des deux sections peuvent être utilisées à la fois dans la section models et dans la section Documents.

## 3. **Changements de la section models**

Avec models comme Documents, l'apparence de la section models a changé. Au lieu de voir des éléments de menu pour chaque model, ils apparaîtront maintenant dans un tableau consultable.

Dans la section models, vous pourrez trouver les changements suivants :

### 3.1 **Tableau model**

Le nouveau tableau models peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/01-model-table.png)

### 3.2 **Colonnes**

La liste model contient des colonnes qui affichent la plupart des informations que vous devez connaître sur vos models.

_Nom_ Le nom du model-Document Le nom du model est également le nom que vous verrez dans le sélecteur de revision dans la vue 3D.

**Nom du Document** Le nom du Document-model dans la section Documents

**Nom de revision** Le nom de la dernière revision

### 3.3 **Contrôle d'accès**

Si un model a été restreint pour vous dans la section Documents, vous ne le voyez ni dans la section Documents, ni dans le tableau models, ni dans le sélecteur de revision.

### 3.4 **Sélection d'éléments de tableau**

Avec le tableau model, vous pouvez maintenant sélectionner une série de models en maintenant Maj enfoncée. Vous pouvez également ajouter ou supprimer des models de votre sélection en maintenant Ctrl enfoncé.

### 3.5 **Boutons d'action**

Auparavant, la seule action que vous pouviez effectuer sur les models sélectionnés était leur ouverture en 3D. Maintenant, vous pouvez télécharger, supprimer et ouvrir la vue 2D de vos models sélectionnés. Si vous supprimez un model connecté à un Document, le Document perdra la connexion au model, mais le Document restera dans la section Document.

### 3.6 **Contrôle d'accès à Document-models**

**Création d'un model-Document** Si vous créez un model avec le bouton de création de model dans la section models, vous serez invité à sélectionner l'endroit où vous voulez que le Document-model lié se termine dans la section Documents. Dans la boîte de dialogue de création de model, vous pourrez également donner un nom au model. Le Document-model lié résultant aura le même nom que le model lors de sa création. Catenda Hub mémorisera le dossier que vous avez choisi en dernier et le sélectionnera automatiquement la prochaine fois que vous créerez un model-Document.

Si votre projet a commencé sans models comme Documents, un dossier appelé « Models » aura apparu dans votre structure de dossiers. Le dossier models qui apparaît contient tous les Document-models qui sont liés aux model-Documents de la section model. Les Document-models peuvent être déplacés de ce dossier n'importe où dans la section Documents à laquelle vous avez accès. Les Document-models du dossier Models peuvent également être supprimés (et restaurés) si vous le souhaitez. Les Document-models n'ont pas besoin d'être dans le dossier et le dossier models peut être supprimé si nécessaire.

**Création d'une revision de model** Pour pouvoir télécharger de nouvelles revisions vers un model, vous devez maintenant avoir au moins un accès en écriture au Document model. De nouvelles revisions du model peuvent être ajoutées au Document et vice versa.

> **Note :** Les commentaires de revision ont été désactivés et peuvent maintenant être activés de manière optionnelle avec [des champs personnalisés sur les revisions](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents).

**Téléchargement d'une revision de model** Vous devez avoir au moins un accès en lecture au Document-model pour pouvoir télécharger le model.

### 3.7 **Menu d'information à droite**

Un menu d'information à droite sera disponible si un model est sélectionné.

**Champ Document** Dans ce menu, vous verrez vos informations sur le model ainsi qu'un champ gris qui se lie au Document-model de la section Document qui est lié à ce model-Document. Cliquez sur le champ Document pour ouvrir le Document-model qui est lié à ce model.

**Étiquettes model** Vous pouvez maintenant également ajouter des Étiquettes à vos models ici.

**Statut du model** Si des Statuts ont été configurés dans les paramètres Document, vous pourrez configurer un Statut pour votre model ici.

**Transformation de model** Si vous avez ouvert ce model en 3D, vous pourrez configurer la transformation de model ici.

## 4. **Changements de la section Documents**

Bien que les changements visuels ne soient pas aussi apparents que dans la section models, il y a quelques choses qui changeront dans la section Documents lorsque models comme Documents est activé. Voici à quoi peuvent ressembler les Document-models dans la section Documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/02-documents-section-changes.png)

Dans la section Documents, vous pourrez trouver les changements suivants :

### 4.1 **Filtre model**

Dès que vous avez des models dans la section models, vous verrez un Filtre model apparaître dans votre menu de Filtres. Avec ce Filtre, vous pouvez afficher/masquer les Document-models qui ont été créés.

### 4.2 **Colonnes**

**Icône** Vous pourrez distinguer un Document-model d'un Document ordinaire par le badge model situé en bas à droite de l'icône du Document-model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/03-columns.png)

**Nom** Le nom du Document

**Nom du model** Le nom du model Si votre Document IFC n'a pas été lié à un model, vous verrez ici un bouton de création de model.

**Nom de revision** Le nom de la dernière revision du model

**Visionneuse** Une colonne avec des boutons pour ouvrir chaque Document-model individuellement dans la Visionneuse 3D. L'ouverture des Document-models dans la Visionneuse 3D n'est possible que si le Document a été lié à un model.

### 4.3 **Boutons d'action**

Téléchargez, supprimez ou chargez les vues 2D/3D des models sélectionnés dans la Visionneuse respective en sélectionnant un ou plusieurs models.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-9e345595c719.png" width="310"/>    <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-959af958f499.png" width="310"/>

Cela signifie que vous pouvez supprimer plusieurs models à la fois au lieu d'un par un comme auparavant. Si vous supprimez un Document connecté à un model, vous devrez approuver un avertissement indiquant que le model connecté au Document sera également supprimé.

> **Note :** Cela signifie que vous pouvez supprimer un model sans perdre les données. (Les Documents supprimés peuvent être récupérés)

### 4.4 **Contrôle d'accès à model-Documents**

**Création de Document-models** Pour pouvoir télécharger de nouvelles revisions vers un model, vous devez maintenant avoir au moins un accès en écriture au Document model. Vous faites cela en créant un model dans le menu d'action d'un Document. Après cela, vous verrez le Document comme un model dans la section models. Le model-Document dans la section models aura le même nom que le Document model, bien que l'un ou l'autre puisse être modifié ultérieurement tout en restant lié. De nouvelles revisions du model peuvent être ajoutées comme revisions au Document et vice versa.

> **Note :** Cela signifie que vous pouvez créer des models à partir de plusieurs fichiers IFC à la fois au lieu d'avoir à les télécharger un par un

**Téléchargement de revisions vers les Document-models** Vous devez avoir au moins un accès en écriture au Document-model pour pouvoir télécharger de nouvelles revisions vers le model. Cela signifie que vous pouvez utiliser la fonction de téléchargement multiple pour télécharger des fichiers IFC vers plusieurs Document-models à la fois

**Téléchargement de Document-models** Vous devez avoir au moins un accès en lecture au Document-model pour pouvoir télécharger le model. Cela signifie que vous pouvez configurer l'accès pour permettre le téléchargement de models séparés au lieu de simplement tous les models ou aucun.

### 4.5 **Découvrabilité**

Les Document-models peuvent maintenant être trouvés dans la section Documents comme n'importe quel autre Document.

- Les Document-models peuvent être structurés en dossiers pour faciliter la navigation vers le bon ensemble de models.
- Des Étiquettes peuvent être ajoutées aux Document-models pour trouver tous les Document-models qui appartiennent à un type.
- [Des champs personnalisés peuvent être ajoutés à des dossiers](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) où les Documents sont téléchargés pour rechercher des valeurs de métadonnées liées à chaque Document-model
- [Des champs personnalisés peuvent être ajoutés à des dossiers](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) où les Documents sont téléchargés pour pouvoir ajouter des informations à chaque revision dans chaque Document model.

Consultez [ici](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) pour des suggestions sur la façon de structurer vos Document-models afin qu'ils soient faciles à trouver.

### 4.6 **Approuver les fichiers IFC partagés**

Les fichiers IFC peuvent maintenant être téléchargés comme revisions partagées afin qu'ils puissent suivre un processus d'approbation avant d'être publiés.

### 4.7 **Convention de nommage avec Document-models**

Les noms dans la section Documents incluent souvent des abréviations compressées pour garder le nom du Document court tout en montrant certaines informations sur le sujet du Document. Le nom du Document-model peut donc différer du nom du model-Document pour le maintenir en ligne avec les autres Documents de la section Documents tout en conservant un nom facile à lire à utiliser dans la Visionneuse 3D de la section models. Le nom du Document du Document-model sera le nom reconnu lors du téléchargement de Documents dans la section Documents. Si le nom est similaire ou identique au Document, une nouvelle revision sera automatiquement créée comme pour les autres Documents.

Parce que les Document-models se comportent de la même manière que les models ordinaires, il est maintenant possible d'utiliser la convention de nommage avec les Document-models pour assurer que les participants de votre projet donnent le bon nom au Document lors du téléchargement.
