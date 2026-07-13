# Plugin Catenda Revit

> **Remarque :** Le fichier d'installation du plugin se trouve dans [cet article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Le plugin Catenda Revit est un plugin qui peut être installé pour Autodesk Revit. Avec ce plugin, vous pourrez collaborer sur des viewpoints 3D, des topics et des Documents avec les autres Membres du projet de construction.

Les topics suivants sont décrits dans cet article :

## 1. **Installation**

Lorsque le plugin Catenda Revit est installé sur Windows, ses fichiers d'installation apparaîtront dans le dossier suivant.

`C:\ProgramData\Autodesk\ApplicationPlugins\CatendaHub.bundle`

### 1.1 **Désinstallation**

Pour désinstaller le plugin, accédez au menu Windows suivant :

`Paramètres Windows -> Applications -> Applications installées`

Trouvez Catenda pour Autodesk® Revit® dans la liste et cliquez sur le menu d'action sur le côté droit pour désinstaller.

## 2. **Ouverture de la fenêtre du plugin**

Après l'installation, le panneau Catenda se trouve dans le ruban Compléments. Selon vos paramètres de ruban, le panneau Catenda peut ressembler à ceci :

**Ruban complet - Par défaut**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/01-opening-the-plugin-window.png)

**Boutons du panneau**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/02-opening-the-plugin-window.png)

**Titres du panneau**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/03-opening-the-plugin-window.png)

**Réduire en onglets**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/04-opening-the-plugin-window.png)

### 2.1 **Topics**

Cliquez sur Topics pour ouvrir la fenêtre du plugin Catenda vers la page des topics. Si aucun utilisateur n'est connecté, la page de connexion s'affiche à la place.

### 2.2 **Télécharger IFC**

Cliquez sur Télécharger IFC pour ouvrir la fenêtre du plugin Catenda vers la page de téléchargement IFC. Si aucun utilisateur n'est connecté, la page de connexion s'affiche à la place.

### 2.3 **Catenda**

Cliquez sur Catenda pour être redirigé vers [https://hub.catenda.com/](https://hub.catenda.com/) dans le navigateur système par défaut.

## 3. **Connexion**

Voici ce à quoi peut ressembler la fenêtre du plugin lorsqu'elle est ancrée à droite :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/05-signing-in.png)

Connectez-vous avec votre adresse e-mail et votre mot de passe Catenda.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-703202eeb52b.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3e163e70c122.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3b6b4eaa010e.png" width="180"/>

Si l'authentification multifacteur est activée pour votre compte, vous devrez entrer votre code MFA. Cliquez [ici](https://support.catenda.com/en/articles/7891486-sign-in-page) pour en savoir plus sur la page de connexion.

Cliquez sur « Autoriser l'accès » pour permettre au plugin Revit pour Bimsync Arena d'accéder à votre compte Catenda Hub.

### 3.1 **Révoquer l'accès**

L'accès à votre compte Catenda Hub peut être révoqué à tout moment en accédant à votre [page application](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) Catenda Hub et en cliquant sur « Révoquer l'accès » à proximité du « Plugin Revit pour Bimsync Arena ».

## 4. **Liste des Topics**

Après la connexion, la vue principale du plugin Catenda Hub s'ouvre. Sur cette page, se trouve le menu principal pour naviguer dans votre projet Catenda Hub, les topic boards et les topics.

Les topics suivants sont décrits dans cette section :

### 4.1 **Interface**

![Header.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/06-interface.png)

1. Sélectionnez votre projet Catenda Hub
2. Sélectionnez un topic board dans ce projet
3. Créez un nouveau topic dans le topic board actuellement sélectionné
4. Triez les topics actuellement affichés
5. Ouvrez le menu du complément Catenda Hub
6. Recherchez et filtrez les topics affichés
7. La liste des topics actuellement filtrés dans le topic board

### 4.2 **Sélection du projet et du topic board**

La sélection d'un projet Catenda Hub affichera la liste des topic boards dans ce projet, ce qui vous permettra d'en sélectionner un pour afficher les topics correspondants. Il enregistrera également le projet Catenda Hub et le topic board dans votre modèle Revit et les ouvrira automatiquement la prochaine fois que vous ouvrirez ce modèle.

![ProjectInfo.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/07-project-and-topic-board-selection.png)

### 4.3 **Actions**

Les actions du plugin se trouvent vers le haut à droite :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/08-actions.png)

