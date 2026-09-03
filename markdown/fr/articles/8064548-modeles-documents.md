# Modèles en tant que documents

Auparavant, il était possible de télécharger des fichiers IFC à deux endroits distincts sur Catenda Hub. Avec la fonction _modèles en tant que documents_, ces deux emplacements pour les fichiers de modèle seront fusionnés en une seule fonction transparente. Si vous créez un modèle dans la section modèles, un document sera lié et créé dans la section documents. Si vous téléchargez un document IFC, vous pouvez utiliser le bouton d'action "créer un modèle" pour lier et créer un modèle dans la section modèles. Avec cette fonction, les modèles de la section modèles peuvent être traités comme des documents tandis que les modèles de la section documents peuvent être traités exactement comme des modèles.

## 1. **Migration Avant/Après - Différences principales**

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e8e8e880; width: 126px; padding: 8px;"><h1 id="h_3632d3cc1b"></h1></td><td style="background-color: #e8e8e880; width: 262px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_2093155130"><b>Avant</b></h2></td><td style="background-color: #e8e8e880; width: 248px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_d5cfcbcb2d"><b>Après</b></h2></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Comportement principal</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Les modèles existaient uniquement dans la section Modèle. L'utilisateur devait télécharger le même fichier IFC dans les sections Document et Modèle.</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Les modèles sont créés à partir de fichiers IFC téléchargés dans la section Documents, si l'utilisateur le demande. Le fichier IFC et son modèle associé sont alors liés.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Interface utilisateur</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Différente</b> de la section Documents et affichant moins d'informations, essentiellement une liste de modèles.</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Identique</b> à la section Documents : un tableau personnalisable avec les métadonnées associées.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Droits d'accès</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Ne pouvait pas être appliqué</b> aux modèles</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Peut être appliqué</b> aux modèles à partir de leur document associé dans la section documents</p></td></tr></tbody></table></div>

## 2. **Familier mais différent**

Maintenant que les deux sections ont été liées, il est important de noter qu'il existe encore certaines différences clés entre les sections modèles et documents. Dans la section modèles, vous pourrez voir tous les modèles-documents rassemblés dans une liste. Ici, vous verrez vos modèles-documents d'une manière similaire à la façon dont ils seront utilisés dans la visionneuse 3D. Dans la section documents, vous pourrez voir les documents-modèles dans votre structure de documents. Ici, vous verrez vos documents-modèles d'une manière similaire à la façon dont ils seront utilisés dans votre environnement de données commun. Tous les modèles sont liés à leur propre document et les fonctionnalités des deux sections peuvent être utilisées dans la section modèles et dans la section documents.

## 3. **Modifications de la section modèles**

Avec les modèles en tant que documents, la section modèles a changé d'apparence. Au lieu de voir des éléments de menu pour chaque modèle, ils apparaîtront désormais dans un tableau consultable.

Dans la section modèles, vous pourrez trouver les modifications suivantes :

### 3.1 **Tableau des modèles**

Le nouveau tableau des modèles peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/01-model-table.png)

### 3.2 **Colonnes**

La liste des modèles contient des colonnes qui affichent la plupart des informations que vous devez connaître sur vos modèles.

_Nom_ Le nom du modèle-document Le nom du modèle est également le nom que vous verrez dans le sélecteur de révision dans la vue 3D.

**Nom du document** Le nom du document-modèle dans la section documents

**Nom de révision** Le nom de la dernière révision

### 3.3 **Contrôle d'accès**

Si un modèle a été restreint pour vous dans la section documents, vous ne le verrez ni dans la section documents, ni dans le tableau des modèles, ni dans le sélecteur de révision.

### 3.4 **Sélection d'éléments de tableau**

Avec le tableau des modèles, vous pouvez maintenant sélectionner une plage de modèles en maintenant la touche Maj enfoncée. Vous pouvez également ajouter ou supprimer des modèles de votre sélection en maintenant la touche Ctrl enfoncée.

### 3.5 **Boutons d'action**

