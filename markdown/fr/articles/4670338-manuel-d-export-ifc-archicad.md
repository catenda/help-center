# Manuel d'exportation IFC pour Archicad

Lors de l'exportation d'un IFC, gardez à l'esprit ce qui est pertinent pour votre exportation IFC. Le fichier IFC peut être volumineux et difficile à utiliser s'il contient beaucoup d'informations. Par conséquent, il est important de ne pas exporter d'informations inutiles. Dans ce rapport, vous trouverez différents conseils pour filtrer votre exportation IFC dans Archicad.

## 1. **1. Informations sur le projet**

Avant d'exporter un IFC de votre projet, assurez-vous que les informations du projet sont configurées. Les informations du projet se trouvent ici :

`Fichier -> Info -> Informations sur le projet`

Voici à quoi les informations du projet peuvent ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/01-1-project-info.png)

Par défaut, les différents champs seront vides. Bien qu'ils soient vides, un identifiant unique est créé pour chaque projet, site et bâtiment répertorié.

### 1.1 **1.1 Plusieurs IFC du même projet Archicad**

Dans certaines situations, plusieurs fichiers IFC sont exportés à partir du même projet Archicad. Voici des exemples :

**1.1.1 Fichiers IFC avec des objets provenant de différents domaines d'études** Un modèle MEP avec conduits, un modèle architectural avec des murs et un modèle structurel avec toutes les dalles.

**1.1.2 Bâtiments multiples** Parfois, plusieurs bâtiments sont modélisés ensemble dans le même fichier Archicad et un IFC séparé est exporté pour chacun d'eux.

**1.1.3 Choix de conception différents** Lorsque différentes variantes d'un bâtiment sont modélisées dans le même fichier Archicad, chaque variante est souvent exportée vers son propre fichier IFC.

### 1.2 **1.2 Configuration des informations du projet**

Qu'il soit prévu d'exporter plusieurs fichiers IFC ou non, il est souvent judicieux d'entrer des valeurs dans les informations du projet afin qu'elles n'aient pas à être modifiées ultérieurement. Les informations du projet sont importantes à remplir car elles ont un effet sur les GUID du fichier. Chaque type d'IFC exporté doit avoir ses propres paramètres de projet. Les paramètres du projet peuvent être importés et exportés en bas à droite. De cette manière, plusieurs profils peuvent être supportés pour les exportations du fichier. Pour Catenda, il est important que les IFC dans différents modèles aient des informations différentes configurées tandis que l'IFC qui sera dans le même modèle ait les mêmes informations configurées.

## 2. **2. Paramètres d'exportation IFC**

Pour exporter l'ensemble du projet, vous devez vous tenir en vue 3D. Assurez-vous d'utiliser le bon traducteur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/02-2-ifc-export-settings.png)

Cliquez sur le bouton des options pour voir un résumé de vos paramètres d'exportation IFC. Sous le filtre de modèle, vous pouvez également choisir de filtrer davantage.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/03-2-ifc-export-settings.png)

La boîte de traducteurs IFC vous permet de consulter ou de modifier les paramètres du traducteur, ou de créer de nouveaux traducteurs. Si vous souhaitez modifier votre exportation IFC, il est recommandé de dupliquer l'un des traducteurs prédéfinis afin de ne pas mélanger l'un des traducteurs par défaut. Dupliquez un traducteur ici : Cliquez sur nouveau > Dupliquer > sélectionnez le traducteur que vous souhaitez dupliquer. Si vous souhaitez fusionner l'IFC, vous pouvez le faire dans la même bannière.

![image-2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/04-2-ifc-export-settings.png)

## 3. **3. Différents paramètres de l'exportation**

3.1 [Filtre de modèle](#h_138e653078) vous permet de filtrer ce que vous souhaitez exporter par différents paramètres prédéfinis. 3.2 [Mappage de type](#h_a34c1332a3) vous permet de choisir quel type d'IFC chaque élément est exporté. 3.3 [Conversion de géométrie](#h_db084b5d6b) vous permet de choisir quel type de géométrie vous souhaitez exporter. 3.4 [Mappage des propriétés](#h_d48644eb35) vous permet de définir des critères basés sur les types. 3.5 [Conversion de données](#h_7f1df4ecb9) vous permet de choisir quel type de données vous souhaitez exporter du modèle. 3.6 [Conversion d'unités](#h_36caead1cd) vous permet de choisir les unités de mesure que vous souhaitez exporter dans votre IFC.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/05-3-different-settings-in-the-export.png)

## 4. **4. Filtre de modèle**

### 4.1 **Exporter des grilles dans l'IFC**

Parfois, vous souhaitez que les grilles soient également exportées pour pouvoir les voir dans Catenda Hub. Accédez au filtre de modèle pour l'exportation IFC et assurez-vous que la case à cocher « Système de grille et éléments » est cochée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/06-exporting-grids-in-the-ifc.png)

## 5. **5. Mappage de type**

Lorsqu'un IFC est exporté, tous les éléments du modèle se voient attribuer un type IFC. Si vous sélectionnez le traducteur IFC que vous souhaitez utiliser, vous pouvez alors accéder au mappage de type et cliquer sur Mapper les types IFC pour l'importation pour gérer le type de mappage de type que vous souhaitez sur votre IFC exporté.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/07-5-type-mapping.png)

