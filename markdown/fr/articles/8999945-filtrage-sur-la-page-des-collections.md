# Filtrage sur la page des collections

L'option de recherche et de filtrage que vous verrez dans la partie supérieure de la fenêtre. Vous pouvez rechercher en écrivant le nom de la collection.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/svz5chty/01-intro.png)

Dans la barre de recherche, vous pouvez rechercher n'importe quelle collection à laquelle vous avez accès.

## 1. **Panneau de filtre de gauche**

En cliquant sur le bouton de filtre, un panneau apparaîtra sur le côté gauche. En cochant les cases, vous affinerez la recherche. Ces filtres peuvent être sauvegardés en haut de la liste des filtres. Lorsque vous appliquez l'un de ces filtres, le texte du filtre sera ajouté à votre URL. Si vous partagez cette URL, la personne qui l'ouvrira verra le même filtre que vous si elle y a accès. Par exemple, si vous partagez une URL avec le filtre « Je suis » activé, le destinataire verra les filtres qu'il suit lorsqu'il ouvrira l'URL. Lorsque vous survolez l'un des filtres du panneau de gauche, vous pouvez cliquer uniquement à droite du filtre pour supprimer tout autre filtre précédemment appliqué.

## 2. **Filtres sauvegardés**

Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la façon de sauvegarder un ensemble de filtres

## 3. **Filtres**

Cliquez sur le bouton de filtre en haut à gauche pour qu'un panneau apparaisse sur le côté gauche. Lorsqu'un filtre est appliqué, l'URL visible dans le navigateur change avec lui. Dans cet article, les filtres sont affichés comme suit : _Nom du filtre dans le menu_ - `Nom du filtre dans l'URL=Option de filtre dans l'URL`

**Filtre par défaut** Le filtre par défaut n'est initialement pas visible dans l'URL. Lorsque la page est visitée pour la première fois, le filtre suivant est appliqué. _Collections suivies par moi et Équipes dont je fais partie_ - `followers=my-teams,me`

### 3.1 **Enregistrer et partager le filtre actuel**

Allez à l'URL d'une page filtrée pour charger cette page avec le filtre appliqué. Les filtres appliqués peuvent être sauvegardés vers le haut du menu des filtres. Cliquez [ici](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) pour en savoir plus sur la façon d'enregistrer et de partager les filtres

### 3.2 **Masquer les filtres vides**

Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la limitation des résultats des filtres.

### 3.3 **Collections suivies**

_Je suis_ - `followers=me` Collections suivies par l'utilisateur.

_Mon équipe suit_ - `followers=my-teams` Collections suivies par les Équipes dont l'utilisateur fait partie.

_Toutes les collections_ - `followers=all` Toutes les collections avec ou sans suivi. Ce filtre s'applique automatiquement lorsque le bouton x dans la barre de recherche est cliqué ou lorsque les filtres « Je suis » et « Mon équipe suit » sont tous les deux désactivés.

### 3.4 **Créé par moi**

Créé par - `createdBy=<Creator GUID>` Il n'y a pas de bouton d'interface utilisateur pour ce filtre. Lorsque vous filtrez sur privé ou partagé avec le projet, cela sera automatiquement défini sur votre propre utilisateur, mais vous pouvez le modifier avec le GUID d'un autre utilisateur.

Privé - `visibility=private` Partagé avec le projet - `visibility=project-members`

### 3.5 **Finalisé**

Finalisé - `finalized=true` Non finalisé - `finalized=false`

### 3.6 **Partagé en externe**

Partagé en externe - `sharedBy=email,link`

> **Remarque :** En écrivant soit email soit lien ici, vous pouvez affiner votre recherche

Non partagé en externe - `sharedBy=not-shared`

### 3.7 **Filtres de date**

Publié - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Cliquez sur sélectionner les dates pour sélectionner les dates entre lesquelles vous souhaitez rechercher Cliquez [ici](https://support.catenda.com/en/articles/6511685-date-filter) pour en savoir plus sur le filtre de date

## 4. **Rechercher**

Vous pouvez rechercher des correspondances exactes de texte dans les noms de fichiers d'au moins 3 caractères

### 4.1 **Rechercher**

_Recherche de texte_ - `search=test`

**Contenu pouvant être recherché** nom de la collection

**Casse** La recherche de texte n'est pas sensible aux caractères majuscules ou minuscules.

**Quantités de caractères** N'importe quelle quantité de caractères. Le contenu qui inclut la phrase recherchée est trouvé.

**Espace blanc** Les caractères d'espace blanc au début d'une phrase de recherche sont supprimés.
