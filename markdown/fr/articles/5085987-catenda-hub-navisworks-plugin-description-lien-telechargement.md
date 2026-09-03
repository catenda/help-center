# Plugin Catenda Navisworks

> **Remarque :** Le fichier d'installation du plugin se trouve dans [cet article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Le plugin Catenda Navisworks est un plugin qui peut être installé pour Nemetchek Archicad. Avec ce plugin, vous pourrez collaborer sur des viewpoints 3D, des sujets et des documents avec les autres membres du projet de construction.

## 1. **À propos du plugin**

Le complément Catenda Hub pour Autodesk® Navisworks® est l'outil parfait pour les projets collaborant dans Catenda Hub. Tous vos sujets sont synchronisés en temps réel entre Navisworks et Catenda Hub, ce qui vous permet de créer, d'accéder, de partager et de communiquer des sujets. Le format des sujets est BCF pour que les sujets puissent être partagés sur n'importe quel logiciel ou plateforme BIM compatible BCF. Ce complément vous permet de visualiser, créer et modifier les sujets en toute transparence dans Navisworks. Vous pouvez également télécharger et fédérer le modèle IFC stocké dans Catenda Hub vers votre client local.

### 1.1 **Les fonctionnalités incluent :**

- Accès à tous vos projets Catenda
- Filtrer et gérer les sujets dans les listes de sujets
- Créer de nouveaux sujets directement à partir de Navisworks
- Localiser les sujets dans votre modèle Navisworks
- Créer une nouvelle vue 3D pour chaque commentaire
- Créer des sujets BCF à partir de clashes trouvés à l'aide de Clash Detective
- Assigner des sujets à d'autres Membres du projet
- Modifier le statut du sujet et d'autres propriétés

## 2. **Collaboration basée sur le cloud**

Catenda Hub donne vie à vos données de construction sur une plateforme de collaboration basée sur le cloud couvrant l'ensemble du cycle de vie du bâtiment. Catenda gère les informations de votre projet du début à la remise et au-delà, en assurant la rétention des données et des connaissances à travers toutes les phases du projet.

## 3. **Normes ouvertes**

Catenda Hub est un outil de collaboration BIM avec support de toutes les normes buildingSMART (IFC, bSDD, BCF). Il est livré avec une gamme d'API pour une intégration facile dans votre propre logiciel.