Le mappage de type a principalement deux options différentes pour trier vos types IFC.

### 5.1 **5.1 Type d'élément**

Chaque élément se voit automatiquement attribuer un type IFC de base. Vous pouvez voir le type IFC attribué de chaque élément dans le gestionnaire de projet et dans les paramètres d'élément.

### 5.2 **5.2 Classification**

Cette méthode permet un mappage de type IFC plus flexible et détaillé, selon les normes de classification spécifiées. Les éléments de zone et d'ouverture sont définis sur un type IFC fixe. IFCSpace et IFCOpeningElements.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/08-5-2-classification.png)

## 6. **6. Conversion de géométrie**

La conversion de géométrie pour l'exportation IFC vous permet de convertir votre géométrie de différentes manières.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/09-6-geometry-conversion.png)

### 6.1 Conversions des éléments Archicad

**6.1.1 Exporter uniquement les géométries qui « Participent à la détection de collision »** Exporter uniquement les objets qui se croisent avec d'autres objets

**6.1.2 Exporter la géométrie des produits de type IFC** Produits de type inclus

**6.1.3 Exporter la géométrie brute des éléments** Géométrie brute incluse

**6.1.4 Exporter toute la géométrie des éléments du modèle comme :** _Paramétrique avec exceptions_ - par défaut

**Paramétrique (Extrudé/révolutionné)** _BREP_ - Géométrie précise - Si ceci est sélectionné, les deux options suivantes seront également BREP

**6.1.5 Éléments dans les opérations d'éléments solides :** _Extrudé/révolutionné_ - par défaut _BREP_ - Géométrie précise

**6.1.6 Éléments avec jonctions** Certains éléments peuvent se croiser avec d'autres éléments qui peuvent couper des parties de l'extrusion.

Extrudé/révolutionné - Connecter les coins des éléments Cela ajoute des jonctions à vos éléments extrudés. Avec cette option, vous verrez que les éléments comme les murs ou les toits, surtout les éléments inclinés, se connectent bien.

Extrudé/révolutionné sans jonctions - par défaut Cela rend l'exportation plus rapide Si vous avez des éléments à 90 degrés comme des murs ou des toits, vous ne remarquerez probablement pas de différence avec cette option. Si vous avez des murs inclinés, vous remarquerez qu'au coin où les murs se connectent, au lieu de couper l'excédent de l'extrusion droite, les murs passent juste droit l'un devant l'autre et ne se connectent pas bien.

BREP Géométrie précise

**6.1.7 Éléments paramétriques** Les éléments Archicad peuvent être exportés comme géométrie paramétrique, souvent sous la forme de lignes directrices qui sont extrudées à une distance. La géométrie paramétrique facilite l'édition de l'objet après sa création. Bien que cette option conserve l'éditabilité, la géométrie peut souvent être quelque peu imprécise car la définition est une approximation de la géométrie. Cette option est recommandée si vous avez l'intention d'importer l'IFC dans Archicad ou un autre programme d'édition pour effectuer d'autres modifications.

BREP Exporter la géométrie comme des surfaces BREP séparées. Au lieu de décrire les objets par leurs paramètres tels que la longueur/largeur/hauteur avec les surfaces générées en résultat, chaque surface est décrite comme une surface séparée avec un emplacement en 3D. Les objets peuvent toujours contenir plusieurs surfaces, mais celles-ci seront des surfaces libres. Après l'exportation, les surfaces BREP doivent être éditées individuellement car les paramètres ne sont plus appliqués à la surface. Avec l'option BREP, les surfaces exactes sont exportées sans laisser de place à une différence d'interprétation des paramètres entre les outils de création. Les surfaces sont colorées individuellement et auront la même couleur dans Catenda Hub qu'elles le font dans Archicad. Les couleurs de surface peuvent être configurées dans le menu suivant :

`Options -> Attributs d'éléments -> Surfaces`

Il peut être bon de configurer tous les paramètres d'une surface car ils seront écrits dans l'IFC.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/10-6-1-conversions-of-archicad-elements.png)

Les surfaces dans la visionneuse 3D de Catenda ont un ombrage plat sans source lumineuse présente. Cela signifie que les valeurs telles que Ambient, Attenuation, Shinyness, Emission et Specular ne sont pas interprétées lorsque la surface est visualisée dans la visionneuse 3D de Catenda. Les valeurs suivantes sont interprétées par Catenda lors de l'affichage de la surface dans la visionneuse 3D :

Couleur de surface La couleur de la surface

Transmission Quelle quantité vous pouvez voir à travers l'objet (Remplace le paramètre d'opacité translucide)

