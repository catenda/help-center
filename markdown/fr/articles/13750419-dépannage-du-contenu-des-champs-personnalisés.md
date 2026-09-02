# Dépannage du contenu des champs personnalisés

## 1. **Impossible de restaurer l'option de liste déroulante archivée**

Un blocage logique se produit si une tentative est faite pour restaurer une option archivée alors que le **Nom** associé est actuellement utilisé par une option active. Comme il n'est possible d'assigner un nom qu'à une seule option, la restauration est bloquée. _Accès requis :_ Accès administrateur

Pour récupérer la valeur archivée, il est possible de suivre cette séquence :

**Renommer la valeur active** L'option active utilisant actuellement le nom est modifiée par un administrateur en une valeur temporaire pour libérer le nom dans le système.

**Restaurer la valeur archivée** La **Liste désactivée** est accédée, et l'action **Restaurer** est sélectionnée pour l'élément requis.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/01-unable-to-restore-archived-dropdown-option.png)

**Corriger les données** Les noms et les codes sont ajustés à l'état correct.

**Rétablir les noms** Le nom temporaire est ramené au nom d'origine prévu.

## 2. **Unicité des noms et des codes**

Il est important de distinguer le **Nom** d'une option de son **Code**. Chaque option de liste déroulante se compose de ces deux éléments, et il n'est possible d'enregistrer une option que si le nom et le code sont tous deux uniques dans ce champ personnalisé spécifique.

## 3. **Erreur de nom en double**

Il n'est possible d'assigner un nom qu'à une seule option dans une liste déroulante. Si une erreur de nom en double s'affiche, les étapes suivantes sont effectuées : _Accès requis :_ Accès administrateur

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/02-duplicate-name-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/03-duplicate-name-error.png)

**Vérification de la liste active** La liste des options actives est vérifiée pour confirmer si le nom est déjà utilisé.

**Vérification de la liste désactivée** La liste désactivée est vérifiée, car les noms assignés aux éléments archivés restent dans le système.

**Résolution** Il n'est possible de procéder que soit en utilisant un nom unique différent, soit en renommant l'option existante qui détient le nom.

## 4. **Erreur de code en double**

Il n'est possible d'assigner un code qu'à une seule option dans un champ personnalisé de liste déroulante. Le code est une valeur unique utilisée pour identifier les blocs pour les conventions de dénomination. _Accès requis :_ Accès administrateur

Si une erreur de code en double s'affiche :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/04-duplicate-code-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/05-duplicate-code-error.png)

**Vérification de la liste active** La liste active est vérifiée pour voir si le code est déjà utilisé.

**Vérification de la liste désactivée** La liste désactivée est vérifiée, car les codes assignés aux éléments archivés occupent toujours cette valeur unique.

**Résolution** Il n'est possible de procéder que soit en utilisant un code unique différent, soit en désactivant l'option existante qui détient le code.

## 5. Modification des codes existants

Il n'est possible de définir un code que lors de la création initiale d'une option ou si une option existante n'a pas encore de code assigné. Une fois qu'un code est ajouté et enregistré, il est verrouillé à cette valeur et le champ devient non modifiable.

**Restrictions de modification** Il n'est possible de modifier le **Nom** d'une option qu'après l'application d'un code. Le champ **Code** apparaît grisé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/06-modifying-existing-codes.png)

Avant application :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/07-modifying-existing-codes.png)

Après application :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/08-modifying-existing-codes.png)

**Récupération d'un code** Si un code est déjà utilisé par un élément archivé, il n'est possible d'utiliser ce code spécifique qu'en restaurant d'abord l'option archivée à partir de la liste désactivée. Il n'est pas possible de soumettre une nouvelle option avec un code qui est techniquement toujours détenu par un élément désactivé.

**Modification d'un code** Pour utiliser un code complètement différent pour un nom existant, il n'est possible de le faire qu'en désactivant l'option actuelle et en créant une nouvelle avec le code souhaité.

## 6. Erreurs de saisie pour les champs entiers

Des contraintes spécifiques existent pour les champs entiers qui entraînent des erreurs de saisie de données :

**Nombres entiers uniquement** Il n'est possible d'enregistrer que des nombres entiers dans un champ personnalisé entier.

**Caractères non numériques** Bien qu'il n'est possible de taper que des nombres directement dans le champ, il est possible de coller des caractères non numériques.

**Comportement du bouton Enregistrer** S'il y a des caractères non numériques dans le champ, le bouton Enregistrer est désactivé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/09-input-errors-for-integer-fields.png)

## 7. **Visibilité du tableau et filtrage**

Si un champ personnalisé n'est pas visible sur un tableau de problèmes, les paramètres suivants sont vérifiés :

**Attribution du champ** La création d'un champ personnalisé permet de l'ajouter à un tableau de problèmes. Le champ doit être ajouté au tableau spécifique pour apparaître dans l'en-tête du problème.

**Affichage du tableau** Il n'est possible de voir les données de champ personnalisé dans un format de liste que si la colonne correspondante est sélectionnée dans l'affichage du tableau du tableau de problèmes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/10-board-visibility-and-filtering.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/11-board-visibility-and-filtering.png)

**Limites des Filtres** Il n'est possible de filtrer les champs personnalisés que s'il y a jusqu'à 10 champs assignés.
