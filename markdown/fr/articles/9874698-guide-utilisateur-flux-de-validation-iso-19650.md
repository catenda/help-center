# Nouveau workflow de statut - ISO 19650

Le nouveau workflow de statut est une fonctionnalité à la demande qui peut être activée pour les projets en cours. Les nouveaux projets créés à partir d'un projet modèle pour lequel cette fonctionnalité est activée ont cette fonctionnalité activée. La série ISO 19650 est une norme internationale de bonnes pratiques qui définit les processus de gestion de l'information dans un contexte plus large de transformation numérique dans l'industrie de la construction. De nombreux acteurs de l'industrie de la construction ont adopté la norme ISO 19650 pour gérer les processus de livraison et d'approbation des documents dans les projets.

## 1. **Cycle de vie d'un document**

Selon la norme ISO, un document peut avoir quatre états différents ;

### 1.1 **🏗️ En cours (WiP)**

Les fichiers en cours de traitement et constamment remplacés dans l'environnement local de l'utilisateur. Ces fichiers sont généralement téléchargés sur Catenda uniquement pour que les gens puissent voir la progression de l'utilisateur.

### 1.2 **👥 Partagé**

Les fichiers prêts à être partagés avec les autres membres du projet pour la coordination et les révisions finales de divers métiers et/ou spécialistes. Ces fichiers sont téléchargés sur Catenda et envoyés aux parties concernées pour examen et approbation.

### 1.3 **📰 Publié**

Les fichiers qui sont coordonnés, finalisés et acceptés comme livrable contractuel. Ces fichiers ont suivi un processus d'examen et sont considérés comme « prêts pour la prochaine étape (construction, remise, quantitatif, délivrance de permis, etc.) »

### 1.4 **📦 Archivé**

L'information a été utilisée et peut être archivée pour rester disponible si nécessaire par la suite (audit, création du fichier des travaux exécutés, etc.)

### 1.5 **États du document - ISO 19650**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/01-document-states-iso-19650.png)

### 1.6 **Workflow sur Catenda Hub**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/02-workflow-on-catenda-hub.png)

## 2. **Configuration du workflow de statut**

L'activation et la configuration du workflow de statut partagé sont réservées aux administrateurs de projet.

_Accès requis_ L'accès à la configuration du statut du document dans la [zone de contrôle d'accès](https://support.catenda.com/en/articles/4670273-project-settings-page#h_3b98ced32a) de la [page des paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page). Les membres ayant cet accès n'auront accès qu'au menu de configuration du statut dans les paramètres du document. Ils ne pourront pas voir ou modifier les autres menus dans les paramètres du document.

Sous [paramètres du document](https://support.catenda.com/en/articles/7831371-document-settings), accédez à [Workflow de statut](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) et activez les statuts partagés

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/03-configuring-status-workflow.png)

Définissez les statuts partagés et publiés à utiliser dans le projet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/04-configuring-status-workflow.png)

Définissez le statut partagé par défaut pour les nouvelles révisions. Les nouvelles révisions seront initialement téléchargées en tant que révisions partagées qui peuvent être publiées ultérieurement. Le statut par défaut doit donc être un statut de révision partagée. Ce statut sera sélectionné dans la boîte de dialogue de téléchargement pour chaque téléchargement de document et peut être remplacé par un autre statut partagé lors du processus de téléchargement.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/05-configuring-status-workflow.png)

## 3. **Familier mais différent**

Après l'activation du workflow de statut, vous verrez deux onglets apparaître au-dessus des tableaux de documents et de modèles.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/06-familiar-but-different.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/07-familiar-but-different.png)

### 3.1 **Espace de travail**

Tous les téléchargements de nouvelles révisions ont lieu ici. La dernière révision partagée est affichée pour chaque document et modèle.

### 3.2 **Publié**

Une version en miroir de l'onglet espace de travail. La même structure de dossiers que dans l'espace de travail s'affiche. Seuls les documents et modèles avec révisions publiées s'affichent.

> **Remarque :** Voir les révisions partagées dans l'aperçu des révisions de l'aperçu du document, même si vous avez ouvert le document à partir de l'onglet publié. _Accès requis :_ Révisions partagées

### 3.3 **Télécharger de nouvelles révisions partagées**

Un statut de révision sera visible pour chaque fichier téléchargé dans la boîte de dialogue de téléchargement.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/08-upload-new-shared-revisions.png)

