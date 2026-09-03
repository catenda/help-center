# Page de contenu des champs personnalisés

Vous pourrez trouver la page d'un champ personnalisé en cliquant sur le champ correspondant sur la [page des champs personnalisés](https://support.catenda.com/en/articles/6550459-custom-fields-page) que vous trouverez en tant que sous-page de la [page des paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page).

La création d'un champ personnalisé vous permettra de l'ajouter à un tableau de problèmes. Les problèmes dans ce tableau auront alors un nouveau champ dans l'en-tête. Vous pourrez également voir une colonne dans la vue tableau du tableau de problèmes et vous pourrez filtrer ces champs.

## 1. **Menu Nouvelle action d'élément**

Les administrateurs pourront trouver les boutons d'action en haut à droite de la page de contenu d'un champ personnalisé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/01-new-item-action-menu.png)

_Nouveau champ personnalisé_ Cliquez sur le bouton plus vert en haut à droite ou sur l'action Nouveau champ personnalisé dans le menu d'action pour créer un [nouveau champ personnalisé](https://support.catenda.com/en/articles/8445575-creating-a-custom-field)

**Archive** Ouvrez le menu d'action avec les trois points en haut à droite pour trouver l'action Archive en haut à droite. Il n'est possible que d'archiver un champ personnalisé. Il n'est pas possible de supprimer un champ personnalisé.

Au lieu de supprimer, les champs personnalisés ne peuvent qu'être archivés. Un champ personnalisé archivé disparaîtra de

## 2. **Champ personnalisé de type "Date"**

Un champ de date affiche une date sur le calendrier grégorien. La date s'affiche au format configuré sur la page du compte pour chaque membre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/02-date-custom-field.png)

Ce champ peut être utilisé pour enregistrer la date de création initiale si l'information a été créée un certain temps avant sa soumission à Catenda et que les métadonnées sont connues mais ne sont pas reflétées dans les métadonnées du document ou le titre.

## 3. **Champ personnalisé des nombres décimaux**

Un champ de nombre décimal affiche jusqu'à 6 chiffres après la virgule. S'il y a plus de 6 chiffres après la virgule, la notation scientifique sera utilisée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/03-decimal-number-custom-field.png)

Ce champ est souvent utilisé pour enregistrer des montants tels que le coût des matériaux ou l'impact budgétaire.

**Limite** Les champs personnalisés décimaux ont une limite de valeurs entre `-0.000000001` et `2147483647` par champ personnalisé entier qui est rempli. Les champs personnalisés décimaux ont une limite de 17 nombres combinés avant et après le séparateur décimal. Pour les nombres plus grands, la notation scientifique peut être utilisée. Par exemple `1.0991234567890123e+22` Le nombre de caractères peut être limité davantage avec une convention de nommage pour utilisation dans le nom de téléchargement du document.

## 4. **Champ personnalisé de la liste déroulante**

Pour accéder à la page du champ personnalisé d'un champ de liste déroulante, cliquez sur un champ de liste déroulante.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/04-dropdown-custom-field.png)

Lorsqu'un champ personnalisé de liste déroulante est créé pour la première fois, vous serez automatiquement amené à cette page. Une page de champ personnalisé de liste déroulante peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/05-dropdown-custom-field.png)

### 4.1 **Titre et description**

Les administrateurs pourront modifier le titre et la description du champ en cliquant sur le crayon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/06-title-and-description.png)

### 4.2 **Onglets Actif et désactivé**

Sous la description, l'onglet Actif est activé par défaut. Cliquez sur l'onglet désactivé pour afficher les valeurs de liste déroulante qui ont été précédemment désactivées.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/07-active-and-disabled-tabs.png)

**Restaurer** Utilisez l'action de restauration pour restaurer une valeur de liste déroulante précédemment désactivée

> **Remarque :** Chaque valeur dans la liste des valeurs actives doit avoir un nom unique, assurez-vous donc que le nom n'est pas déjà utilisé lors de la restauration d'une valeur.

### 4.3 **Options de liste déroulante** - Liste active

Dans la liste active, vous pourrez trouver les options de liste déroulante actuellement actives.

_Ancre_ Les administrateurs pourront configurer l'ordre des options en faisant glisser l'ancre dans la colonne la plus à gauche.

**Nom** Ici, les utilisateurs verront le nom d'une option de liste déroulante. Si le champ de liste déroulante a été [ajouté à une liste de sujets](https://support.catenda.com/en/articles/6563368-custom-fields-in-a-topic-board), vous verrez ce nom comme une option dans la liste. Un nom ne peut être assigné qu'à une seule option.

**Code** Ici, les utilisateurs verront le code d'une option de liste déroulante. Le code est utilisé pour [identifier un bloc avec une convention de nommage](https://support.catenda.com/en/articles/7869240-how-to-use-custom-fields-in-naming-convention). Un code ne peut être assigné qu'à une seule option.

**Éditer et désactiver** Les administrateurs pourront modifier le nom d'une option après sa création. Si le champ n'a pas encore de code, il est possible d'ajouter un code. Après modification, cliquez sur enregistrer ou annuler pour confirmer.

Les administrateurs pourront désactiver les options en cliquant sur désactiver et en cliquant sur confirmer. La désactivation est similaire à la suppression car l'option disparaîtra partout sur le hub Catenda mais peut être récupérée ultérieurement à partir de la liste désactivée.

Une fois qu'un code est ajouté, il n'est plus possible de modifier le code. Si vous souhaitez utiliser un code différent, vous pouvez désactiver l'option et créer une nouvelle option.

### 4.4 **Options de liste déroulante -** Liste désactivée

