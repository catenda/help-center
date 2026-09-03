# Cas d'usage de nommage de révision

> Découvrez des exemples réels de nommage de révision. Voyez comment les équipes équilibrent espace et lisibilité grâce aux séquences de version, au mappage de statut et aux préfixes YYMMDD compacts ou YYYYMMDD clairs pour le tri chronologique.

Lors de l'activation d'une convention de nommage sur un dossier, les équipes de projet personnalisent souvent les blocs dynamiques pour s'adapter à des flux de travail de suivi internes spécifiques. Vous trouverez ci-dessous des exemples pratiques montrant comment différentes Équipes utilisent des champs personnalisés et le bouton **Identifiant de document** pour maintenir un espace de travail organisé.

## 1. **1. Rôles du projet et stratégies de mise en œuvre**

L'adoption de conventions de nommage est généralement motivée soit par un mandat du propriétaire du projet, soit par le désir des Membres du projet de mieux voir leurs fichiers. Une convention de nommage structurée permet aux Membres de l'équipe de rechercher plus efficacement des composants spécifiques des noms de Documents. Indépendamment de qui lance le flux de travail, les Membres du projet doivent contacter un administrateur de projet pour configurer et activer la convention de nommage, car un accès administratif est requis pour modifier ces paramètres.

La portée de la mise en œuvre dépend généralement de qui la demande :

### 1.1 **1.1 Mandats du propriétaire du projet**

Lorsqu'une convention est demandée par le propriétaire du projet, elle est fréquemment mise en œuvre à l'échelle du projet. Dans ces scénarios, un dossier distinct et désigné est souvent créé pour accueillir les Documents qui ne correspondent pas aux exigences strictes de la convention.

### 1.2 **1.2 Demandes des membres du projet**

Lorsqu'une convention est demandée par un individu ou un sous-groupe spécifique pour améliorer un flux de travail localisé, elle n'est généralement activée que sur son dossier de travail spécifique, tandis que le reste de l'Équipe du projet continue à fonctionner sans convention.

## 2. **2. Flux de travail de séquence de version**

La séquence de version est utilisée pour suivre les mises à jour consécutives des fichiers. En fonction des exigences du projet, les Équipes choisissent entre des pistes de longueur variable en expansion, des espaces réservés avec tirets rigides ou des indicateurs numériques simples.

### 2.1 Séquence de version standard (`v1`, `v2`, `v3`)

**2.1.1 L'équipe** Liam (Responsable BIM) et Sophia (Ingénieur structure).

**2.1.2 Le flux de travail** Sophia télécharge régulièrement des fichiers de modèle structurel sur la plateforme. Liam demande que tous les modèles entrants soient explicitement étiquetés avec des séquences de version standard comme `v1`, `v2` ou `v3`.

**2.1.3 Comportement et considérations** Bien que cette configuration soit simple au début, les pistes de version peuvent s'étendre à des chiffres doubles ou triples (par exemple, `v10` ou `v123`) à mesure que le projet progresse. Pour adapter cette croissance, un champ de texte avec une longueur infinie (variable) ou une longueur fixe plus grande est établi.

Une considération visuelle clé avec cette approche est que si le bloc est situé au milieu du nom de fichier, l'ajout d'un deuxième ou d'un troisième caractère à la séquence décalera visuellement tous les blocs de nommage suivants sur des emplacements de caractères. Pour empêcher ces étiquettes de version décalées de créer des conteneurs de Documents complètement séparés lors de chaque téléchargement, l'Identifiant de document doit être désactivé.

**2.1.4 La configuration**

- **Champ source :** Champ de texte personnalisé.
- **Longueur :** Laissé vierge pour une longueur variable, ou défini sur un nombre fixe plus grand.
- **Identifiant de document :** Désactivé.

**2.1.5 Le résultat** Lorsque Sophia télécharge des fichiers nommés `Structural_Model_v1.ifc` et `Structural_Model_v10.ifc`, la plateforme reconnaît les chaînes de version changeantes. Les fichiers s'empilent proprement en tant que révisions séquentielles sous un conteneur de document unique et statique nommé `Structural_Model`.

### 2.2 Séquence alphanumérique avec tirets (`--`, `-a`, `-b`)

**2.2.1 L'équipe** Sarah (Architecte principal) et Tom (Coordinateur BIM).

**2.2.2 Le flux de travail** Sarah émet des dessins architecturaux selon une progression où la version initiale commence par un double tiret (`--`), suivi d'un suivi alphabétique (`-a`, `-b`) au fur et à mesure que les modifications se produisent. Elle collabore avec Tom, qui gère les mises en page des dossiers.

**2.2.3 Comportement et considérations** Contrairement à la séquence de version standard, cette configuration avec tirets maintient la longueur du bloc exactement identique. Lorsqu'une nouvelle lettre de version est introduite, un tiret d'espace réservé est sacrifié pour maintenir un espacement uniforme.