Par le passé, la seule action que vous pouviez effectuer sur les modèles sélectionnés était l'ouverture de ces modèles en 3D. Maintenant, vous pouvez télécharger, supprimer et ouvrir la vue 2D de vos modèles sélectionnés. Si vous supprimez un modèle connecté à un document, le document perdra la connexion au modèle, mais le document restera dans la section documents.

### 3.6 **Contrôler l'accès aux documents-modèles**

**Création d'un modèle-document** Si vous créez un modèle avec le bouton créer un modèle dans la section modèles, vous serez invité à sélectionner l'endroit où vous souhaitez que le document-modèle lié aboutisse dans la section documents. Dans la boîte de dialogue créer un modèle, vous pourrez également donner un nom au modèle. Le document-modèle lié résultant aura le même nom que le modèle lors de sa création. Catenda Hub mémorisera le dossier que vous avez choisi en dernier et le sélectionnera automatiquement la prochaine fois que vous créerez un modèle-document.

Si votre projet a commencé sans modèles en tant que documents, un dossier appelé 'Modèles' aura été créé dans votre structure de dossiers. Le dossier des modèles qui apparaît contient tous les documents-modèles qui sont liés aux modèles-documents de la section modèles. Les documents-modèles peuvent être déplacés hors de ce dossier n'importe où dans la section documents à laquelle vous avez accès. Les documents-modèles dans le dossier Modèles peuvent également être supprimés (et restaurés) si désiré. Les documents-modèles ne doivent pas être dans le dossier et le dossier des modèles peut être supprimé si nécessaire.

**Création d'une révision de modèle** Pour pouvoir télécharger de nouvelles révisions vers un modèle, vous devez maintenant disposer d'au moins un accès en écriture au modèle de document. De nouvelles révisions du modèle peuvent être ajoutées au document et vice versa.

> **Remarque :** Les commentaires de révision ont été désactivés et peuvent maintenant éventuellement être activés avec [des champs personnalisés sur les révisions](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents).

**Téléchargement d'une révision de modèle** Vous devez disposer d'au moins un accès en lecture au modèle-document pour pouvoir télécharger le modèle.

### 3.7 **Menu d'informations de droite**

Un menu d'informations de droite sera disponible si un modèle est sélectionné.

**Champ de document** Dans ce menu, vous verrez les informations de votre modèle ainsi qu'un champ grisé qui renvoie au document-modèle dans la section documents qui est lié à ce modèle-document. Cliquez sur le champ de document pour ouvrir le document-modèle qui est lié à ce modèle.

**Étiquettes de modèle** Vous pouvez maintenant également ajouter des étiquettes à vos modèles ici.

**Statut du modèle** Si des statuts ont été configurés dans les paramètres du document, vous pourrez configurer un statut pour votre modèle ici.

**Transformation de modèle** Si vous avez ouvert ce modèle en 3D, vous pourrez configurer la transformation du modèle ici.

## 4. **Modifications de la section documents**

Bien que les modifications visuelles ne soient pas aussi apparentes que dans la section modèles, il y a quelques éléments qui changeront dans la section documents lorsque la fonction modèles en tant que documents est activée. Voici ce à quoi les documents-modèles peuvent ressembler dans la section documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/02-documents-section-changes.png)

Dans la section documents, vous pourrez trouver les modifications suivantes :

### 4.1 **Filtre de modèles**

Dès que vous avez des modèles dans la section modèles, vous verrez un filtre de modèles apparaître dans votre menu de filtre. Avec ce filtre, vous pouvez afficher/masquer tous les documents-modèles qui ont été créés.

### 4.2 **Colonnes**

**Icône** Vous pourrez distinguer un document-modèle d'un document ordinaire par le badge de modèle en bas à droite de l'icône du document-modèle.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/03-columns.png)

**Nom** Le nom du document

**Nom du modèle** Le nom du modèle. Si votre document IFC n'a pas été lié à un modèle, vous verrez un bouton créer un modèle ici.

**Nom de révision** Le nom de la dernière révision du modèle

**Visionneuse** Une colonne avec des boutons pour ouvrir chaque document-modèle individuel dans la visionneuse 3D. L'ouverture des documents-modèles dans la visionneuse 3D n'est possible que si le document a été lié à un modèle.

