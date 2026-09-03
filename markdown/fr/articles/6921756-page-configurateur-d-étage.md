# Page Configurateur d'étage

> Comment avoir un PDF en tant que superposition dans votre vue 2D

En configurant les étages dans un projet, des vues préparées dans la [Visionneuse 2D](https://support.catenda.com/en/articles/4854537-2d-viewer) peuvent être créées pour les Membres. La page du configurateur d'étage se trouve comme sous-page de la [page des modèles](https://support.catenda.com/en/articles/4670286-models-page). Les noms Storey et Building utilisés ici proviennent de la norme IFC. Bien que les termes Storey et Building soient souvent davantage utilisés dans les infrastructures sociales, cet outil est tout aussi utile, sinon plus utile, pour les projets d'infrastructures physiques ou numériques. _Accès requis :_ Administrateur de projet

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/01-intro.png)

Dans un projet, les Membres peuvent composer des étages en activant et en désactivant les vues 2D avec la géométrie générée à partir de différents modèles disponibles dans le projet. Configurez un étage pour créer un étage configuré avec des vues 2D générées à partir d'un ensemble de modèles disponibles aux Membres du projet. Superposez un document PDF dans un étage pour afficher les traits qui pourraient ne pas être visibles dans la géométrie générée à partir du modèle.

Voici à quoi peut ressembler la page du configurateur d'étage dans un nouveau projet :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/02-intro.png)

Voici à quoi peut ressembler un étage configuré avec un dessin superposé

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/03-intro.png)

## 1. **Actions**

Le menu d'action sur la page du configurateur d'étage se trouve en ouvrant les trois points à droite du bouton plus vert en haut à droite.

![Ajouter un nouveau bâtiment](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/04-actions.png)

### 1.1 **Ajouter un nouveau bâtiment**

Cliquez [ici](https://support.catenda.com/en/articles/12291366-storey-configurator-actions) pour en savoir plus sur l'ajout d'un nouveau bâtiment.

### 1.2 **PDF**

Pour compléter les étapes de cet article, vous aurez besoin d'un Plan PDF pour chaque étage où vous souhaitez un pdf comme superposition.

> **Remarque :** Chaque étage doit être dans un PDF séparé. Un étage peut avoir plusieurs PDF

## 2. **Configuration**

Réglez votre vue pour pouvoir voir votre modèle 2D et tous vos modèles.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/05-setup.png)

## 3. **Configuration des étages**

C'est ici que vous alignez votre Plan PDF avec votre vue 2D, cela doit être fait une fois pour chaque étage.

Par défaut, vous aurez un Bâtiment dans votre Vue d'ensemble. Cela contient également les Niveaux de l'IFC importé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/06-storey-configuration.png)

La définition d'un Nom pour le Bâtiment est importante car il s'affichera plus tard, donc choisissez quelque chose d'explicite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/07-storey-configuration.png)

Chaque Niveau IFC est représenté dans un Étage. Ici, vous pouvez définir le Nom et l'Élévation.

> **Remarque :** La modification de l'Élévation modifiera la représentation de votre vue 2D.

Dans l'Étage, vous pouvez définir la Superposition, cliquez sur « Afficher les options supplémentaires »

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/08-storey-configuration.png)

Ici, vous voyez la fonction « Dessins attachés à l'étage ». Cliquez sur Ajouter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/09-storey-configuration.png)

Une boîte de dialogue s'ouvrira et vous demandera le PDF téléchargé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/10-storey-configuration.png)

Lorsque vous avez sélectionné le PDF souhaité, cliquez sur Ajouter ce Document. Cela vous amènera à la boîte de dialogue d'alignement.

## 4. **Dialogue d'alignement**

C'est ici que vous définirez la superposition et la positionnerez.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/11-alignment-dialogue.png)

Votre bâtiment devrait être sélectionné maintenant. Tout ce qui reste à faire est de sélectionner l'étage avec lequel vous souhaitez aligner votre dessin.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/12-alignment-dialogue.png)

Maintenant, vous devriez voir votre PDF sélectionné et l'Étage sélectionné sur votre écran.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/13-alignment-dialogue.png)

Avec les Marqueurs A et B, vous définissez la position de la superposition. Les Points que vous sélectionnez doivent correspondre. Il est préférable de choisir l'intersection de deux grilles par exemple.

Utilisez le marqueur par glisser-déposer pour les placer. Vous pouvez également zoomer en faisant défiler dans le dessin.

Après les avoir placés, cliquez sur « Suivant : Confirmer le résultat »

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/14-alignment-dialogue.png)

### 4.1 **Dialogue d'approbation**

Après avoir confirmé la position des marqueurs, la boîte de dialogue d'approbation s'ouvre. Ici, vous pouvez examiner la superposition pour voir si cela fonctionne pour vous.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/15-approve-dialogue.png)

Ici, une modification peut toujours être apportée en cliquant sur Précédent : Placer les points du modèle et du dessin. Une fois que vous êtes satisfait de votre alignement, vous confirmez en cliquant sur Approuver.

Cela vous ramènera au Configurateur d'étage et maintenant vous pouvez configurer l'étage suivant. Le placement des dessins peut également être modifié dans cette boîte de dialogue.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/16-approve-dialogue.png)

**Important :** Ici, vous devez cliquer sur Enregistrer la configuration.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/17-approve-dialogue.png)

## 5. **Comment l'utiliser**

Maintenant que tout est configuré, vous pouvez l'utiliser dans votre travail quotidien. Une fois votre configuration de bâtiment terminée, vous pouvez actualiser la page. Si vous êtes dans votre vue Modèle et que vous ouvrez la Vue 2D, il y a une Option pour sélectionner le Bâtiment.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/18-how-to-use-it.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/19-how-to-use-it.png)

Sélectionnez le Bâtiment fraîchement renommé

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/20-how-to-use-it.png)

Et votre superposition PDF sera visible.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/21-how-to-use-it.png)

Le configurateur d'étage affichera toujours la dernière révision du ou des dessins alignés