Un défi principal avec cette stratégie est que une fois tous les tirets d'espace réservé dans la longueur prédéfinie épuisés, la convention s'arrête. Par conséquent, cette approche n'est recommandée que lorsqu'il y a une compréhension claire de la limite de révision maximale pour les Documents.

**2.2.4 La configuration :**

- **Champ source**
  Champ de texte personnalisé configuré avec une longueur fixe stricte (par exemple, 2 ou 3 caractères) ou un champ de liste déroulante personnalisé contenant les variations exactes autorisées.
- **Identifiant de document :** Désactivé.
- **Le résultat**
  Lorsque Sarah télécharge `FloorPlan_--.pdf` suivi plus tard par `FloorPlan_-a.pdf`, la plateforme lit les étiquettes de séquence changeantes pour la validation mais les supprime lors du nommage du fichier dans l'espace de travail. Tom et l'équipe de conception voient un conteneur de Document unique nommé `FloorPlan` où les variations historiques s'empilent en tant que révisions sans décaler les caractères suivants.

### 2.3 Séquence de suivi numérique simple (`01`, `02`, `03`)

**2.3.1 L'équipe** David (Dessinateur structure) et Chloe (Ingénieur structure principal).

**2.3.2 Le flux de travail** David met à jour fréquemment les dessins de détails structurels et les marque numériquement sur son ordinateur local à l'aide d'indicateurs séquentiels comme `01`, `02` et `03`. Chloe examine ces détails et compte sur la plateforme pour s'assurer que David saisit des nombres plutôt que des lettres de texte accidentelles.

**2.3.3 Comportement et considérations** Un bloc de règle axé sur les entiers est ajouté à la structure du dossier pour valider les entrées. Notez que bien qu'il garantisse que seules les entrées numériques sont utilisées, le système acceptera tout entier valide plutôt que de forcer un décompte séquentiel rigide.

**2.3.4 La configuration**

- **Champ source :** Champ entier personnalisé.
- **Identifiant de document :** Désactivé.

**2.3.5 Le résultat** Lorsque David télécharge `Steel_Detail_01.pdf`, le champ entier confirme que le bloc contient des données numériques et permet le téléchargement. Si David fait une erreur et tente de télécharger un fichier contenant des lettres dans ce bloc, le système rejette le fichier. Chloe peut surveiller les fichiers en sachant que bien que la plateforme accepte tout entier valide et ne force pas David à compter dans une séquence chronologique rigide, elle garantit une chronologie numérique propre dans le panneau d'information du fichier.

## 3. **3. Flux de travail de mappage de Statut abrégé (`W`, `D`, `P`)**

**3.1 L'équipe** Elena (Ingénieur CVCA) et Marcus (Chef de projet).

**3.2 Le flux de travail :** Elena utilise un système de nommage local où elle ajoute des codes d'abréviation à une seule lettre pour indiquer le statut du cycle de vie d'un dessin : `W` pour En cours, `D` pour Brouillon et `P` pour Publié. Marcus, le Chef de projet, doit connaître le statut exact de ses feuilles d'ingénierie en un coup d'œil mais préfère les mots complets et descriptifs plutôt que les abréviations.

**3.3 Comportement et considérations** Une configuration de liste déroulante est appliquée au dossier pour combler le fossé entre les codes d'abréviation locaux et les titres d'affichage des métadonnées de la plateforme.

**3.4 La configuration :**

- **Champ source :** Champ de liste déroulante personnalisé.
- **Configuration de mappage**
  Le "Code" est défini pour correspondre aux marqueurs de noms de fichiers locaux d'Elena (`W`, `D`, `P`), tandis que le "Nom" est écrit intégralement comme valeur d'affichage (`En cours`, `Brouillon`, `Publié`).
- **Identifiant de document :** Désactivé.

**3.5 Le résultat** Lorsqu'Elena télécharge `HVAC_Layout_W.pdf`, le système correspond au code `W` et remplit automatiquement l'affichage des métadonnées en tant que `En cours`. Lorsque Marcus développe le menu d'informations de droite pour examiner le fichier, le nom de document principal reste un `HVAC_Layout` propre et statique, tandis que la section **Informations de révision** affiche explicitement « En cours ».

## 4. **4. Suivi numérique des dates et tri chronologique**

### 4.1 **4.1 L'équipe**

Oliver (Responsable des Documents) et Emma (Responsable du site).

### 4.2 **4.2 Le flux de travail**

Oliver traite les rapports quotidiens du site et doit suivre exactement quand chaque rapport a été généré. Emma, la Responsable du site, accède fréquemment à la table des Documents et exige que les fichiers soient hautement organisés. Parce que les blocs de date natifs ne sont pas utilisés dans les conventions de nommage, Oliver et Emma utilisent des champs personnalisés numériques pour saisir des chaînes de date. Ils explorent deux variations de configuration distinctes en fonction du comportement souhaité des fichiers.

### 4.3 **4.3 Date comme marqueur de révision (ordre standard)**