### 4.3 **Boutons d'action**

Téléchargez, supprimez ou chargez les vues 2D/3D des modèles sélectionnés dans la visionneuse respective en sélectionnant un ou plusieurs modèles.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-9e345595c719.png" width="310"/>    <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-959af958f499.png" width="310"/>

Cela signifie que vous pouvez supprimer plusieurs modèles à la fois au lieu de les supprimer un par un comme avant. Si vous supprimez un document qui est connecté à un modèle, vous devrez approuver un avertissement selon lequel le modèle connecté au document sera également supprimé.

> **Remarque :** Cela signifie que vous pouvez supprimer un modèle sans perdre les données. (Les documents supprimés peuvent être récupérés)

### 4.4 **Contrôler l'accès aux documents-modèles**

**Création de documents-modèles** Pour pouvoir télécharger de nouvelles révisions vers un modèle, vous devez maintenant disposer d'au moins un accès en écriture au modèle de document. Vous le faites en créant un modèle dans le menu d'action d'un document. Après cela, vous verrez le document en tant que modèle dans la section modèles. Le modèle-document dans la section modèles aura le même nom que le modèle de document, bien que chacun puisse être modifié ultérieurement tout en restant liés. De nouvelles révisions du modèle peuvent être ajoutées en tant que révisions du document et vice versa.

> **Remarque :** Cela signifie que vous pouvez créer des modèles à partir de plusieurs fichiers IFC en même temps au lieu de devoir les télécharger un par un

**Téléchargement de révisions vers des document-modèles** Vous devez disposer d'au moins un accès en écriture au document-modèle pour pouvoir télécharger de nouvelles révisions du modèle. Cela signifie que vous pouvez utiliser la fonction de téléchargement multiple pour télécharger des fichiers IFC vers plusieurs document-modèles à la fois

**Téléchargement de documents-modèles** Vous devez disposer d'au moins un accès en lecture au document-modèle pour pouvoir télécharger le modèle. Cela signifie que vous pouvez configurer l'accès pour permettre le téléchargement de modèles distincts au lieu de simplement tous les modèles ou aucun modèle.

### 4.5 **Découverte**

Les documents-modèles peuvent maintenant être trouvés dans la section documents comme n'importe quel autre document.

- Les documents-modèles peuvent être structurés dans des dossiers pour faciliter la navigation vers le bon ensemble de modèles.
- Des étiquettes peuvent être ajoutées aux documents-modèles pour trouver tous les documents-modèles qui appartiennent à un type.
- [Des champs personnalisés peuvent être ajoutés aux dossiers](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) où les documents sont téléchargés pour rechercher des valeurs de métadonnées liées à chaque document-modèle
- [Des champs personnalisés peuvent être ajoutés aux dossiers](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) où les documents sont téléchargés pour pouvoir ajouter des informations à chaque révision dans chaque modèle de document.

Consultez [ici](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) pour des suggestions sur la façon de structurer vos documents-modèles afin qu'ils soient faciles à trouver.

### 4.6 **Approuver les fichiers IFC partagés**

Les fichiers IFC peuvent maintenant être téléchargés en tant que révisions partagées afin qu'ils puissent suivre un processus d'approbation avant d'être publiés.

### 4.7 **Convention de nommage avec documents-modèles**

Les noms de la section documents incluent souvent des abréviations compressées pour garder le nom du document court tout en affichant certaines informations sur le sujet du document. Le nom du document-modèle peut donc être différent du nom du modèle-document pour le maintenir en conformité avec les autres documents de la section documents tout en conservant un nom facile à lire pour utilisation dans la visionneuse 3D de la section modèles. Le nom du document du document-modèle sera le nom reconnu lors du téléchargement de documents dans la section documents. Si le nom est similaire ou identique au document, une nouvelle révision sera automatiquement créée tout comme avec les autres documents.

Comme les documents-modèles se comportent de la même manière que les modèles ordinaires, il est maintenant possible d'utiliser la convention de nommage avec les documents-modèles pour s'assurer que les participants de votre projet donnent le bon nom au document lors du téléchargement.
