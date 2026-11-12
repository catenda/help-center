# Exporter toutes les données du projet

> Aperçu des méthodes d'export des données de projet, documents, modèles et topics dans Catenda Hub. Options : synchronisation Desktop Connector, rapports PDF/A, audit des autorisations d'accès et sauvegardes cloud automatisées vers AWS S3 ou Azure Blob.

Catenda Hub propose des méthodes d'export flexibles adaptées à diverses besoins de projet, allant des téléchargements quotidiens à l'archivage automatisé en entreprise. Selon les besoins spécifiques du projet, il est possible de synchroniser de grandes structures de dossiers à l'aide de Desktop Connector, de générer des listes de contrôle de livraison de Documents personnalisées et des archives PDF/A via la page Rapports, ou de documenter les autorisations d'accès au projet pour les pistes d'audit. Pour les organisations nécessitant des sauvegardes cloud continues, Catenda Data Export fournit des transferts automatisés directement vers AWS S3 ou Azure Blob storage.

## 1. **Pourquoi exporter**

Les propriétaires de projets et les participants au projet ont souvent besoin de conserver des copies locales de la documentation du projet pendant et après le cycle de vie du projet.

### 1.1 **Soumission de données et changements de phase**

Les données du projet peuvent être nécessaires à diverses étapes clés du projet :

**Changements de phase** La transition entre la planification, la conception et la construction exige souvent l'extraction de captures instantanées de données, en particulier si les projets sont mis en attente ou cédés à de nouvelles parties.

**Demandes gouvernementales** Les soumissions formelles aux autorités sont fréquemment requises au cours ou après la fin d'un projet.

**Appels d'offres** Préparation de packages de soumission de Documents pour les appels d'offres.

### 1.2 **Rétention de données indépendantes et protection de l'accès**

L'export ne se limite pas à l'achèvement du projet. Les Membres du projet qui ne sont pas propriétaires des données principales du projet ont souvent besoin de leurs propres copies pour assurer un accès continu à leur travail.

Les Membres du projet ne sont pas toujours informés à l'avance de la fin de l'accès au projet, et l'accès peut parfois être révoqué plus tôt que prévu. Étant donné que l'accès peut être perdu sans avertissement, la configuration **d'exports planifiés et récurrents**, comme avec **Catenda Data Export** ou le **Catenda Desktop Connector**, est essentielle. Ces outils récurrents garantissent que les Membres du projet conservent une sauvegarde locale ou cloud jusqu'à la dernière exécution planifiée avant de perdre l'accès.

### 1.3 **Archivage et conformité des données**

Les réglementations et les normes de l'industrie mandatent fréquemment que les parties responsables conservent les dossiers du projet pendant de longues périodes, souvent s'étendant sur des années ou des décennies. La documentation du système, les dossiers de produits et les fichiers de conformité peuvent avoir besoin d'être stockés sur les serveurs de l'entreprise ou dans les référentiels désignés.

### 1.4 **Fermeture du projet**

Lorsqu'un projet actif se termine ou qu'une période de licence prend fin, Catenda garantit que les données du projet restent stockées en toute sécurité. Même si l'accès au projet se termine, les données restent récupérables sur les serveurs Catenda pendant jusqu'à trois ans.

### 1.5 **Option d'archive figée**

Une option d'archivage permet aux projets de rester accessibles en tant que référentiels figés et en lecture seule pour les Membres sélectionnés.

## 2. **Options d'export standard**

Ces outils d'export intégrés sont disponibles directement dans l'interface standard pour tous les participants au projet autorisés.

### 2.1 **Export des modèles**

Étant donné que chaque modèle dans Catenda est lié à un Document dans la section Documents, les capacités d'export standard de Documents s'appliquent également aux modèles. De plus, des options d'export dédiées sont disponibles spécifiquement pour les modèles :