[Vidéo YouTube](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **Installation**

Lorsque le plugin Catenda Navisworks est installé sur Windows, ses fichiers d'installation apparaîtront dans le dossier suivant.

`C:\ProgramData\Autodesk\ApplicationPlugins\Catenda.BCF.bundle`

Les paramètres configurés dans le plugin se trouvent ici :

`C:\Users\<Username>\AppData\Local\Autodesk_Inc\Roamer.exe_Url_<GUID>\<Version>`

### 4.1 **Désinstallation**

Pour désinstaller le plugin, accédez au menu Windows suivant :

`Paramètres Windows -> Applications -> Applications installées`

Trouvez le plugin BCF Catenda Navisworks version \<version> dans la liste et cliquez sur le menu d'action sur le côté droit pour désinstaller.

## 5. **Onglet Catenda**

Après avoir installé le plugin, l'onglet Catenda apparaîtra. Navisworks devra peut-être être redémarré pour que l'onglet apparaisse. Sur la page d'accueil de Navisworks, l'onglet sera initialement grisé.

Démarrez un nouveau projet Navisworks ou ouvrez-en un pour commencer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

Voici à quoi peut ressembler l'onglet Catenda lorsqu'il est sélectionné

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### 5.1 **Catenda**

Le bouton Catenda dans le menu Plugins Catenda de l'onglet Catenda ouvrira le navigateur par défaut avec la [page de connexion](https://support.catenda.com/en/articles/7891486-sign-in-page) de Catenda Hub.

### 5.2 **Plugin BCF**

Le bouton Plugin BCF dans le menu Plugins Catenda de l'onglet Catenda ouvrira le plugin Catenda Navisworks avec le menu des paramètres activé. Le menu des paramètres du plugin Catenda Navisworks peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

**Ancrage du plugin** Faites glisser la barre de titre de la fenêtre vers l'un des côtés de l'application pour l'ancrer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

Voici à quoi peut ressembler l'application lorsqu'elle est ancrée sur la droite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **Paramètres**

Voici à quoi le menu des paramètres peut ressembler après avoir cliqué sur Connexion en haut à gauche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

Sur le côté gauche, la page de connexion de Catenda s'affiche. Suivez les étapes décrites dans l'[article sur la connexion](https://support.catenda.com/en/articles/7891486-sign-in-page) pour vous connecter.

Voici à quoi le menu des paramètres peut ressembler après s'être connecté avec succès.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

Si la session de connexion a expiré, le bouton d'actualisation peut être utilisé pour actualiser la session de connexion.

### 6.1 **Authentifier**

**Jeton** Vous verrez votre jeton d'authentification Catenda après vous être connecté.

### 6.2 **IFCGuid**

**Catégorie et propriété** Catégorie par défaut : Élément Propriété par défaut : IfcGUID

**Mappage des propriétés** Le plugin Catenda Navisworks attache les objets aux viewpoints dans les sujets en fonction du GUID du IfcProject dans l'IFC. Dans Navisworks, ce GUID se trouve dans les propriétés de l'objet. Voici un exemple avec un objet sélectionné :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

Selon le contenu de votre IFC, le GUID IfcProject peut se trouver dans une ou plusieurs autres propriétés ou catégories. Surtout si Navisworks a été lancé avec un paramètre de langue autre que l'anglais, le nom de la catégorie Élément sera le mot Élément dans cette langue tandis que le mot par défaut est toujours l'anglais dans le plugin Catenda Navisworks. Pour résoudre ce problème, modifiez la Catégorie en le mot Élément dans la langue dans laquelle Navisworks est lancé.

2e, 3e, 4e Catégorie et Propriété S'il y a plusieurs catégories et propriétés qui pourraient inclure le GUID IFCProject, elles peuvent également être ajoutées.

### 6.3 **Chemins d'accès**

**CheminTéléchargement** L'emplacement du fichier où aboutissent les modèles et documents téléchargés via le plugin.

### 6.4 **Captures**

**Placement** Droite - par défaut Les captures sont affichées à droite

Dessous Les captures sont affichées dessous

## 7. **Listes de sujets**

Dans le menu Listes de sujets, un aperçu des sujets dans les listes de sujets de différents projets peut être vu. Voici à quoi peut ressembler le menu Listes de sujets.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

Cliquez sur l'onglet projets pour charger la liste des listes de sujets dans ce projet dans l'onglet des listes de sujets.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **Nouveau sujet**

Cliquez sur le bouton Nouveau sujet pour créer un nouveau sujet.

## 8. **Sujet**

Dans le menu des sujets, les sujets sélectionnés peuvent être modifiés et de nouveaux sujets peuvent être soumis. Voici à quoi peut ressembler le menu des sujets :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### 8.1 **Flèches de navigation**

Utilisez les flèches de navigation dans le menu pour vous déplacer entre les différents sujets de la liste de sujets.

### 8.2 **Nouveau sujet**

Créer un nouveau sujet

### 8.3 **Ajouter un viewpoint**

Ajouter un viewpoint de la position actuelle de la caméra au sujet actuel.

### 8.4 **Mise à jour**

Mettez à jour le sujet sur Catenda avec les informations qui ont été ajoutées dans le plugin.

### 8.5 **Numéro du sujet**

Le numéro du sujet dans le projet.

### 8.6 **Actualiser**

Chargez les dernières informations du sujet à partir de Catenda.

### 8.7 **Effacer les plans de coupe**

Cliquez sur le bouton Effacer les plans de coupe pour effacer les plans de coupe dans la visionneuse.

## 9. **Clashes**

Dans le menu des clashes, les sujets peuvent être soumis en tant que résultat des résultats de Clash Detective. Voici à quoi peut ressembler le menu des clashes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### 9.1 **Exécuter un test Clash Detective**

Pour commencer avec le menu des clashes, trouvez le Clash Detective dans le ruban :

`Onglet Accueil -> Menu Outils -> Clash Detective`

**Aperçu du test** Ajouter un nouveau test. Voici à quoi peut ressembler votre aperçu du test :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

**Règles** Sélectionnez les règles ou créez de nouvelles règles.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

**Sélectionner** Sélectionnez les modèles que vous souhaitez vérifier les uns contre les autres pour les clashes et exécutez le test.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

**Résultats** Parcourez le résultat et nommez vos clashes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

**Menu contextuel** Cliquez avec le bouton droit sur une ligne de clash pour ouvrir le menu contextuel suivant :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

Groupe Regroupez les clashes du même type.

Viewpoint Ajustez le viewpoint avec Focus sur clash, puis ouvrez à nouveau le menu viewpoint du menu contextuel pour enregistrer le viewpoint sur le clash. C'est le viewpoint qui se retrouvera dans le sujet sur Catenda.

Paramètres d'affichage Cliquez sur les paramètres d'affichage à droite pour ouvrir les paramètres d'affichage.

Mise en évidence Modifiez les couleurs des objets de l'un ou l'autre modèle qui entrent en collision l'un avec l'autre.

Isolation Paramètres de transparence

Viewpoints Définissez les viewpoints pour auto-actualiser, auto-charger ou charger manuellement.

Simulation Afficher la simulation ou non

Afficher dans le contexte Tous, fichier ou accueil.

Éléments Vous voyez ici les objets liés au clash sélectionné.

**Rapport** Voici à quoi peut ressembler le menu du rapport :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

Contenu Sélectionnez le contenu de votre rapport

Inclure des clashes Sélectionnez les clashes à inclure

Paramètres de sortie Sélectionnez soit le test actuel pour le test sélectionné dans l'aperçu du test, soit tous les tests pour tous les tests de l'aperçu du test combinés ou séparés.

Format de rapport Utilisez l'option viewpoints et cochez la case Préserver la mise en évidence des résultats.

### 9.2 **Clashes dans le plugin Catenda**

Après l'exécution d'un test de clash, les viewpoints apparaissent dans l'onglet des clashes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **Ajouter un sujet**

Créer un sujet en sélectionnant un ou plusieurs clashes Donner un titre au sujet Cliquer sur Ajouter un sujet.

**Liste déroulante Ajouter un sujet** Les sujets peuvent être créés de la manière suivante :

Créer un sujet combiné

- Créer un sujet à partir des clashes sélectionnés
  - Créer un sujet avec un viewpoint pour chaque clash sélectionné dans le Clash Detective de Navisworks.
- Créer un sujet à partir des clashes sélectionnés (Viewpoint consolidé)
  - Créer un sujet avec un seul viewpoint qui est agrandi pour inclure tous les clashes sélectionnés dans le Clash Detective de Navisworks.

Créer plusieurs sujets

- Créer un sujet pour chaque clash sélectionné
  - Créer un sujet pour chaque clash sélectionné dans le plugin Catenda Navisworks.
- Créer un sujet pour chaque groupe de clashes
  - Créer un sujet pour chaque groupe de clashes sélectionné dans le plugin Catenda Navisworks, avec un viewpoint pour chaque clash du groupe de clashes.
- Créer un sujet pour chaque groupe de clashes (Viewpoint consolidé)
  - Créer un sujet pour chaque groupe de clashes sélectionné dans le plugin Catenda Navisworks, avec un seul viewpoint qui est agrandi pour inclure tous les clashes sélectionnés.
- Créer un sujet pour chaque clash non groupé
  - Créer un sujet pour chaque clash non groupé sélectionné dans le plugin Catenda Navisworks

### 9.4 **Modifier le statut**

Modifiez le statut des clashes sélectionnés dans le plugin Catenda Navisworks à l'un des statuts suivants dans les résultats du test Navisworks.

- Nouveau
- Actif
- Examiné
- Approuvé
- Résolu

## 10. **Modèles**

Téléchargez, ouvrez et ajoutez les révisions de modèles du projet Catenda sélectionné dans le menu Listes de sujets au projet Navisworks. Voici à quoi peut ressembler le menu des modèles :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### 10.1 **Recherche**

Recherchez les modèles du projet Catenda

### 10.2 **Actualiser**

Actualisez la liste des modèles du projet Catenda

### 10.3 **Télécharger la sélection**

Téléchargez le ou les modèle(s) sélectionné(s) de Catenda vers votre système local

### 10.4 **Ouvrir la sélection**

Ouvrez le ou les modèle(s) sélectionné(s) dans un nouveau projet Navisworks

### 10.5 **Ajouter la sélection**

Ajoutez le ou les modèle(s) sélectionné(s) au projet Navisworks actuel. Pour pouvoir ajouter un modèle au projet Navisworks actuel, il doit d'abord être téléchargé.

### 10.6 **Bibliothèque de documents Catenda**

Ouvrez la fenêtre de la Bibliothèque de documents Catenda. Voici à quoi peut ressembler la fenêtre de la Bibliothèque de documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

**Flèche de navigation** Montez d'un niveau dans la structure des dossiers.

**Actualiser** Actualisez les Documents de la Bibliothèque de documents.

**Télécharger** Téléchargez la dernière révision du Document Catenda sélectionné vers votre système local.

**Télécharger** Téléchargez la dernière révision du Document Catenda sélectionné vers votre système local.

**Colonnes** Navigation Double-cliquez sur la flèche de navigation ou n'importe où ailleurs sur la ligne d'un dossier pour ouvrir ce dossier.

Nom Le nom du dossier ou du Document

Nom du Document Le nom du Document

Image L'image du Document

Révision Le numéro de révision du Document

### 10.7 **Colonnes**

**Boîte de sélection** La boîte de sélection du modèle

**Icône de modèle** L'icône du modèle

**Nom** Le nom du modèle

**Révision Catenda** Le numéro de révision le plus récent du projet Catenda

**Révision Navisworks**

**Télécharger** Cliquez sur l'icône de téléchargement pour télécharger la dernière révision du modèle. Lorsque le numéro de révision apparaît dans la colonne Révision Navisworks, le modèle est Téléchargé.

**Ouvrir** Cliquez sur l'icône d'ouverture pour ouvrir le modèle dans un nouveau projet Navisworks.

**Ajouter** Cliquez sur l'icône d'ajout pour ajouter le modèle au projet Navisworks actuel.

### 10.8 **Téléchargement de modèles depuis Catenda Hub**

Vous pouvez facilement télécharger les modèles IFC de votre projet Catenda en utilisant ce plugin et les actions de l'onglet Modèles. Pour télécharger sur votre appareil local : Cliquez sur le bouton de téléchargement pour chaque modèle que vous souhaitez télécharger. Les modèles seront enregistrés dans un nouveau dossier portant le nom du projet sous le chemin de téléchargement spécifié dans l'onglet paramètres. Par exemple :

`C:\...\Documents\Nom du projet Catenda`

### 10.9 **Créer un fichier .nwf fusionné utilisant les IFC de Catenda Hub**

Pour pouvoir utiliser les viewpoints BCF de votre projet Catenda dans le plugin Catenda, vous avez besoin d'un fichier NavisWorks fusionné contenant les IFC de Catenda. Téléchargez les modèles IFC que vous souhaitez fusionner en suivant les étapes ci-dessus. Ouvrez l'un des fichiers que vous avez téléchargés dans NavisWorks. Fusionnez plus de modèles du même projet dans le modèle NavisWorks en utilisant « Ajouter ». Une fois que vous avez tous les fichiers que vous souhaitez fusionner ajoutés, enregistrez le fichier en tant que fichier .nwf. Enregistrez le fichier dans le même dossier que vos fichiers IFC téléchargés. Utilisez ce fichier fusionné lors de la visualisation des viewpoints BCF dans Navisworks. Vous pouvez également utiliser ce fichier fusionné pour exécuter des tests de collision dans NavisWorks.
