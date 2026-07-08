# Manuel d'exportation IFC Archicad

Lorsque vous exportez un IFC, gardez à l'esprit ce qui est pertinent pour votre exportation IFC. Le fichier IFC peut être volumineux et difficile à utiliser s'il contient beaucoup d'informations. Par conséquent, il est important de ne pas exporter d'informations inutiles. Dans ce rapport, vous obtiendrez différents conseils pour filtrer votre exportation IFC dans Archicad.

## 1. Informations sur le projet

Avant d'exporter un IFC à partir de votre projet, assurez-vous que les informations du projet sont configurées. Les informations du projet se trouvent ici :

`Fichier -> Infos -> Informations sur le projet`

Voici à quoi peuvent ressembler les informations sur le projet :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/01-project-info.png)

Par défaut, les différents champs seront vides. Bien qu'ils soient vides, un identifiant unique est créé pour chaque projet, site et bâtiment qui figure dans la liste. Dans certaines situations, plusieurs fichiers IFC sont exportés à partir du même projet Archicad. Voici des exemples :

Fichiers IFC contenant des objets issus de différents domaines d'étude. Un modèle MEP avec des conduits, un modèle architectural avec des murs et un modèle structurel avec toutes les dalles.

Plusieurs bâtiments Parfois, plusieurs bâtiments sont modélisés ensemble dans le même fichier Archicad et un IFC séparé est exporté pour chacun d'eux.

Différents choix de conception. Lorsque différentes variantes d'un bâtiment sont modélisées dans le même fichier Archicad, chaque variante est généralement exportée vers son propre fichier IFC.

### 1.1 Configuration des informations sur le projet

Qu'il y ait des plans pour exporter plusieurs fichiers IFC ou non, il est souvent judicieux de saisir des valeurs dans les informations du projet pour ne pas avoir à les modifier ultérieurement. Les informations du projet sont importantes à remplir car elles ont un effet sur les GUID du fichier. Chaque type d'IFC exporté doit avoir ses propres paramètres de projet. Les paramètres du projet peuvent être importés et exportés en bas à droite. De cette manière, plusieurs profils peuvent être pris en charge pour les exportations à partir du fichier. Pour Catenda, il est important que les IFC dans différents modèles aient des informations différentes configurées, tandis que les IFC qui seront dans le même modèle ont les mêmes informations configurées.

## 2. Paramètres d'exportation IFC

Pour exporter l'ensemble du projet. Vous devez être en vue 3D. Assurez-vous d'utiliser le traducteur correct.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/02-ifc-export-settings.png)

Cliquez sur le bouton Options pour voir un résumé de vos paramètres d'exportation IFC. Sous le filtre du modèle, vous pouvez également choisir de filtrer davantage.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/03-ifc-export-settings.png)

La zone Traducteurs IFC vous permet d'afficher ou de modifier les paramètres du traducteur, ou de créer de nouveaux traducteurs.

Si vous souhaitez modifier votre exportation IFC, il est recommandé de dupliquer l'un des traducteurs prédéfinis pour ne pas déranger l'un des traducteurs par défaut. Dupliquer un traducteur ici :

Cliquez sur nouveau > Dupliquer > sélectionnez le traducteur à dupliquer.

Si vous souhaitez fusionner l'IFC, vous pouvez le faire sous la même bannière.

![image-2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/04-ifc-export-settings.png)

---

### 2.1 Différents paramètres dans l'exportation

