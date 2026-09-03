# Liste de sujets à partir d'une liste de sujets existante

Vous pouvez créer une nouvelle liste de sujets en cliquant sur l'action de nouvelle liste de sujets sur la [page des listes](https://support.catenda.com/en/articles/9413644-boards-page). L'action se trouve avec le bouton plus vert en haut à droite ou dans le menu d'actions adjacent. Accès requis : accès en écriture pour créer de nouvelles listes de sujets dans le menu d'accès sur la [page des paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page).

Voici à quoi peut ressembler la page Nouvelle liste de sujets :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/01-intro.png)

## 1. **Nom**

Donnez à la liste de sujets un nom comme exigence minimale pour ajouter la liste de sujets. La liste des listes de sujets est triée par nom de liste de sujets selon l'[ordre de tri typique des listes](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) sur Catenda. Il est donc souvent judicieux d'utiliser une convention de nommage lors du nommage des listes de sujets. Voici un exemple de ce que les listes de sujets pourraient s'appeler :

![Liste des tableaux de bord thématiques introduction examen des documents approuvé approuvé avec commentaires rejeté documents breeam socre coordination coût projets](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/02-name.png)

## 2. **Description**

La description de la liste de sujets est facultative et ne peut être vue ultérieurement dans les paramètres de la liste de sujets que par ceux disposant d'un accès complet à la liste de sujets. La description de la liste de sujets suit les règles générales de [mise en forme des messages](https://support.catenda.com/en/articles/8430847-formatting-of-posts) sur Catenda.

## 3. **Copier les paramètres d'une liste de sujets existante**

Pour copier les paramètres d'une liste de sujets lors de la création d'une liste de sujets, cliquez sur le menu "copier les paramètres d'une liste de sujets existante" pour sélectionner une liste de sujets existante dans le projet à partir de laquelle les paramètres doivent être copiés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/03-copy-settings-from-an-existing-topic-board.png)

Après avoir sélectionné la liste de sujets, il est possible de choisir les paramètres à copier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/04-copy-settings-from-an-existing-topic-board.png)

### 3.1 **Copier les statuts et les types**

Activez le bouton radio Copier les statuts et les types pour obtenir les mêmes statuts avec leur nom de statut, couleur et type de métastatut dans la liste de sujets à créer.

### 3.2 **Copier les paramètres d'autorisation**

Activez le bouton radio Copier les paramètres d'autorisation pour obtenir les mêmes statuts avec leur couleur dans la liste de sujets à créer.

## 4. **Compatibilité BCF 1.0**

Les topic boards utilisés pour exporter des sujets vers d'autres outils de gestion de sujets qui ne supportent que BCF jusqu'à la version 1.0 doivent être verrouillés pour la compatibilité afin de s'assurer que les sujets générés dans Catenda arrivent sans erreur de l'autre côté. Les sujets BCF 1.0 générés ailleurs peuvent être importés dans n'importe quel topic board, que ce board soit verrouillé pour la compatibilité ou non.

### 4.1 **Pas de modification des statuts ou des types**

En verrouillant un topic board pour la compatibilité, il ne sera pas possible de modifier les statuts et les types disponibles dans le topic board. Tant que le topic board est verrouillé pour la compatibilité, les statuts et types prédéfinis tels que spécifiés dans BCF 1.0 sont rendus disponibles et ne peuvent pas être modifiés. _Statuts :_ "Ouvert" et "Fermé" _Types :_ "Erreur", "Avertissement", "Info" et "Inconnu"

### 4.2 **Verrouillage et déverrouillage de la compatibilité BCF 1.0 après la création**

La case de compatibilité BCF 1.0 peut être décochée dans les paramètres du topic board à tout moment pour augmenter le nombre de statuts possibles sur le board. Si les statuts d'un topic board ne sont pas compatibles avec BCF 1.0, il est également possible de supprimer tous les statuts incompatibles et de verrouiller à nouveau le board pour la compatibilité BCF 1.0 à tout moment après la création.

### 4.3 **Copier les paramètres à partir d'une liste verrouillée**

Si un topic board est sélectionné dans le menu Copier les paramètres à partir d'un autre topic board, la case de compatibilité BCF 1.0 est verrouillée et sera cochée ou non selon que le topic board sélectionné pour copier les paramètres est verrouillé pour la compatibilité BCF 1.0 ou non.

## 5. **Ajouter**

Cliquez sur Ajouter pour ajouter la nouvelle liste de sujets.

> **Remarque :** La liste de sujets doit avoir au moins un nom pour pouvoir être ajoutée

Il n'y a pas de notification lors de la création de la liste de sujets.

## 6. **Création de liste de sujets lors de la création d'un projet**

Lors de la création d'un nouveau projet, le projet commence par une liste de sujets par défaut appelée "Problèmes". Si la case à cocher pour les listes de sujets d'un projet modèle est cochée lors de la création du projet, le projet commence par les listes de sujets et les paramètres de la liste de sujets du projet modèle sélectionné.

> **Remarque :** Bien que les paramètres de ces nouvelles listes de sujets soient les mêmes que dans la liste de sujets des modèles, les GUID des listes de sujets, des statuts et des types sont uniques au projet dans lequel ils se trouvent.
