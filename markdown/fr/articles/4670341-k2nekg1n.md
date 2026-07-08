# Manuel d'export IFC Revit

Ce manuel d'export IFC a pour objectif de fournir à l'utilisateur un guide sur la façon d'exporter l'IFC à bon escient. Un fichier IFC peut rapidement devenir lourd et volumineux lorsque vous avez beaucoup d'informations à extraire du modèle. C'est pourquoi lors de l'export d'un IFC, vous devez décocher les informations inutiles. Lors du téléchargement d'un modèle vers Catenda, il n'est pas toujours nécessaire d'avoir beaucoup d'informations et un haut niveau de détail dans le modèle. Un peu plus tard dans ce manuel, nous reviendrons sur les paramètres que nous recommandons pour rendre le modèle un peu plus petit et un peu plus facile à utiliser. Ici, nous allons parcourir étape par étape la façon la plus appropriée d'exporter un IFC de Revit vers Catenda.

## 1. **Paramètres du projet**

Avant d'exporter, il est important de s'assurer que les GUID de votre projet Revit sont corrects.

`Gérer -> Paramètres -> Informations du projet -> Paramètres IFC`

![Informations du projet Paramètres IFC IfcSite GUID IfcBuilding GUID IfcProject GUID](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/01-project-settings.png)

Si le GUID est différent d'un export précédent, les objets des exports plus récents ne seront pas correctement liés aux GUID dans les thèmes BCF. Lorsque vous créez un nouveau projet, il aura un identifiant unique.

## 2. **Modifier l'export IFC**

Lorsque Revit est ouvert et que vous êtes prêt à exporter, vous pouvez effectuer les opérations suivantes.

![En haut à gauche de l'écran, appuyez sur fichier](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/02-modify-ifc-export.png)

En haut à gauche, nous trouvons l'onglet "Fichier".

---

> **Conseil :** **À retenir :** _Vous voudrez peut-être avoir un dossier dédié pour vos IFC, afin d'avoir toujours le contrôle de l'emplacement de votre fichier !_

Le menu d'export IFC se trouve ici :

`Fichier -> Exporter -> IFC`

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/03-modify-ifc-export.png)

Voici à quoi peut ressembler le menu Export IFC :

![Export IFC](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/04-modify-ifc-export.png)

Nom du fichier Entrez le nom et l'emplacement que le fichier exporté aura dans le système

Configuration d'export Choisissez parmi les configurations prédéfinies suivantes : \<Configuration en session> IFC 2x3 Vue de coordination 2.0 IFC 2x3 Vue de coordination IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Vue d'échange FM de base IFC 2x3 Vue de coordination IFC 2x3 COBie 2.4 Vue de livrable de conception IFC4 Vue de référence [Architecture] IFC4 Vue de référence [Structural] IFC4 Vue de référence [BuildingService] IFC4 Vue de référence [Non officielle] IFC4x3 IFC-SG Vue des exigences réglementaires

Lorsque le plugin Catenda pour Revit est utilisé, une configuration d'export prédéfinie supplémentaire pour utilisation avec Catenda est ajoutée à la liste des options.

## 3. **Modifier la configuration**

Cliquez sur Modifier la configuration dans la partie configuration d'export de la boîte de dialogue d'export ifc. C'est ici que les paramètres nécessaires pour les exports IFC peuvent être modifiés et que des configurations personnalisées peuvent être créées. Voici à quoi peut ressembler le menu de modification de la configuration :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/05-modify-setup.png)

Cette fenêtre contient les onglets suivants :

---

### 3.1 **Général**

![Général](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/06-general.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/07-general.png)

Nous allons vous guider à travers les différents paramètres.

**Version IFC** Sélection de la version IFC.

**Exigence d'échange** Ces options peuvent varier selon la version IFC sélectionnée. IFC 2x3 Coordination View 2.0

- Échange de référence architecturale
- Échange de référence MEP
- Échange de référence structurelle

**Mappage des catégories** Avant Revit 2026, cette option était disponible dans Fichier -> Exporter -> Options -> Options d'exportation IFC. Voici à quoi peut ressembler le menu Gérer les paramètres de mappage d'exportation IFC :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/08-general.png)

**Type de fichier** Sélection du type IFC.

**Phase à exporter** Si vous avez utilisé l'outil de phase dans Revit, vous pouvez ici choisir et exporter uniquement les nouvelles structures ou les structures existantes.

