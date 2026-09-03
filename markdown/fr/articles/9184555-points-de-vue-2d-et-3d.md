# Points de vue 2D et 3D

Les points de vue 2D et 3D peuvent être ajoutés en tant que [commentaire d'un sujet](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_f76b44d3ca). Les captures sont des moyens polyvalents de communiquer sur les informations 2D et 3D car elles contiennent non seulement des informations visuelles mais peuvent également être utilisées pour décrire un endroit et un moment dans un document ou un modèle. Les informations enregistrées dans les captures vous permettent de collaborer avec des informations 2D et 3D car vous pourrez lire votre capture dans n'importe lequel de vos services compatibles BCF et IFC.

Voici à quoi peut ressembler une capture 3D :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/01-intro.png)

La capture ci-dessous avait la configuration suivante au moment de la prise de la capture : la capture a été recréée avec les révisions originales. Les 7 documents de modèle connectés à la capture ont été chargés dans la visionneuse 3D. Les 5 objets sélectionnés des documents de modèle ont été sélectionnés, 2 documents non connectés aux modèles ont été chargés, dont un IFC et un nuage de points. Les captures 2D auront les mêmes boutons mais avec une image de la visionneuse 2D jointe.

## 1. **Création d'une capture**

Si vous avez un modèle chargé en 3D, vous pouvez cliquer sur le bouton plus à gauche du champ de commentaire du sujet pour joindre une capture 3D à votre commentaire. Si vous avez la visionneuse 2D ouverte, vous pouvez cliquer sur le bouton plus à gauche du champ de commentaire du sujet pour joindre une capture 2D à votre commentaire. Une capture est automatiquement créée si vous avez chargé quelque chose en 2D ou 3D et que vous créez un nouveau sujet. Cliquez [ici](https://support.catenda.com/en/articles/10345863-snapshots) pour en savoir plus sur les captures.

## 2. **Images de la visionneuse**

Les captures sont le meilleur moyen de créer des images de haute qualité ou des rendus à partir de la visionneuse Catenda Hub pour les raisons suivantes :

- Les images de capture peuvent être téléchargées depuis l'[aperçu pièce jointe](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8).
- Les images de capture peuvent avoir des résolutions plus élevées que simplement prendre une capture d'écran de la visionneuse.
- Les images de capture ont des arrière-plans transparents. Avec les captures 3D, l'image contient uniquement des pixels là où se trouvent des objets en 3D. Avec les captures 2D, l'image contient uniquement des pixels là où se trouvent des lignes en 2D.

### 2.1 **Taille de l'image**

La taille de l'image jointe dépend de la taille de la visionneuse et du pourcentage de zoom du navigateur. Le nombre de pixels dans une image de capture dépend de la taille de la visionneuse, du pourcentage de zoom du navigateur et de l'échelle d'affichage de votre système d'exploitation. La plus grande image que j'ai pu générer jusqu'à présent a été de 6417 pixels par 11113 pixels. Pour créer une capture aussi grande, j'avais les paramètres suivants :

- Affichage moniteur 4K.
- Panneau de contenu et panneau 3D visibles.
- Panneau de contenu aussi petit que possible.
- Navigateur en plein écran.
- Échelle du navigateur 10 %
- Échelle d'affichage dans Windows 100 %

ces paramètres sont très lourds pour le système et votre PC risque de ne pas pouvoir les gérer. Vous devrez peut-être ajuster ces paramètres pour les adapter à vos spécifications.

## 3. **Icônes de lecture**

Les captures contiennent des informations sur le moment où vous avez créé la capture.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/02-play-icons.png)

Si un objet a été masqué au moment de la création, l'objet avec cet ID sera masqué lors de la recréation de la capture. Si un objet a été isolé, l'objet avec cet ID sera affiché tandis que les objets non isolés seront masqués. Cela s'applique également à tous les objets avec de nouveaux ID qui pourraient être ajoutés aux versions plus récentes du modèle.

### 3.1 **Refaire la capture**

Les captures sont excellentes pour montrer aux gens ce que vous regardez car ils pourront recréer les mêmes vues non seulement dans Catenda Hub mais aussi dans leur environnement.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/03-recreate-snapshot.png)

Les captures peuvent être recréées en les lisant à la fois dans Catenda Hub et dans nos plugins. Dans Catenda Hub, la capture déplacera la caméra au bon endroit de notre visionneuse. Dans les plugins, la visionneuse du logiciel hôte s'affichera.

