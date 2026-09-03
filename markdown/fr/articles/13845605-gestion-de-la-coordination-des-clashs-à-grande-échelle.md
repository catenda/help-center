# Gestion de la coordination des clashs à grande échelle

Cet article a été généré en interrogeant notre agent d'assistance IA. L'invite fournie vers le bas peut être utilisée pour générer votre propre version mise à jour de ce cas d'usage à mesure que les articles d'assistance sur lesquels l'IA est entraînée changent au fil du temps.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hkk8f581/01-intro.png)

## 1. **Rencontrer Sarah Chen, gestionnaire BIM chez Morrison Construction**

Sarah Chen supervise la coordination numérique du nouveau projet Metro Transit Hub. Avec 15 ans d'expérience en technologie de la construction, Sarah se spécialise dans la transformation des rapports de détection de clashs externes en flux de travail de coordination rationalisés au sein de Catenda Hub en utilisant des listes de sujets, des étiquettes et le suivi des milestones. Le rôle de Sarah se concentre sur la création du plan d'exécution BIM et l'établissement de processus de contrôle de qualité numérique. Elle travaille avec des ingénieurs structures utilisant Tekla, des équipes MEP dans Revit et des architectes dans ArchiCAD - tous nécessitant une coordination transparente grâce à des listes de sujets organisées avec des statuts et des types personnalisés.

### 1.1 **Points clés à retenir**

Sarah gère les équipes multidisciplinaires via des listes de sujets structurées, crée des flux de travail de coordination en utilisant des outils externes et assure la conformité aux milestones par des processus numériques.

### 1.2 **Pourquoi l'organisation des listes de sujets est importante**

Le projet Metro Transit Hub a généré plus de 3 000 détections de clashs lorsque l'équipe a lancé la détection de clashs dans Solibri Model Checker. Sans organisation appropriée, ces problèmes créeraient du chaos et des délais manqués. Sarah avait besoin de listes de sujets distinctes pour différentes disciplines, chacune avec des statuts personnalisés (Actif, En révision, Résolu, Approuvé) et des types (Clash, RFI, Avertissement) pour suivre le cycle de vie de chaque point de coordination. Les étiquettes sont devenues cruciales pour regrouper les sujets par étage, priorité ou système technique, améliorant considérablement la découvertabilité.

### 1.3 **Points clés à retenir**

La séparation des listes de sujets prévient la surcharge d'informations, les statuts personnalisés suivent la progression et les étiquettes permettent un filtrage et une attribution efficaces.

## 2. **Rôles et responsabilités**

**Ingénieur en chef structures** Marcus Rodriguez gère la coordination de la charpente métallique en utilisant les listes de sujets Structure-MEP dédiées. Il filtre les sujets par statut assigné et résout les conflits structurels dans les 48 heures en utilisant le suivi des milestones.

**Gestionnaire de coordination MEP** Lisa Park supervise les systèmes mécaniques grâce à des listes de sujets spécifiques au MEP. Elle utilise des étiquettes pour prioriser les problèmes critiques et gère les conflits de routage par des flux de travail de statut personnalisés.

**Chef de conception architecturale** David Kim maintient l'intention de conception par les listes Architecture-MEP Integration. Il examine les résolutions de clashs en utilisant les filtres de milestones et approuve les modifications de conception avec les mises à jour de statut appropriées.

**Gestionnaire de la construction sur site** Jennifer Walsh utilise l'accès mobile avec des filtres d'étiquettes pour se concentrer sur les problèmes spécifiques à l'étage. Elle crée des sujets basés sur le site et les relie aux milestones de coordination existants.

**Points clés à retenir** Chaque rôle fonctionne dans des listes de sujets spécifiques, utilise des étiquettes pour le filtrage et suit la progression par l'intégration des milestones.

### 2.1 **Cas d'usage réel : Metro Transit Hub**

Le niveau 3 Concourse du projet nécessitait trois listes de sujets distinctes :

Coordination Structure-MEP Intégration Architecture-MEP Vérification sur site

Sarah a configuré chaque liste avec des statuts et des types personnalisés correspondant au processus de coordination du projet. Elle a implémenté des étiquettes pour les niveaux d'étage (L1, L2, L3), la priorité (Critique, Élevée, Moyenne, Basse) et le type de système (HVAC, Électrique, Plomberie, Structure). Cela a permis aux équipes de filtrer efficacement les sujets - les équipes MEP pourraient afficher uniquement les problèmes « L3 + Critique + HVAC ».

L'intégration des milestones a lié les sujets de coordination aux délais du projet, fournissant une visibilité en temps réel sur les problèmes qui pourraient bloquer la progression. Les équipes pourraient assigner les sujets directement aux membres responsables avec des délais clairs.

### 2.2 **Points clés à retenir**

Les listes de sujets multiples organisent les disciplines, les étiquettes permettent un filtrage précis et le suivi des milestones assure le respect des délais.

## 3. **Guide de mise en œuvre étape par étape**

### 3.1 **Création de listes de sujets spécifiques aux disciplines**

Sarah crée des listes distinctes pour la coordination Structure-MEP, l'intégration Architecture-MEP et la vérification sur site. Chaque liste reçoit une configuration personnalisée pour les statuts (Actif, En révision, Résolu, Approuvé) et les types (Clash, RFI, Avertissement, Coordination).

### 3.2 **Implémentation des systèmes d'étiquettes**