**Téléchargement de modèles sélectionnés** Sélectionnez un ou plusieurs modèles sur la [page modèles](https://support.catenda.com/fr/articles/4670286-page-modeles) et utilisez l'action de téléchargement pour extraire leurs dernières révisions.

**Téléchargement de révision individuelle** Sélectionnez un modèle sur la [page modèles](https://support.catenda.com/fr/articles/4670286-page-modeles) et utilisez le bouton de téléchargement à côté de chaque révision dans le panneau d'information de droite. Cela fournit un moyen efficace de télécharger des révisions spécifiques directement sans avoir besoin de charger la page complète [contenu du modèle](https://support.catenda.com/fr/articles/4670270-page-de-contenu-du-model). Alternativement, les révisions individuelles peuvent également être téléchargées directement à partir de la page de contenu d'un modèle.

**Export de modèle avancé** Accédez à la [page d'export de modèle](https://support.catenda.com/fr/articles/4670280-page-d-export-de-modele) pour empaqueter les révisions sélectionnées sur plusieurs modèles dans un seul fichier ZIP téléchargeable. Cette méthode inclut des options avancées pour améliorer les fichiers modèle exportés en intégrant des balises, des propriétés définies par l'utilisateur ou des informations de Bibliothèque.

### 2.2 **Export des Sujets (3 façons)**

Les données des Sujets peuvent être extraites à l'aide de trois formats principaux via [échange de Sujets](https://support.catenda.com/fr/articles/4670289-echanger-des-sujets), en fonction de la manière dont l'information sera affichée, analysée ou stockée :

**BCF (Format de collaboration BIM)** Une norme ouverte conçue pour capturer et transférer des informations de Sujets qui respectent strictement la spécification BCF officielle, y compris les horodatages de création de Sujets individuels. Ce format garantit une large interopérabilité multiplateforme, ce qui le rend idéal pour rouvrir, modifier ou échanger des données de Sujets de manière transparente avec d'autres logiciels compatibles BCF. Pour les référentiels de Documents à long terme généraux où des aperçus directs de fichiers sont nécessaires, les formats PDF ou Excel sont généralement préférés.

**Excel** Exporte les paramètres des Sujets dans un format de feuille de calcul pour le filtrage, le tri et la manipulation de données. Ce format fournit des lignes et des colonnes structurées qui sont idéales pour sélectionner et copier des données, et les fichiers Excel peuvent être facilement prévisualisés dans la plupart des plates-formes d'archivage. À des fins d'archivage, l'export PDF est généralement préféré à Excel car il inclut plus d'informations.

**PDF** Génère un rapport récapitulatif clair et lisible au format PDF standard (v1.4), accessible sans logiciel spécialisé (voir [exportation des sujets en PDF](https://support.catenda.com/fr/articles/9784934-exporter-des-sujets-en-pdf)). Les exportations PDF standard incluent un horodatage de téléchargement consolidé pour les rapports officiels et l'archivage, offrant davantage d'informations qu'une exportation Excel. Bien que l'exportation de base génère un fichier PDF standard (v1.4) que de nombreux systèmes d'archivage convertissent automatiquement au format PDF/A lors du téléversement pour une prévisualisation à long terme, les projets dont la [page Reports](https://support.catenda.com/fr/articles/12303098-page-rapports) est activée (fonctionnalité optionnelle) peuvent également exporter les sujets dans des formats d'archivage, comme décrit dans [Exportation des données de projet avec Reports](https://support.catenda.com/fr/articles/17779017-exportation-des-donnees-de-projet-avec-des-rapports) _(uniquement pour les clients utilisant l'éditeur de rapports)_.

### 2.3 **Export des Documents et des collections**

**Téléchargements par lot et dossier** Sélectionnez des dossiers individuels, des lots de Documents spécifiques ou tous les éléments visibles du tableau à la fois pour générer une archive ZIP téléchargeable. Le téléchargement par lots gérables en sélectionnant des sous-dossiers spécifiques ou des groupes de fichiers ciblés est recommandé pour des transferts fluides lors de l'utilisation de grands ensembles de données.

- **Onglet Publié**<br>Extrait la dernière révision publiée pour chaque document sélectionné.
- **Onglet Espace de travail**<br>Extrait la dernière révision partagée pour chaque document sélectionné (nécessite la permission "Afficher les révisions partagées"). Notez que les révisions brouillon héritées ne peuvent pas être téléchargées par lot dans une archive ZIP et sont téléchargées individuellement.

**Téléchargement de révision individuelle** Sélectionnez un Document sur la [page Documents](https://support.catenda.com/fr/articles/8204673-page-documents) et cliquez sur le bouton de téléchargement à côté de chaque révision répertoriée dans le menu d'information de droite. C'est un moyen plus facile de télécharger des révisions individuelles ou historiques car la page d'aperçu du Document n'a pas besoin d'être chargée, ce qui vous permet de sélectionner un autre Document dans le tableau et de télécharger ses révisions dans le menu de droite sans avoir besoin d'ouvrir une nouvelle page d'aperçu.

**Collections publiques** Utilisez [collections](https://support.catenda.com/fr/articles/6344318-page-collections) pour créer des Liens publics pour les sous-ensembles de Documents sélectionnés, permettant aux tiers externes de télécharger des fichiers sans nécessiter un compte Catenda. Notez que seules les révisions publiées peuvent être ajoutées aux collections.

**Fichiers supprimés** Recherchez « supprimé » dans la barre de recherche Documents pour localiser et exporter les Documents précédemment supprimés. Gardez à l'esprit que ce Filtre est spécifique à la langue et correspondra au terme « supprimé » dans vos paramètres de langue actuels.

### 2.4 **Connecteur de bureau (Sauvegarde locale automatisée)**

Le [Catenda Desktop Connector](https://support.catenda.com/fr/articles/8358861-connecteur-catenda-desktop) permet une synchronisation en arrière-plan afin de télécharger périodiquement les nouvelles revisions de documents directement sur un disque local. Contrairement aux exportations web par lots, les documents téléchargés arrivent directement sur votre système sous forme de fichiers bruts non compressés, sans nécessiter d'extraction manuelle des archives.

**Sauvegardes planifiées et instantanées** Les tâches peuvent être planifiées pour s'exécuter automatiquement à intervalles réguliers ou exécutées à la demande, garantissant que les Membres du projet conservent une copie locale à jour de Documents même si l'accès au projet est révoqué de manière inattendue.

**Transferts API directs** Les transferts d'ensembles de données volumineux sont beaucoup plus rapides que les téléchargements via le navigateur Web en tirant parti des connexions API directes sans limitations ni surcharge du navigateur.

**Options de hiérarchie** Télécharge les structures de dossiers sélectionnées avec leur hiérarchie complète intacte, ou extrait les fichiers sélectionnés individuellement directement sous forme de liste plate dans le dossier local désigné.

### 2.5 **Accès des Membres et journaux d'activité**

**Listes de sujets** Documentez les autorisations d'accès au tableau en utilisant deux vues disponibles :

- **Vue d'accès par utilisateur**<br>Affichage des niveaux d'accès des utilisateurs individuels directement à partir du menu d'information de droite d'une liste de sujets ou d'un sujet sélectionné.<br>_Accès requis :_ accès en lecture à la liste de sujets
- **Configuration complète de l'équipe**<br>Capturez des captures d'écran des paramètres de permission au niveau de l'équipe dans les paramètres d'accès de la liste de sujets.<br>_Accès requis :_ accès complet à la liste de sujets ou administrateur de projet

**Accès aux Documents et modèles** Exportez l'[aperçu d'accès](https://support.catenda.com/fr/articles/6660820-page-d-apercu-des-acces-aux-documents) pour enregistrer les autorisations pour les Membres et les Équipes. Accès requis : Administrateur du projet. Étant donné que chaque modèle est lié à un Document dans la section Documents, les autorisations d'accès pour les modèles sont régies par les autorisations de Document sous-jacentes et sont enregistrées à l'aide du même aperçu d'accès aux Documents ou des menus d'autorisation.

**Accès aux révisions des Documents et modèles** Affichage des autorisations à partir du [menu de droite d'une révision de Document](https://support.catenda.com/fr/articles/8302244-menu-droit-d-une-revision-informations-de-revision) et capture de captures d'écran si nécessaire.

**Autorisations d'actions à l'échelle du projet** Documentez les autorisations à l'échelle du projet sur la [page des paramètres du projet](https://support.catenda.com/fr/articles/4670273-page-des-parametres-du-projet) (telles que la création de Listes de sujets, l'invitation de nouveaux Membres, la configuration des Statuts de Document et la création ou la suppression de modèles) en utilisant deux vues disponibles :

- **Affichage d'accès par utilisateur**<br>Les membres du projet peuvent développer chaque menu sous le contrôle d'accès pour voir quels utilisateurs individuels ont la permission d'effectuer chaque action.
- **Configuration complète**<br>Les administrateurs peuvent ouvrir la boîte de dialogue d'édition d'accès pour afficher et gérer les configurations de permissions au niveau de l'équipe.<br>_Accès requis :_ administrateur de projet

**Profils utilisateur et détails des Membres** Les informations concernant les Membres du projet et les Équipes sont disponibles pour extraction ou documentation, y compris :

- Noms d'utilisateur et adresses e-mail (voir [informations personnalisées des Membres](https://www.google.com/search?q=https://support.catenda.com/fr/articles/11769670-informations-personnalisees-des-membres)).
- Appartenances à l'Équipe, Sujets assignés, révisions de modèles téléchargées et paramètres d'autorisation (capturés via la [page des Membres](https://www.google.com/search?q=https://support.catenda.com/fr/articles/4670291-page-membres-et-equipes) ou [page d'équipe](https://www.google.com/search?q=https://support.catenda.com/fr/articles/4670291-page-membres-et-equipes)).

### 2.6 **Notifications**

Capturez les pages de notification via des captures d'écran de la [page de notification du projet](https://support.catenda.com/fr/articles/4670295-page-de-notifications-de-projet), en utilisant le [filtre de limite](https://support.catenda.com/fr/articles/8304417-filtrage-sur-la-page-des-notifications) pour maximiser les éléments visibles par page.

Configurez un compte administratif dédié avec les [paramètres de notification spécifiques au projet](https://support.catenda.com/fr/articles/4670262-parametres-de-notifications-specifiques-au-projet) activés pour les résumés e-mail afin de maintenir les journaux de notification interrogeables.

### 2.7 **Page Rapports (Fonctionnalité Opt-In)**

La [page Reports](https://support.catenda.com/fr/articles/12303098-page-rapports) est une fonctionnalité optionnelle qui peut être demandée pour les projets en cours. Les projets qui l'ont activée peuvent également exporter les données de Documents et de Sujets sous forme de rapports formatés, y compris des formats pour l'archivage à long terme.

**Gestion basée sur des modèles** Lorsqu'elle est activée, les administrateurs de projet utilisent la [page des modèles de rapport](https://support.catenda.com/fr/articles/12380837-page-des-gabarits-de-rapports) pour configurer leurs propres modèles de rapport et générer des exportations formatées pour les Documents ou Sujets sélectionnés.

Ce qui peut être exporté, et dans quels formats de fichiers, est décrit dans [Exportation des données de projet avec Reports](https://support.catenda.com/fr/articles/17779017-exportation-des-donnees-de-projet-avec-des-rapports) _(uniquement pour les clients utilisant l'éditeur de rapports)_.

## 3. **Export de données Catenda**

Catenda Data Export est vendu séparément de Catenda Hub. Contrairement aux téléchargements ci-dessus, il copie automatiquement les données de projet, directement depuis Catenda Hub vers l'espace de stockage cloud propre à une organisation, dans Amazon S3 ou Azure Blob storage. Il convient aux organisations qui souhaitent une sauvegarde qui suit leurs projets, ou des enregistrements de projet conservés dans leur propre stockage. Il ne s'adresse pas uniquement aux propriétaires de projet. Un propriétaire de projet peut exporter une sauvegarde complète de ses projets, et un participant au projet peut exporter les données auxquelles il a accès dans les projets auxquels il participe. Pour en savoir plus, consultez [À propos de Catenda Data Export](https://support.catenda.com/fr/articles/17779020-a-propos-de-catenda-data-export) _(pour les lecteurs non connectés)_ et [Introduction à Catenda Data Export](https://support.catenda.com/fr/articles/17779027-introduction-a-catenda-data-export) _(uniquement pour les clients connectés)_. Les clients qui disposent de ce service trouveront la configuration dans [Catenda Data Export](https://support.catenda.com/fr/articles/17779052-export-de-donnees-catenda) _(uniquement pour les clients Data Export)_.