1\. [Filtre du modèle](#model-filter) vous permet de filtrer ce que vous souhaitez exporter selon différents paramètres prédéfinis. 2\. [Mappage des types](#type-mapping) vous permet de choisir le type d'IFC utilisé pour exporter chaque élément. 3\. [Conversion de géométrie](#geometry-conversion) vous permet de choisir quel type de géométrie vous souhaitez exporter. 4\. [Mappage des propriétés](#property-mapping) vous permet de configurer des critères selon les types. 5\. [Conversion de données](#data-conversion) vous permet de choisir quel type de données vous souhaitez exporter du modèle. 6\. [Conversion d'unités](#unit-conversion) vous permet de choisir les unités de mesure que vous souhaitez utiliser pour exporter votre IFC.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/05-different-settings-in-the-export.png)

---

## 3. Filtre du modèle

### 3.1 Exportation de grilles dans l'IFC

Parfois, vous souhaiterez que les grilles soient également exportées pour pouvoir les voir dans Catenda Hub.

Accédez au filtre du modèle pour l'exportation IFC et assurez-vous que la case à cocher "Système de grille et éléments" est cochée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/06-exporting-grids-in-the-ifc.png)

---

## 4. Mappage des types

Lorsqu'un IFC est exporté, tous les éléments du modèle se voient attribuer un type IFC.

Si vous sélectionnez le traducteur IFC que vous souhaitez utiliser, vous pouvez accéder au mappage des types et cliquer sur Mapper les types IFC pour l'importation afin de gérer le type de mappage des types IFC que vous souhaitez sur votre IFC exporté.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/07-2-type-mapping.png)

Le mappage des types dispose principalement de deux options différentes pour trier vos types IFC.

### 4.1 Type d'élément

Chaque élément se voit automatiquement attribuer un type IFC de base. Vous pouvez voir le type IFC attribué à chaque élément dans le gestionnaire de projets et dans les paramètres d'élément.

### 4.2 Classification

Cette méthode permet un mappage des types IFC plus flexible et détaillé, selon des normes de classification spécifiées. Les éléments de zone et d'ouverture sont définis sur un type IFC fixe. IFCSpace et IFCOpeningElements.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/08-classification.png)

---

## 5. Conversion de géométrie

La conversion de géométrie pour l'exportation IFC vous permettra de convertir votre géométrie de différentes façons.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/09-3-geometry-conversion.png)

### 5.1 Conversions d'éléments Archicad

**Exporter la géométrie de tous les éléments du modèle comme :** _Paramétrique avec exceptions_ - par défaut _BREP_ - Géométrie précise - Si cette option est sélectionnée, les deux options suivantes seront également BREP

**Éléments dans les opérations d'éléments solides :** _Extrudé/revolté_ - par défaut _BREP_ - Géométrie précise

Éléments avec jonctions Certains éléments peuvent se croiser avec d'autres éléments qui peuvent découper des parties de l'extrusion. _Extrudé/revolté_ - Connecter les coins des éléments Cela ajoute des jonctions à vos éléments extrudés. Avec cette option, vous verrez que les éléments comme les murs ou les toits, en particulier les éléments inclinés, se connectent bien.

_Extrudé/revolté sans jonctions_ - par défaut - Cela accélère l'exportation. Si vous avez des éléments à 90 degrés comme des murs ou des toits, vous ne remarquerez probablement pas de différence avec cette option. Si vous avez des murs inclinés, vous remarquerez que dans le coin où les murs se connectent, au lieu de découper l'excès de l'extrusion droite, les murs passent juste l'un après l'autre et ne se connectent pas bien.

_BREP_ - Géométrie précise

Éléments paramétriques Les éléments Archicad peuvent être exportés en tant que géométrie paramétrique, souvent sous la forme de lignes de guidage qui sont extrudées sur une certaine distance. La géométrie paramétrique facilite la modification de l'objet après sa création. Bien que cette option conserve la capacité d'édition, la géométrie peut souvent être quelque peu imprécise car la définition est une approximation de la géométrie. Cette option est recommandée si vous avez l'intention de réimporter le fichier IFC dans Archicad ou dans un autre programme de modification pour apporter d'autres modifications.

BREP Exporter la géométrie en tant que surfaces BREP séparées. Au lieu de décrire les objets par leurs paramètres tels que longueur/largeur/hauteur avec les surfaces générées en résultat, chaque surface est décrite en tant que surface séparée avec une localisation en 3D. Les objets peuvent toujours contenir plusieurs surfaces, mais celles-ci seront des surfaces libres. Après l'exportation, les surfaces BREP doivent être modifiées individuellement car les paramètres ne s'appliquent plus à la surface. Avec l'option BREP, les surfaces exactes sont exportées sans possibilité de différence dans l'interprétation des paramètres entre les outils d'édition. Les surfaces sont colorées individuellement et auront la même couleur dans Catenda Hub qu'elles le font dans Archicad. Les couleurs de surface peuvent être configurées dans le menu suivant :

`Options -> Attributs d'élément -> Surfaces`

Il peut être bon de configurer tous les paramètres d'une surface car ils seront écrits dans l'IFC.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/10-conversions-of-archicad-elements.png)

Les surfaces dans la visionneuse 3D de Catenda ont un ombrage plat sans source lumineuse présente. Cela signifie que les valeurs telles que Ambiant, Atténuation, Brillance, Émission et Spéculaire ne sont pas interprétées lors de la visualisation de la surface dans la visionneuse 3D de Catenda. Les valeurs suivantes sont interprétées par Catenda lors de l'affichage de la surface dans la visionneuse 3D :

