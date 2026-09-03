# Mesure vers les plans glissants

Cet article décrit comment les outils de mesure de la Visionneuse 3D peuvent être utilisés non seulement pour mesurer sur des objets, mais aussi pour mesurer sur des éléments à partir de plans glissants comme les grilles ou les alignements. Voici à quoi cela peut ressembler après l'utilisation d'outils de mesure comme le ruban à mesurer, la mesure ponctuelle et la mesure laser pour mesurer entre les lignes d'annotation des plans glissants, les surfaces des plans glissants et les objets des modèles.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/01-intro.png)

## 1. **Commencer à mesurer vers les plans glissants**

Suivez ces étapes pour commencer à mesurer vers les plans glissants.

### 1.1 **Aperçu des plans glissants**

Les plans glissants qui peuvent être mesurés sont définis dans les modèles IFC mis à disposition dans le projet. Si des modèles avec des plans glissants sont disponibles, la [liste déroulante du plan glissant](https://support.catenda.com/en/articles/4670327-sliding-plane-dropdown) devient visible dans le coin supérieur droit de la [Visionneuse 3D](https://support.catenda.com/en/articles/8227211-3d-viewer) et peut ressembler à ceci :

![Plan de glissement déroulant dans la Visionneuse 3D](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/02-previewing-sliding-planes.png)

Préparez les plans glissants à mesurer en ouvrant la liste déroulante et en cliquant sur le bouton œil pour afficher un aperçu des lignes d'annotation d'une grille ou d'un alignement.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/03-previewing-sliding-planes.png)

### 1.2 **Paramètres recommandés pour la mesure**

Des mesures précises sont essentielles pour éviter les malentendus dans le projet. Il peut donc être judicieux de vérifier les paramètres avant de commencer à mesurer.

**Paramètres de la Visionneuse 3D** La liste déroulante des paramètres de la Visionneuse 3D se trouve avec l'icône d'engrenage vers le coin supérieur droit de la Visionneuse 3D :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/04-recommended-settings-for-measuring.png)

Comme les lignes des plans glissants incluent des lignes d'annotation fines et du texte qui sont souvent sensibles au rendu net dans un environnement 3D, les [paramètres de la Visionneuse 3D](https://support.catenda.com/en/articles/5784718-3d-viewer-settings#h_16d759320b) suivants sont recommandés pour rendre l'expérience de mesure aussi bonne que possible.

**Paramètres de la Visionneuse 3D - Qualité d'affichage** La qualité standard est recommandée car la qualité élevée modifie le rapport entre les pixels affichés par Catenda et les pixels visibles sur l'écran, ce qui peut avoir un effet négatif sur la précision des mesures.

**Paramètres de la Visionneuse 3D - Anticrénelage** Il est recommandé de modifier ce paramètre par rapport au paramètre FXAA par défaut en utilisant au moins 2x MSAA ou plus. Les lignes fines en 3D sont souvent difficiles à afficher, car plus une ligne fine est diagonale, plus ses bords deviennent dentés. Modifier le paramètre d'anticrénelage n'a pas d'effet sur la précision de la mesure, mais cela peut aider à mieux voir les lignes, car les bords dentés peuvent faire que les lignes fines deviennent tellement fines qu'elles deviennent difficiles à visualiser.

**Paramètres de la Visionneuse 3D - Élévation du sol** Surtout lorsque vous essayez de mesurer jusqu'à une ligne d'annotation sous terre, il peut être judicieux de choisir un environnement sans plan de sol ou de déplacer le plan de sol vers le bas, en dessous de l'élévation du plan glissant.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/05-recommended-settings-for-measuring.png)

