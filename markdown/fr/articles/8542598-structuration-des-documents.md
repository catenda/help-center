# Structuration des documents

Il existe plusieurs façons de structurer et de nommer vos dossiers et documents. Selon le type de projet, différentes structures et conventions de nommage peuvent vous convenir mieux que d'autres. Cet article contient des conseils utiles pour décider comment configurer votre environnement de données.

## 1. **Noms d'éléments**

Plusieurs facteurs peuvent influencer la façon dont les éléments d'une structure sont nommés. La découvrabilité et la longueur du chemin sont souvent des facteurs importants.

### 1.1 **Propriété**

La personne qui établit le nom est souvent familiarisée avec le contenu de l'élément nommé.

**Documents personnels** Lors du nommage d'éléments pour usage personnel, une façon personnelle de nommer l'élément est souvent la meilleure, car la personne qui nomme le document peut facilement retrouver l'élément en le recherchant ultérieurement. Même la personne qui nomme l'élément peut avoir du mal à retrouver ses propres informations par la suite.

**Documents de collaboration** Lors du nommage d'éléments pour la collaboration, plusieurs personnes travailleront avec les différents éléments. Les noms des dossiers sont donc souvent prédéfinis dans les projets afin qu'ils soient faciles à reconnaître dans les différents projets d'un certain type appartenant à la même organisation.

**Exigences minimales** Les exigences minimales pour le nommage des Documents sont souvent convenues. Puisque différents mots peuvent avoir des significations différentes pour différentes personnes, il est souvent important de discuter avec l'équipe des noms donnés aux éléments afin que chacun soit conscient de la façon de nommer les éléments et de ce qu'il faut rechercher.

### 1.2 **Schémas de nommage**

Suivre les bonnes pratiques de nommage des Documents est toujours utile, mais chacun a ses propres préférences. Une stratégie de nommage qui vous convient ne convient pas toujours à d'autres.

