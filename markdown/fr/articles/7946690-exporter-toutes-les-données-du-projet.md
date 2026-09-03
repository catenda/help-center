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

**Téléchargement de modèles sélectionnés** Sélectionnez un ou plusieurs modèles sur la [page modèles](https://support.catenda.com/en/articles/4670286-models-page) et utilisez l'action de téléchargement pour extraire leurs dernières révisions.

**Téléchargement de révision individuelle** Sélectionnez un modèle sur la [page modèles](https://support.catenda.com/en/articles/4670286-models-page) et utilisez le bouton de téléchargement à côté de chaque révision dans le panneau d'information de droite. Cela fournit un moyen efficace de télécharger des révisions spécifiques directement sans avoir besoin de charger la page complète [contenu du modèle](https://support.catenda.com/en/articles/4670270-model-contents-page). Alternativement, les révisions individuelles peuvent également être téléchargées directement à partir de la page de contenu d'un modèle.

**Export de modèle avancé** Accédez à la [page d'export de modèle](https://support.catenda.com/en/articles/4670280-model-export-page) pour empaqueter les révisions sélectionnées sur plusieurs modèles dans un seul fichier ZIP téléchargeable. Cette méthode inclut des options avancées pour améliorer les fichiers modèle exportés en intégrant des balises, des propriétés définies par l'utilisateur ou des informations de Bibliothèque.

### 2.2 **Export des Sujets (3 façons)**

Les données des Sujets peuvent être extraites à l'aide de trois formats principaux via [échange de Sujets](https://support.catenda.com/en/articles/4670289-exchange-topics), en fonction de la manière dont l'information sera affichée, analysée ou stockée :

**BCF (Format de collaboration BIM)** Une norme ouverte conçue pour capturer et transférer des informations de Sujets qui respectent strictement la spécification BCF officielle, y compris les horodatages de création de Sujets individuels. Ce format garantit une large interopérabilité multiplateforme, ce qui le rend idéal pour rouvrir, modifier ou échanger des données de Sujets de manière transparente avec d'autres logiciels compatibles BCF. Pour les référentiels de Documents à long terme généraux où des aperçus directs de fichiers sont nécessaires, les formats PDF ou Excel sont généralement préférés.

**Excel** Exporte les paramètres des Sujets dans un format de feuille de calcul pour le filtrage, le tri et la manipulation de données. Ce format fournit des lignes et des colonnes structurées qui sont idéales pour sélectionner et copier des données, et les fichiers Excel peuvent être facilement prévisualisés dans la plupart des plates-formes d'archivage. À des fins d'archivage, l'export PDF est généralement préféré à Excel car il inclut plus d'informations.

**PDF** Génère un rapport résumé lisible et net au format PDF standard (v1.4) accessible sans logiciel spécialisé (voir [export des sujets vers PDF](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf)). Les exports PDF standard incluent un horodatage de téléchargement consolidé pour les rapports formels des autorités et l'archivage, fournissant plus d'informations qu'un export Excel. Bien que l'export de base génère un fichier PDF standard (v1.4), que de nombreux systèmes d'archivage convertissent automatiquement en PDF/A lors du téléchargement pour un aperçu à long terme, l'export direct vers les formats natifs PDF/A-1, PDF/A-2 et PDF/A-3 est également disponible via la [page Rapports](https://support.catenda.com/en/articles/12303098-reports-page) optionnelle.

### 2.3 **Export des Documents et des collections**

**Téléchargements par lot et dossier** Sélectionnez des dossiers individuels, des lots de Documents spécifiques ou tous les éléments visibles du tableau à la fois pour générer une archive ZIP téléchargeable. Le téléchargement par lots gérables en sélectionnant des sous-dossiers spécifiques ou des groupes de fichiers ciblés est recommandé pour des transferts fluides lors de l'utilisation de grands ensembles de données.

- **Onglet Publié**
  Extrait la dernière révision publiée pour chaque Document sélectionné.
- **Onglet Espace de travail**
  Extrait la dernière révision partagée pour chaque Document sélectionné (nécessite l'autorisation « Afficher les révisions partagées »). Notez que les révisions brouillon héritées ne peuvent pas être téléchargées par lots dans une archive ZIP et sont téléchargées individuellement.

**Téléchargement de révision individuelle** Sélectionnez un Document sur la [page Documents](https://support.catenda.com/en/articles/8204673-documents-page) et cliquez sur le bouton de téléchargement à côté de chaque révision répertoriée dans le menu d'information de droite. C'est un moyen plus facile de télécharger des révisions individuelles ou historiques car la page d'aperçu du Document n'a pas besoin d'être chargée, ce qui vous permet de sélectionner un autre Document dans le tableau et de télécharger ses révisions dans le menu de droite sans avoir besoin d'ouvrir une nouvelle page d'aperçu.

**Collections publiques** Utilisez [collections](https://support.catenda.com/en/articles/6344318-collections-page) pour créer des Liens publics pour les sous-ensembles de Documents sélectionnés, permettant aux tiers externes de télécharger des fichiers sans nécessiter un compte Catenda. Notez que seules les révisions publiées peuvent être ajoutées aux collections.

**Fichiers supprimés** Recherchez « supprimé » dans la barre de recherche Documents pour localiser et exporter les Documents précédemment supprimés. Gardez à l'esprit que ce Filtre est spécifique à la langue et correspondra au terme « supprimé » dans vos paramètres de langue actuels.

### 2.4 **Connecteur de bureau (Sauvegarde locale automatisée)**

Le [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) permet la synchronisation en arrière-plan pour télécharger périodiquement les nouvelles révisions de Documents directement sur un lecteur local. Contrairement aux exports web par lots, les Documents téléchargés arrivent directement sur votre système en tant que fichiers bruts, décompressés, sans nécessiter l'extraction manuelle d'archives.

**Sauvegardes planifiées et instantanées** Les tâches peuvent être planifiées pour s'exécuter automatiquement à intervalles réguliers ou exécutées à la demande, garantissant que les Membres du projet conservent une copie locale à jour de Documents même si l'accès au projet est révoqué de manière inattendue.

**Transferts API directs** Les transferts d'ensembles de données volumineux sont beaucoup plus rapides que les téléchargements via le navigateur Web en tirant parti des connexions API directes sans limitations ni surcharge du navigateur.

**Options de hiérarchie** Télécharge les structures de dossiers sélectionnées avec leur hiérarchie complète intacte, ou extrait les fichiers sélectionnés individuellement directement sous forme de liste plate dans le dossier local désigné.

### 2.5 **Accès des Membres et journaux d'activité**

**Listes de sujets** Documentez les autorisations d'accès au tableau en utilisant deux vues disponibles :

- **Vue d'accès par utilisateur**
  Affiche les niveaux d'accès des utilisateurs individuels directement à partir du menu d'information de droite d'une Liste de sujets ou d'un Sujet sélectionné.
  ​_Accès requis :_ accès en lecture à la Liste de sujets
- **Configuration complète de l'Équipe**
  Capturez des captures d'écran des paramètres d'autorisation complets au niveau de l'Équipe dans les paramètres d'accès de la Liste de sujets.
  ​_Accès requis :_ Accès complet à la Liste de sujets ou administrateur du projet

**Accès aux Documents et modèles** Exportez l'[aperçu d'accès](https://support.catenda.com/en/articles/6660820-document-access-overview-page) pour enregistrer les autorisations pour les Membres et les Équipes. Accès requis : Administrateur du projet. Étant donné que chaque modèle est lié à un Document dans la section Documents, les autorisations d'accès pour les modèles sont régies par les autorisations de Document sous-jacentes et sont enregistrées à l'aide du même aperçu d'accès aux Documents ou des menus d'autorisation.

**Accès aux révisions des Documents et modèles** Affichage des autorisations à partir du [menu de droite d'une révision de Document](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision-revision-info) et capture de captures d'écran si nécessaire.

**Autorisations d'actions à l'échelle du projet** Documentez les autorisations à l'échelle du projet sur la [page des paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page) (telles que la création de Listes de sujets, l'invitation de nouveaux Membres, la configuration des Statuts de Document et la création ou la suppression de modèles) en utilisant deux vues disponibles :

- **Vue d'accès par utilisateur**
  Les Membres du projet peuvent développer chaque menu sous contrôle d'accès pour voir quels utilisateurs individuels ont la permission d'effectuer chaque action.
- **Configuration complète**
  Les administrateurs peuvent ouvrir la boîte de dialogue d'édition d'accès pour afficher et gérer les configurations d'autorisation au niveau de l'Équipe.
  ​_Accès requis :_ Administrateur du projet

**Profils utilisateur et détails des Membres** Les informations concernant les Membres du projet et les Équipes sont disponibles pour extraction ou documentation, y compris :

- Noms d'utilisateur et adresses e-mail (voir [informations personnalisées des Membres](https://www.google.com/search?q=https://support.catenda.com/en/articles/11769670-custom-member-information%23h_c15463ee3f)).
- Appartenances à l'Équipe, Sujets assignés, révisions de modèles téléchargées et paramètres d'autorisation (capturés via la [page des Membres](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page) ou [page d'équipe](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page)).

### 2.6 **Notifications**

Capturez les pages de notification via des captures d'écran de la [page de notification du projet](https://support.catenda.com/en/articles/4670295-project-notifications-page), en utilisant le [filtre de limite](https://support.catenda.com/en/articles/8304417-filtering-on-the-notifications-page) pour maximiser les éléments visibles par page.

Configurez un compte administratif dédié avec les [paramètres de notification spécifiques au projet](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings) activés pour les résumés e-mail afin de maintenir les journaux de notification interrogeables.

### 2.7 **Page Rapports (Fonctionnalité Opt-In)**

**Activation de l'opt-in** La page rapports est une fonctionnalité optionnelle qui peut être demandée à être activée pour les projets en cours. Bien qu'aucun paiement supplémentaire ne soit requis pour utiliser cet outil, le propriétaire du projet doit accepter de l'activer sur le projet, ce qui signifie qu'il n'est pas actif par défaut dans de nombreux projets. Notez que les nouveaux projets créés à partir de projets Template où les rapports sont activés n'ont pas automatiquement cette fonctionnalité activée.

**Gestion basée sur les Template** Lorsqu'elles sont activées, les administrateurs du projet peuvent utiliser la [page des modèles de rapport](https://support.catenda.com/en/articles/12380837-report-templates-page) pour configurer les modèles de rapport personnalisés et générer des exports formatés pour les Documents ou les Sujets sélectionnés.

**Rapports de Document** Exportez les métadonnées du Document et les détails de révision pour tous les fichiers sélectionnés, y compris le nom du Document, le nom de la révision, le numéro de révision le plus récent, le Statut, les champs personnalisés, le créateur, le téléchargeur et les horodatages de création/téléchargement.

- **Cas d'utilisation clés**
  Idéal pour générer des listes de contrôle de livraison de Documents formels pour accompagner une collection, ou compiler des listes de Documents structurées pour l'analyse de données.
- **Métadonnées et attributs du modèle**
  Bien que le contenu réel des fichiers de Document ne soit pas inclus, les métadonnées du modèle peuvent être exportées via les rapports de Document car les modèles maintiennent des Liens vers la section Document. Les scripts personnalisés dans les Template peuvent également être utilisés pour dériver des attributs supplémentaires, tels que l'extraction des types de fichiers à partir des noms de Document.

**Rapports de Sujets** Exportez les en-têtes de Sujets globaux ainsi que les détails complets du corps du Sujet, y compris les descriptions, les commentaires et les images de commentaires incorporées.

**Formats d'export disponibles** Les rapports créés à partir de n'importe quel Template peuvent être exportés vers plusieurs formats selon vos besoins de flux de travail :

- **PDF / PDF/A**
  Génère des rapports formatés propres et prend directement en charge la conformité PDF/A native (PDF/A-1, PDF/A-2 et PDF/A-3) pour répondre aux normes strictes d'archivage à long terme et aux normes légales formelles.
- **Excel**
  Exporte des données tabulaires structurées dans des lignes et des colonnes de feuille de calcul, ce qui le rend idéal pour la manipulation de données et l'analyse externe.
- **Formats supplémentaires**
  Une large gamme de formats de fichiers supplémentaires au-delà de PDF et Excel sont également pris en charge pour l'export ; l'aperçu complet se trouve dans l'article [page des rapports](https://support.catenda.com/en/articles/12303098-reports-page).

**Stockage centralisé** Les rapports générés sont répertoriés directement dans le tableau des rapports et intégrés automatiquement dans le tableau Documents principal pour une gestion facile.

## 3. **Export de données Catenda**

Contrairement aux téléchargements standard pilotés par l'utilisateur, Catenda Data Export est une solution automatisée en libre-service conçue pour transférer de manière transparente les données du projet directement dans le stockage cloud d'une organisation. Si votre organisation souhaite activer cette fonctionnalité, vous pouvez contacter le service des ventes à [sales@catenda.com](mailto:sales@catenda.com). Une fois activée, elle fournit des sauvegardes automatisées directement entre les environnements cloud sans nécessiter de scripts personnalisés, contournant les contraintes de mémoire du navigateur, les limitations d'espace de stockage local et les interruptions réseau grâce à la vérification de somme de contrôle automatisée.

### 3.1 **Rôles et autorisations de l'organisation**

La configuration et la gestion de Catenda Data Export nécessitent un **Administrateur de l'organisation**. Contrairement à un Propriétaire de l'organisation, dont les droits administratifs sont limités à une seule organisation, ou aux Membres de projet standard, un Administrateur de l'organisation dispose d'un accès élevé sur toutes les organisations appartenant à un compte couvrant. Ce rôle unique accorde la visibilité interorganisationnelle requise et l'autorité pour configurer et gérer les exports cloud automatisés.

### 3.2 **Étapes de configuration**

La configuration des exports de données automatisés implique quatre étapes principales :

1. **Sélectionner la destination**
   Choisissez un fournisseur de stockage cloud, Amazon Web Services (AWS) S3 ou Microsoft Azure Blob storage, et configurez l'authentification.
1. **Définir la portée et les formats de données**
   - **Types de données**
     Exportez les Documents, les modèles et les Sujets.
     Les données des Sujets peuvent être automatiquement converties en rapports résumés PDF lisibles ou en fichiers BCF standard lors du transfert.
   - **Sélection du projet**
     Choisissez tous les projets, sélectionnez manuellement des projets spécifiques, ou configurez des règles de correspondance dynamique en utilisant des modèles de nom de projet (glob ou expression régulière / regex) pour inclure automatiquement les nouveaux projets à leur création.
1. **Sélectionner le mode d'export**
   - **Mode continu**
     Expédie les données automatiquement selon un calendrier quotidien.
     Cette configuration récurrente garantit que les Membres du projet non propriétaires maintiennent une sauvegarde à jour jusqu'à la dernière exécution quotidienne si l'accès au projet se termine de manière inattendue.
   - **Mode capture**
     Effectue une exécution unique pour exporter un ensemble de données complet à un jalon spécifique ou à une remise de projet.
1. **Déployer**
   Finalisez et activez la configuration d'export en sélectionnant Créer.

### 3.3 **Contenu extrait et vérification de l'intégrité**

**Métadonnées et champs personnalisés** Les champs personnalisés associés aux Documents et aux Sujets sont exportés aux côtés des fichiers principaux en tant que fichiers JSON structurés, garantissant la rétention complète des attributs sans génération manuelle de rapports.

**Vérification de l'intégrité** Chaque exécution d'export génère un fichier de somme de contrôle pour vérifier que les fichiers exportés correspondent aux données source dans Catenda Hub et ont été transférés complètement sans perte réseau.

**Hiérarchie organisée** Les fichiers exportés sont automatiquement structurés dans des dossiers organisés par date, nom de projet et la hiérarchie exacte des dossiers maintenue dans Catenda Hub.
