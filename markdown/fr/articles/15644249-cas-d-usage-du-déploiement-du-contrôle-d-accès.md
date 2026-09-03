# Cas d'usage du déploiement du contrôle d'accès

La structuration d'un environnement de contrôle d'accès dans Catenda Hub nécessite d'aligner les mécanismes du système avec des rôles de projet spécifiques et des flux de travail collaboratifs. Pour résoudre proprement les règles qui se chevauchent, le système applique une ligne d'autorité stricte : les remplacements individuels directs établissent une limite finale absolue, tandis que tous les chemins non remplacés se combinent pour accorder le niveau de permission maximal disponible. Les stratégies de configuration décrites ci-dessous démontrent comment déployer les limites d'équipes, les verrouillages individuels et les portées de conteneurs pour satisfaire les exigences réelles de sécurité et opérationnelles.

## 1. **1. La communauté générale du projet**

### 1.1 **1.1 Espaces de travail isolés des sous-traitants**

**Qui** Une équipe de sous-traitants spécialisés unique nécessitant une autonomie interne.

**L'objectif** L'équipe de sous-traitants doit avoir la liberté totale de télécharger, modifier, organiser et corriger des fichiers dans leur section assignée. Les collègues au sein de la même entreprise doivent pouvoir corriger les erreurs des uns et des autres ou réorganiser les structures de dossiers librement, mais les tiers externes doivent être complètement bloqués pour éviter les suppressions accidentelles ou la visibilité non autorisée.

**La configuration** La ligne de base globale **Tous les utilisateurs** est définie sur **Pas d'accès**, tandis que le **Paramètre d'équipe** de sous-traitant spécifique reçoit **Accès complet**.

**La stratégie de portée** Cette stratégie est généralement déployée quand un projet est nouveau. La **propagation descendante** est activée sur la structure de dossiers de haut niveau, permettant aux administrateurs de repousser rapidement l'autonomie interne complète dans tout le chemin des sous-répertoires.

### 1.2 **1.2 Dossiers de collaboration interdisciplinaire**

**Qui** Plusieurs disciplines de conception (p. ex., architectes, ingénieurs en structures, MEP) travaillant dans un environnement partagé.

**L'objectif** Un espace de travail partagé doit être fourni où diverses équipes distinctes peuvent télécharger des modèles, coordonner des conceptions et référencer des fichiers simultanément sans restrictions.

**La configuration** Cet environnement peut être établi en utilisant l'une de deux méthodes : soit une **équipe interdisciplinaire** dédiée et fusionnée est créée et reçoit l'accès en **écriture**, soit chaque équipe de discipline individuelle (équipe architecture, équipe structures, etc.) est explicitement ajoutée au conteneur avec l'accès en **écriture**.

**La stratégie de portée** Parce que les exigences de collaboration changent fréquemment dans différentes branches d'un répertoire, ce cas d'usage se concentre sur les dossiers spécifiques des « feuilles » plus profonds dans la hiérarchie. La portée est limitée au **conteneur immédiat uniquement**, s'assurant que les règles de collaboration ouverte ne s'étendent pas accidentellement dans d'autres zones restreintes.

### 1.3 **1.3 Visibilité entre équipes et audit**

**Qui** Auditeurs externes, représentants clients ou équipes d'ingénierie secondaires.

**L'objectif** Une équipe de travail principale doit maintenir le contrôle total ou les droits de téléchargement dans un répertoire, mais une équipe externe ou un tiers doit activement surveiller la progression, examiner les documents et voir exactement ce qui se passe en temps réel sans aucune capacité à modifier les données.

**La configuration** Le groupe de travail principal reçoit l'**accès complet** ou l'accès en **écriture**, tandis que le groupe d'audit ou l'équipe secondaire reçoit explicitement l'accès en **lecture**.

**La stratégie de portée** Cette configuration utilise le mappage du **conteneur immédiat uniquement** sur les dossiers des feuilles localisées. Elle permet aux parties prenantes de se voir accorder une visibilité ciblée dans les sections de travail terminées tout en gardant les brouillons non approuvés dans les dossiers adjacents complètement cachés.

## 2. **2. Sous-traitants et contributeurs externes**

### 2.1 **2.1 Assignations d'équipes fluides pour le personnel rotatif**

**Qui** Fournisseurs externes et entreprises de sous-traitance ayant un roulement de personnel élevé.

**L'objectif** L'accès doit rester stable et sécurisé même quand le personnel se déplace fréquemment d'entrée et de sortie du projet ou change de rôles corporatifs.