**Schémas de nommage à l'échelle de l'équipe** Au sein d'une équipe, les contributeurs à une structure de fichiers s'accordent souvent sur un schéma de nommage. Il peut s'agir d'une suggestion verbale, comme indiquer aux gens de mettre la date dans le nom, ou elle peut être appliquée en créant une [convention de nommage](https://support.catenda.com/en/articles/7832559-naming-conventions-page) selon laquelle les gens doivent nommer leurs fichiers pour pouvoir les télécharger du tout.

**Schémas de nommage à l'échelle du projet** Dans un environnement de données commun, plusieurs Équipes se réunissent souvent. Les équipes pourraient ne pas encore avoir de règle de nommage en place ou être disposées à changer la leur, mais si elles ont déjà nommé leurs Documents d'une certaine façon pendant très longtemps, il peut être difficile de les convaincre de faire autrement. Dans ce cas, une bonne solution est de permettre aux gens de télécharger des fichiers avec le nom qu'ils préfèrent, à condition qu'ils changent le nom du Document qui contient le fichier à la convention convenue par le projet. De cette façon, le Membre de l'équipe pourra retrouver son Document par le [nom original du fichier](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page) tandis qu'un Membre du projet pourra le retrouver par son [nom du Document](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page).

### 1.3 **Longueur du nom**

Être descriptif et écrire des mots complets peut vous aider à lire le mot et à comprendre d'un coup d'œil le contenu du Document. Cela ne signifie pas que le nom du Document doit être une phrase complète. Les noms de Documents qui sont trop longs à lire peuvent ressembler à un mur de texte et sont rapidement survolés. Il est donc recommandé de garder les noms à 1 à 5 mots.

**Limitations externes** Au sein de Catenda, les structures de dossiers de toute longueur de chemin peuvent être importées et exportées. D'autres logiciels avec lesquels ces informations sont échangées peuvent avoir des limitations sur le nombre total de caractères des dossiers parents et du nom du Document qui forment le chemin vers un Document dans la structure. Les fichiers Zip sont souvent utilisés pour échanger des structures de dossiers. Sous Windows, la limite de chemin pour les fichiers zip est de 260 caractères par exemple. Dans OneDrive et SharePoint, cette limite est augmentée, mais reste limitée à 400 unités Unicode.

### 1.4 **Contrôle de version**

Une situation typique dans laquelle les gens finissent par se retrouver est d'appeler leur Document quelque chose comme:

**Présentation\_Final** Puis, quand ils ont besoin de faire un changement, cela devient: _Présentation\_Final\_Final, Final\_Final\_Pour de vrai, Final\_LastOneIPromise._ À ce stade, vous abandonnez et l'appelez simplement le suivant: _Présentation\_Soumis_ Cette situation peut être évitée en décidant d'une convention de versioning dès le début. Vous pouvez commencer votre fichier avec _Présentation\_v1_, _Présentation\_v2_, etc... Cela s'assurera que différentes versions du même fichier dans un ordre logique. Bien qu'il existe un bon système de révision sur Catenda, il peut toujours être judicieux d'ajouter un numéro de version. Parfois, votre décompte de révision locale diffère de celui qui a été téléchargé. Disons que vous avez téléchargé v3 de la présentation mais que la suivante que vous avez téléchargée était v5. La révision sur Catenda s'incrémentera d'une unité tandis que votre révision locale s'est incrémentée de 2. De cette façon, vous pouvez suivre la version qui est la bonne.

### 1.5 **Séparation des informations**

Historiquement, les systèmes ont eu du mal avec les espaces dans les noms de Documents. Bien que de nombreux systèmes puissent désormais gérer les espaces dans les noms de Documents, il peut y avoir des raisons de supprimer les espaces des noms de Documents. Vous voudrez peut-être pouvoir rechercher deux mots ensemble qui ne sont pas deux mots distincts. Vous pourriez aussi espérer compresser le nombre de caractères dans un nom en supprimant les espaces. Lorsque vous prenez un nom de fichier normal comme:

**this is a normal file name that is very long with many words.png** et vous supprimez les espaces, cela devient un gâchis illisible et brouillé car vous avez besoin de quelques repères visuels pour savoir où se trouvent les limites des mots:

**thisisanormalfilenamethatisverylongwithmanywords.png** Si la compression est votre objectif, vous ne voudrez pas introduire un autre caractère pour séparer chaque mot car vous reviendriez à la même longueur qu'avant. Au lieu de cela, ce que vous pouvez faire est de mettre en majuscules chaque mot.

**ThisIsANormalFileNameThatIsVeryLongWithManyWords.png** Bien que cela soit déjà légèrement mieux, il est toujours assez difficile à lire avec des noms plus longs. Si l'objectif est de minimiser l'espace, vous pouvez essayer de regrouper les mots qui vont ensemble:

**ThisIs\_ANormalFileName\_ThatIs\_VeryLong\_WithManyWords.png** Maintenant, nous commençons à entrer dans le territoire d'un bon nom de fichier court et lisible. Même lorsque la longueur du fichier n'a pas de sens, penser à compresser des mots comme ceci a du sens car il est plus facile de comprendre les mots groupés en un coup d'œil. Si vous ne vous souciez pas de la longueur de votre nom de fichier, ce que vous pouvez faire pour que ce soit encore mieux est d'introduire un séparateur secondaire. Voyez ici comment les mots groupés sont séparés d'une manière tandis que les mots au sein de chaque groupe sont séparés d'une autre manière.

**This-is\_A-normal-File-name\_That-is\_Very-long\_With-many-words.png** Notez qu'en séparant chaque mot, il était possible d'ajouter mettre en majuscules chaque premier mot mais ensuite avoir des minuscules pour les suivants.

### 1.6 **Compression des informations**

Dans les cas où il y a de nombreux Documents différents qui sont tous légèrement différents, il n'a pas de sens de répéter les mêmes 4 mots encore et encore juste pour ajouter une variation sur le 5e mot. Dans ce cas, vous voudrez peut-être utiliser une abréviation pour chaque mot. Exemple: _Architecture_ peut se transformer en _ARC_, Le premier étage peut se transformer en 1er. Le fait que vous puissiez avoir plus d'informations dans moins d'espace est à la fois une force et une faiblesse. Bien qu'il soit facile d'être 100% correct avec les informations du nom de fichier de cette façon, ce n'est pas toujours la meilleure façon de nommer vos fichiers. Lorsque vous ajoutez des abréviations, vous commencez rapidement à remarquer que les noms de vos fichiers deviennent un gâchis brouillé et illisible. Prenez par exemple: _20110101\_ARC\_BLDG1\_BLCK2\_FLR4\_Q4\_Wa3\_Win4\_S\_C\_v4_ Bien qu'il puisse avoir du sens pour l'auteur du fichier que ce soit un fichier de: 01 janvier 2011 sur la quatrième version d'un appui en béton dans la fenêtre 4 sur le mur 3 au 4e étage du bloc 2 dans le bâtiment 1 par l'architecte. Je suis à peu près sûr que personne d'autre dans le projet ne prendra le temps de le lire. Surtout pas quand ce que le chercheur cherchait vraiment était:

**20110101\_ARC\_BLDG1\_BLCK1\_FLR4\_Q4\_Wa2\_Win3\_S\_C\_V4** Qui est une fenêtre complètement différente! Si cela en vient à ce point, il est préférable de diviser vos fichiers dans des dossiers.

### 1.7 **Ordre de tri**

La section des Documents est automatiquement triée par nom. Il peut donc être judicieux d'ajouter des caractères au début du Document afin que le Document le plus pertinent apparaisse en premier.

**Ordre chronologique** Afin d'obtenir un aperçu historique sur Catenda Hub, vous pouvez toujours trier par publié ou créé. Par défaut, les documents sont triés par nom. Lorsqu'un membre ouvre un dossier pour la première fois, le document le plus récent peut donc ne pas être en haut. Pour résoudre ce problème, vous pouvez ajouter la date du document à l'avant du document : _20110101_ serait le premier janvier 2011. Cela peut également être utile si vous avez des documents qui ont été créés il y a longtemps, puis importés à Catenda Hub. Bien que ce nom puisse être modifié, il peut être une information utile lorsque vous recherchez un document. De cette façon, vous pouvez également trier la colonne de nom par date.

**Ordre alphanumérique** Pour savoir quels caractères viennent avant d'autres caractères, veuillez vous référer à l'[ordre de tri des listes](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) sur Catenda. Afin d'obtenir vos documents dans l'ordre d'importance, vous pouvez toujours trier par étiquettes ou par nombre de révisions. Par défaut, les documents sont triés par nom. Lorsqu'un membre ouvre un dossier pour la première fois, le document le plus important peut donc ne pas être en haut. Pour résoudre ce problème, vous pouvez ajouter un caractère au début du nom qui le fait venir en premier. Par exemple, vous pouvez appeler vos fichiers : _1.0 Le plus important. 1.1 Moins important, 1.2 etc..._ Ensuite, vous découvrez peut-être que certains enfreignent votre règle en téléchargeant accidentellement un document avec un 0 devant, ce qui finit par venir en premier. Ce que vous pourriez alors faire est d'ajouter un \_ avant le nom pour vous assurer qu'il vient avant n'importe quel élément. Cette bataille de qui vient en premier peut sembler sans fin. Il peut donc être utile de regarder l'[ordre de tri des listes](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) pour voir quels caractères viennent avant d'autres pour voir ce qui a du sens d'utiliser dans votre cas.

## 2. **Sous-dossiers**

Il peut être difficile de trouver des informations s'il y a beaucoup d'informations dans une liste et que vous devez faire défiler loin pour trouver les informations que vous recherchez.

### 2.1 **Quand déplacer des Documents dans des dossiers**

S'il y a trop de Documents ou de dossiers dans un dossier, ils peuvent devenir difficiles à trouver car vous devrez faire défiler loin vers le bas de la liste pour trouver le Document que vous recherchez. À ce stade, il est souvent judicieux d'ajouter un sous-dossier dans cette liste et de diviser les Documents par leur propriété la plus importante.

Cela peut être une gamme de propriétés comme:

**Type de Document (Dessin, image, feuille de calcul)**

**Sujet associé (Murs et fenêtres)**

**Domaine d'étude (ARC, MEP, STR)**

**Partie qui l'a téléchargé (Groupe 1, Groupe 2, Groupe 3)**

**Date de téléchargement (20110101, 20231225)**

**Maturité (Brouillon, Soumis, Approuvé, Refusé)**

Les raisons qui peuvent influencer la décision de la façon de diviser vos Documents peuvent être:

**Découvrabilité**

**Contrôle d'accès**

### 2.2 **Quand déplacer des Documents hors des dossiers**

Après avoir travaillé avec une structure de Documents pendant un certain temps, vous remarquerez que vous commencez à créer de nombreux sous-dossiers. S'il faut beaucoup de clics pour descendre au sous-dossier, vous n'avez pas résolu le problème que vous essayiez de résoudre en créant des sous-dossiers en premier lieu car les informations sont toujours difficiles à trouver. Il est recommandé de ne pas descendre plus de 3 niveaux lors de la création de sous-dossiers. C'est parce que la plupart des gens pourraient se souvenir des deux derniers dossiers dans lesquels ils se trouvaient, mais plus vous allez profondément, plus vous commencez à oublier d'où vous venez. Afin de prévenir cela, vous pouvez déplacer vos sous-dossiers d'un niveau vers le haut.

**Voici un exemple d'un dossier qui a 4 niveaux de profondeur:** 01\_Models-and-drawings 0101\_Models 010101\_ARC 01010101\_Window 01010102\_Wall 010102\_MEP 01010201\_Ducts 01010202\_Vents 010103\_STR 0102\_Drawings

**Ce dossier peut être simplifié pour devenir:** 0101\_Models\_ARC 010101\_Window 010102\_Wall 0102\_Models\_MEP 010201\_Ducts 010202\_Vents 0103\_Models\_\_STR 0201\_Drawings

**Ou peut-être encore plus simple:** 010101\_Models\_ARC\_Window 010102\_Models\_ARC\_Wall 010201\_Models\_MEP\_Ducts 010202\_Models\_MEP\_Vents 010301\_Models\_\_STR 020101\_Drawings

Comme vous pouvez le voir, l'ajout de plusieurs dossiers similaires au même niveau peut aider à réduire le nombre de clics qu'il faut pour descendre au dossier contenant les Documents que vous recherchez. Une autre chose que vous pourriez remarquer est que plus vous simplifiez la structure des dossiers, plus les noms de fichiers deviennent longs. Lorsque les noms de fichiers deviennent trop longs, ils deviennent difficiles à lire. Il est donc important de maintenir un équilibre entre la [longueur du nom de fichier](#h_7549bd95d9) et la [profondeur du dossier](#h_e27bb794b2).

## 3. **Arborescence des dossiers**

### 3.1 **Type de Document**

Dans cette structure de Documents, vous structurez vos fichiers selon le type de Document qu'il s'agit. Tous les plans vont dans le dossier des plans, tous les résumés de réunion vont dans le dossier des résumés, etc. Cette structure de fichiers est plus facile à utiliser pour le client car les fichiers livrés par les consultants sont tous rassemblés à un seul endroit. Cette structure de fichiers est plus difficile à utiliser pour les consultants car ils ont de nombreux endroits différents où ils livrent leurs fichiers.

**Exemple de structure de fichiers** Un exemple de ce type de structure de Documents peut être:

0101\_Information 010101\_Admin 010102\_Contrats 0201\_Images\_Présentations YYMMDD\_Presentation-title.ppt 0202\_Images\_Visites-de-site YYMMDD\_Site-visit-title.jpg 0301\_2D 03010101\_Plan\_Étage 030101010101\_DWG\_ARC YYMMDD\_Drawing-title.dwg 030101010102\_DWG\_STR 030101010103\_DWG\_MEP 030101010103\_DWG\_LAN 030101010201\_PDF\_ARK YYMMDD\_Drawing-title.pdf 030101010202\_PDF\_STR 030101010203\_PDF\_MEP 030101010203\_PDF\_LAN 03010102\_Plan\_Plafond 03010103\_Plan\_Sortie-de-secours 03010201\_Section 03010301\_Élévation 0302\_3D 03020101\_Modèles\_Archicad 030201010101\_PLN\_ARC 030201010102\_PLN\_STR YYMMDD\_Drawing-title.ifc 030201010103\_PLN\_MEP 030201010104\_PLN\_LAN 030201010201\_IFC\_ARC 030201010202\_IFC\_STR 030201010203\_IFC\_MEP 030201010204\_IFC\_LAN 03020102\_Modèles\_Navisworks 03020103\_Modèles\_Revit 030201030101\_RVT\_ARC 030201030201\_IFC\_ARC 03020104\_Modèles\_Rhinoceros 03020105\_Modèles\_Solibri 03020106\_Modèles\_Nuages-de-points 03020201\_Visualisation\_Rendus 03020202\_Visualisation\_Images-haute-résolution

### 3.2 **Type de domaine**

Dans cette structure de Documents, vous séparez d'abord les différents domaines d'études qui participent à votre projet. Ce type de structure de dossiers peut être bon si vous voulez donner à vos utilisateurs un accès complet à leur propre zone où ils sont libres de déplacer les fichiers comme ils le souhaitent. Cette structure de fichiers est plus facile à utiliser pour les consultants car ils ont leur propre zone où ils peuvent avoir le contrôle sur tous les fichiers qu'ils téléchargent. Cette structure de fichiers est plus difficile à utiliser pour le client car les fichiers des différents consultants sont dispersés dans leur propre dossier respectif.

_Exemple de structure de fichiers_

0101\_Information 010101\_Admin 010102\_Contrats 0201\_ARC 02010101\_2D 02010201\_3D\_Archicad 0201020101\_PLN 0201020102\_IFC YYMMDD\_Drawing-title.ifc 02010202\_3D\_Navisworks 02010203\_3D\_Revit 0201020301\_RVT 0201020301\_IFC 02010204\_3D\_Rhinoceros 02010205\_3D\_Solibri 02010206\_3D\_Nuages-de-points 02010307\_Contrats 0202\_MEP 020201\_2D 020202\_3D 020203\_Contrats 0203\_STR 0204\_LAN

## 4. **Dossier de modèles**

Avec les modèles en tant que Documents activés, il est possible de connecter les modèles de la section des modèles avec les Documents de la section des Documents. Si de nouveaux modèles sont créés dans la section des modèles, ils apparaîtront dans un dossier appelé le dossier des modèles. Les modèles peuvent être déplacés en dehors du dossier des modèles et déplacés à l'endroit où vous voulez qu'ils soient dans la structure des Documents.

Similaire aux exemples ci-dessus, vous pouvez soit structurer vos modèles par type: 01\_Models -> 0101\_ARC -> YYMMDD\_Model-title.ifc

Ou vous pouvez structurer vos modèles par domaine d'étude: 01\_ARC -> 0101\_Models -> YYMMDD\_Model-title.ifc

La meilleure option à choisir ici dépend de si vous pensez que vos utilisateurs utiliseront le [filtre de modèles](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page#h_1723ca8291). Si vous séparez les modèles par domaine d'étude, il peut être difficile pour les utilisateurs de trouver les modèles 3D qui sont mélangés avec les autres Documents de chaque domaine d'étude. Si vous êtes confiant que vos utilisateurs trouveront le [filtre de modèles](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page#h_1723ca8291), vous pouvez utiliser cette option. Si vous ne croyez pas que vos utilisateurs utiliseront ce filtre, il est préférable d'avoir tous vos modèles dans leur propre dossier de modèles afin que l'utilisateur soit conscient que ce dossier contient des modèles qui peuvent être ouverts en 3D.
