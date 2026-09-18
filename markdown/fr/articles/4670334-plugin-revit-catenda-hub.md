# Extension Catenda Revit

> **Remarque :** Le fichier d'installation du plugin se trouve dans [cet article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

L'extension Catenda Revit est une extension qui peut être installée pour Autodesk Revit. Avec cette extension, vous pourrez collaborer sur des points de vue 3D, des sujets et des documents avec les autres membres du projet de construction

## 1. **Installation**

Lorsque l'extension Catenda Revit est installée sur Windows, ses fichiers d'installation s'affichent dans le dossier suivant.

`C:\ProgramData\Autodesk\ApplicationPlugins\CatendaHub.bundle`

### 1.1 **Désinstallation**

Pour désinstaller l'extension, accédez au menu Windows suivant :

`Paramètres Windows -> Applications -> Applications installées`

Trouvez Catenda pour Autodesk® Revit® dans la liste et cliquez sur le menu d'actions sur le côté droit pour désinstaller.

## 2. **Ouverture de la fenêtre de l'extension**

Après l'installation, le panneau Catenda se trouve dans le ruban Compléments. En fonction de vos paramètres de ruban, le panneau Catenda peut ressembler à ceci :

**Ruban complet - Par défaut**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/01-opening-the-plugin-window.png)

**Boutons du panneau**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/02-opening-the-plugin-window.png)

**Titres du panneau**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/03-opening-the-plugin-window.png)

**Réduire aux onglets**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/04-opening-the-plugin-window.png)

### 2.1 **Sujets**

Cliquez sur Sujets pour ouvrir la fenêtre de l'extension Catenda sur la page des sujets. Si aucun utilisateur n'est connecté, la page de connexion s'affiche à la place.

### 2.2 **Charger l'IFC**

Cliquez sur Charger l'IFC pour ouvrir la fenêtre de l'extension Catenda sur la page de chargement IFC. Si aucun utilisateur n'est connecté, la page de connexion s'affiche à la place.

### 2.3 **Catenda**

Cliquez sur Catenda pour être redirigé vers [https://hub.catenda.com/](https://hub.catenda.com/) dans le navigateur système par défaut.

## 3. **Connexion**

Voici à quoi la fenêtre de l'extension peut ressembler lorsqu'elle est ancrée sur la droite :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/05-signing-in.png)

Connectez-vous avec votre adresse e-mail et votre mot de passe Catenda.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-703202eeb52b.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3e163e70c122.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3b6b4eaa010e.png" width="180"/>

Si l'authentification multifacteur est activée pour votre compte, vous serez invité à entrer votre code MFA. Cliquez [ici](https://support.catenda.com/en/articles/7891486-sign-in-page) pour en savoir plus sur la page de connexion.

Cliquez sur « Autoriser l'accès » pour permettre à l'extension Revit pour Bimsync Arena d'accéder à votre compte Catenda Hub.

### 3.1 **Révoquer l'accès**

L'accès à votre compte Catenda Hub peut être révoqué à tout moment en accédant à votre [page d'application](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) Catenda Hub et en cliquant sur « Révoquer l'accès » à côté de « Extension Revit pour Bimsync Arena ».

## 4. **Liste des sujets**

Après la connexion, la vue principale de l'extension Catenda Hub s'ouvre. Sur cette page, vous trouverez le menu principal pour naviguer dans votre projet Catenda Hub, les listes de sujets et les sujets.

### 4.1 **Interface**

![Header.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/06-interface.png)

1. Sélectionnez votre projet Catenda Hub
1. Sélectionnez une liste de sujets dans ce projet
1. Créer un nouveau sujet dans la liste de sujets actuellement sélectionnée
1. Trier les sujets actuellement affichés
1. Ouvrir le menu de l'extension Catenda Hub
1. Rechercher et filtrer les sujets affichés
1. La liste des sujets actuellement filtrés dans la liste de sujets

### 4.2 **Sélection du projet et de la liste de sujets**

