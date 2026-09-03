# Échanger des sujets

Vous pourrez trouver l'action d'échange de sujets dans le [menu d'action pour nouvel élément](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) en haut à droite d'une liste de sujets. Le menu d'échange de sujets peut ressembler à ceci :

![Échange basé sur les fichiers nouveau topic échange topics historique importer bcf exporter topics se connecter à un client bcf synchroniser les topics directement avec n'importe quel client compatible BCF en utilisant l'URL ci-dessous](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/01-intro.png)

## 1. **Importer BCF**

Utilisez l'action d'importation BCF pour importer des fichiers BCF. Voici à quoi peut ressembler la fenêtre d'importation BCF :

![Importer BCF télécharger fichier bcf : sélectionner fichier parcourir sélectionner board générer de nouveaux types et statuts à partir du fichier BCF](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/02-import-bcf.png)

Catenda s'engage à 100% en faveur des normes ouvertes. Sur cette base, nous avons implémenté l'importation et l'exportation de BCF (format de collaboration BIM). Cela signifie que l'utilisateur peut importer et exporter des sujets vers/depuis d'autres logiciels qui supportent ce format (par exemple Solibri, Navisworks et bien d'autres). Vous pouvez par exemple importer un fichier contenant des données de contrôle de collision pour le même modèle créé dans une autre application logicielle. De cette façon, vous pouvez continuer votre flux de travail dans Catenda.

**Plusieurs sujets par BCF** Un fichier BCF peut contenir plusieurs sujets

**Taille maximale du fichier** La taille maximale du fichier BCF qui peut être importé est de 500 Mo.

### 1.1 **Envoyer un fichier BCF**

Cliquez sur parcourir pour sélectionner un fichier BCF que vous souhaitez envoyer

### 1.2 **Sélectionner une liste de sujets**

Sélectionnez la liste de sujets où vous souhaitez importer le sujet.

### 1.3 **Générer les nouveaux types et statuts à partir du fichier BCF**

Si votre fichier BCF contient des statuts et des types qui n'existent pas dans la liste de sujets, vous pourrez les créer automatiquement en cochant cette case. _Accès requis:_ Accès complet à la liste de sujets

Si votre fichier BCF contient des statuts et des types qui n'existent pas dans la liste de sujets, les statuts/types non existants seront dissociés si cette case reste décochée. Après la fin de l'importation, vous pouvez mapper les statuts/types dissociés à des statuts/types existants.

_Liaison de plusieurs statuts/types à la fois_ S'il y a des statuts/types dissociés dans une liste de sujets, vous verrez un message d'avertissement orange indiquant qu'il y a des champs dissociés dans la liste de sujets. _Accès requis:_ Administrateur du projet

![Topics il y a des champs non liés dans ce topic board cliquez ici pour lier](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/03-generate-new-types-and-statuses-from-the-bcf-file.png)

Cliquer sur le lien vous mènera à la zone [champs dissociés](https://support.catenda.com/en/articles/4670277-topic-board-settings#h_3bd7e3e759) des [paramètres de la liste de sujets](https://support.catenda.com/en/articles/4670277-topic-board-settings) où vous pouvez lier tous les champs d'un type à une valeur existante en une seule fois.

## 2. **Exporter des sujets**​

Vous pourrez exporter les sujets soit en choisissant exporter les sujets dans le [menu d'action pour nouvel élément](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) en haut à droite d'une liste de sujets, soit en sélectionnant un sujet dans la liste de sujets et en choisissant l'option d'exportation dans le [menu d'action pour élément sélectionné](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_b5c00c149b) au-dessus de la liste de sujets. La fenêtre d'exportation de sujets peut ressembler à ceci :

![Exporter topics tous les topics du topic board actuel filtre actuel topics sélectionnés bcf excel pdf v3.0](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/04-export-topics.png)

> **Note:** Les sujets ne peuvent être exportés que d'une liste de sujets à la fois.

### 2.1 **Options de filtrage**

**Tous les sujets de la liste de sujets active**

**Filtre actuel**

**Sujets sélectionnés**

### 2.2 **Exportation BCF**

Selon la version de BCF que vous choisissez, vous pouvez obtenir différents types de fichiers. BCF v3.0 et v2.1 produiront un fichier .bcf tandis que v2.0 produira un fichier .bcfzip

### 2.3 **Exportation Excel**

Il est possible d'exporter les sujets vers Excel. Il y aura une ligne par sujet et une colonne par colonne dans la vue de tableau de la liste de sujets. L'ordre des colonnes sera le même que l'ordre des colonnes par défaut de la [vue de tableau](https://support.catenda.com/en/articles/6941099-table-view-in-an-topic-board#h_3102328063) de la liste de sujets.

> **Note:** Aucune image et seulement le dernier commentaire d'un sujet seront exportés.

### 2.4 **Exportation PDF**

Cliquez [ici](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf) pour en savoir plus sur l'exportation de sujets au format PDF

## 3. **Page des rapports**

Avec la page des rapports, il est possible de créer des rapports personnalisés non seulement sur les sujets mais aussi sur les documents. La page des rapports est une fonctionnalité à la demande qui peut être demandée pour être activée pour les projets en cours. Les nouveaux projets créés en fonction d'un projet modèle pour lequel cette fonctionnalité est activée n'ont pas cette fonctionnalité activée. Ces rapports peuvent ensuite être exportés non seulement vers Excel et PDF, mais aussi vers de nombreux autres formats de fichier. Cliquez [ici](https://support.catenda.com/en/articles/12303098-reports-page) pour en savoir plus sur la page des rapports

## 4. **Se connecter à un client BCF**

Si vous utilisez Catenda Hub comme serveur BCF, vous pouvez vous connecter directement à d'autres logiciels. Ici, vous pouvez envoyer et recevoir des sujets vers et depuis Catenda sans avoir à exporter et importer les sujets. Cela utilise l'API BCF standardisée (par buildingSMART International). Des exemples de logiciels supportant ceci sont Navisworks, Revit, Archicad et Solibri. Dans ces logiciels, vous pouvez utiliser l'URL générale de notre serveur qui est [https://api.catenda.com/](https://api.catenda.com/) après laquelle vous obtiendrez toutes les listes de sujets de tous vos projets. Cela peut rapidement devenir une longue liste à parcourir, donc pour vous aider, nous fournissons le lien vers votre liste de sujets actuelle dans ce menu. Si vous utilisez ce lien à la place, vous pourrez facilement trouver les sujets que vous recherchez.