Couleur de la surface La couleur de la surface

Transmittance Quelle est la transparence de l'objet (Remplace le paramètre d'opacité translucide)

Diffus Quelle est l'intensité ou la clarté de la couleur de la surface

**Définir la position du modèle IFC par :** Cette option décide de l'emplacement du projet. Il est important de convenir d'un point de coordonnées commun à référencer dans le projet dès le début. Le modifier pourrait signifier que plusieurs consultants doivent déplacer leurs objets, ce qui n'est souvent pas possible vers la fin d'un projet.

Point d'arpentage et origine du projet - par défaut Avec cette option, la distance de (0,0,0) à votre modèle dans Archicad sera la distance de (0,0,0 + coordonnées de votre point d'arpentage) à votre modèle dans Catenda Hub + Si vous avez défini une localisation de projet, votre modèle se retrouvera à ces coordonnées dans Catenda Hub

Origine du projet uniquement Avec cette option, la distance de (0,0,0) à votre modèle dans Archicad sera la distance de (0,0,0) à votre modèle dans Catenda Hub.

Point d'arpentage uniquement Avec cette option, la distance du point d'arpentage dans Archicad à vos modèles sera la distance de (0,0,0) à votre modèle dans Catenda Hub

### 5.2 Options relatives au schéma IFC

**Mode de préservation des matériaux (IFC2x3 uniquement)** - Ne jamais exploser les éléments, la préservation n'est pas garantie Avec cette option, vous exporterez l'objet entier en tant qu'objet unique

- Exploser uniquement si nécessaire pour préserver les matériaux - Par défaut
  Avec cette option, vous n'exportez des objets séparés pour chaque matériau composite que si nécessaire

- Exploser tous les éléments en parties, préserver les matériaux
  Avec cette option, tous les objets sont exportés en tant qu'objets séparés pour chaque matériau

Si vous avez un matériau composite, cela signifie qu'un objet séparé sera exporté pour chaque matériau. Vous avez souvent un pare-vapeur de 1-5 mm qui se traduira par un objet très mince. Lorsque les objets sont aussi minces, la géométrie peut être imprécise. Les matériaux muraux problématiques peuvent ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/11-ifc-schema-related-options.png)

Cela peut rendre difficile pour les logiciels de découper des trous à travers la surface, car l'imprécision rend difficile de déterminer exactement où le trou est censé être. Si vous remarquez donc que vos ouvertures ne sont pas découpées, il peut être utile d'activer cette option. L'activation de cette option exporte le mur en tant qu'objet unique au lieu de nombreux objets composites minces.

### 5.3 Structures composites et profils complexes

**Diviser les éléments de construction complexes en parties** Ici, vous pouvez choisir pour quel type d'éléments vous souhaitez que l'élément composite soit divisé et pour lesquels vous ne souhaitez pas qu'il soit divisé. Si vous choisissez cette option, vous ne pourrez pas faire un choix pour le mode de préservation des matériaux.

---

## 6. Mappage des propriétés

Dans le mappage des propriétés (Fichier > IFC > Interopérabilité > Mappage des propriétés), vous pouvez choisir la version d'IFC que vous souhaitez exporter. vous avez la norme IFC2x3 et la norme IFC4. Vous pouvez également ajouter des psets pour exporter avec votre IFC. Si vous le faites, vous devez dupliquer le schéma IFC que vous avez choisi.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/12-4-property-mapping.png)

Après avoir créé un doublon de votre IFC standard, vous pouvez ajouter les propriétés que vous souhaitez à ce nouveau paramètre prédéfini en sélectionnant le schéma IFC et en cliquant sur _Mapper les propriétés IFC pour l'exportation_.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/13-4-property-mapping.png)

---

## 7. Conversion de données

Lors de la conversion de données, vous sélectionnez le type de données que vous souhaitez obtenir de votre exportation IFC en plus de la géométrie. cochez les cases de ce que vous souhaitez exporter.

Les paramètres d'élément lisent le paramètre d'élément Archicad et le convertissent en quantités IFC ou propriétés IFC. En fonction de leur type. En choisissant cette option, vous augmentez considérablement la taille du fichier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/14-5-data-conversion.png)

Quantités de base IFC Lit les paramètres de taille, de surface et de volume. Si vous ne cochez pas cette case, vous pourriez avoir des difficultés à importer votre IFC vers Catenda Hub.

## 8. Conversion d'unités

Définissez les unités de longueur, d'angle, de surface, de volume, de devise et de temps pour votre exportation.