Vous pourrez trouver ici toutes les options actuellement désactivées. Les administrateurs pourront cliquer sur restaurer pour restaurer l'une des options désactivées.

### 4.5 **Ajout d'une option**

Après création, un champ personnalisé de liste déroulante n'aura pas encore d'options. Les administrateurs pourront ajouter des options en cliquant sur le bouton d'ajout d'options en bas à gauche

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/08-adding-an-option.png)

Après avoir cliqué sur ajouter des options, vous verrez le dialogue suivant :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/09-adding-an-option.png)

_Nom_ Ici, vous pouvez ajouter un nom et un code pour chaque option de liste déroulante.

**Code** Le code est utilisé pour [identifier un bloc avec une convention de nommage](https://support.catenda.com/en/articles/7869240-how-to-use-custom-fields-in-naming-convention). Le code est une valeur unique que vous pouvez définir sur un élément. Cela signifie que vous ne pouvez pas ajouter le même code deux fois.

**Dépannage des noms et codes** Cliquez [ici](https://support.catenda.com/en/articles/13750419-custom-field-content-troubleshooting) pour en savoir plus s'il y a des défis avec le nom et le code.

### 4.6 **Ajout de plusieurs options**

Dans un champ de liste déroulante, vous souhaitez souvent ajouter plus d'une option. Si vous ajoutez un nom et cliquez sur soumettre, vous devez cliquer sur « Ajouter des options » à chaque fois que vous souhaitez ajouter une option, ce qui peut être fastidieux et prendre beaucoup de temps. Il existe donc plusieurs façons d'ajouter rapidement des options.

**Rester ouvert à la soumission** Pour continuer à ajouter une option après l'autre, vous pouvez cocher le bouton « Rester ouvert à la soumission ». Si ce bouton est coché, vous pourrez ajouter le nom de l'option suivante immédiatement après avoir soumis l'option précédente, vous n'aurez donc pas à cliquer sur « Ajouter des options » à tout moment.

**Ajouter plusieurs options** Si vos options sont déjà préparées en dehors de Catenda, vous pouvez les coller correctement en cliquant sur le bouton « Ajouter plusieurs options ». Lorsque vous cliquez sur ce bouton, le dialogue changera et vous pourrez coller une chaîne. Si Catenda peut interpréter correctement la chaîne, les noms et les codes de vos options collées seront reconnus et vous pourrez les tous soumettre à la fois.

**Création d'une chaîne de collage**

- Copier-coller Excel

Un moyen facile de créer une chaîne de collage est de copier des lignes et des colonnes à partir d'un logiciel d'édition de tableau comme Excel. Si vous ajoutez vos noms dans la première ligne et optionnellement vos codes dans la deuxième, vous pouvez les copier et les coller dans le dialogue de collage. Vos noms et codes seront alors automatiquement formatés correctement.

- Chaîne séparée par des virgules

Pour créer une chaîne qui se transformera en un ensemble d'options, séparez vos options par une « virgule »  `,` ou une « nouvelle ligne » `\n`. Par exemple, « Electrical,Architecture » se transformera en options `Electrical` et `Architecture`

- Noms et codes dans une chaîne

Facultativement, si vous souhaitez l'ajouter, vous pouvez ajouter un code à votre option en le séparant par une « tabulation », « deux-points » `:`, « point-virgule » `;` et « tube » `|`. Par exemple, « Electrical:el,Architecture:arc » se transformera en option `Electrical` avec le code `el` et l'option `Architecture` avec le code `arc`.

Après avoir collé la chaîne dans le champ de collage, vous pouvez cliquer quelque part sur la page pour voir si votre formatage a réussi.

> **Remarque :** Si le champ de liste déroulante est ajouté à une liste de sujets, le nombre de champs que vous ajoutez et si votre champ est obligatoire sont importants. S'il y a jusqu'à 10 champs, vous pouvez filtrer pour chacun des champs. Si le champ n'est pas obligatoire, le champ peut être filtré selon que le champ est défini ou non.

**Limite** Bien qu'il soit possible d'ajouter jusqu'à 450 options à la fois, il est recommandé d'ajouter jusqu'à 100 options à la fois.

### 4.7 **Limite**

Les champs personnalisés de liste déroulante ont une limite de sélection d'une option parmi jusqu'à 1000 options par champ personnalisé de liste déroulante.

## 5. **Champ personnalisé entier**

Un champ personnalisé entier affiche des nombres entiers.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/10-integer-custom-field.png)

Seuls les nombres entiers sont autorisés avec ce champ et pas de décimales. Ceci est souvent utilisé pour enregistrer les occurrences.

**Limite** Les champs personnalisés entiers ont une limite de valeurs entre `-2147483648` et `2147483647` par champ personnalisé entier qui est rempli. Le nombre de caractères peut être limité davantage avec une convention de nommage pour utilisation dans le nom de téléchargement du document. Pour les nombres plus grands, un champ décimal peut être utilisé avec la notation scientifique.

## 6. **Champ personnalisé texte**

Un champ personnalisé texte affiche une chaîne de texte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/11-text-custom-field.png)

Le texte s'affiche sur une seule ligne. Un bon exemple de champ texte est un champ appelé commentaire qui peut être rempli et vu à partir de la vue tableau. Dans les conventions de nommage, il est souvent utilisé pour limiter une certaine quantité de caractères autorisés pour un champ dans un titre de document.

**Limite** Les champs personnalisés texte ont une limite maximale de 200 caractères par champ personnalisé texte qui est rempli. Le nombre de caractères peut être limité davantage avec une convention de nommage pour utilisation dans le nom de téléchargement du document.