La sélection d'un projet Catenda Hub affichera la liste des listes de sujets dans ce projet, vous permettant d'en sélectionner une pour afficher les sujets correspondants. Elle enregistrera également le projet Catenda Hub et la liste de sujets dans votre modèle Revit et les ouvrira automatiquement la prochaine fois que vous ouvrirez ce modèle.

![ProjectInfo.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/07-project-and-topic-board-selection.png)

### 4.3 **Actions**

Les actions de l'extension se trouvent en haut à droite :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/08-actions.png)

Cliquez [ici](https://support.catenda.com/en/articles/13168755-actions-in-the-catenda-revit-plugin) pour en savoir plus sur les différentes actions de l'extension Catenda Revit.

### 4.4 **Sélection de sujet**

Dans la liste des sujets, vous trouverez toutes les informations principales sur un sujet :

![IssueInformation.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/09-topic-selection.png)

1. Le titre du sujet
1. Son statut (Ouvert, Fermé, ...), son type (Info, Erreur, ...) et ses étiquettes
1. Le membre qui demande le sujet
1. Le membre auquel le sujet est assigné
1. La date d'échéance du sujet
1. Quand le sujet a été mis à jour pour la dernière fois. Vous pouvez survoler la date pour afficher la date et l'heure complètes de la mise à jour.
1. Le nombre de commentaires dans le sujet
1. L'image du premier commentaire du sujet
1. Numéro de sujet Catenda Hub

Vous pouvez cliquer sur n'importe quel sujet pour accéder à la [page de détails du sujet](#h_445d3efa52).

### 4.5 **Trier les sujets**

Vous pouvez trier les sujets affichés pour apporter les plus pertinents en premier.

![sort.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/10-sort-topics.png)

1. Afficher en premier le sujet créé le plus récemment
1. Afficher en premier le sujet le plus ancien
1. Afficher en premier le sujet mis à jour le plus récemment. La mise à jour d'un sujet peut impliquer la modification de l'une de ses propriétés, titre, commentaires, …
1. Afficher en premier le sujet mis à jour le moins récemment
1. Afficher en premier la date d'échéance la plus récente
1. Afficher en premier la date d'échéance la plus ancienne

### 4.6 **Filtrer les sujets**

À l'aide de la barre de filtres, vous pouvez combiner n'importe quel type de filtre pour afficher uniquement les sujets les plus pertinents.

Les filtres actuels s'affichent sous forme de petits jetons dans la barre de filtres. Ici, seuls les sujets avec le statut « Ouvert » s'affichent. Cliquez dans la barre de filtres pour afficher tous les filtres disponibles (1).

![AvailableFilters.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/11-filter-topics.png)

Sur la gauche (2) se trouve le nom du filtre, chaque filtre appartient à un type affiché sur la droite (3).

Les types de filtres disponibles incluent :

- Demandé par : Obtenir tous les sujets demandés par un utilisateur donné
- Assigné à : Obtenir tous les sujets assignés à un utilisateur donné
- Date d'échéance : Obtenir tous les sujets en retard ou dont la date d'échéance est dans moins d'un mois, deux semaines, une semaine ou un jour
- Statut : Obtenir tous les sujets d'un statut donné (Ouvert, Fermé, ...)
- Type : Obtenir tous les sujets d'un type donné (Erreur, Avertissement, Info, ...)
- Étiquette : Obtenir tous les sujets avec une étiquette donnée
- Mes sujets : Obtenir tous les sujets qui vous sont assignés ou que vous avez demandés

Vous pouvez rechercher ces filtres en tapant du texte dans la barre de filtres (1). Vous pouvez également utiliser ceci pour créer un filtre de texte pour rechercher un texte spécifique dans le titre ou la description du sujet (2).

![TextFilter.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/12-filter-topics.png)

## 5. **Détails du sujet**

Dans cette vue, vous pouvez examiner et modifier un sujet spécifique.

### 5.1 **Interface**

![IssueDetailView.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/13-interface.png)

1. Retourner à la [Liste des sujets](#h_642fa61854)
1. Actualiser le contenu de ce sujet
1. Naviguer entre les sujets
1. Définir le statut du sujet (Ouvert, Fermé, ...)
1. Définir le type de sujet (Erreur, Avertissement, Info, ...)
1. Définir la date d'échéance du sujet
1. Définir le membre assigné au sujet. Vous pouvez assigner un sujet à un utilisateur individuel ou à une équipe.
1. Définir le membre qui demande ce sujet. Vous pouvez définir un utilisateur individuel ou une équipe.
1. Modifier les étiquettes du sujet
1. La liste des commentaires du sujet

### 5.2 **Propriétés du sujet**

Vous pouvez modifier n'importe quelle propriété du sujet : Statut, type, assignataire, demandeur, date d'échéance, étiquettes. Chaque menu affichera une liste des propriétés disponibles. Cependant, vous ne pouvez pas créer directement un nouveau statut, type ou étiquette dans l'extension, vous devrez utiliser l'interface web de Catenda Hub pour le faire.

Vous pouvez cliquer sur le titre pour le modifier :

![editTitle.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/14-topic-properties.gif)

Vous pouvez cliquer sur l'icône en forme de stylo pour modifier la description :

![editDescription.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/15-topic-properties.gif)

Vous pouvez également taper du texte dans la barre d'étiquettes pour filtrer la liste des filtres :

![editLabels.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/16-topic-properties.gif)

### 5.3 **Commentaires**

Tous les commentaires s'affichent sous le sujet. Un commentaire peut contenir du texte, une image, une capture de votre vue Revit actuelle ou un point de vue.

![CommentDetail.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/17-comments.png)

1. L'auteur du commentaire
1. Quand le commentaire a été créé. Vous pouvez survoler la date pour afficher la date et l'heure complètes de la mise à jour.
1. Le [bouton de zoom](#h_d873968c27) (voir le chapitre ci-dessous)
1. L'image associée au commentaire
1. Le texte du commentaire

### 5.4 **Zoom**

Si le commentaire contient un point de vue, vous pouvez effectuer un zoom sur ce point de vue. Le zoom créera une nouvelle vue 3D dans votre modèle Revit centrée sur le même point de vue.

![zoom.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/18-zoom.gif)

Pour que le point de vue soit pertinent, vous devez avoir ouvert le même modèle que celui où le commentaire a été créé. L'extension suppose que des coordonnées partagées ont été utilisées lors de l'exportation du modèle en IFC.

Si le point de vue a été créé à partir d'une vue en perspective, la nouvelle vue 3D aura son mode de projection défini sur « Perspective ». Sinon, le mode de projection sera « Orthographique ».

L'extension créera une seule vue en perspective et une seule vue orthographique. Après les avoir créées, elle les réutilisera pour tout usage ultérieur de la fonction de zoom. Vous pouvez modifier cela dans le [menu des paramètres](#h_b02502c589). Vous pouvez également utiliser le menu des paramètres pour modifier le nom de ces vues.

### 5.5 **Éléments associés**

Si le sujet contient des éléments associés, l'extension les sélectionnera dans Revit lorsque vous effectuez un zoom sur un point de vue.

![relatedElements.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/19-related-elements.gif)

Pour que cette fonction fonctionne, votre modèle Revit doit avoir été exporté en IFC avec l'option « Enregistrer le GUID IFC dans un paramètre d'élément après l'exportation ». Cela ajoute le paramètre IFCGuid sur chaque objet, permettant à l'extension de sélectionner les éléments associés.

### 5.6 **Ajouter un commentaire**

Vous pouvez ajouter des commentaires à un sujet en écrivant dans la zone de texte et en cliquant sur Soumettre.

Vous pouvez également ajouter une image à partir de votre ordinateur en cliquant sur le bouton « Plus ». Vous pouvez annoter cette image en cliquant sur l'aperçu de l'image après l'avoir sélectionnée.

![createComment.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/20-add-comment.gif)

### 5.7 **Ajouter une capture 3D**

Vous pouvez également ajouter votre vue Revit actuelle en tant que point de vue et une capture jointe à votre commentaire. Comme n'importe quelle image, vous pouvez annoter la capture en cliquant sur l'aperçu de l'image.

Si le paramètre IFCGUID est présent, les éléments sélectionnés dans Revit seront ajoutés à votre sujet en tant qu'éléments associés.
