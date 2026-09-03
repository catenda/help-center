# Filtrage sur la page des objets

Le panneau de filtrage sur la page des objets peut être ouvert en cliquant sur le bouton de filtrage à gauche de la barre de recherche sur la page des objets.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/01-intro.png)
Voici à quoi le menu de recherche ou de filtrage peut ressembler lorsqu'il est ouvert :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/02-intro.png)

## 1. **Filtres**

Cliquez sur le bouton de filtrage en haut à gauche pour qu'un panneau apparaisse sur le côté gauche. Lorsqu'un filtre est appliqué, l'URL visible dans le navigateur change. Dans cet article, les filtres sont affichés comme suit : _Nom du filtre dans le menu_ - `Nom du filtre dans l'URL=Option du filtre dans l'URL`

**Filtre par défaut** Le filtre par défaut n'est pas initialement visible dans l'URL. Lorsque la page est consultée pour la première fois, le filtre suivant est appliqué.

**Aucun filtre**

### 1.1 **Enregistrer et partager le filtre actuel**

Allez à l'URL d'une page filtrée pour charger cette page avec le filtre appliqué. Les filtres appliqués peuvent être enregistrés vers le haut du menu de filtrage. Cliquez [ici](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) pour en savoir plus sur la façon d'enregistrer et de partager les filtres

### 1.2 **Masquer les filtres vides**

Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la limitation des résultats de filtrage.

### 1.3 **Modèles**

Cliquez sur 3D à droite de la catégorie Modèles dans le menu de filtrage pour filtrer tous les modèles actuellement chargés dans la Visionneuse 3D.

Nom du modèle - `model=<Model GUID>` Filtrer sur un ensemble de modèles de projet.

### 1.4 **Sélectionné**

Sélectionné - `selected=true` Filtrer pour afficher uniquement les lignes des objets sélectionnés dans la Visionneuse 3D.

## 2. **Filtres qui ne sont pas listés dans le panneau de filtrage**

### 2.1 **Requête**

Recherche par requête - `query=<Product>,<Operator>,<Value>` Cliquez dans la barre de recherche ou de filtrage pour configurer un filtre qui compare deux valeurs.

**Produit** La première sélection peut être n'importe quel type de produit IFC. Voici à quoi peut ressembler la liste déroulante de produit :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/03-query.png)

**Opérateur** L'opérateur ne peut être sélectionné qu'après qu'un produit a été sélectionné. La partie opérateur du filtre de requête détermine comment le produit est comparé à la valeur. Selon que le produit peut avoir n'importe quelle valeur ou si le produit ne peut avoir qu'un ensemble limité de valeurs, différents opérateurs peuvent être choisis :

Opérateurs toujours disponibles : Égal - `equals` Lorsque le produit sélectionné a exactement la valeur saisie

N'est pas égal - `not-equals` Lorsque le produit sélectionné n'a pas exactement la valeur saisie

Existe - `exists` Lorsque « Existe » est sélectionné, seul un produit peut être sélectionné, pas une valeur, car toutes les valeurs font partie de ce filtre

N'existe pas - `not-exists` Lorsque « N'existe pas » est sélectionné, seul un produit peut être sélectionné, pas une valeur, car toutes les valeurs font partie de ce filtre

Opérateurs d'ensemble de valeurs limité Voici à quoi peut ressembler la liste déroulante de l'opérateur lorsque la propriété sélectionnée a un ensemble limité de valeurs :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/04-query.png)

Contient - `contains`

Ne contient pas - `not-contains` Pour obtenir des résultats sur les produits qui ne contiennent pas une valeur spécifique

A une valeur - `has-value` Lorsque « A une valeur » est sélectionné, seul un produit peut être sélectionné, pas une valeur, car toutes les valeurs font partie de ce filtre

Opérateurs de valeur quelconque Voici à quoi peut ressembler la liste déroulante de l'opérateur lorsque la propriété sélectionnée peut avoir n'importe quelle valeur :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/05-query.png)

Dans la plage - `range-inclusive` Lorsque l'opérateur de plage est sélectionné, il y a deux champs de valeur. Voici à quoi cela peut ressembler lorsqu'un filtre de plage est modifié :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/06-query.png)

La plage sera tout ce qui va de la première valeur à la deuxième valeur.

Supérieur ou égal - `greater-than-equals`

Supérieur à - `greater-than`

Inférieur ou égal - `less-than-equals`

Inférieur à - `less-than`

**Valeur** Le champ de valeur se comporte différemment selon les valeurs possibles que le produit sélectionné peut avoir.

Valeur numérique Lorsque le produit sélectionné ne peut avoir qu'une valeur numérique, des flèches sont affichées lorsque le champ de valeur est cliqué et seuls les chiffres peuvent être saisis.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/07-query.png)

Valeurs suggérées Lorsqu'un produit peut avoir une valeur de texte, elle peut être saisie directement dans le champ de valeur. Voici à quoi peut ressembler le menu de valeur lorsque le produit Entité a été sélectionné.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/08-query.png)

Lorsque vous cliquez dans le champ de valeur, une liste d'éléments suggérés s'affiche sous le champ. Si le produit sélectionné ne peut avoir qu'un ensemble limité de valeurs, cet ensemble limité de valeurs s'affiche dans la liste des éléments suggérés. Si le produit sélectionné peut avoir n'importe quelle valeur, la liste des éléments suggérés affiche une liste de valeurs que d'autres produits de ce type ont.