Un statut de révision sera appliqué pour chaque fichier extrait d'un fichier compressé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/09-upload-new-shared-revisions.png)

### 3.4 Publier les révisions partagées

**Plusieurs documents dans la structure du document** Une action de publication sera disponible dans le menu d'action des éléments existants d'un ou plusieurs documents sélectionnés avec des révisions partagées.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/10-publish-shared-revisions.png)

**Révision unique dans l'aperçu ou la structure du document** Une action de publication sera disponible sous forme d'icône et dans le menu d'action des informations de révision d'une révision partagée dans le menu d'information de droite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/11-publish-shared-revisions.png)

**Plusieurs modèles** Une action de publication sera disponible dans les informations de révision d'un document avec une révision partagée dans le menu d'information de droite dans la structure du document et dans l'aperçu du document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/12-publish-shared-revisions.png)

_Accès requis :_ Révisions partagées

### 3.5 **Contrôle d'accès**

Une fois que le workflow de statut est activé, vous verrez deux nouvelles colonnes apparaître à droite de la colonne d'accès dans la boîte de dialogue de contrôle d'accès d'un dossier ou d'un document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/13-access-control.png)

Le tableau ci-dessous explique comment les coches affectent l'expérience utilisateur pour chaque niveau d'accès.

- Cochez « peut publier » pour un membre ou une équipe ayant un accès en écriture pour leur permettre de publier les révisions partagées et de modifier les statuts des révisions publiées.
- Décochez « afficher les révisions partagées » pour un membre ou une équipe ayant un accès en lecture pour qu'ils ne voient que les révisions officielles publiées.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><h3 id="h_e9579ad9ca"><b>Accès partagé publié</b></h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 class="intercom-align-center" id="h_dea1580c70">Lecture</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 class="intercom-align-center" id="h_3c6b6d7d28">Écrire</h3></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_a33339c27e">Peut cocher « Afficher les révisions partagées »</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Peut cocher. <br/>Décoché par défaut.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Toujours coché</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_e909b5dc48">Peut cocher « Peut publier »</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Jamais coché</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Peut décocher. <br/>Coché par défaut</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_95374b8adf">Afficher les documents</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Les documents avec uniquement des révisions partagées ne sont visibles que si « afficher les révisions partagées » est coché</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Les documents avec des révisions partagées et les documents avec des révisions publiées sont visibles</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_e401f7a37f">Afficher les révisions partagées dans les informations du document</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Les révisions partagées ne sont visibles que si « afficher les révisions partagées » est coché</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Les révisions partagées et publiées sont visibles</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_13cbc969df">Éditer et afficher les statuts des révisions partagées</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Visible si « afficher les révisions partagées » est coché mais non modifié</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_b228d7c432">Éditer et afficher les statuts des révisions publiées</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Peut uniquement afficher le statut de la révision publiée</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Modifier si « Peut publier » est coché, sinon uniquement consultable</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_13248acfd2">Publier les documents</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Publier si « Peut publier » est coché</p></td></tr></tbody></table></div>

### 3.6 **Numéros de révision majeurs et mineurs**

Les révisions partagées ont un numéro de révision mineur (par exemple #0,1, #2,3, #4,1) Les révisions publiées ont un numéro de révision majeur (#1, #2, #3 et ainsi de suite)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/14-major-and-minor-revision-numbers.png)

### 3.7 Ouverture de l'aperçu du document

Dans la structure du document, vous verrez la dernière révision à laquelle vous avez accès. Cliquez sur le nom d'un document pour ouvrir l'aperçu du document de la révision affichée.

**Onglet Espace de travail** La dernière révision de l'onglet espace de travail peut être : Révision partagée - _Accès requis :_ Révisions partagées Révision publiée - _Accès requis :_ Lecture

**Onglet Publié** La dernière révision de l'onglet publié peut être : Révision publiée - _Accès requis :_ Lecture

> **Remarque :** Les révisions partagées peuvent être visibles dans l'aperçu des révisions de l'aperçu du document, même si vous avez ouvert le document à partir de l'onglet publié. _Accès requis :_ Révisions partagées

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/15-opening-the-document-preview.png)

### 3.8 **Informations sur la révision**

Sélectionnez un seul document ou ouvrez l'aperçu du document en cliquant sur le document. Les informations sur la révision actuelle seront visibles dans le [menu d'information de droite](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/16-revision-information.png)