**Limites d'espaces** Il s'agit de savoir comment les informations sur les salles peuvent être utilisées ultérieurement. a. Niveau 1 - Exemple d'utilisation : Retraits quantitatifs, gestion, exploitation et maintenance (FDVU). b. Niveau 2 - Exemple d'utilisation : Analyse énergétique, analyse lumineuse.

**Type d'installation** Cette option n'est disponible que pour IFC 4x3 Choisir parmi les options suivantes : Pont (IfcBridge) Bâtiment (IfcBuilding) Installation maritime (IfcMarineFacility) Chemin de fer (IfcRailway) Route (IfcRoad)

**Diviser les murs, colonnes, conduits par niveau** Ici vous pouvez f. Par exemple, diviser les murs horizontalement s'ils sont modelés sur plusieurs étages.

_Informations d'en-tête de fichier... Adresse du projet..._ Ici vous pouvez mettre des informations sur qui a fourni l'IFC, l'adresse du projet, etc.

**Origine du projet** Origine du projet, nous la plaçons sur Coordonnées partagées actuelles - Coordonnées partagées actuelles.

> **Note :** Ceci a été déplacé vers Référence géographique à partir de Revit 2025

**Inclure les éléments en acier** Inclut les composants en acier s'ils sont modelés.

> **Note :** Ceci a été déplacé vers Contenu supplémentaire à partir de Revit 2025

---

### 3.2 **Contenu supplémentaire**

![Contenu supplémentaire](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/09-additional-content.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/10-additional-content.png)

Exporter les fichiers liés en tant que fichiers IFC séparés Si vous souhaitez inclure les fichiers liés dans l'IFC, vous pouvez cocher cette option. Il est recommandé d'exporter chaque fichier séparément et d'importer chacun dans son propre modèle.

Exporter uniquement les objets visibles visibles dans le fichier IFC de la vue.

- Exporter les salles, zones et espaces dans les vues 3D
  Cette option peut être utile pour sélectionner des zones dans la visionneuse 2D.

Inclure les éléments en acier, _remplis_

Exporte les éléments de plan 2D, _remplis, régions_ (rayures).

Exporter les grilles de plafond Les grilles de plafond sont des éléments 2D et ne sont donc pas affichées dans la visionneuse 3D de Catenda.

---

### 3.3 **Ensembles de propriétés**

![Ensembles de propriétés](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/11-property-sets.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/12-property-sets.png)

Exporte tous les ensembles de propriétés Revit (pset / propriétés) Voici un exemple d'un mur exporté avec cette option : Revit (_Gauche_) --- Catenda (_Droite_)

<img alt="Propriétés" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="Propriétés" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

Les propriétés typiques qui s'affichent dans le menu des propriétés sont : Contraintes, Définition de la section transversale, Dimensions, Structural, Données d'identité, Autre

Les propriétés typiques qui s'affichent dans le menu Identification sont : Paramètres IFC Exporter les propriétés IFC standard. Exporte les quantités calculées des objets. Listes d'exportation par lots Exporter un ensemble de propriétés unique

**Paramètres de classification** Voici un exemple de ce à quoi peuvent ressembler les paramètres de classification avec OmniClass.

![Paramètres de classification](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/13-property-sets.png)

**Nom** Le nom de la classification

**Source (Éditeur)** L'éditeur de la classification

**Édition** L'édition de la classification

**Date d'édition** La date de la classification

**Localisation de la documentation** Cela doit être un emplacement de documentation valide

**Nom du champ de classification** Le nom du champ de classification est le nom du paramètre dans vos objets qui contiendra la valeur de classification. Ce paramètre se trouve souvent au niveau de la famille. Modifiez une famille pour voir ses propriétés

![Modifier la famille](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/14-property-sets.png)

Voici à quoi peut ressembler le paramètre dans les propriétés

![Numéro OmniClass des propriétés](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/15-property-sets.png)

