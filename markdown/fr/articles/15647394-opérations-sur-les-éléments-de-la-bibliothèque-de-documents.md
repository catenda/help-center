# Opérations sur les éléments de la Bibliothèque de Documents

## 1. **1. Opérations sur les dossiers**

Ce sont les différentes opérations qui peuvent être effectuées sur un dossier selon les niveaux d'accès.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Opération</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Accès requis</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Afficher le contenu du dossier / partager un Lien de dossier</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lecture</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Créer un Document, ajouter un sous-dossier, renommer le dossier</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Écriture</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Déplacer, supprimer, modifier les paramètres d'accès (ACL)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Accès complet</p></td></tr></tbody></table></div>

### 1.1 **1.1 Accès requis: Lecture**

**Comportement par défaut** Tous les Membres ont au minimum un accès en écriture par défaut. Un Membre peut avoir un accès en lecture à un dossier s'il a été créé dans un dossier où l'accès en lecture a été configuré ou si l'accès en lecture a été configuré spécifiquement pour le dossier. Le dossier peut avoir été déplacé ultérieurement, de sorte que son accès ne doit pas nécessairement être identique au dossier dans lequel il se trouve.

**Afficher le contenu du dossier** Les Membres ayant un accès en lecture peuvent naviguer dans le contenu d'un dossier. Différent accès peut être configuré au contenu du dossier, de sorte que les Membres ayant un accès en lecture peuvent ne pas avoir accès à tous les éléments du dossier.

**Partager un dossier** Les Membres ayant un accès en lecture peuvent partager des Liens vers des dossiers via un lien de partage ou en reliant l'URL. Le destinataire du lien de partage peut avoir un accès différent et peut ne pas voir le même contenu du dossier. Un lien public vers une collection peut être créé avec le contenu du dossier afin que n'importe qui puisse télécharger le contenu de la collection indépendamment des paramètres d'accès.

### 1.2 **1.2 Accès requis: Écriture**

**Comportement par défaut** Tous les Membres ont au minimum un accès en écriture par défaut.

**Créer un Document dans un dossier** Les Membres ayant un accès en écriture à un dossier peuvent créer de nouveaux Documents dans ce dossier.

**Ajouter un dossier dans un dossier** Les Membres ayant un accès en écriture à un dossier peuvent créer de nouveaux dossiers dans ce dossier.

**Renommer un dossier** Les Membres ayant un accès en écriture à un dossier peuvent renommer le dossier.

### 1.3 **1.3 Accès requis: Accès complet**

**Comportement par défaut** Le propriétaire du dossier (créateur du dossier) et les administrateurs ont par défaut un accès complet.

**Déplacer un dossier** Les Membres ayant un accès complet peuvent déplacer des dossiers vers d'autres dossiers. Les propriétaires de dossiers (créateur du dossier) ont souvent un accès complet et peuvent donc déplacer leurs propres dossiers. Les Membres ont souvent un accès en écriture aux Documents créés par d'autres Membres. Les Membres ne peuvent donc souvent déplacer que les dossiers qu'ils ont créés, sauf s'ils se trouvent dans un dossier où ils ont reçu un accès plus élevé.

**Supprimer un dossier** Les Membres ayant un accès complet peuvent supprimer un dossier indépendamment de l'accès défini dans le dossier.

**Modifier l'ACL du dossier** Les Membres ayant un accès complet à un dossier peuvent modifier les paramètres d'accès de ce dossier.

## 2. **2. Opérations sur les Documents**

Ce sont les différentes opérations qui peuvent être effectuées sur un Document selon les niveaux d'accès.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Opération</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Accès requis</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Partager un Lien de Document</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lecture</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Liens/déconnexion d'objets, modifier les Étiquettes, créer, renommer, créer un model (IFC)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Écriture</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Déplacer vers un autre dossier, supprimer, modifier l'ACL</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Accès complet</p></td></tr></tbody></table></div>

> **Note:** La création ou la suppression d'un model à partir d'un Document IFC nécessite également un accès en écriture pour "créer et supprimer des models" dans les paramètres du projet.

### 2.1 **2.1 Accès requis: Lecture**

**Comportement par défaut** Tous les Membres ont au minimum un accès en écriture par défaut. Un Membre peut avoir un accès en lecture à un Document s'il a été téléchargé dans un dossier où l'accès en lecture a été configuré ou si l'accès en lecture a été configuré spécifiquement pour le Document. Le Document peut avoir été déplacé ultérieurement, de sorte que son accès ne doit pas nécessairement être identique au dossier dans lequel il se trouve.

**Partager un Document** Les Documents peuvent être partagés avec un lien de partage ou en reliant l'URL. Le destinataire du lien de partage peut avoir un accès différent et peut ne pas voir les mêmes révisions de Document. Un lien public vers une collection peut être créé avec une révision de Document spécifique, de sorte que n'importe qui puisse télécharger le contenu de la collection indépendamment des paramètres d'accès.

### 2.2 **2.2 Accès requis: Écriture**

