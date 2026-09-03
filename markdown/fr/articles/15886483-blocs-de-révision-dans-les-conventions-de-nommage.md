# Blocs de révision dans les conventions de nommage

> Apprenez à configurer des blocs dynamiques dans les conventions de nommage de dossiers. Voyez comment les fichiers s'empilent en révisions séquentielles, où afficher les résultats et comment utiliser les champs personnalisés sans identifiant de document.

Lorsqu'une convention de nommage est activée sur un dossier, les fichiers sont automatiquement analysés lors du processus de téléchargement pour s'assurer qu'ils correspondent à des motifs structurels spécifiques. Si les noms de fichiers locaux contiennent des blocs qui changent constamment à chaque nouvelle version, le dossier peut être configuré pour les reconnaître dynamiquement.

Lorsqu'elle est correctement configurée, le téléchargement de différents fichiers locaux avec des données de version variables les mappe sur le même conteneur de document. Au lieu de créer des entrées de document séparées et désordonnées pour chaque petit changement de fichier, la plateforme reconnaît automatiquement le nom de base partagé et les empile sous forme de révisions séquentielles sous un seul document.

## 1. Où afficher les détails du document

Une fois les fichiers téléchargés avec succès, la plateforme sépare clairement les détails statiques du document des données de version changeantes :

### 1.1 **1.1 Le menu Information de droite**

La sélection d'un document dans la liste des fichiers et l'expansion de l'onglet **Infos fichier** sur le côté droit de la page affichent les données segmentées.

**1.1.1 Informations du document** Ceci affiche les données des blocs de nommage qui restent constants tout au long du cycle de vie entier du document.

**1.1.2 Informations de révision** Ceci extrait et affiche automatiquement les valeurs des blocs changeants directement à partir du nom de fichier téléchargé.

**1.1.3 Nom de révision** Ceci énumère explicitement le nom de fichier local inchangeable et original exactement tel qu'il a été stocké sur le disque dur local.

### 1.2 **1.2 Le tableau Documents**

Pour afficher les noms de fichiers d'origine en un coup d'œil dans les listes de fichiers principales, la colonne **"Nom de révision"** (Nom d'origine) peut être activée. Les ajustements de visibilité des colonnes sont strictement liés aux profils de comptes individuels, ce qui signifie qu'un espace de travail peut être personnalisé sans modifier l'affichage par défaut pour le reste de l'équipe.

## 2. Configuration des blocs de révision changeants

Pour créer une convention de nommage qui isole clairement les marqueurs de version changeants des noms de document statiques, les comportements de bloc individuels doivent être ajustés dans les paramètres de convention. La navigation vers la page des conventions de nommage s'effectue dans les paramètres du projet. _Accès requis :_ Administrateur

### 2.1 Le paramètre critique : désactiver l'identifiant du document

Pour tout bloc qui change par révision, l'**identifiant de document** doit être basculé à **Désactivé**. Ce paramètre garantit que la plateforme valide les caractères lors du téléchargement pour maintenir la cohérence, mais les supprime lors de la finalisation du nom de document réel.

C'est le mécanisme exact qui permet aux fichiers avec des chaînes de version variables de s'empiler proprement sous forme de révisions plutôt que de générer des documents complètement nouveaux.

### 2.2 Utilisation des sources de champs personnalisés

Pour contrôler exactement quels caractères sont autorisés dans ces blocs dynamiques, des champs personnalisés sont attribués en tant que **Source** de bloc. Selon les besoins de suivi, différents types de champs peuvent être utilisés pour appliquer des contraintes de validation :

**2.2.1 Champs de texte personnalisés** Cette option permet un nombre flexible ou fixe de caractères pour les entrées alphanumériques standard.

**2.2.2 Champs personnalisés déroulants** Cette option restreint le bloc à un ensemble prédéfini de valeurs spécifiques, jusqu'à une limite de 1 000 options. Ceci est très bénéfique lorsque les codes de nom de fichier court doivent être mappés à des noms complets et descriptifs dans la plateforme.

**2.2.3 Champs de nombre entier personnalisés** Cette option force le bloc à accepter strictement les nombres. Notez que bien qu'elle garantisse que seules les entrées numériques sont utilisées, le système acceptera tout entier valide plutôt que de forcer un décompte séquentiel stricte et étape par étape.
