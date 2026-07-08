# Nouveau flux de travail de statut - ISO 19650

Le nouveau flux de travail de statut est une fonctionnalité à la demande qui peut être demandée pour être activée pour les projets en cours. Les nouveaux projets créés sur la base d'un projet modèle où cette fonctionnalité est activée disposent de cette fonctionnalité activée. La série ISO 19650 est une norme internationale de bonnes pratiques qui définit les processus de gestion de l'information dans un contexte plus large de transformation numérique dans l'industrie de la construction. De nombreux acteurs de l'industrie de la construction ont adopté l'ISO-19650 comme norme pour gérer les processus de livraison et d'approbation des documents dans les projets.

## 1. **Cycle de vie d'un document**

Selon la norme ISO, un document peut avoir quatre états différents ;

### 1.1 **🏗️ Travail en cours (WiP)**

Les fichiers sur lesquels on travaille et qui sont constamment remplacés dans l'environnement local de l'utilisateur. Ces fichiers sont généralement uniquement téléchargés dans Catenda afin que les gens puissent voir la progression de l'utilisateur.

### 1.2 **👥 Partagé**

Les fichiers qui sont prêts à être partagés avec d'autres membres du projet afin que la coordination et les examens finaux de différents corps de métier et/ou spécialistes puissent avoir lieu. Ces fichiers sont téléchargés sur Catenda et envoyés aux parties concernées pour examen et approbation.

### 1.3 **📰 Publié**

Les fichiers qui sont coordonnés, finalisés et acceptés comme livrable contractuel. Ces fichiers ont traversé un processus d'examen et sont considérés comme « prêts pour l'étape suivante (construction, remise, quantitatif, délivrance de permis, etc.) »

### 1.4 **📦 Archivé**

L'information a été utilisée et peut être archivée afin de rester disponible si nécessaire par la suite (audit, création du dossier des travaux réalisés, etc.)

### 1.5 **États du document - ISO 19650**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/01-document-states-iso-19650.png)

### 1.6 **Flux de travail sur Catenda Hub**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/02-workflow-on-catenda-hub.png)

## 2. **Configuration du flux de travail de statut**

L'activation et la configuration du flux de travail de statut partagé sont réservées aux administrateurs de projet.

_Accès requis_ L'accès à la configuration du statut du document dans la [zone de contrôle d'accès](https://support.catenda.com/en/articles/4670273-project-settings-page#h_3b98ced32a) de la [page des paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page). Les membres ayant cet accès n'auront accès qu'au menu de configuration du statut dans les paramètres du document. Ils ne pourront pas voir ni modifier les autres menus dans les paramètres du document.

Sous [paramètres du document](https://support.catenda.com/en/articles/7831371-document-settings) accédez à [Flux de travail de statut](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) et activez les statuts partagés

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/03-configuring-status-workflow.png)

Définissez les statuts partagés et publiés à utiliser dans le projet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/04-configuring-status-workflow.png)

Définissez le statut partagé par défaut pour les nouvelles révisions. Les nouvelles révisions seront initialement téléchargées en tant que révisions partagées qui peuvent être publiées ultérieurement. Le statut par défaut doit donc être un statut de révision partagée. Ce statut sera sélectionné dans la boîte de dialogue de téléchargement pour chaque téléchargement de document et peut être modifié vers un statut partagé différent au cours du processus de téléchargement.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/05-configuring-status-workflow.png)

## 3. **Familier mais différent**

Après activation du flux de travail de statut, vous verrez deux onglets apparaître au-dessus des tableaux de documents et modèles.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/06-familiar-but-different.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/07-familiar-but-different.png)

### 3.1 **Espace de travail**

Tous les téléchargements de nouvelles révisions ont lieu ici. La dernière révision partagée s'affiche pour chaque document et modèle.

### 3.2 **Publié**

Une version miroir de l'onglet espace de travail. La même structure de dossiers que dans l'espace de travail s'affiche. Seuls les documents et modèles avec des révisions publiées s'affichent.

> **Remarque :** Voir les révisions partagées dans l'aperçu de révision de l'aperçu du document, même si vous l'avez ouvert à partir de l'onglet publié. _Accès requis :_ Révisions partagées

### 3.3 **Télécharger de nouvelles révisions partagées**

Un statut de révision s'affichera pour chaque fichier téléchargé dans la boîte de dialogue de téléchargement.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/08-upload-new-shared-revisions.png)

Un statut de révision s'appliquera à chaque fichier extrait d'un fichier compressé.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/09-upload-new-shared-revisions.png)