Cliquez [ici](https://support.catenda.com/en/articles/13168755-actions-in-the-catenda-revit-plugin) pour en savoir plus sur les différentes actions du plugin Catenda Revit.

### 4.4 **Sélection du topic**

Dans la liste des topics, vous trouverez toutes les informations principales sur un topic :

![IssueInformation.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/09-topic-selection.png)

1. Le titre du topic
2. Son Statut (Ouvert, Fermé, …), son type (Info, Erreur, …) et ses Étiquettes
3. Le Membre qui a demandé le topic
4. Le Membre auquel le topic est Assigné à
5. L'Echéance du topic
6. Quand le topic a été mis à jour pour la dernière fois. Vous pouvez passer la souris sur la date pour afficher la date et l'heure complètes de la mise à jour.
7. Le nombre de commentaires dans le topic
8. L'image du premier commentaire dans le topic
9. Numéro du topic Catenda Hub

Vous pouvez cliquer sur n'importe quel topic pour accéder à la [page de détails du topic](#topic-details).

### 4.5 **Trier les topics**

Vous pouvez trier les topics affichés pour vous montrer les plus pertinents en premier.

![sort.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/10-sort-topics.png)

1. Affiche le topic créé le plus récemment en premier
2. Affiche le topic le plus ancien en premier
3. Affiche le topic mis à jour le plus récemment en premier. La mise à jour d'un topic peut impliquer de modifier l'une de ces propriétés, titre, commentaires, …
4. Affiche le topic mis à jour le moins récemment en premier
5. Affiche l'Echéance la plus proche en premier
6. Affiche l'Echéance la plus ancienne en premier

### 4.6 **Filtrer les topics**

En utilisant la barre de Filtres, vous pouvez combiner n'importe quel type de filtre pour afficher uniquement les topics les plus pertinents.

Les Filtres actuels s'affichent sous forme de petites puces dans la barre de Filtres. Ici, seuls les topics avec le Statut « Ouvert » sont affichés. Cliquez dans la barre de Filtres pour afficher tous les Filtres disponibles (1).

![AvailableFilters.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/11-filter-topics.png)

Sur la gauche (2) se trouve le nom du filtre, chaque filtre appartient à un type affiché sur la droite (3).

Les types de Filtres disponibles incluent :

- Demandé par : Obtient tous les topics demandés par un utilisateur donné
- Assigné à : Obtient tous les topics assignés à un utilisateur donné
- Echéance : Obtient tous les topics en retard ou dont l'Echéance est inférieure à un mois, deux semaines, une semaine ou un jour
- Statut : Obtient tous les topics d'un Statut donné (Ouvert, Fermé, …)
- Type : Obtient tous les topics d'un type donné (Erreur, Avertissement, Info, …)
- Étiquette : Obtient tous les topics avec une Étiquette donnée
- Mes topics : Obtient tous les topics assignés ou demandés par vous-même

Vous pouvez rechercher ces Filtres en tapant du texte dans la barre de Filtres (1). Vous pouvez également l'utiliser pour créer un filtre de texte afin de rechercher un texte spécifique dans le titre ou la description du topic (2).

![TextFilter.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/12-filter-topics.png)

## 5. **Détails du Topic**

Dans cette vue, vous pouvez consulter et modifier un topic spécifique.

Les topics suivants sont décrits dans cette section :

### 5.1 **Interface**

![IssueDetailView.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/13-interface.png)

1. Retournez à la [Liste des Topics](#topic-list)
2. Actualiser le contenu de ce topic
3. Naviguer entre les topics
4. Définir le Statut du topic (Ouvert, Fermé, …)
5. Définir le type du topic (Erreur, Avertissement, Info, …)
6. Définir l'Echéance du topic
7. Définir le Membre assigné au topic. Vous pouvez assigner un topic à un utilisateur individuel ou à une Équipe.
8. Définir le Membre demandant ce topic. Vous pouvez définir un utilisateur individuel ou une Équipe.
9. Modifier les Étiquettes du topic
10. La liste des commentaires du topic

### 5.2 **Propriétés du topic**

Vous pouvez modifier n'importe quelle propriété du topic : Statut, type, assigné, demandeur, Echéance, Étiquettes. Chaque menu affichera une liste des propriétés disponibles. Cependant, vous ne pouvez pas créer directement un nouveau Statut, type ou Étiquette dans le plugin, vous devrez utiliser l'interface web de Catenda Hub pour cela.

Vous pouvez cliquer sur le titre pour le modifier :

![editTitle.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/14-topic-properties.gif)

Vous pouvez cliquer sur l'icône du stylo pour modifier la description :

![editDescription.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/15-topic-properties.gif)

Vous pouvez également taper du texte dans la barre d'Étiquettes pour filtrer la liste des Filtres :

![editLabels.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/16-topic-properties.gif)

### 5.3 **Commentaires**

Tous les commentaires sont affichés ci-dessous le topic. Un commentaire peut contenir du texte, une image, une Capture de votre vue Revit actuelle ou un viewpoint.

![CommentDetail.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/17-comments.png)

1. L'auteur du commentaire
2. Quand le commentaire a été créé. Vous pouvez passer la souris sur la date pour afficher la date et l'heure complètes de la mise à jour.
3. Le [bouton zoom](#zoom) (voir le chapitre ci-dessous)
4. L'image associée au commentaire
5. Le texte du commentaire

### 5.4 **Zoom**

Si le commentaire contient un viewpoint, vous pouvez zoomer sur ce viewpoint. Zoomer créera une nouvelle vue 3D dans votre modèle Revit concentrée sur le même viewpoint.

![zoom.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/18-zoom.gif)

Pour que le viewpoint soit pertinent, vous devez avoir ouvert le même modèle que celui dans lequel le commentaire a été créé. Le plugin suppose que les coordonnées partagées ont été utilisées lors de l'export du modèle en IFC.

Si le viewpoint a été créé à partir d'une vue en perspective, la nouvelle vue 3D aura son mode de projection défini sur « Perspective ». Sinon, le mode de projection sera « Orthographique ».

Le complément créera une seule vue en perspective et une vue orthographique. Après les avoir créées, il les réutilisera pour toute utilisation ultérieure de la fonction de zoom. Vous pouvez le modifier dans le menu des paramètres. Vous pouvez également utiliser le menu des paramètres pour modifier le nom de ces vues.

### 5.5 **Éléments liés**

Si le topic contient des éléments liés, le complément les sélectionnera dans Revit lorsque vous zoomerez vers un viewpoint.

![relatedElements.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/19-related-elements.gif)

Pour que cette fonction fonctionne, votre modèle Revit doit avoir été exporté en IFC avec l'option « Stocker le GUID IFC dans un paramètre d'élément après l'export ». Cela ajoute le paramètre IFCGuid sur chaque objet, permettant au plugin de sélectionner les éléments liés.

### 5.6 **Ajouter un commentaire**

Vous pouvez ajouter des commentaires à un topic en écrivant dans la zone de texte et en cliquant sur Soumettre.

Vous pouvez également ajouter une image de votre ordinateur en cliquant sur le bouton « Plus ». Vous pouvez annoter cette image en cliquant sur l'image d'aperçu après l'avoir sélectionnée.

![createComment.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/20-add-comment.gif)

### 5.7 **Ajouter une Capture 3D**

Vous pouvez également ajouter votre vue Revit actuelle comme viewpoint et une Capture jointe à votre commentaire. Tout comme n'importe quelle image, vous pouvez annoter la Capture en cliquant sur l'image d'aperçu.

Si le paramètre IFCGUID est présent, les éléments sélectionnés dans Revit seront ajoutés à votre topic en tant qu'éléments liés.