**Recommandation d'application logicielle** Quel que soit l'[échelle de zoom](https://support.catenda.com/en/articles/13927149-application-software-recommendation?q=3d+v) configurée dans le navigateur utilisé pour mesurer dans la Visionneuse 3D, il est recommandé de ne pas modifier l'échelle de zoom du navigateur pendant la mesure, car cela peut contribuer à réduire la précision de la mesure. Réglez le navigateur sur l'échelle de zoom préférée et veillez à actualiser la page après chaque modification de l'échelle de zoom, même si la modification a été effectuée sur un autre onglet ou si elle a été ramenée à sa valeur initiale.

## 2. **Mesure vers les lignes d'annotation des plans glissants**

Chacun des outils de mesure peut être utilisé sur les lignes d'annotation des plans glissants.

### 2.1 **Comportement d'accrochage**

Lorsque vous survolez une ligne d'annotation avec le réticule activé, le réticule s'accrochera à la ligne d'annotation. Lorsque vous vous accrochez à l'extrémité d'une ligne d'annotation, le centre du réticule devient vert. Lorsque vous vous accrochez au milieu d'une ligne d'annotation, le centre du réticule devient rouge.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/inline-96b1b8f9c6c8.png" width="290"/> --- <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/inline-d30d54cd3f18.png" width="290"/>

### 2.2 **Mesure laser sur les lignes d'annotation**

Voici à quoi cela peut ressembler lors de l'utilisation de l'outil de mesure laser sur la ligne d'annotation d'une grille.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/06-laser-measure-on-annotation-lines.png)

**Mesure verticale et horizontale le long du segment de ligne d'annotation** Remarquez que le réticule semble plat dans la direction verticale lorsque vous survolez une ligne d'annotation. Lors de la mesure des lignes d'annotation, c'est le plan vertical le long de la ligne d'annotation qui est mesuré. La ligne verte est la ligne horizontale sur ce plan et la ligne rouge est la ligne verticale sur ce plan et suit le segment de ligne d'annotation

Tant pour la ligne de mesure verticale (rouge) que pour la ligne de mesure horizontalement le long du segment (vert), la ligne de mesure se comporte différemment selon les objets rencontrés. S'il y a des objets dans une direction le long de la ligne de mesure, une ligne mesurant la distance jusqu'à l'objet le plus proche s'affiche. S'il y a des objets dans les deux directions le long de la ligne de mesure, une ligne mesurant la distance entre ces objets s'affiche.

**Mesure horizontale selon un angle oblique au segment d'annotation** La ligne bleue est la ligne qui peut être observée selon un angle oblique au segment d'annotation qui est mesuré horizontalement. S'il y a des objets dans une direction le long de la ligne de mesure, une ligne mesurant la distance jusqu'à l'objet le plus proche s'affiche. S'il y a des objets dans les deux directions, des lignes mesurant les distances jusqu'à l'objet le plus proche dans chaque direction s'affichent, car cette ligne intersecte la ligne d'annotation elle-même et effectue une mesure jusqu'à celle-ci.

**Mesure manquante** Si des objets manquent dans l'une des directions de mesure, les coordonnées sont également affichées comme avec la mesure ponctuelle.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/07-laser-measure-on-annotation-lines.png)

### 2.3 **Ruban à mesurer sur les lignes d'annotation**

L'outil de ruban à mesurer peut être utilisé pour mesurer à la fois entre un objet et une ligne d'annotation ou entre deux lignes d'annotation. Par exemple, trouvez la distance entre deux lignes de grille en mesurant à partir d'un point sur une ligne de grille jusqu'à un point sur une autre ligne de grille.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/08-tape-measure-on-annotation-lines.png)

### 2.4 **Mesure ponctuelle sur les lignes d'annotation**

La mesure ponctuelle peut être utilisée sur les lignes d'annotation comme l'un des autres outils de mesure.

## 3. **Mesure vers les surfaces des plans glissants**

Activez la surface du plan glissant en appuyant sur le cercle blanc où se trouve le cercle de la ligne d'annotation. Plusieurs surfaces de plans glissants peuvent être ouvertes à la fois. Les mesures laser qui ont été effectuées sur des objets peuvent être étendues jusqu'à la ligne d'annotation. Utilisez ensuite la "Mesure laser" ou le "Ruban à mesurer" pour mesurer jusqu'aux surfaces des plans glissants qui sont activées.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/09-measuring-to-sliding-plane-surfaces.gif)
