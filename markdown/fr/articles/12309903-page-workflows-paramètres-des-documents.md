# Page Workflows - Paramètres des documents

La page des flux de travail se trouve en cliquant sur le bouton configurer les flux de travail dans le menu des approbations de la [page des paramètres des documents](https://support.catenda.com/fr/articles/7831371-page-des-parametres-du-document) dans les projets où le nouveau flux de travail de validation est actif et les statuts partagés sont activés dans le menu du flux de travail des statuts des [paramètres des documents](https://support.catenda.com/fr/articles/7831371-page-des-parametres-du-document). Le nouveau flux de travail de validation est actif dans tous les nouveaux projets. Les projets qui utilisent une version héritée du flux de travail de validation peuvent demander une migration vers le nouveau flux de travail de validation au support. Sur la page des flux de travail, les flux de travail pour différentes configurations d'approbation peuvent être configurés. _Accès requis :_ Administrateur

La page workflows peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/01-intro.png)

Les sujets suivants seront décrits dans cet article :

_[Nouvelles actions d'élément](https://support.catenda.com/fr/articles/8204673-page-documents#h_d0f4a44fb7) - [Rechercher ou filtrer](https://support.catenda.com/fr/articles/8204673-page-documents#h_bbf4dcad58) - [Menu droit](https://support.catenda.com/fr/articles/8204673-page-documents#h_fc89aaa1fe) - [Tableau](https://support.catenda.com/fr/articles/8204673-page-documents#h_54e8dfcac2) - [Sous-pages](https://support.catenda.com/fr/articles/8204673-page-documents#h_5751ccd2b7)_

Bien que la page des flux de travail soit une sous-page de la page des approbations, comme c'est apparent car la page des approbations est mise en évidence et le fil d'Ariane en haut, la page n'est accessible que depuis le menu des approbations dans les paramètres des documents.

## 1. **Nouvelles actions d'élément**

Les nouvelles actions d'élément se trouvent en haut à droite de la page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/02-new-item-actions.png)

Voir ici pour savoir ce que font les différentes actions.

## 2. **Options de recherche ou de filtrage**

Voici à quoi le menu de recherche ou de filtrage peut ressembler sur la page workflows.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/03-search-or-filter-options.png)

Dans la barre de recherche, tout workflow disponible sur la page workflows peut être recherché.

### 2.1 **Panneau de filtre gauche**

En cliquant sur le bouton de filtre, un panneau apparaîtra sur le côté gauche. Cochez les cases pour affiner la recherche. Lorsque l'un de ces filtres est appliqué, le texte du filtre sera ajouté à votre URL. Si l'URL de la page filtrée est partagée, la personne qui l'ouvre verra les mêmes résultats que ceux actuellement affichés tant qu'elle y a accès.

### 2.2 **Filtres**

> **Remarque :** L'URL de la page Web change selon les filtres appliqués. Cela permet au tableau de documents filtrés actuel d'être partagé avec les autres membres qui font partie du projet.

Si plusieurs des mêmes filtres sont sélectionnés, ils sont séparés par un `,` ou `%2C` Si plusieurs filtres sont sélectionnés, ils sont séparés par `&` ou `%26` Différents filtres et leurs équivalents d'URL :

**Statut** Actif - Par défaut - `status=active` Archivé - `status=archived `

> **Remarque :** Il est uniquement possible d'afficher soit les workflows actifs, soit les workflows archivés, pas les deux à la fois

**Recherche** Recherche textuelle - `search=test` Par défaut, la recherche textuelle correspond uniquement aux workflows actifs. Pour rechercher les statuts archivés, filtrez d'abord sur archivé, puis utilisez la recherche textuelle.

## 3. **Tableau workflows**

Le tableau workflows peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/04-workflows-table.png)

Cliquez [ici](https://support.catenda.com/fr/articles/11748020-tableaux-sur-catenda) pour en savoir plus sur la façon de travailler avec les tableaux dans Catenda. Dès qu'un workflow est créé, il apparaît sous forme de ligne dans le tableau workflows.

### 3.1 **Contenu de la ligne**

**Ligne de workflow** L'ouverture du contenu d'une ligne de workflow ouvre la page de workflow pour ce workflow. Voici à quoi la page de workflow peut ressembler lorsqu'elle est ouverte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/05-row-content.png)

Sur la page de workflow d'un workflow, il est possible de voir comment le workflow a été configuré.

Titre La seule partie du workflow qui peut être modifiée est le nom du workflow.

Fuseau horaire Si un fuseau horaire est sélectionné pour le workflow, il restera le même toute l'année. Si une localisation géographique est sélectionnée pour le workflow, le décalage GMT changera en fonction du fuseau horaire actuellement actif pour cette localisation géographique.

Mise à jour Cliquez sur mise à jour pour mettre à jour le titre.

### 3.2 **Colonnes**

Certaines colonnes du tableau workflows sont activées par défaut tandis que d'autres peuvent être masquées et doivent être activées. En fonction de l'ordre des colonnes configuré, les premières colonnes sont affichées tandis que le tableau peut devoir être défilé latéralement pour afficher d'autres colonnes activées. L'ordre par défaut et le paramètre de visibilité des colonnes sur la page workflows sont les suivants :

Titre - _Par défaut_ Le titre du workflow

Créé par - _Par défaut_ Le membre qui a créé le workflow.

Créé à - _Par défaut_ La date et l'heure de création du workflow

Statut - _Par défaut_ Le statut du workflow

## 4. **Flux de travail provenant d'un projet de modèle**

Les projets créés à partir d'un projet de modèle incluent les flux de travail d'approbation et les modèles de sujets de ce projet de modèle. Ces flux de travail sont répertoriés dans le tableau des flux de travail du nouveau projet. Cliquez [ici](https://support.catenda.com/fr/articles/4670245-creer-un-nouveau-projet) pour en savoir plus sur la création d'un projet basé sur un projet de modèle.