- Publiez la révision actuelle avec l'action de publication.
  _Accès requis :_ Révisions partagées

- Modifiez le statut d'une révision partagée en un statut de révision partagée différent.
  _Accès requis :_ Accès en lecture et révisions partagées

- Modifiez le statut d'une révision publiée en un statut de révision publiée différent.
  _Accès requis :_ Accès en écriture et révisions publiées

**Boîte de dialogue des informations de révision** Cliquez sur la zone de révision pour voir un aperçu de toutes les révisions du document dans la [boîte de dialogue des informations de révision](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71). Un lien vert entre une révision publiée et une révision partagée indique quelle révision partagée a été publiée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/17-revision-information.png)

### 3.9 Révisions partagées et publiées dans Catenda Site

Seules les révisions publiées sont visibles dans Catenda Site.

## 4. Accès à la configuration du statut

1. L'accès à la configuration du statut du document peut être configuré à partir de la [page des paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page) :

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-868820a898ba.png" width="500"/></div>

1. Le statut des documents peut ensuite être [configuré](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) à partir des paramètres dans la section documents :

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-931418a5fab1.png" width="500"/></div>

1. Enfin, ces statuts de document peuvent être assignés au statut de révision de fichier accessible depuis le bouton à trois points en haut à droite dans la [section Approbations](https://support.catenda.com/en/articles/8349340-approvals-page). Il est également possible de configurer ici un modèle de sujet.

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-3cdbebefca38.png" width="500"/></div>

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-f8ab7f3194ff.png" width="300"/></div>

## 5. **Workflow d'approbation**

1. Un workflow d'approbation est créé par un administrateur.
   1. Équipe de soumission
   1. Équipe de révision (au moins une étape d'approbation est requise)
   1. Équipe de révision finale
1. Un membre d'une équipe de soumission soumet une demande d'approbation avec un ensemble de révisions partagées sur la page des approbations.
1. Les membres des équipes de soumission assignés à l'étape examinent les documents soumis dans l'approbation et donnent soit une validation approuvée, soit une validation rejetée.
1. Une fois que toutes les étapes ont été complétées, un membre de l'équipe de révision finale examine les validations qui ont été soumises au nom des différentes équipes à chaque étape et donne sa validation finale d'approuvé, approuvé avec commentaire ou rejeté.
   1. L'approbateur final est en mesure de prendre une décision finale et éclairée sur la question de savoir si ce document doit être publié (approuvé) ou rejeté (rester partagé)

### 5.1 **Workflow d'approbation hérité**

1. Une demande d'approbation nomme un éditeur (personne chargée de prendre la décision finale concernant la publication) et un ou plusieurs réviseurs, chargés de valider (ou non) l'ensemble des documents
1. Chaque réviseur décidera si le document partagé est approuvé, approuvé avec commentaire ou rejeté
1. À la fin de l'examen, l'éditeur choisira le résultat de l'approbation en sélectionnant les documents à publier.
1. À partir des paramètres d'approbation, des sujets liés aux documents peuvent être créés afin de suivre le processus ultérieurement

Une démonstration détaillée de ces étapes est présentée dans le tutoriel suivant :

[Vidéo YouTube](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## 6. **Désactivation du workflow de statut**

Si vous souhaitez désactiver le workflow de statut, vous pouvez le faire en cliquant sur le bouton radio dans les [paramètres du document](https://support.catenda.com/en/articles/7831371-document-settings). Les onglets Publié et Partagé dans la section documents disparaîtront alors. Les documents téléchargés alors que le workflow de statut n'est pas activé seront téléchargés comme publiés et s'afficheront dans l'onglet publié lorsque le workflow de statut sera activé.

## 7. **Avantages de l'utilisation du workflow de statut**

- L'onglet Publié sert de zone désignée pour les documents contractuels. Les membres du projet peuvent facilement trouver des documents vérifiés.
- Les documents sont validés avant d'être publiés
- Vous pouvez configurer plus facilement votre processus de livraison selon la norme ISO 19650
- Les documents de coordination/collaboration sont séparés des documents contractuels
- Plusieurs révisions partagées peuvent être sélectionnées et téléchargées, alors que dans la version précédente, les brouillons ne pouvaient être téléchargés qu'un à la fois
- Limitez ce que les gens peuvent voir dans l'application mobile Catenda Site