Elle établit des étiquettes pour le niveau d'étage, la priorité, le type de système et la responsabilité. Les étiquettes deviennent le mécanisme de filtrage principal, permettant aux équipes de trouver rapidement les problèmes qui leur sont assignés en utilisant des combinaisons comme « L3 + Priorité élevée + Structural ».

### 3.3 **Configuration des statuts et des flux de travail de type**

Chaque liste de sujets est configurée avec un minimum d'un statut ouvert et d'un statut fermé. Les types sont personnalisés pour chaque discipline - les listes structurales pourraient avoir des types « Foundation Clash » et « Steel Conflict » tandis que les listes MEP utilisent « Routing Issue » et « Equipment Clash ».

### 3.4 **Établissement de l'attribution et de l'intégration des milestones**

Les sujets sont assignés directement aux membres de l'équipe avec des dates d'échéance liées aux milestones du projet. La plateforme suit les attributions par personne et par équipe, avec des filtres disponibles pour « Mes sujets », « Assigné à moi » et des vues spécifiques aux milestones.

### 3.5 **Importation des résultats externes de détection de clashs**

Lors de l'importation de rapports BCF depuis Solibri, Sarah s'assure qu'ils atterrissent dans la liste de sujets appropriée avec les étiquettes et les attributions correctes. Les équipes peuvent ensuite créer des sujets à partir des résultats de clashs en utilisant diverses options - des sujets combinés uniques ou des sujets individuels pour chaque clash.

### 3.6 **Points clés à retenir**

La configuration systématique des listes de sujets, l'étiquetage complet et l'intégration des milestones créent la responsabilité et la transparence dans les processus de coordination.

## 4. **Lectures complémentaires :**

- [Page des paramètres de la liste de sujets](https://support.catenda.com/en/articles/4670277-topic-board-settings-page)
- [Plugin Catenda Archicad](https://support.catenda.com/en/articles/5519276-catenda-archicad-plugin)
- [Plugin Catenda Revit](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin)
- [Plugin Catenda Navisworks](https://support.catenda.com/en/articles/5085987-catenda-navisworks-plugin)
- [Étape 5 - Sujets](https://support.catenda.com/en/articles/10576182-step-5-topics)

## 5. Invite

### 5.1 **Caractère**

Vous êtes un gestionnaire BIM pour un entrepreneur général sur un projet d'infrastructure d'intensité élevée. Vous êtes l'architecte du plan d'exécution BIM (BEP) et l'autorité principale pour le contrôle de qualité numérique et les milestones de coordination.

### 5.2 **Expérience**

Vous êtes un maître de la coordination numérique qui prospère pendant les semaines à forte charge où des milliers de clashs techniques et géométriques sont identifiés. Vous comprenez que la gestion de ces éléments à grande échelle nécessite de s'éloigner des rapports PDF statiques vers un hub de coordination centralisé et dynamique. Vous savez comment exploiter les instincts naturels « trouver et réparer » d'une équipe de projet en leur fournissant un environnement professionnel et structuré pour leur travail.

### 5.3 **Objectif**

Votre objectif est de transformer un ensemble de données massif en un flux de travail exploitable par :

**Séparation des listes de sujets :** Organiser des milliers de sujets en listes spécifiques aux catégories pour éviter les silos de données.

**Définition des cycles de vie :** Établir des statuts et des types clairs pour chaque liste pour assurer que les conceptions suivent un chemin de validation strict.

**Assurer la responsabilité :** Répartir la charge de travail entre les équipes pour assurer que les problèmes bloquant les milestones sont résolus avant les examens formels.

**Assurer la transparence :** Créer une piste d'audit irréprochable pour chaque décision, révision et approbation.

### 5.4 **Situation**

Le projet entre dans une phase critique de coordination et votre logiciel de détection de clashs vient d'identifier des milliers de problèmes. Pour gérer cela dans Catenda Hub, vous implémentez le système suivant :

**Séparation des listes de sujets :** Vous créez des listes distinctes basées sur la discipline (par exemple, Structure, MEP, Architecture) ou la gravité. Cela maintient les itérations techniques organisées et consultables.

**Configuration des statuts et des types :** Pour chaque liste, vous configurez des types spécifiques (par exemple, Clash, RFI, Avertissement) et des statuts (par exemple, Actif, En cours, Résolu, Approuvé). Cela garantit que le cycle de vie de chaque point de coordination est suivi selon les normes ISO 19650.

**Suivi via milestones :** Vous liez les sujets dans différentes listes aux milestones du projet. Cela vous permet de suivre la santé en temps réel et d'identifier exactement quels clashs bloqueront la continuation du projet s'ils ne sont pas résolus à une date spécifique.

**Regroupement avec étiquettes :** Vous utilisez des étiquettes pour regrouper les sujets par étage, priorité ou système technique. Cela améliore considérablement la découvertabilité, permettant aux équipes de filtrer et de trouver rapidement les problèmes dont elles sont responsables.

**Distribution de la charge de travail :** Vous divisez les responsabilités en assignant les sujets à des membres spécifiques ou à des équipes multidisciplinaires. En liant les sujets directement aux objets BIM et aux vues 3D, vous vous assurez que le responsable Structural ou MEP peut trouver, discuter et résoudre le problème sans jamais quitter son environnement de création natif.

### 5.5 **Incitation**

Votre succès est mesuré en atteignant les milestones contractuels à temps avec zéro ressaisie de données manuelle. Vous savez qu'une décision non documentée en contexte est une décision qui n'a pas eu lieu. Votre objectif est de fournir un rapport « sans clash » qui serve de police d'assurance inaltérable pour l'historique du projet.