### 3.4 Publier les révisions partagées

**Plusieurs documents dans la structure du document** Une action de publication sera disponible dans le menu d'action des éléments existants d'un ou plusieurs documents sélectionnés avec des révisions partagées.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/10-publish-shared-revisions.png)

**Révision unique dans l'aperçu du document ou la structure du document** Une action de publication sera disponible sous la forme d'une icône et dans le menu d'action des informations de révision d'une révision partagée dans le menu d'informations de droite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/11-publish-shared-revisions.png)

**Plusieurs modèles** Une action de publication sera disponible dans les informations de révision d'un document avec une révision partagée dans le menu d'informations de droite dans la structure du document et dans l'aperçu du document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/12-publish-shared-revisions.png)

_Accès requis :_ Révisions partagées

### 3.5 **Contrôle d'accès**

Une fois le flux de travail de statut activé, vous verrez deux nouvelles colonnes apparaître à droite de la colonne d'accès dans la boîte de dialogue de contrôle d'accès d'un dossier ou d'un document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/13-access-control.png)

Le tableau ci-dessous explique comment les coches affectent l'expérience de l'utilisateur pour chaque niveau d'accès.

- Cochez "peut publier" pour un membre ou une équipe ayant un accès en écriture pour lui permettre de publier des révisions partagées et de modifier les statuts de révision publiée.
- Décochez "voir les révisions partagées" pour un membre ou une équipe ayant un accès en lecture afin qu'il ne voie que les révisions officielles et publiées.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><h3 id="h_e9579ad9ca"><b>Accès partagé publié</b></h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_dea1580c70">Lecture</h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_3c6b6d7d28">Écriture</h3></td></tr><tr><td><h3 id="h_a33339c27e">Peut cocher "Voir les révisions partagées"</h3></td><td><p class="intercom-align-center">Peut cocher. <br/>Non coché par défaut.</p></td><td><p class="intercom-align-center">Toujours coché</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e909b5dc48">Peut cocher "Peut publier"</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Jamais coché</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Peut décocher. <br/>Coché par défaut</p></td></tr><tr><td><h3 id="h_95374b8adf">Voir les documents</h3></td><td><p class="intercom-align-center">Les documents avec uniquement des révisions partagées ne sont visibles que si "voir les révisions partagées" est coché</p></td><td><p class="intercom-align-center">Les documents avec des révisions partagées et les documents avec des révisions publiées sont visibles</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e401f7a37f">Voir les révisions partagées dans les informations du document</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Les révisions partagées ne sont visibles que si "voir les révisions partagées" est coché</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Les révisions partagées et publiées sont visibles</p></td></tr><tr><td><h3 id="h_13cbc969df">Modifier et afficher les statuts de révision partagée</h3></td><td><p class="intercom-align-center">Consulté si "voir les révisions partagées" est coché mais pas modifié</p></td><td><p class="intercom-align-center">x</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_b228d7c432">Modifier et afficher les statuts de révision publiée</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Peut uniquement afficher le statut de révision publiée</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Modifier si "Peut publier" est coché, sinon uniquement visible</p></td></tr><tr><td><h3 id="h_13248acfd2">Publier les documents</h3></td><td><p class="intercom-align-center">-</p></td><td><p class="intercom-align-center">Publier si "Peut publier" est coché</p></td></tr></tbody></table></div>

### 3.6 **Numéros de révision majeurs et mineurs**

Les révisions partagées ont un numéro de révision mineur (par exemple #0.1, #2.3, #4.1). Les révisions publiées ont un numéro de révision majeur (#1, #2, #3 et ainsi de suite)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/14-major-and-minor-revision-numbers.png)

### 3.7 Ouverture de l'aperçu du document

Dans la structure du document, vous verrez la dernière révision à laquelle vous avez accès. Cliquez sur le nom d'un document pour ouvrir l'aperçu du document de la révision affichée.

**Onglet Espace de travail** La dernière révision dans l'onglet espace de travail peut être : Révision partagée - _Accès requis :_ Révisions partagées Révision publiée - ​_Accès requis :_ Lecture

**Onglet Publié** La dernière révision dans l'onglet publié peut être : Révision publiée - _Accès requis :_ Lecture

> **Remarque :** Les révisions partagées peuvent être visibles dans l'aperçu de révision de l'aperçu du document, même si vous l'avez ouvert à partir de l'onglet publié. _Accès requis :_ Révisions partagées

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/15-opening-the-document-preview.png)

### 3.8 **Informations de révision**