**Comportement par défaut** Tous les Membres ont au minimum un accès en écriture par défaut.

**Lier/Délier des objets** Les Membres ayant au minimum un accès en écriture peuvent lier et délier des objets à un Document.

**Modifier les Étiquettes** Les Membres ayant au minimum un accès en écriture peuvent ajouter et supprimer des Étiquettes d'un Document.

**Créer un nouveau Document** Les Membres ayant au minimum un accès en écriture au dossier parent peuvent créer des Documents dans ce dossier.

**Renommer un Document** Les Membres ayant au minimum un accès en écriture peuvent renommer des Documents.

**Créer un model** Les Membres ayant au minimum un accès en écriture à un Document peuvent créer un model à partir d'un Document ifc qui apparaît sur la page des models. Extension requise: `.ifc` ou `.ifczip` _Accès supplémentaire requis:_ Accès en écriture pour créer et supprimer des models dans les paramètres du projet

**Supprimer un model** Les Membres ayant au minimum un accès en écriture peuvent supprimer le Lien model d'un Document qui est lié à un model afin qu'il disparaisse de la page des models. _Accès supplémentaire requis:_ Accès en écriture pour créer et supprimer des models dans les paramètres du projet

### 2.3 **2.3 Accès requis: Accès complet**

**Comportement par défaut** Le propriétaire du Document (créateur du Document et souvent le téléchargeur de la première révision) et les administrateurs ont par défaut un accès complet.

**Déplacer un Document vers un autre dossier** Les Membres ayant un accès complet peuvent déplacer des Documents vers d'autres dossiers. Les propriétaires de Documents (créateur du Document et souvent le téléchargeur de la première révision) ont souvent un accès complet et peuvent donc déplacer leurs propres Documents. Les Membres ont souvent un accès en écriture aux Documents créés par d'autres Membres. Les Membres ne peuvent donc souvent déplacer que les Documents qu'ils ont créés, sauf s'ils se trouvent dans un dossier où ils ont reçu un accès plus élevé.

**Supprimer un Document** Les Membres ayant un accès complet peuvent supprimer un Document indépendamment de l'accès défini dans le dossier.

**Modifier l'ACL** Les Membres ayant un accès complet à un Document peuvent modifier l'accès à ce Document.

## 3. **3. Opérations de révision publiée**

Le tableau ci-dessous relie les opérations qui peuvent être effectuées sur une révision publiée aux niveaux d'accès. Par défaut, toutes les nouvelles révisions dans les Documents sont publiées. Si les révisions partagées ont été activées, toutes les nouvelles révisions dans les Documents sont créées par défaut en tant que révisions partagées.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Opération</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Accès requis</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Prévisualiser dans Catenda Hub, accéder aux applications (mobile / Catenda Site), Visionneuse 2D/3D, télécharger, comparer, ajouter à une collection, partager</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lecture</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Retirer</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Accès complet</p></td></tr></tbody></table></div>

### 3.1 **3.1 Accès requis: Lecture**

**Prévisualiser dans Catenda Hub** Les Membres ayant au minimum un accès en lecture à un Document peuvent prévisualiser les révisions publiées dans Catenda Hub.

**Accéder aux applications** Les Membres ayant au minimum un accès en lecture à un Document peuvent accéder aux révisions publiées à partir d'applications qui accèdent à l'API comme notre application mobile, Catenda Site.

**Boutons de la Visionneuse 2D/3D** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions de Document 3D publiées peuvent utiliser les boutons 2D et 3D dans la colonne de la Visionneuse pour charger le Document 3D dans la Visionneuse respective. L'une des conditions suivantes est requise:

- Document lié à model et la dernière révision est un `.ifc` ou `.ifczip` traité avec succès
- La dernière révision est un nuage de points
- La dernière révision est un CityGML

**Partager une révision publiée** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions publiées peuvent partager des Liens vers les révisions via un lien de partage ou en reliant l'URL. Le destinataire du lien de partage peut avoir un accès différent et peut ne pas être en mesure de consulter le Document. Un lien public vers une collection peut être créé avec une révision publiée spécifique, de sorte que n'importe qui puisse télécharger le contenu de la collection indépendamment des paramètres d'accès.

**Comparer** Les Membres ayant au minimum un accès en lecture à un Document avec au moins deux révisions pdf présentes peuvent utiliser la fonction de comparaison. Accès supplémentaire requis: Deuxième révision PDF publiée présente dans le Document

**Télécharger** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions publiées peuvent télécharger les révisions publiées dans le Document.

**Ajouter à une collection** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions publiées peuvent ajouter une révision publiée d'un Document à une collection.

### 3.2 **3.2 Accès requis: Accès complet**

**Retirer** Les Membres ayant un accès complet à un Document peuvent retirer les révisions publiées dans le Document.

## 4. **4. Opérations de révision de brouillon - Héritage**

Le tableau ci-dessous relie les opérations qui peuvent être effectuées sur une révision de brouillon aux niveaux d'accès. Les révisions de brouillon ne sont disponibles que dans les projets créés avant le 2 octobre 2025.