Si vous avez exporté votre ifc avec une classification et l'avez importé en tant que modèle dans Catenda, vous verrez sa classification suggérée comme une [bibliothèque suggérée](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) lors de la création d'une nouvelle bibliothèque sur la [page des bibliothèques](https://support.catenda.com/en/articles/8065645-libraries-page). Si une valeur dans la propriété que vous avez spécifiée correspond à une valeur dans la documentation fournie, elle sera trouvée et pourra être utilisée pour sélectionner des objets avec cette valeur via la bibliothèque de classification que vous avez créée.

---

### 3.4 **Niveau de détail**

![Niveau de détail](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/16-level-of-detail.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/17-level-of-detail.png)

Il s'agit de savoir à quel point nous avons de détails, par exemple. tasses, rampes ou peut-être roues de vélo. Il y a 4 niveaux de détail différents.

Très faible Faible Moyen Élevé

Lorsque le niveau est élevé, il devient le plus détaillé comme indiqué dans l'image ci-dessous.

![Niveau de détail très faible et élevé](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/18-level-of-detail.png)

---

Lors de l'exportation d'IFC à partir de Revit pour être utilisés dans Catenda Hub, nous recommandons de ne pas définir le niveau de détail sur élevé. Il y aura beaucoup de détails et de polygones supplémentaires dans les modèles exportés avec un niveau de détail plus élevé, ce qui n'est pas toujours nécessaire et ralentira la navigation du modèle. Ceci est un exemple de la différence entre l'exportation avec le paramètre Très faible et Élevé.

![Ceci est une rampe d'escalier exportée avec le paramètre Élevé. 900 000 polygones](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/19-level-of-detail.png)

![C'est le même modèle exporté avec le paramètre Très faible. 33 000 polygones.](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/20-level-of-detail.png)

L'apparence du modèle sera presque la même, mais le nombre de polygones diminuera considérablement et la navigation dans Catenda Hub sera beaucoup plus rapide.

---

### 3.5 **Avancé**

![Avancé](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/21-advanced.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/22-advanced.png)

**Exporter les pièces comme éléments de construction** Exporter les pièces comme élément IFC standard.

**Autoriser l'utilisation de la représentation mixte "Solid Model"** Sélectionnez cette option pour permettre le mélange de géométries BRep et d'extrusion pour une unité.

**Utiliser la vue active lors de la création de la géométrie** Sélectionnez cette option pour utiliser la vue active pour générer la géométrie. Notez que cela peut avoir des résultats inattendus s'il est utilisé sur une vue non 3D.

**Utiliser le nom de la famille et du type comme référence** Sélectionnez cette option pour utiliser les noms de famille et de type pour les références.

**Utiliser les limites de salle 2D pour le volume de salle** Sélectionnez cette option pour utiliser une approche simplifiée du calcul du volume de salle (basée sur l'extrusion de limites d'espace 2D), qui est également standard lors de l'exportation vers IFC 2x2.

**Inclure l'élévation IfcSite dans l'origine du positionnement local du site** Sélectionnez cette option pour inclure la hauteur du décalage Z pour la position locale dans IfcSite. Décochez l'option pour l'exclure.

**Stocker le GUID IFC dans un paramètre d'élément après l'exportation** Sélectionnez cette option pour enregistrer les GUID IFC générés dans le fichier de projet après l'exportation. Cela ajoutera des paramètres "GUID IFC" aux éléments et à leurs types ainsi que des informations de projet pour les guides de projet, de site Web et de bâtiment.

**Exporter la boîte englobante** Sélectionnez cette option pour exporter les représentations "Boîte englobante". Cette option reste automatiquement sélectionnée pour l'exportation GSA.

**Conserver la géométrie tessellée comme triangulation** Si vous avez des éléments courbes complexes ou des coques et qu'elles ne s'affichent pas correctement après l'exportation IFC, vous pouvez sélectionner cette option. Gardez à l'esprit que vous pourriez produire un fichier IFC très volumineux.

**Utiliser le nom du type uniquement pour le nom du type IFC** Sélectionnez cette option si vous souhaitez que l'ID BAT ou l'ID de l'objet apparaisse comme le nom de l'entité.

**Utiliser le nom Revit visible comme nom d'entité IFC** Sélectionnez cette option si vous souhaitez que le nom de l'objet Revit soit le nom de l'entité

**Toujours exporter les sols et toits facettés comme une seule entité IFC** Sélectionnez cette option pour combiner les faces des sols et des toits avec plusieurs faces en une seule entité.

**Définir l'utilisateur "Dernière modification" comme auteur dans les informations du projet** Sélectionnez cette option si vous êtes l'auteur des modifications de cette exportation

**Entités à exporter** Voici à quoi peut ressembler le menu Sélection d'entité IFC qui s'ouvre :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/23-advanced.png)

---

### 3.6 **Référence géographique**

Il est important que vos coordonnées Revit soient synchronisées avec les autres modèles de votre projet pour qu'ils se retrouvent au même endroit. Par conséquent, mesurez les coordonnées dans Catenda Hub avec une mesure de point et spécifiez une base de coordonnées dans Revit à un point qui se trouve au même endroit que le point mesuré dans Catenda Hub.

![Spécifier les coordonnées au point](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/24-geographic-reference.png)

Vous pouvez trouver cette option dans l'onglet Gérer -> Coordonnées -> Spécifier la base de coordonnées. _Spécifier les coordonnées au point_ Déplace un modèle et fait tourner le modèle vers le nord vrai en spécifiant les coordonnées pour Nord/Sud, Est/Ouest et Élévation. Dans Revit, il est souvent plus facile de modéliser selon des angles de 90 degrés et vous ne souhaitez pas faire tourner le modèle entier. Dans ce cas, vous pouvez faire tourner le nord vrai à la place. Vous trouverez l'option dans la liste déroulante Position sous Coordonnées dans l'onglet Gérer.

![Référence géographique](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/25-geographic-reference.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/26-geographic-reference.png)

**Site du projet** Interne

**Base de coordonnées** Vous pouvez modifier ce paramètre pour vous assurer que votre projet est orienté vers le nord Coordonnées partagées - Point d'arpentage par défaut Point de base du projet Origine interne Point de base du projet Orienté vers le nord vrai Origine interne Orientée vers le nord vrai

> **Note :** Si vous liez un IFC dans l'onglet Insérer, votre fichier lié sera placé près de vos objets et ne sera pas à l'emplacement décrit dans l'IFC. Pour importer un IFC au bon endroit, cliquez sur Fichier -> Ouvrir -> IFC à la place.

**Remplacer** Ici vous pouvez remplacer la référence du système de coordonnées projetée

---

### 3.7 **Informations sur l'entreprise**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/27-company-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/28-company-info.png)

Ce menu n'est disponible que lorsque la configuration IFC2x3 COBie 2.4 Design Deliverable View est sélectionnée dans le menu de gauche.

---

### 3.8 **Informations sur le projet**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/29-project-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/30-project-info.png)

Ce menu n'est disponible que lorsque la configuration IFC2x3 COBie 2.4 Design Deliverable View est sélectionnée dans le menu de gauche.

---

## 4. **Options IFC**

Les options IFC d'un projet Revit se trouvent dans :

`Fichier -> Exporter -> Options -> Options IFC`

![Exporter -> Options -> Options IFC](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/31-ifc-options.png)

> **Note :** À partir de Revit 2026, cette option est maintenant disponible dans : `Exporter -> IFC -> Général -> Mappage des catégories -> Menu Action à droite de la liste déroulante`

Dans les _Options IFC_, nous configurons les paramètres pour exporter un modèle vers un fichier IFC. Ici, vous pouvez personnaliser les propriétés de configuration pour exporter un modèle vers IFC. Ce qui a été mentionné au début de ce manuel, c'est qu'il n'est pas nécessaire de extraire trop d'informations du modèle. N'hésitez pas à décocher les informations inutiles avant l'exportation.

![Classes d'exportation IFC](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/32-ifc-options.png)

Il est possible de visualiser les grilles dans Catenda Hub, et si vous en avez dans votre modèle Revit, c'est dans les Options IFC que vous pouvez définir les grilles à exporter dans l'IFC. Par défaut, celles-ci ne sont pas exportées à partir de Revit.

## 5. **Couleurs et matériaux**

Les couleurs affichées dans Catenda sont lues à partir du fichier IFC qui est importé. Lorsque la propriété matériau d'une famille est ajoutée aux paramètres IFC, la couleur du matériau dans la propriété matériau est ajoutée à l'IFC et ainsi affichée dans Catenda. Dans Revit, les matériaux se trouvent dans le navigateur de matériaux :

`Onglet Gérer -> Section Paramètres -> Matériaux`
Dans le navigateur de matériaux, le paramètre de couleur se trouve dans l'onglet graphiques du matériau :

![Gérer -> Matériaux -> Navigateur de matériaux -> Créer un nouveau matériau](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/33-colors-and-materials.png)

Il est également possible de verrouiller l'ombrage sur les paramètres de rendu.

![Apparence](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/34-colors-and-materials.png)

Les surfaces de la visionneuse 3D de Catenda ont un ombrage plat sans source de lumière. Les valeurs suivantes sont interprétées par Catenda lors de l'affichage de la surface dans la visionneuse 3D :

Générique

- Couleur
- Dégradé d'image

Transparence

- Montant
- Dégradé d'image
- Translucidité

Teinte

- Couleur de teinte