Sélectionnez un seul document ou ouvrez l'aperçu du document en cliquant sur le document. Les informations sur la révision actuelle seront visibles dans le [menu d'informations de droite](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/16-revision-information.png)

- Publiez la révision actuelle avec l'action de publication.
  _Accès requis :_ Révisions partagées

- Changez un statut de révision partagée à un statut de révision partagée différent.
  _Accès requis :_ Accès en lecture et révisions partagées

- Changez un statut de révision publiée à un statut de révision publiée différent.
  _Accès requis :_ Accès en écriture et révisions publiées

**Boîte de dialogue d'informations de révision** Cliquez sur la boîte de révision pour voir un aperçu de toutes les révisions du document dans la [boîte de dialogue d'informations de révision](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71). Un lien vert entre une révision publiée et une révision partagée indique quelle révision partagée a été publiée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/17-revision-information.png)

### 3.9 Révisions partagées et publiées dans Catenda Site

Seules les révisions publiées sont visibles dans Catenda Site.

## 4. Accès à la configuration du statut

1. L'accès à la modification de la configuration du statut du document peut être configuré à partir de la [page des paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page) :

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-868820a898ba.png" width="500"/></div>

2. Le statut des documents peut ensuite être [configuré](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) à partir des paramètres dans la section des documents :

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-931418a5fab1.png" width="500"/></div>

3. Enfin, ces statuts de document peuvent être assignés au statut d'examen de fichier accessible à partir du bouton trois points en haut à droite dans la [section Approbations](https://support.catenda.com/en/articles/8349340-approvals-page). Il est également possible de configurer ici un modèle de sujet.

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-3cdbebefca38.png" width="500"/></div>

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-f8ab7f3194ff.png" width="300"/></div>

## 5. **Flux de travail d'approbation**

1. Un flux de travail d'approbation est créé par un administrateur.
   1. Équipe de soumetteurs
   2. Équipe d'examinateurs (au moins une étape d'approbation est requise)
   3. Équipe des examinateurs finals
2. Un membre d'une équipe de soumetteurs soumet une demande d'approbation avec un ensemble de révisions partagées sur la page des approbations.
3. Les membres des équipes de soumetteurs assignés à l'étape examinent les documents soumis dans l'approbation et donnent soit une validation approuvée, soit rejetée.
4. Une fois toutes les étapes terminées, un membre de l'équipe des examinateurs finals examine les validations qui ont été soumises au nom des différentes équipes à chaque étape et donne sa validation finale approuvée, approuvée avec commentaire ou rejetée.
   1. L'approbateur final est capable de prendre une décision finale et éclairée sur la question de savoir si ce document doit être publié (approuvé) ou rejeté (rester partagé)

### 5.1 **Flux de travail d'approbation hérité**

1. Une demande d'approbation désigne un éditeur (personne chargée de prendre la décision finale concernant la publication) et un ou plusieurs examinateurs, chargés de valider (ou non) l'ensemble des documents
2. Chaque examinateur décidera si le document partagé est Approuvé, Approuvé avec commentaire ou Rejeté
3. À la fin de l'examen, l'éditeur choisira le résultat de l'approbation en sélectionnant les documents à publier.
4. À partir des paramètres d'approbation, les sujets liés aux documents peuvent être créés afin de suivre le processus plus tard

Une démonstration détaillée de ces étapes est présentée dans le tutoriel suivant :

[Vidéo YouTube](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## 6. **Désactivation du flux de travail de statut**

Si vous souhaitez désactiver le flux de travail de statut, vous pouvez le faire en cliquant sur le bouton radio dans [les paramètres du document](https://support.catenda.com/en/articles/7831371-document-settings). Les onglets publié et partagé dans la section du document disparaîtront ensuite. Les documents téléchargés lorsque le flux de travail de statut n'est pas activé seront téléchargés comme publiés et s'afficheront dans l'onglet publié lorsque le flux de travail de statut sera activé.

## 7. **Avantages de l'utilisation du flux de travail de statut**

- L'onglet publié sert de zone désignée pour les documents contractuels. Les membres du projet peuvent facilement trouver des documents vérifiés.
- Les documents sont validés avant d'être publiés
- Vous pouvez configurer votre processus de livraison sur la base de l'ISO 19650 beaucoup plus facilement
- Les documents de coordination/collaboration sont séparés des documents contractuels
- Plusieurs révisions partagées peuvent être sélectionnées et téléchargées, tandis que dans la version précédente, les brouillons ne pouvaient être téléchargés qu'un par un
- Limitez ce que les gens peuvent voir dans l'application mobile Catenda Site
