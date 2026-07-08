# Extension Catenda Navisworks

> **Remarque :** Le fichier d'installation de l'extension se trouve dans [cet article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

L'extension Catenda Navisworks est une extension qui peut être installée pour Nemetchek Archicad. Avec cette extension, vous pourrez collaborer sur les points de vue 3D, les rubriques et les documents avec les autres Membres du projet de construction.

## 1. **À propos de l'extension**

Le complément Catenda Hub pour Autodesk® Navisworks® est l'outil idéal pour les projets collaborant dans Catenda Hub. Tous vos sujets sont synchronisés en temps réel entre Navisworks et Catenda Hub, ce qui vous permet de créer, d'accéder, de partager et de communiquer les sujets. Le format de la rubrique est BCF afin que les rubriques puissent être partagées sur n'importe quel logiciel ou plateforme BIM compatible BCF. Ce complément vous permet de visualiser, créer et modifier les rubriques de manière transparente dans Navisworks. Vous pouvez également télécharger et fédérer le modèle IFC stocké dans Catenda Hub sur votre client local.

### 1.1 **Les fonctionnalités incluent :**

- Accès à tous vos projets Catenda
- Filtres et gestion des rubriques dans les tableaux de rubriques
- Créer de nouvelles rubriques directement à partir de Navis Works
- Localiser les rubriques dans votre modèle Navisworks
- Créer une nouvelle vue 3D pour chaque commentaire
- Créer des rubriques BCF à partir des interférences trouvées à l'aide de Clash Detective
- Affecter les rubriques à d'autres Membres du projet
- Modifier le Statut de la rubrique et d'autres propriétés

## 2. **Collaboration basée sur le cloud**

Catenda Hub donne vie à vos données de construction sur une plateforme de collaboration basée sur le cloud couvrant l'ensemble du cycle de vie du bâtiment. Catenda gère vos informations de projet du début à la livraison et au-delà, garantissant la conservation des données et des connaissances dans toutes les phases du projet.

## 3. **Normes ouvertes**

Catenda Hub est un outil de collaboration BIM avec support pour toutes les normes buildingSMART (IFC, bSDD, BCF). Il est livré avec une gamme d'API pour une implémentation facile dans votre propre logiciel.

[Vidéo YouTube](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **Installation**

Lorsque l'extension Catenda Navisworks est installée sur Windows, ses fichiers d'installation apparaissent dans le dossier suivant.

`C:\\ProgramData\\Autodesk\\ApplicationPlugins\\Catenda.BCF.bundle`

Les paramètres configurés dans l'extension se trouvent ici :

`C:\\Users\\\<Username>\\AppData\\Local\\Autodesk\_Inc\\Roamer.exe\_Url\_\<GUID>\\\<Version>`

### 4.1 **Désinstallation**

Pour désinstaller l'extension, accédez au menu Windows suivant :

`Paramètres Windows -> Applications -> Applications installées`

Trouvez l'extension Catenda Navisworks BCF version \<version> dans la liste et cliquez sur le menu d'action du côté droit pour désinstaller.

## 5. **Onglet Catenda**

Après avoir installé l'extension, l'onglet Catenda apparaîtra. Navisworks devra peut-être être redémarré pour que l'onglet apparaisse. Sur la page d'accueil de Navisworks, l'onglet sera initialement grisé.

Démarrez un nouveau projet ou ouvrez un projet Navisworks pour commencer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

Voici à quoi ressemble l'onglet Catenda lorsqu'il est sélectionné

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### 5.1 **Catenda**

Le bouton Catenda dans le menu Extensions Catenda de l'onglet Catenda ouvrira le navigateur par défaut avec la [page de connexion](https://support.catenda.com/en/articles/7891486-sign-in-page) de Catenda Hub.

### 5.2 **Extension BCF**

Le bouton Extension BCF dans le menu Extensions Catenda de l'onglet Catenda ouvrira l'extension Catenda Navisworks avec le menu paramètres activé. Le menu paramètres de l'extension Catenda Navisworks peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

**Ancrage de l'extension** Faites glisser la barre de titre de la fenêtre vers l'un des côtés de l'application pour l'ancrer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

Voici à quoi ressemble l'application lorsqu'elle est ancrée à droite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **Paramètres**

Voici à quoi peut ressembler le menu paramètres après avoir cliqué sur Connexion en haut à gauche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

Sur le côté gauche, la page de connexion de Catenda s'affiche. Suivez les étapes décrites dans l'[article connexion](https://support.catenda.com/en/articles/7891486-sign-in-page) pour vous connecter.

Voici à quoi peut ressembler le menu paramètres après s'être connecté avec succès.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

Si la session de connexion a expiré, le bouton actualiser peut être utilisé pour actualiser la session de connexion.

### 6.1 **Authentification**

**Jeton** Ici, vous verrez votre jeton d'authentification Catenda après vous être connecté.

### 6.2 **IFCGuid**

**Catégorie et propriété** Catégorie par défaut : Élément Propriété par défaut : IfcGUID

**Mappage des propriétés** L'extension Catenda Navisworks attache les objets aux points de vue dans les rubriques en fonction du GUID du IfcProject dans l'IFC. Dans Navisworks, ce GUID se trouve dans les propriétés de l'objet. Voici un exemple avec un objet sélectionné :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

Selon le contenu de votre IFC, le GUID IfcProject peut se trouver dans une ou plusieurs autres propriétés ou catégories. Particulièrement si Navisworks a été lancé avec un paramètre de langue autre que l'anglais, le nom de la catégorie Élément sera le mot Élément dans cette langue, tandis que le mot par défaut est toujours l'anglais dans l'extension Catenda Navisworks. Pour résoudre ce problème, changez la Catégorie en le mot Élément dans la langue dans laquelle Navisworks est lancé.

2ème, 3ème, 4ème Catégorie et Propriété S'il existe plusieurs catégories et propriétés qui pourraient inclure le GUID IfcProject, elles peuvent également être ajoutées.

### 6.3 **Chemins**

**Chemin de téléchargement** L'emplacement du fichier où les modèles et les Documents téléchargés via l'extension se retrouvent.

### 6.4 **Captures**

**Positionnement** Droite - par défaut Les captures sont affichées à droite

Au-dessous Les captures s'affichent au-dessous

## 7. **Tableaux de rubriques**

Dans le menu Tableaux de rubriques, un aperçu des rubriques dans les tableaux de rubriques de différents projets peut être vu. Voici à quoi peut ressembler le menu Tableaux de rubriques.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

Cliquez sur l'onglet projets pour charger la liste des tableaux de rubriques dans ce projet dans l'onglet tableaux de rubriques.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **Nouvelle rubrique**

Cliquez sur le bouton Nouvelle rubrique pour créer une nouvelle rubrique.

## 8. **Rubrique**

Dans le menu rubrique, les rubriques sélectionnées peuvent être modifiées et les nouvelles rubriques peuvent être soumises. Voici à quoi peut ressembler le menu rubrique :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### 8.1 **Flèches de navigation**

Utilisez les flèches de navigation dans le menu pour vous déplacer entre les différentes rubriques du tableau de rubriques.

### 8.2 **Nouvelle rubrique**

Créer une nouvelle rubrique

### 8.3 **Ajouter un point de vue**

Ajouter un point de vue de la position de caméra actuelle à la rubrique actuelle.

### 8.4 **Mettre à jour**

Mettre à jour la rubrique sur Catenda avec les informations qui ont été ajoutées dans l'extension.

### 8.5 **Numéro de rubrique**

Le numéro de la rubrique dans le projet.

### 8.6 **Actualiser**

Charger les dernières informations de la rubrique à partir de Catenda.

### 8.7 **Effacer les plans de coupe**

Cliquez sur le bouton Effacer les plans de coupe pour effacer les plans de coupe dans la Visionneuse.

## 9. **Interférences**

Dans le menu interférences, les rubriques peuvent être soumises en résultat des résultats de Clash Detective. Voici à quoi peut ressembler le menu interférences.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### 9.1 **Exécution d'un test Clash Detective**

Pour commencer à utiliser le menu interférences, trouvez Clash Detective dans le ruban :

`Onglet Accueil -> Menu Outils -> Détective des interférences`

**Aperçu du test** Ajouter un nouveau test. Voici à quoi peut ressembler votre aperçu du test :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

**Règles** Sélectionnez les règles ou créez-en de nouvelles.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

**Sélectionner** Sélectionnez les modèles que vous souhaitez vérifier les uns par rapport aux autres pour les interférences et exécutez le test.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

**Résultats** Passez en revue le résultat et nommez vos interférences.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

**Menu contextuel** Cliquez avec le bouton droit de la souris sur une ligne d'interférence pour ouvrir le menu contextuel suivant :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

Groupe Groupez ensemble les interférences de type similaire.

Point de vue Ajustez le point de vue avec Focus sur interférence, puis ouvrez à nouveau le menu point de vue du menu contextuel pour enregistrer le point de vue sur l'interférence. C'est le point de vue qui se retrouvera dans la rubrique sur Catenda.

Paramètres d'affichage Cliquez sur paramètres d'affichage à droite pour ouvrir les paramètres d'affichage.

Mise en évidence Modifiez les couleurs des objets de l'un ou l'autre modèle qui se heurtent les uns aux autres.

Isolation Paramètres de transparence

Points de vue Définissez les points de vue pour qu'ils se mettent à jour automatiquement, se chargent automatiquement ou se chargent manuellement.

Simulation Afficher la simulation ou non

Afficher en contexte Tous, fichier ou accueil.

Éléments Ici vous voyez les objets qui sont liés à l'interférence sélectionnée.

**Rapport** Voici à quoi peut ressembler le menu rapport :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

Contenu Sélectionnez le contenu de votre rapport

Inclure les interférences Sélectionnez les interférences à inclure

Paramètres de sortie Sélectionnez soit le test actuel pour le test sélectionné dans l'aperçu du test, soit tous les tests pour tous les tests combinés ou séparés dans l'aperçu du test.

Format de rapport Utilisez l'option points de vue et cochez la case Conserver le surlignage des résultats.

### 9.2 **Interférences dans l'extension Catenda**

Après l'exécution d'un test d'interférence, les points de vue apparaissent dans l'onglet interférences.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **Ajouter une rubrique**

Créer une rubrique en sélectionnant une ou plusieurs interférences Donnez un titre à la rubrique Cliquez sur ajouter une rubrique.

**Menu déroulant Ajouter une rubrique** Les rubriques peuvent être faites de la manière suivante :

Créer une rubrique combinée

- Créer une rubrique à partir des interférences sélectionnées
  - Créer une rubrique avec un point de vue pour chaque interférence sélectionnée dans Navisworks Clash Detective.
- Créer une rubrique à partir des interférences sélectionnées (Point de vue consolidé)
  - Créer une rubrique avec un point de vue unique qui est éloigné pour inclure toutes les interférences sélectionnées dans Navisworks Clash Detective.

Créer plusieurs rubriques

- Créer une rubrique pour chaque interférence sélectionnée
  - Créer une rubrique pour chaque interférence sélectionnée dans l'extension Catenda Navisworks.
- Créer une rubrique pour chaque groupe d'interférences
  - Créer une rubrique pour chaque groupe d'interférences sélectionné dans l'extension Catenda Navisworks, avec un point de vue pour chaque interférence du groupe d'interférences.
- Créer une rubrique pour chaque groupe d'interférences (Point de vue consolidé)
  - Créer une rubrique pour chaque groupe d'interférences sélectionné dans l'extension Catenda Navisworks, avec un point de vue unique qui est éloigné pour inclure toutes les interférences sélectionnées.
- Créer une rubrique pour chaque interférence non groupée
  - Créer une rubrique pour chaque interférence non groupée sélectionnée dans l'extension Catenda Navisworks

### 9.4 **Modifier le Statut**

Modifier le Statut des interférences sélectionnées dans l'extension Catenda Navisworks vers l'un des Statuts suivants dans les résultats du test Navisworks.

- Nouveau
- Actif
- Examiné
- Approuvé
- Résolu

## 10. **Modèles**

Téléchargez, ouvrez et ajoutez les révisions de modèles du projet Catenda sélectionné dans le menu Tableaux de rubriques au projet Navisworks. Voici à quoi peut ressembler le menu modèles :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### 10.1 **Recherche**

Recherchez les modèles du projet Catenda

### 10.2 **Actualiser**

Actualiser la liste des modèles du projet Catenda

### 10.3 **Télécharger la sélection**

Téléchargez le(s) modèle(s) sélectionné(s) de Catenda vers votre système local

### 10.4 **Ouvrir la sélection**

Ouvrir le(s) modèle(s) sélectionné(s) dans un nouveau projet Navisworks

### 10.5 **Ajouter la sélection**

Ajoutez le(s) modèle(s) sélectionné(s) au projet Navisworks actuel. Pour pouvoir ajouter un modèle au projet Navisworks actuel, il doit d'abord être téléchargé.

### 10.6 **Bibliothèque de Documents Catenda**

Ouvrez la fenêtre Bibliothèque de Documents Catenda. Voici à quoi peut ressembler la fenêtre Bibliothèque de Documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

**Flèche de navigation** Remontez d'un niveau dans la structure des dossiers.

**Actualiser** Actualiser les Documents de la Bibliothèque de Documents.

**Télécharger** Téléchargez la dernière révision du Document Catenda sélectionné sur votre système local.

**Charger** Chargez la dernière révision du Document Catenda sélectionné sur votre système local.

**Colonnes** Navigation Double-cliquez sur la flèche de navigation ou ailleurs sur la ligne d'un dossier pour ouvrir ce dossier.

Nom Le nom du dossier ou du Document

Nom du Document Le nom du Document

Image L'image du Document

Révision Le numéro de révision du Document

### 10.7 **Colonnes**

**Case de sélection** La case de sélection du modèle

**Icône de modèle** L'icône du modèle

**Nom** Le nom du modèle

**Révision Catenda** Le numéro de révision le plus récent dans le projet Catenda

**Révision Navisworks**

**Télécharger** Cliquez sur l'icône de téléchargement pour télécharger la dernière révision du modèle. Lorsque le numéro de révision s'affiche dans la colonne Révision Navisworks, le modèle est téléchargé.

**Ouvrir** Cliquez sur l'icône d'ouverture pour ouvrir le modèle dans un nouveau projet Navisworks.

**Ajouter** Cliquez sur l'icône d'ajout pour ajouter le modèle au projet Navisworks actuel.

### 10.8 **Téléchargement de modèles à partir de Catenda Hub**

Vous pouvez facilement télécharger les modèles IFC de votre projet Catenda en utilisant cette extension et les actions de l'onglet Modèles. Pour télécharger sur votre appareil local : cliquez sur le bouton de téléchargement pour chaque modèle que vous souhaitez télécharger. Les modèles seront enregistrés dans un nouveau dossier avec le nom du projet sous le chemin de téléchargement spécifié dans l'onglet paramètres. Par exemple :

`C:\\...\\Documents\\Nom du projet Catenda`

### 10.9 **Créer un fichier .nwf fusionné en utilisant des IFC de Catenda Hub**

Pour pouvoir utiliser les points de vue BCF de votre projet Catenda dans l'extension Catenda, vous avez besoin d'un fichier NavisWorks fusionné contenant les IFC de Catenda. Téléchargez les modèles IFC que vous souhaitez fusionner en suivant les étapes ci-dessus. Ouvrez l'un des fichiers que vous avez téléchargés dans NavisWorks. Fusionnez d'autres modèles du même projet dans le modèle NavisWorks à l'aide d'« Ajouter ». Une fois que vous avez tous les fichiers que vous souhaitez fusionner ajoutés, enregistrez le fichier en tant que fichier .nwf. Enregistrez le fichier dans le même dossier que vos fichiers IFC téléchargés. Utilisez ce fichier fusionné lors de la visualisation des points de vue BCF dans Navisworks. Vous pouvez également utiliser ce fichier fusionné pour exécuter des tests de collision dans NavisWorks.
