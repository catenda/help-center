# Menu Inspect

Le menu Inspect se trouve comme premier menu dans le [panneau d'informations](https://support.catenda.com/en/articles/8238584-information-panel).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/01-intro.png)

Sélectionnez un objet dans la [Visionneuse 3D](https://support.catenda.com/en/articles/8227211-3d-viewer) ou [panneau d'arborescence](https://intercom.help/bimsync-arena/en/articles/4670290-trees-panel) pour commencer. Les propriétés et les informations connexes sont affichées dans le menu Inspect. Après avoir sélectionné un objet, le panneau Inspect peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/02-intro.png)

La sélection de plus d'un objet affiche les Sujets, propriétés, quantités, matériaux ou Bibliothèques communs. Votre préférence concernant le menu que vous avez ouvert dans le menu Inspect sera mémorisée entre les projets et les sessions. Cela signifie que, peu importe si vous avez fermé le navigateur et l'avez réouvert ou le projet dans lequel vous vous trouvez, les mêmes menus seront toujours ouverts lorsque vous sélectionnez un objet.

## 1. **Identification**

Dans le menu d'identification, vous verrez toutes les données d'identification de l'objet sélectionné. L'identification ne s'affichera que pour un objet à la fois.

### 1.1 **Nom**

Le nom de l'objet

### 1.2 **Étiquette**

L'étiquette de l'objet

### 1.3 **Entité**

Le type d'entité de l'objet

### 1.4 **GUID**

Le GUID de l'objet. Ce code est unique pour chaque objet et peut être utilisé pour identifier l'objet tout au long des révisions du fichier IFC.

### 1.5 **Type**

Le type de l'objet. Chaque type a son propre GUID unique. Deux objets qui semblent avoir le même type peuvent en réalité avoir des types différents avec des GUID différents qui leur sont associés. Cliquez sur le type pour sélectionner tous les objets de ce type. Cela activera l'arborescence des types dans le [panneau d'arborescence](https://intercom.help/bimsync-arena/en/articles/4670290-trees-panel) où vous pouvez voir le type que vous avez sélectionné dans la liste des types pour ce modèle.

### 1.6 **Type prédéfini**

Le type prédéfini vous indique quel type de type vous traitez

### 1.7 **Contenant**

Si votre objet fait partie d'une hiérarchie, vous verrez le nœud parent de la hiérarchie ici. Cliquez sur le nœud parent pour sélectionner tous les objets contenus par ce nœud parent. Cela activera l'arborescence de contention dans le [panneau d'arborescence](https://intercom.help/bimsync-arena/en/articles/4670290-trees-panel) où vous pouvez voir le nœud de contention dans la hiérarchie des objets de votre modèle.

## 2. **Alignements**

Avec un alignement sélectionné dans le panneau d'arborescence, cliquez sur Afficher tous les segments pour ouvrir le tableau des alignements.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/03-alignments.png)

Voici à quoi pourrait ressembler le tableau des alignements :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/04-alignments.png)

Cliquez [ici](https://support.catenda.com/en/articles/11748020-tables-on-catenda) pour en savoir plus sur les tableaux sur Catenda

## 3. **Sujets**

Dans le menu Sujets, vous pourrez voir s'il y a des Sujets ouverts ou fermés qui sont [liés à](https://support.catenda.com/en/articles/8053299-right-menu-in-a-topic#h_758f17abbc) votre objet sélectionné ou vos objets sélectionnés. Le menu Sujets peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/05-topics.png)

### 3.1 **Nouveau sujet**

Cliquez sur le bouton + pour créer un nouveau sujet dans le tableau de sujets actuel. Si vous créez un sujet de cette manière, vos objets sélectionnés seront automatiquement liés au sujet, vous n'aurez donc pas besoin de les lier manuellement.

Cliquer sur ouvert, fermé, votre photo de profil ou la photo non assignée filtrera tous les tableaux de sujets en fonction de ce sur quoi vous avez cliqué.

### 3.2 **Sujets ouverts**

Le nombre de Sujets ouverts auquel votre objet sélectionné est lié

### 3.3 **Fermé**

Le nombre de Sujets fermés auquel votre objet sélectionné est lié

### 3.4 **Photo de profil**

Le nombre de Sujets ouverts liés à vos objets sélectionnés qui vous ont été assignés

### 3.5 **Non assigné**

Le nombre de Sujets ouverts liés à vos objets sélectionnés sans assignataire

## 4. **Propriétés, Quantités et Matériaux**

Vous pouvez trouver ici les propriétés que les objets sélectionnés ont en commun. Le menu des propriétés peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/06-properties-quantities-and-materials.png)

### 4.1 **Bouton Filtrer les valeurs vides**

Cliquez sur l'icône de Filtre pour masquer les propriétés qui n'ont aucune valeur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/07-filter-empty-values-button.png)

### 4.2 **Bouton Afficher la valeur du type**

Si votre objet sélectionné ou vos objets sélectionnés possèdent des propriétés héritées du type d'objet, vous verrez le bouton Afficher la valeur du type.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/08-display-type-value-button.png)

Activez ce bouton pour afficher les propriétés qui ont été héritées du type. Lorsque ce bouton est activé, vous verrez la valeur du type comme ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/09-display-type-value-button.png)

### 4.3 **Valeurs de propriétés**

Toutes les paires propriété-valeur communes des objets sélectionnés seront affichées. Si des valeurs ne sont présentes que dans l'un des objets, cette propriété ne s'affichera que si l'objet ayant cette valeur est sélectionné.

### 4.4 **Ensembles de propriétés**

Dans la liste des propriétés, vous pouvez trouver soit des propriétés séparées, soit des ensembles de propriétés (PSets) qui contiennent plusieurs propriétés chacune avec sa propre valeur. Comme vous le voyez dans l'image ci-dessus, les 4 premières propriétés étaient des propriétés séparées suivies de trois ensembles de propriétés avec des propriétés à l'intérieur.

**Développement/rétraction des ensembles de propriétés** Les ensembles de propriétés peuvent être développés ou rétractés en cliquant sur la flèche à côté de son nom. Tant que vos objets sélectionnés ont un ensemble de propriétés, votre préférence de développement/rétraction sera mémorisée, mais dès que vous sélectionnez un objet sans l'ensemble de propriétés, elle sera réinitialisée.

### 4.5 **Quantités**

Vous pouvez trouver ici les quantités que les objets sélectionnés ont en commun

### 4.6 **Matériaux**

Vous pouvez trouver ici les matériaux que les objets sélectionnés ont en commun

## 5. **Bibliothèques**

Si votre objet sélectionné ou vos objets sélectionnés sont [liés à des documents](https://support.catenda.com/en/articles/8302244-right-menu-in-a-document#h_d0769e55eb) ou des éléments de bibliothèque, vous pourrez les voir ici. Le menu Bibliothèques peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/10-libraries.png)

Vous pouvez cliquer sur le nombre à droite de ces éléments pour obtenir les documents/éléments de bibliothèque liés affichés dans une vue du panneau de contenu. Si vous avez, par exemple, un plan d'étage dans la section Documents lié à un objet mur, vous pourrez cliquer sur Documents ici pour trouver le document dans la section document.

## 6. **Modèle**

Si tous vos objets appartiennent à un modèle, vous pourrez voir ici les informations sur la révision du modèle. Cette information comprend :

**Image du modèle**

**Nom du modèle**

**Numéro de révision**

**Date et heure de publication de la révision**

**Éditeur de révision du modèle**

## 7. **Historique du propriétaire**

S'il y a des informations sur l'historique du propriétaire de la révision dans son fichier IFC, vous pourrez les voir affichées ici. Cette information peut inclure :

**La personne qui a initialement exporté le modèle**

**L'outil d'auteur qui a été utilisé** _Quand le modèle a été exporté_ Vous pourriez également être capable de voir si quelqu'un a modifié le modèle entre l'export depuis l'outil d'auteur et l'import dans Catenda Hub.