### 4.1 **4.1 Accès requis: Aucun accès**

**Accéder aux applications** Seules les révisions publiées peuvent être consultées à partir d'applications qui accèdent à notre API comme notre application mobile, Catenda Site.

**Ajouter à une collection** Seules les révisions publiées peuvent être ajoutées aux collections.

### 4.2 **4.2 Accès requis: Lecture**

**Prévisualiser dans Catenda Hub** Les Membres ayant au minimum un accès en lecture à un Document et un accès en lecture aux brouillons dans les paramètres du projet peuvent prévisualiser les révisions de brouillon dans Catenda Hub. _Accès supplémentaire requis:_ Accès en lecture aux brouillons de Documents dans les paramètres du projet.

**Partager une révision de brouillon** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions de brouillon et un accès en lecture aux brouillons dans les paramètres du projet peuvent partager des Liens vers les révisions de brouillon via un lien de partage ou en reliant l'URL. Le destinataire du lien de partage peut avoir un accès différent et peut ne pas être en mesure de consulter le Document.

**Télécharger** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions de brouillon et un accès en lecture aux brouillons dans les paramètres du projet peuvent télécharger les révisions de brouillon. Les révisions de brouillon peuvent être téléchargées une par une en cliquant sur le bouton de téléchargement dans la zone des révisions du menu de droite de la révision sur la page d'aperçu du Document. _Accès supplémentaire requis:_ Accès en lecture aux brouillons de Documents dans les paramètres du projet

### 4.3 **4.3 Accès requis: Écriture**

**Prévisualiser dans Catenda Hub** _Accès supplémentaire requis:_ Propriétaire du Document

**Publier** Dans les projets où le workflow de statut a été activé avant le 2 octobre 2025, la case à cocher de révision de brouillon est activée par défaut dans le menu de téléchargement mais peut être décochée pour charger une révision publiée à la place.

## 5. **5. Révision partagée**

Le tableau ci-dessous relie les opérations qui peuvent être effectuées sur une révision partagée aux niveaux d'accès. Si les révisions partagées ont été activées, toutes les nouvelles révisions dans les Documents sont créées par défaut en tant que révisions partagées.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Opération</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Accès requis (+ condition supplémentaire)</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Prévisualiser, partager, télécharger</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lecture (+ "Afficher les révisions partagées" coché)</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Publier</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Écriture (+ "Peut publier" coché)</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Retirer</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>"Afficher les révisions partagées" coché</p></td></tr></tbody></table></div>

> **Note:** Note: Seules les révisions publiées peuvent être consultées à partir d'applications ou ajoutées aux collections.

### 5.1 **5.1 Accès requis: Aucun accès**

**Accéder aux applications** Seules les révisions publiées peuvent être consultées à partir d'applications qui accèdent à notre API comme notre application mobile, Catenda Site.

**Ajouter à une collection** Seules les révisions publiées peuvent être ajoutées aux collections.

### 5.2 **5.2 Accès requis: Lecture**

**Prévisualiser dans Catenda Hub** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions partagées et un accès à l'affichage des révisions partagées d'un Document peuvent prévisualiser les révisions partagées dans Catenda Hub. _Accès supplémentaire requis:_ "Afficher les révisions partagées" coché dans le menu d'accès au Document

**Partager une révision partagée** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions partagées et un accès à l'affichage des révisions partagées d'un Document peuvent partager des Liens vers les révisions partagées via un lien de partage ou en reliant l'URL. Le destinataire du lien de partage peut avoir un accès différent et peut ne pas être en mesure de consulter le Document.

**Télécharger** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions partagées et un accès à l'affichage des révisions partagées d'un Document peuvent télécharger les révisions partagées. Les dernières révisions partagées des Documents qui sont sélectionnées dans l'onglet d'espace de travail du tableau des Documents peuvent être téléchargées avec l'action de téléchargement. Les révisions partagées précédentes peuvent être téléchargées une par une en cliquant sur le bouton de téléchargement dans la zone des révisions du menu de droite de la révision sur la page d'aperçu du Document. _Accès supplémentaire requis:_ "Afficher les révisions partagées" est coché dans le menu d'accès au Document

### 5.3 **5.3 Accès requis: Écriture**

**Publier** Les Membres ayant au minimum un accès en écriture à un Document avec des révisions partagées, un accès à l'affichage des révisions partagées d'un Document et un accès à la publication de révisions dans le Document peuvent publier l'une des révisions partagées qui ont été téléchargées depuis la dernière révision publiée dans le Document. _Accès supplémentaire requis:_ "Peut publier" est coché dans le menu d'accès au Document

### 5.4 **5.4 Accès requis: Accès complet**

**Retirer** Les Membres ayant au minimum un accès en lecture à un Document avec des révisions partagées et un accès à l'affichage des révisions partagées d'un Document peuvent retirer les révisions partagées dans le Document. _Accès supplémentaire requis:_ "Afficher les révisions partagées" est coché dans le menu d'accès au Document
