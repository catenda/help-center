# Configuration des dossiers - Paramètres des documents

Le menu de configuration des dossiers se trouve sur la [page des paramètres des documents](https://support.catenda.com/en/articles/7831371-document-settings-page). En configurant un dossier, vous pouvez améliorer la façon dont les Documents sont traités dans ce flux de travail.

## 1. **Tableau des dossiers**

Les dossiers peuvent être configurés dans le tableau des dossiers qui peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/01-folders-table.png)

### 1.1 **Filtre des dossiers configurés**

En haut du tableau, vous pouvez trouver un Filtre pour les dossiers configurés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/02-configured-folders-filter.png)

**Tous les dossiers** Voir tous les dossiers du projet.

**Dossiers configurés** Voir quels dossiers sont configurés dans le projet

### 1.2 **Colonne Dossiers**

Vous voyez ici tous les dossiers du projet. Cliquer sur la flèche ou n'importe où dans cette colonne étendra le dossier pour que vous voyiez ses sous-dossiers. Si vous survolez l'icône ou le nom d'un dossier, vous verrez une icône de Lien que vous pouvez cliquer pour ouvrir le dossier

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/03-folders-column.png)

Cela peut beaucoup aider à voir les résultats du dossier configuré après sa configuration.

**Ajouter une configuration** Cliquez sur le bouton + à droite d'un dossier pour ouvrir le [dialogue de configuration des dossiers](#h_96b6c91fe4). S'il y a des configurations dans des sous-dossiers, vous ne pourrez pas créer de configuration pour le dossier.

**Configuration d'aperçu** Si une configuration est définie pour un dossier, vous pourrez rapidement voir quelle configuration a été définie en cliquant sur l'icône de l'œil. L'aperçu de la configuration peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/04-folders-column.png)

**Modifier la configuration** Si une configuration est définie pour un dossier, vous pourrez la modifier en cliquant sur l'icône de crayon.

**Héritage de configuration** Si une configuration a été définie dans un dossier parent, tous ses sous-dossiers hériteront de sa configuration.

### 1.3 **Colonne Convention de nommage**

Vous voyez ici quels blocs de convention de nommage sont configurés pour une ligne

### 1.4 **Colonne Champs personnalisés**

Vous voyez ici quels champs personnalisés sont configurés pour une ligne

## 2. **Dialogue de configuration des dossiers**

Le dialogue de configuration des dossiers peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/05-folder-configuration-dialogue.png)

### 2.1 **Convention de nommage**

Si vous avez des conventions de nommage configurées sur la [page de convention de nommage](https://support.catenda.com/en/articles/7832559-naming-conventions-page) dans les [paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page), vous pourrez choisir quel dossier la convention de nommage s'applique ici. Lors de l'application d'une convention, tous les nouveaux Documents du dossier et des sous-dossiers doivent :

- Être nommés selon la convention de nommage
- Avoir un nom de document qui ne peut pas être modifié alors que la convention est active
- Rester dans le dossier dans lequel ils ont été téléchargés et ne peuvent pas être déplacés

Pour supprimer une convention de nommage, appuyez sur X.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/06-naming-convention.png)

### 2.2 **Champs personnalisés**

Avec les champs personnalisés, vous pourrez attribuer des champs personnalisés sur tous les Documents dans cette configuration. Les champs personnalisés peuvent être définis pour l'ensemble du document ou pour chaque revision. _Accès requis pour modifier le champ :_ Écriture

**Champs de Documents personnalisés**

- Les valeurs seront stockées sur le Document
- Exemple de champs personnalisés : « Description du document », « Note sur le document », etc...

**Champs de revision personnalisés**

- Les valeurs seront stockées sur chaque revision du Document
- Seules les valeurs stockées sur la dernière revision s'afficheront avec le Document.
- Exemples de champs personnalisés : « Commentaire de revision », « Statut d'approbation », etc...

**Nom** Le nom du champ personnalisé

**Type** Le type de champ personnalisé. Les types de champs personnalisés suivants peuvent être disponibles pour les dossiers : Date Décimal Liste déroulante Entier Texte

**Est obligatoire** Si un champ est obligatoire, il doit toujours avoir une valeur.

> **Remarque :** Une valeur par défaut devra être définie car le Document devra avoir une valeur lors du téléchargement.

**Valeur par défaut** Si une valeur par défaut est définie, cette valeur sera définie pour le champ pour tous les Documents téléchargés après la confirmation de la configuration, sauf s'il est modifié ultérieurement.

## 3. **Attribuer un code QR**

Avec [l'estampage de code QR](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda), vous pourrez sélectionner si vous souhaitez que cette fonction soit activée pour un dossier ici.
