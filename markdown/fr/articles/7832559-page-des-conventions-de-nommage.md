# Page des conventions de nommage

Les administrateurs pourront trouver la page des conventions de nommage comme une sous-page des [paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/01-intro.png)

## 1. **Nommage des fichiers locaux**

Avec les conventions de nommage, vous pouvez limiter les fichiers téléchargés dans un dossier en fonction du nom du fichier d'origine. Ceci est très utile si vous disposez déjà d'un ensemble de règles pour le nommage de vos fichiers locaux. Vous ne devriez pas avoir besoin de renommer vos fichiers pour les télécharger dans Catenda Hub. Si vous n'avez pas de règles pour le nommage de vos fichiers locaux, la convention de nommage n'est pas recommandée.

## 2. **Documents, révisions et fichiers d'origine**

Avant de commencer, il est important de comprendre la différence entre un **Document** Catenda Hub et un **fichier**. Vous pouvez considérer un Document (et les révisions de Documents) dans Catenda Hub comme des _conteneurs de fichiers_. Vous pouvez télécharger un fichier dans ce conteneur et, si vous êtes administrateur, modifier son nom. Les noms de fichiers sont souvent très différents les uns des autres même s'il s'agit de la même version du dessin ou de la feuille que vous souhaitez télécharger. La convention de nommage vous permet de télécharger des fichiers similaires vers le même Document selon un ensemble de règles dans le nom du fichier.

## 3. **Nouvelle convention de nommage**

En haut à droite de la page, vous verrez le bouton Nouvelle convention de nommage.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/02-new-naming-convention.png)

Voici à quoi ressemble une nouvelle convention de nommage.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/03-new-naming-convention.png)

### 3.1 **Informations de convention**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/04-convention-information.png)

**Nom** Le nom de la convention tel qu'il apparaîtra lors de son application dans les paramètres des Documents

**Description** La description de la convention telle qu'elle apparaîtra dans les paramètres des Documents

**Séparateur** Le caractère séparant chaque bloc à l'exception du bloc d'extension de fichier.

### 3.2 **Aperçus**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/05-previews.png)

Les aperçus affichent le modèle que les conventions suivent à la fois dans votre système de fichiers local et dans la structure des Documents de Catenda Hub. Ces derniers peuvent être différents et l'un peut être mappé à l'autre comme vous le verrez

**Nom du Document** La façon dont le Document dans Catenda Hub apparaîtra lorsque le fichier sera téléchargé

**Nom de fichier attendu** La façon dont les fichiers autorisés à être téléchargés sont censés ressembler

### 3.3 **Types d'aperçu**

Lorsque vous survolez les différents types d'aperçu, vous verrez une explication détaillée de ce que chaque aperçu signifie. _Texte - Longueur variable:_ {X} _Texte - Longueur fixe:_ XXXX _Champ personnalisé:_ {Nom du champ personnalisé} _Séparateur:_ Lorsque vous avez trois blocs ou plus, vous verrez le séparateur que vous avez défini

### 3.4 **Blocs**

La convention de nommage se compose d'une série de blocs. Chaque bloc représente une partie du nom du fichier/Document. Cliquez sur Ajouter un bloc pour ajouter un nouveau bloc.

![Ajouter un bloc](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/06-blocks.png)

Une convention a toujours au moins deux blocs: 1\. Le nom du fichier/Document. 2\. Le nom de l'extension du fichier/Document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/07-blocks.png)

**Nom** Le nom du bloc dans la configuration de la convention de nommage afin que vous puissiez les distinguer

**Description** Ici, vous pouvez taper une description de ce que vous attendez de ce bloc

**Identifiant de Document** Si vous attendez une partie du nom de fichier que vous ne souhaitez pas voir dans Catenda Hub, vous pouvez désactiver l'identifiant de Document. Cette partie du nom de fichier sera toujours utilisée pour accepter les fichiers mais ne sera pas visible dans le Document Catenda Hub résultant.

**Activé** Lorsque l'identifiant de Document est activé, ce bloc identifie le nom du Document

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/08-blocks.png)

**Désactivé** Lorsque l'identifiant de Document est désactivé, ce bloc identifie le nom du fichier local.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/09-blocks.png)

**Désactivé** L'identifiant de Document du bloc d'extension est toujours désactivé car chaque fichier a une extension.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/10-blocks.png)

**Source** Qu'est-ce qui qualifiera l'identification du nom du fichier/Document? _Défaut:_ Texte - Ce bloc peut contenir n'importe quel caractère _Champ personnalisé:_ - Limitez les types de caractères que votre bloc accepte avec les champs personnalisés

**Longueur** Combien de caractères peuvent être dans ce bloc. Si ce champ est laissé vide, le bloc aura une longueur variable.

### 3.5 **Soumettre une convention**

![Annuler Soumettre la convention de nommage](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/11-br-submitting-a-convention.png)

Après soumission d'une convention de nommage, elle peut être [activée par dossier](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) dans les [paramètres des Documents](https://support.catenda.com/en/articles/7831371-document-settings).