Diffus Quelle est l'obscurité ou la clarté de la couleur de surface

**6.1.8 Définir la position du modèle IFC par :** Cette option décide de l'emplacement du projet. Il est important de s'entendre sur un point de coordonnées commun auquel faire référence dans le projet dès le début, car le modifier pourrait signifier que plusieurs consultants doivent déplacer leurs objets, ce qui n'est souvent pas réalisable vers la fin d'un projet.

Point d'arpentage et origine du projet - par défaut Avec cette option, la distance de (0,0,0) à votre modèle dans Archicad sera la distance de (0,0,0 + coordonnées de votre point d'arpentage) à votre modèle dans Catenda Hub + le Si vous avez défini un emplacement de projet, votre modèle se retrouvera à ces coordonnées dans Catenda Hub

Origine du projet uniquement Avec cette option, la distance de (0,0,0) à votre modèle dans Archicad sera la distance de (0,0,0) à votre modèle dans Catenda Hub.

Point d'arpentage uniquement Avec cette option, la distance du point d'arpentage dans Archicad à vos modèles sera la distance de (0,0,0) à votre modèle dans Catenda Hub

## 7. **7. Éléments hiérarchiques Archicad**

Exporter les objets dans une hiérarchie plate ou comme sous-éléments imbriqués.

### 7.1 **7.1 Mur rideau**

Convertir en élément unique Conserver la hiérarchie - Par défaut

### 7.2 **7.2 Escalier**

Convertir en élément unique Conserver la hiérarchie - Par défaut

### 7.3 **7.3 Garde-fou**

Convertir en élément unique - Par défaut Conserver la hiérarchie

## 8. **8. Options liées au schéma IFC**

### 8.1 **8.1 Mode de préservation des matériaux (IFC2x3 uniquement)**

**8.1.1 Ne jamais éclater les éléments, la préservation n'est pas garantie** Avec cette option, vous exporterez l'objet entier comme un objet

**8.1.2 Éclater uniquement si nécessaire pour préserver les matériaux - Par défaut** Avec cette option, vous n'exportez des objets séparés pour chaque matériau composite que si nécessaire

**8.1.3 Éclater tous les éléments en parties, préserver les matériaux** Avec cette option, tous les objets sont exportés comme des objets séparés pour chaque matériau. Si vous avez un matériau de mur composite, cela signifie qu'un objet séparé sera exporté pour chaque matériau. Vous avez souvent une barrière de vapeur de 1 à 5 mm, ce qui entraînera un objet très fin. Lorsque les objets sont aussi fins, la géométrie peut être imprécise. Les matériaux de mur problématiques peuvent ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/11-8-1-material-preservation-mode-ifc2x3-only.png)

Cela peut rendre difficile pour les logiciels de découper des trous à travers la surface car l'imprécision rend difficile de déterminer exactement où le trou est censé être. Si vous remarquez donc que vos ouvertures ne sont pas découpées, il peut être utile d'activer cette option. L'activation de cette option exportera le mur comme un seul objet au lieu de nombreux objets composites minces.

## 9. **9. Structures composites et profils complexes**

**9.1 Diviser les éléments de construction complexes en parties** Ici, vous pouvez choisir pour quel type d'éléments vous souhaitez que l'élément composite soit divisé et pour lesquels vous ne le souhaitez pas. Si vous choisissez cette option, vous ne pourrez pas faire de choix pour le mode de préservation des matériaux.

## 10. **10. Mappage des propriétés**

Dans le mappage des propriétés (Fichier > IFC > Interopérabilité > Mappage des propriétés), vous pouvez choisir quel type de version d'IFC vous souhaitez exporter. vous avez la norme IFC2x3 et la norme IFC4. Vous pouvez également ajouter des ensembles de propriétés à exporter avec votre IFC. Si vous le faites, vous devez créer un doublon du schéma IFC que vous choisissez.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/12-10-property-mapping.png)

Une fois que vous avez créé un doublon de votre IFC standard, vous pouvez ajouter les propriétés que vous souhaitez à ce nouveau préréglage en sélectionnant le schéma IFC et en cliquant sur _Mapper les propriétés IFC pour l'exportation_.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/13-10-property-mapping.png)

## 11. **11. Conversion de données**

Sous conversion de données, vous sélectionnez quel type de données en plus de la géométrie vous souhaitez obtenir de votre exportation IFC. cochez les cases de ce que vous souhaitez exporter. Les paramètres d'élément lisent le paramètre d'élément Archicad et le convertissent en quantités IFC ou propriétés IFC. Selon leur type. En choisissant cette option, vous augmentez considérablement la taille du fichier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/14-11-data-conversion.png)

Les quantités de base IFC lisent les paramètres de taille, de zone et de volume. Si vous ne cochez pas cette case, vous risquez d'avoir des problèmes lors de l'importation de votre IFC dans Catenda Hub.

## 12. **12. Conversion d'unités**

Définissez les unités de longueur, d'angle, de zone, de volume, de devise et de temps pour votre exportation.