**La configuration** Les permissions sont assignées exclusivement à un **paramètre d'équipe** (p. ex., « Relecteurs externes ») défini sur **lecture** ou **écriture**. Aucune exception d'utilisateur individuel n'est configurée pour les membres de l'équipe.

**La stratégie de portée** Pour assurer la maintenabilité à long terme, cette configuration utilise la **propagation descendante** dans les répertoires de haut niveau. Quand un nouvel employé rejoint l'entreprise externe, il est simplement ajouté à la structure d'équipe existante, héritant instantanément des permissions correctes dans toute la branche du projet sans ajustements manuels dossier par dossier.

### 2.2 **2.2 Le verrouillage individuel sécurisé**

**Qui :** Consultants hautement sécurisés, auditeurs tiers ou contributeurs externes restreints.

**L'objectif :** Parce que la sécurité et l'intégrité des données sont primordiales, un administrateur doit garantir avec 100 % de certitude qu'un utilisateur spécifique dispose d'un niveau d'accès fixe. Ce niveau doit rester strictement verrouillé, s'assurant que l'utilisateur ne peut pas accidentellement hériter de permissions élevées s'il est par erreur ajouté à une équipe de projet parallèle ou un groupe collaboratif.

**La configuration :** Un **paramètre utilisateur individuel** explicite est appliqué directement au compte de l'utilisateur et défini précisément au niveau requis (tel que **lecture** ou **pas d'accès**).

**La stratégie de portée :** Ceci est appliqué comme un verrouillage localisé sur les nœuds feuille spécifiques en utilisant le paramètre du **conteneur immédiat uniquement**. Parce qu'une assignation individuelle représente l'autorité finale ultime dans la hiérarchie du système, elle remplace toutes les lignes de base globales, les appartenances aux équipes et les privilèges de propriétaire. Même si l'utilisateur est accidentellement assigné à une équipe avec l'accès complet ailleurs, le verrouillage individuel s'assure que ses permissions restent restreintes exactement comme prévu.

## 3. **3. Propriétaires d'éléments et créateurs de contenu**

Catenda Hub assigne automatiquement l'**accès complet** au créateur d'un dossier (qu'il soit créé manuellement ou auto-extrait via une structure ZIP téléchargée), un tableau de sujets ou un conteneur de document nouvellement établi. La propriété s'applique strictement au conteneur de document lui-même, ce qui signifie que si un utilisateur télécharge une nouvelle révision d'un document créé par quelqu'un d'autre, la propriété du conteneur d'origine reste inchangée.

### 3.1 **3.1 Souveraineté du créateur et confidentialité des données**

**Qui** Auteurs internes et contributeurs de contenu standard.

**L'objectif** Un environnement de dossiers partagés est nécessaire où les membres de l'équipe peuvent consulter les fichiers généraux, mais tout individu qui crée initialement un conteneur de document doit conserver le contrôle absolu pour le mettre à jour, le renommer ou le gérer, sans accorder ces mêmes droits de gestion destructifs au reste de l'équipe.

**La configuration** La ligne de base globale **Tous les utilisateurs** ou le cadre d'équipe est limité à **lecture** ou **écriture**, tout en laissant les paramètres utilisateur individuels complètement non configurés pour les contributeurs.

**La logique :** Sans un remplacement individuel, le système par défaut utilise le niveau hérité le plus élevé. Les membres réguliers de l'équipe sont liés par les règles de dossiers standards, mais au moment où l'auteur d'origine interagit avec un conteneur de document _qu'il possède_, son statut de propriétaire intégré les élève à l'accès complet.

### 3.2 **3.2 Espaces de travail privés isolés**

**Qui** Responsables d'équipes spécifiques, directeurs de projet ou auditeurs internes.

**L'objectif** Un dossier strictement confidentiel ou un tableau de sujets doit être établi où un gestionnaire peut télécharger des brouillons, organiser des fichiers sensibles ou conserver des notes internes en total isolement du reste de la communauté du projet.

**La configuration** Le conteneur cible est créé, et la ligne de base globale **Tous les utilisateurs** est explicitement définie sur **Pas d'accès**. Aucune autre équipe générale n'a reçu l'accès.

**La logique** Parce que la ligne de base et les chemins d'équipe sont entièrement fermés, les utilisateurs standards ne voient rien. Cependant, parce que le créateur de ce dossier ou de ce tableau détient automatiquement l'**accès complet du propriétaire**, il conserve la visibilité complète et le contrôle administratif sur l'espace, complètement isolé des membres standard du projet tandis que les administrateurs de projet conservent une surveillance de haut niveau.