Dans cette variation, la date change à chaque nouveau téléchargement de fichier et représente une nouvelle révision du journal quotidien. Oliver utilise deux chiffres pour le jour (`01`–`31`), deux chiffres pour le mois (`01`–`12`) et soit une année à deux chiffres (`26`, `27`) soit une année à quatre chiffres (`2026`, `2027`). Parce qu'une convention de nommage ne permet qu'un seul caractère séparateur principal dans tous ses blocs, la gestion d'un format de date isolé nécessite de choisir entre deux chemins de configuration distincts :

**4.3.1 Trois blocs entiers séparés**

- **Structure**
  Si un trait de soulignement (`_`) est établi comme séparateur principal, le fichier peut être formaté comme `Daily_Report_09_07_2026.pdf`.
  Cela utilise trois champs entiers personnalisés individuels : Jour, Mois et Année.
- **Contraintes de l'identifiant de document**
  Si l'Identifiant de document est activé **Activé** pour ces trois blocs, la date est définitivement intégrée au nom du Document.
  Ceci crée un conteneur de Document distinct pour chaque révision unique, et les valeurs de date restent permanentes car les noms de Documents dans les dossiers de convention de nommage ne peuvent pas être modifiés.
  Pour permettre aux champs de date de varier et d'empiler les fichiers en tant que révisions sous un nom de Document statique unique, il est nécessaire de basculer l'Identifiant de document **Désactivé** pour les trois champs.

**4.3.2 Bloc de texte unique avec séparateurs internes**

- **Structure**
  Pour éviter d'utiliser plusieurs blocs de convention, un caractère alternatif (comme un tiret) peut être utilisé à l'intérieur d'un bloc de champ de texte unique, formaté comme `Daily_Report_09-07-2026.pdf`.
- **Contraintes de validation**
  Il n'est possible de valider que la chaîne de texte globale dans un bloc individuel. Par conséquent, assurer le placement correct des séparateurs internes secondaires repose entièrement sur la précision manuelle de l'utilisateur lors de la préparation du fichier.

### 4.4 Date pour le tri (ordre année-mois-jour)

Dans cette variation, Emma souhaite que la date reste visible dans le nom du Document pour que des fichiers distincts existent pour chaque jour. De plus, Emma exige que la table des Documents trie automatiquement les fichiers dans un ordre chronologique parfait. Les listes au sein de la plateforme sont triées alphanumériquement selon les valeurs Unicode. Si une date est écrite comme Jour-Mois-Année, la liste trie d'abord par le numéro du jour, regroupant tous les fichiers du jour « 01 » de différents mois ensemble.

Pour éviter cela, Oliver place l'année en premier, suivi du mois, puis du jour. Lors de la gestion de ce préfixe, il y a un équilibre entre la conservation de l'espace des caractères et l'assurance d'une lisibilité immédiate, ce qui conduit à deux options de mise en œuvre :

**4.4.1 Préfixe d'année à deux chiffres (`YYMMDD`)** Cette option raccourcit la chaîne de tri en un seul bloc pour éliminer les caractères séparateurs supplémentaires et réduit l'année à deux entiers (par exemple, `26`, `27`, `28`). Cela économise l'espace des caractères, réduisant le risque que les noms de documents longs soient coupés ou tronqués à la fin de la ligne dans l'interface utilisateur. Cependant, cette option sacrifie la lisibilité immédiate.

Une chaîne de date telle que `260126` peut facilement être mal comprise, car il n'est pas immédiatement clair quels nombres représentent l'année et lesquels représentent le jour. Un motif n'devient reconnaissable que après avoir consulté plusieurs fichiers, et la différence ne devient distincte qu'une fois qu'une valeur de jour ou d'année dépasse 31.

**4.4.2 Préfixe d'année à quatre chiffres (`YYYYMMDD`)** Cette option utilise une année complète à quatre chiffres (par exemple, `2026`, `2027`, `2028`) au début du nom. Cette configuration améliore considérablement la clarté et la lisibilité immédiate, rendant la séquence chronologique évidente pour tous les membres de l'équipe. Cependant, elle consomme plus d'espace de caractères au début du nom de fichier, augmentant la probabilité que les informations à la fin des noms de documents longs soient tronquées ou coupées dans l'interface.

**4.4.3 Configuration**

- **Champ source**
  Un champ entier ou de texte personnalisé unique placé au tout début de la convention de nommage, formaté dans une séquence stricte `YYMMDD` ou `YYYYMMDD`.
  Pour maintenir un alignement correct et un tri alphanumérique approprié, les zéros en tête doivent toujours être utilisés pour les mois ou jours à un seul chiffre (par exemple, `01` pour janvier).
- **Identifiant de document :** Activé.

**4.4.4 Résultat** Lorsqu'Oliver télécharge des fichiers comme `260115_Report.pdf` et `260201_Report.pdf`, des documents distincts sont créés car l'identifiant de document est actif. Parce que l'année et le mois viennent en premier et utilisent un remplissage cohérent à deux chiffres, le tableau des documents trie automatiquement les fichiers dans un ordre chronologique impeccable.