- En cliquant sur ce bouton, la capture sera recréée avec le même modèle et les dernières révisions chargées dans la visionneuse 3D.
- les documents de nuage de points ou IFC connectés seront chargés
- La caméra de la visionneuse 3D se déplacera à l'emplacement défini dans la capture.
- Les plans de découpe de la capture seront recréés
- Les objets qui ont été sélectionnés dans la capture seront sélectionnés
- Les couleurs qui ont été définies dans les sélections recevront leurs couleurs spécifiées

### 3.2 **Refaire la capture avec les révisions originales**

Cliquez sur ce bouton pour recréer la capture avec le modèle original.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/04-recreate-snapshot-with-original-revisions.png)

Les révisions du modèle qui étaient actives dans la visionneuse 3D au moment de la création de la capture sont chargées dans la visionneuse 3D lorsque ce bouton est cliqué.

## 4. **Icônes de contenu**

En bas à droite de la capture, vous trouverez des icônes contenant des informations sur le contenu de la capture.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/05-content-icons.png)

Si le panneau de contenu est réduit, vous pouvez trouver certaines de ces icônes de contenu dans le menu d'action :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/06-content-icons.png)

Le menu d'action se trouve vers le bas à droite de la capture où il n'y a pas assez d'espace pour afficher toutes les icônes de contenu.

### 4.1 **Sélecteur de modèle**

Si la visionneuse 3D est ouverte, le menu de chargement du modèle sera disponible

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/07-model-picker.png)

- Les modèles avec une coche dans ce menu seront chargés lorsque la capture sera lue.

    <div class="intercom-container"><img height="24" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-b248400a1359.png" style="height: auto;" width="30"/></div>

- Les modèles avec un plus devant eux seront ajoutés à l'ensemble des modèles avec coche après avoir appuyé sur Enregistrer.

    <div class="intercom-container"><img height="25" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-ca568d75479a.png" style="height: auto;" width="30"/></div>

- Les modèles avec un moins devant eux seront supprimés de l'ensemble des modèles avec coche après avoir appuyé sur Enregistrer.

    <div class="intercom-container"><img height="30" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-ff3494b6d9f8.png" style="height: auto;" width="30"/></div>

- En fonction des paramètres de visibilité des objets de la capture, les modèles ajoutés peuvent être complètement masqués. Même s'ils ne sont pas visibles, vous devriez voir qu'ils sont chargés lorsque le sujet est lu.
- Les modèles qui sont activés lors de l'ouverture de ce menu reflètent les modèles actuellement chargés dans la visionneuse 3D. Pour ajouter/supprimer facilement un ensemble de modèles, vous pouvez créer un signet, lire le signet, aller à la capture, cliquer sur son menu d'action et appuyer sur Enregistrer dans le menu de chargement du modèle.
- Si un modèle dans votre capture a le même GUID IFCPROJECT qu'un modèle dans la section des modèles, les modèles seront automatiquement liés.

Voici un article de BuildingSMART qui décrit comment cela se fait dans Revit [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/08-model-picker.png)

### 4.2 **Afficher les objets sélectionnés**

Sélectionnez les objets qui sont sélectionnés dans les captures, dans la visionneuse 3D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/09-show-selected-objects.png)

Affiche le nombre d'objets sélectionnés dans la capture

### 4.3 **Documents liés**

Cliquez ici pour charger les modèles de la capture en plus des modèles qui existent déjà dans la visionneuse.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/10-linked-documents.png)

Affiche le nombre de modèles chargés dans la capture.

### 4.4 **Définir la position de la caméra**

Déplacez la caméra à la position de la capture dans la visionneuse 3D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/11-set-camera-position.png)

Si vous avez déplacé votre vue 3D après la lecture de la capture, vous pouvez cliquer sur ce bouton pour revenir à la position de la capture.

## 5. **Aperçu de l'image**

Si vous survolez l'image d'une capture 2D ou 3D, une loupe apparaît. Cela peut ressembler à la capture ci-dessous :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/12-image-pop-out.png)

Après l'envoi de la capture, l'image qui y est connectée peut être [agrandie](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8) pour voir son contenu dans un format plus grand et la télécharger.

## 6. **Suppression d'une capture**

Il n'est pas possible de supprimer une capture jointe à un commentaire. Si vous souhaitez supprimer la capture du sujet, vous devrez supprimer l'intégralité du commentaire.
