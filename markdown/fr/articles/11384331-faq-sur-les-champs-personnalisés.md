# FAQ sur les champs personnalisés

Les limites de la façon dont les champs personnalisés peuvent être utilisés seront expliquées ici.

Les rubriques suivantes sont décrites dans cet article:

## 1. **Projet \<=> Projet**

Les champs personnalisés ont un identifiant unique au sein d'un projet et ne peuvent donc pas être échangés d'un projet à un autre. Même si les champs personnalisés ont le même nom dans les deux projets, l'identifiant sera unique et le champ ne sera pas reconnu.

## 2. **Tableau de rubriques \<=> Tableau de rubriques**

Lorsqu'un champ personnalisé est activé pour deux tableaux de rubriques au sein du même projet, les rubriques peuvent être déplacées entre les tableaux et le champ sera conservé.

## 3. **Exportation des champs personnalisés sur les rubriques**

Les champs personnalisés sur les rubriques peuvent être exportés de la manière suivante

Les rubriques suivantes sont décrites dans cette section:

### 3.1 **Exportation PDF de rubrique**

Les valeurs des champs personnalisés sont affichées dans l'exportation PDF des rubriques

### 3.2 **Exportation BCF de rubrique**

Les champs personnalisés ne sont pas encore inclus dans le BCF exporté. Les champs personnalisés feront partie de la norme BCF 4 lorsqu'elle sera publiée. Après la publication, nous et d'autres outils BCF qui suivent la norme travailleront à rendre le champ disponible pour l'échange.

### 3.3 **Exportation Excel de rubrique**

Une colonne sera ajoutée pour chaque champ personnalisé dans le tableau de rubriques.

### 3.4 **API**

Les champs personnalisés dans les tableaux de rubriques [peuvent être configurés](https://developers.catenda.com/topic-api/update-a-topic-board) via l'API. Les champs personnalisés sur les rubriques [peuvent être configurés](https://developers.catenda.com/topic-api/update-topic) via l'API. Les informations sur les champs personnalisés des rubriques peuvent être récupérées via l'API.

### 3.5 **Action de rapport**

Les champs personnalisés sur les rubriques sont uniquement disponibles pour l'exportation avec les exportations PDF, BCF ou Excel et via l'API.

## 4. **Exportation des champs personnalisés sur les documents**

Les champs personnalisés sur les documents peuvent être exportés de la manière suivante

### 4.1 **Action de rapport**

Lorsque la fonctionnalité de rapports à la demande a été demandée pour être activée pour un projet, l'action de rapports est mise à disposition. Si le rapport est configuré avec le nom du champ personnalisé, les informations sur les champs personnalisés des documents sélectionnés dans le tableau des documents peuvent être exportées vers un rapport et enregistrées dans l'un des formats de rapport disponibles.

### 4.2 **API**

Les champs personnalisés sur les documents sont uniquement disponibles pour l'exportation avec l'action de rapport.

### 4.3 **Téléchargement de document**

Les champs personnalisés sur les documents sont uniquement disponibles avec l'action de rapport. Lorsque les documents sont téléchargés avec l'action de téléchargement dans le tableau des documents, le document original est téléchargé. Catenda ne modifie pas le document de quelque manière que ce soit, donc les champs personnalisés ne sont pas non plus ajoutés en tant que métadonnées.
