# Page des paramètres des gabarits de sujet

> Gérez vos paramètres de gabarits de sujet

La page des paramètres des gabarits de sujet se trouve en cliquant sur Configurer les gabarits de sujet sur la [page des paramètres de sujet](https://support.catenda.com/en/articles/14183429-topic-settings-page) qui peut être ouverte à partir du menu de navigation de gauche après l'ouverture de la page des sujets. _Accès requis :_ Administrateur du projet

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/01-intro.png)

Sur la page des paramètres des gabarits de sujet, les gabarits de sujet pour chacune des listes de sujets du projet peuvent être configurés. Après leur création, les gabarits de sujet sont mis à disposition pour remplir automatiquement le texte et les champs des sujets lors de leur création. Les gabarits de sujet peuvent être configurés pour être disponibles dans les processus de création de sujet suivants : [Comment utiliser les gabarits de sujet dans les sujets généraux](https://support.catenda.com/en/articles/14075921-apply-a-general-topic-template-upon-topic-creation) [Comment utiliser les gabarits de sujet dans les sujets de balisage](https://support.catenda.com/en/articles/14078352-apply-a-document-topic-template-when-creating-a-markup-from-a-document) [Comment utiliser les gabarits de sujet avec les approbations](https://support.catenda.com/en/articles/14078683-apply-an-approval-topic-template-to-an-approval-workflow-template)

## 1. **Menu d'action**

Cliquez sur le bouton plus vers le haut à droite pour ouvrir le menu d'action. Voici à quoi peut ressembler le menu d'action en haut à droite de la page des paramètres des gabarits de sujet :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/02-action-menu.png)

Un menu déroulant donnera la possibilité de créer 3 types distincts de gabarit de sujet. Les gabarits de sujet sont distingués en trois types de gabarit différents car les variables qui peuvent être utilisées pour remplir automatiquement le texte et les champs des sujets lors de leur création diffèrent selon le processus de création de sujet qui est utilisé.

## 2. **Options de recherche ou de filtrage**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/03-search-or-filter-options.png)

### 2.1 **Recherche**

_Recherche de texte -_ `search=<Search phrase>` Après avoir entré des caractères dans la barre de recherche ou de filtrage, le premier filtre suggéré change en recherche de texte.

**Contenu pouvant être recherché** Nom du gabarit de sujet

**Capitalisation** La recherche de texte n'est pas sensible aux caractères majuscules ou minuscules.

**Quantité de caractères** Tout montant ou type de caractère peut être recherché.

**Espaces** Les caractères d'espacement au début d'une phrase de recherche peuvent être recherchés mais sont supprimés des noms de gabarit, il n'y aura donc pas de résultats lors de la recherche. Les caractères d'espacement à la fin d'une phrase de recherche sont supprimés.

### 2.2 **Filtrage dans le menu de filtrage**

Les gabarits de sujet sont filtrés soit par l'un des statuts possibles Cliquez sur le menu Statut dans le menu de filtrage pour masquer le statut de l'option qui n'est pas filtré. Il est possible d'appuyer sur le X à droite dans la barre de recherche pour supprimer les balises de filtrage de la barre, mais cela n'a aucun effet. Il est seulement possible de filtrer les gabarits avec le filtre Actif ou Archivé.

_Actif_ - `status=active` - Par défaut Les gabarits de sujet qui peuvent être activement utilisés et configurés pour générer des sujets.

_Archivé_ - `status=archived` Les gabarits de sujet qui ne sont pas disponibles pour être utilisés ou configurés dans le processus de génération de sujet.

## 3. **Tableau des gabarits**

Une fois que vous accédez à votre page de paramètres des gabarits de sujet, un aperçu des gabarits de sujet existants qui ont été créés précédemment peut être consulté. Voici à quoi peut ressembler le tableau des gabarits de sujet :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/04-templates-table.png)

Cliquez [ici](https://support.catenda.com/en/articles/11748020-tables-on-catenda) pour en savoir plus sur la façon de travailler avec les tableaux dans Catenda.

### 3.1 **Contenu des lignes**

Cliquez sur une ligne de sujet pour ouvrir la page de contenu du gabarit de sujet pour ce gabarit.

### 3.2 **Colonnes**

Toutes les colonnes du tableau des gabarits de sujet sont activées par défaut. En fonction de l'ordre des colonnes configuré, les premières colonnes sont affichées tandis que le tableau peut être faire défiler latéralement pour afficher les autres colonnes activées. L'ordre par défaut et le paramètre de visibilité des colonnes sur la page des documents sont les suivants :

Nom Type de gabarit Créé par Créé le Statut Liste de sujets

## 4. **Créer un nouveau gabarit de sujet général**

Peut être utilisé sur les sujets créés à partir de la section Sujet général. Voici les différentes actions que vous devez suivre et les variables que vous pouvez entrer lors de la création d'un nouveau gabarit de sujet général :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/05-create-a-new-general-topic-template.png)

1. **Liste de sujets** : La liste de sujets dans laquelle le gabarit de sujet général peut être généré.
1. **Nom du gabarit** : Le nom du gabarit peut être sélectionné dans le menu déroulant lors de la création, ou mise à jour dans les paramètres plus tard si nécessaire.
1. **Titre du sujet** : Le titre du sujet résultant après création du sujet à partir du gabarit de sujet général.
   Survolez votre souris sur l'icône "?" situé en haut à droite de la zone de titre pour voir comment vous pouvez personnaliser le titre de votre gabarit de sujet avec la variable disponible : `topicCreator`.

    <div class="intercom-container intercom-align-center"><img height="184" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-272165f584d2.png" style="height: auto;" width="300"/></div>

1. **Statut du sujet** : Le statut du sujet résultant après création du sujet à partir du gabarit de sujet général.
1. **Type de sujet** : Le type de sujet résultant après création du sujet à partir du gabarit de sujet général.
1. **Milestone** : Le milestone du sujet résultant après création du sujet à partir du gabarit de sujet général.
1. **Assigné à** : Le responsable du sujet résultant (membre du projet ou équipe) après création du sujet à partir du gabarit de sujet général. Vous pouvez utiliser ici la variable `Topic Creator` pour remplir automatiquement ce champ avec le créateur du sujet si nécessaire.

    <div class="intercom-container intercom-align-center"><img height="94" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-c7f3d7220c54.png" style="height: auto;" width="150"/></div>

1. **Demandé par** : Le demandeur du sujet résultant après création du sujet à partir du gabarit de sujet général. Vous pouvez utiliser ici la variable `Topic Creator` pour remplir automatiquement ce champ avec le créateur du sujet si nécessaire.

    <div class="intercom-container intercom-align-center"><img height="93" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-43e4955bfdd8.png" style="height: auto;" width="150"/></div>

1. **Étiquettes** : Les étiquettes du sujet résultant après création du sujet à partir du gabarit de sujet général.
1. **Description** : La description du sujet résultant après création du sujet à partir du gabarit de sujet général. Cette section supporte le format Markdown et vous pouvez exploiter tout son potentiel pour formater le texte, créer des en-têtes personnalisés et des listes de contrôle.
    Survolez votre souris sur l'icône "?" située en haut à droite de la zone de description pour voir comment vous pouvez utiliser toutes les fonctionnalités disponibles (mentionner les coéquipiers et lier les sujets existants) et les variables (telles que `topicCreator` dans le cas du gabarit de sujet général).

     <div class="intercom-container intercom-align-center"><img height="291" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d2735ca1aec8.png" style="height: auto;" width="300"/></div>

Une fois que vous avez terminé la configuration de votre nouveau gabarit de sujet général, vous pouvez cliquer sur le bouton "Enregistrer" en bas à droite.

## 5. **Nouveau gabarit de sujet pour les documents**

Peut être utilisé sur les sujets créés à partir de balisages sur les documents. Voici les différentes actions que vous devez suivre et les variables que vous pouvez entrer lors de la création d'un nouveau gabarit de sujet pour les documents :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/06-new-document-topic-template.png)

1. **Liste de sujets** : La liste de sujets dans laquelle le gabarit de sujet pour les documents peut être généré.
1. **Nom du gabarit** : Le nom du gabarit peut être sélectionné dans le menu déroulant lors de la création d'un balisage, ou mise à jour dans les paramètres plus tard si nécessaire.
1. **Titre du sujet** : Le titre du sujet résultant après création du sujet à partir du gabarit de sujet pour les documents.
   Survolez votre souris sur l'icône "?" située à droite de la zone de titre pour voir comment vous pouvez personnaliser le titre de votre gabarit de sujet pour les documents avec les variables disponibles : `documentName`, `fileName`, `markupName` et `topicCreator`.

    <div class="intercom-container intercom-align-center"><img height="231" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-dbe5030f1082.png" style="height: auto;" width="300"/></div>

1. **Statut du sujet** : Le statut du sujet résultant après création du sujet à partir du gabarit de sujet pour les documents.
1. **Type de sujet** : Le type de sujet résultant après création du sujet à partir du gabarit de sujet pour les documents.
1. **Milestone** : Le milestone du sujet résultant après création du sujet à partir du gabarit de sujet pour les documents.
1. **Assigné à** : Le responsable du sujet résultant (membre du projet ou équipe) après création du sujet à partir du gabarit de sujet pour les documents. Différentes variables peuvent être utilisées ici, telles que `Document owner`, `File uploader`, `Markup creator`, `Publisher` et `Topic creator`.

    <div class="intercom-container intercom-align-center"><img height="228" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b3156a6c2724.png" style="height: auto;" width="150"/></div>

1. **Demandé par** : Le demandeur du sujet résultant après création du sujet à partir du gabarit de sujet pour les documents. Différentes variables peuvent être utilisées ici, telles que `Document owner`, `File uploader`, `Markup creator`, `Publisher` et `Topic creator`.

    <div class="intercom-container intercom-align-center"><img height="171" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-0c4680dfae06.png" style="height: auto;" width="150"/></div>

1. **Étiquettes** : Les étiquettes du sujet résultant après création du sujet à partir du gabarit de sujet pour les documents. Notez que vous pouvez extraire les étiquettes du document à partir duquel vous avez créé le balisage en utilisant la variable `Labels from documents` ci-dessous :

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Description** : La description du sujet résultant après création du sujet à partir du gabarit de sujet pour les documents. Cette section supporte le format Markdown et vous pouvez exploiter tout son potentiel pour formater le texte, créer des en-têtes personnalisés et des listes de contrôle.
    Survolez votre souris sur l'icône "?" située en haut à droite de la zone de description pour voir comment vous pouvez utiliser toutes les fonctionnalités disponibles (mentionner les coéquipiers et lier les sujets existants) et les variables (telles que `documentName`, `fileName`, `markupName` et `topicCreator` dans le cas du gabarit de sujet pour les documents).

     <div class="intercom-container intercom-align-center"><img height="349" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b8f3e2dabde9.png" style="height: auto;" width="300"/></div>

Une fois que vous avez terminé la configuration de votre nouveau gabarit de sujet pour les documents, vous pouvez cliquer sur le bouton "Enregistrer" en bas à droite.

## 6. **Nouveau gabarit de sujet pour les approbations**

Peut être utilisé sur les sujets générés après la fermeture d'un circuit d'approbation. _Accès requis :_ Statuts partagés activés (onglets Workspace et publié visibles sur les pages des documents et des modèles)

> **Note :** Cette option n'apparaît que si les workflows de statut actuel et de validation sont en cours d'utilisation. Les projets créés après le 2 octobre 2025 utilisent automatiquement les workflows de statut actuel et de validation.

Voici les différentes actions que vous devez suivre et les variables que vous pouvez entrer lors de la création d'un nouveau gabarit de sujet pour les approbations :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/07-new-approval-topic-template.png)

1. **Liste de sujets** : La liste de sujets dans laquelle le gabarit de sujet pour les approbations sera généré après la fermeture d'un circuit d'approbation.
1. **Nom du gabarit** : Le nom du gabarit d'un gabarit de sujet pour les approbations peut être sélectionné dans le menu déroulant d'un modèle de circuit d'approbation, ou mise à jour dans les paramètres plus tard si nécessaire.
1. **Titre du sujet** : Le titre du sujet résultant après la fermeture du circuit d'approbation associé.
   Survolez votre souris sur l'icône "?" située à droite de la zone de titre pour voir comment vous pouvez personnaliser le titre de votre gabarit de sujet pour les approbations avec les variables disponibles : `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName` et `topicCreator`.

    <div class="intercom-container intercom-align-center"><img height="272" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-6038b1d41fed.png" style="height: auto;" width="300"/></div>

1. **Statut du sujet** : Le statut du sujet résultant après la fermeture du circuit d'approbation associé.
1. **Type de sujet** : Le type de sujet résultant après la fermeture du circuit d'approbation associé.
1. **Milestone** : Le milestone du sujet résultant après la fermeture du circuit d'approbation associé.
1. **Assigné à** : Le responsable du sujet résultant (membre du projet ou équipe) lors de la fermeture du circuit d'approbation associé. Différentes variables peuvent être utilisées ici, telles que `Approval request approver`, `Approval requested approver team`, `Approval request submitter`, `Approval request submitter team`, `Document owner`, `File uploader`, `Markup creator`, `Markup creator team`, `Publisher`.

    <div class="intercom-container intercom-align-center"><img height="182" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b012d92ee132.png" style="height: auto;" width="150"/></div>

1. **Demandé par** : Le demandeur du sujet résultant après la fermeture du circuit d'approbation associé. Différentes variables peuvent être utilisées ici, telles que `Approval request approver`, `Approval requested approver team`, `Approval request submitter`, `Approval request submitter team`, `Document owner`, `File uploader`, `Markup creator`, `Markup creator team`, `Publisher`.

    <div class="intercom-container intercom-align-center"><img height="181" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d7986adac70c.png" style="height: auto;" width="150"/></div>

1. **Étiquettes** : Les étiquettes du sujet résultant après la fermeture du circuit d'approbation associé. Notez que vous pouvez extraire les étiquettes du document à partir duquel vous avez créé le balisage en utilisant la variable `Labels from documents` ci-dessous :

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Description** : La description du sujet résultant après la fermeture du circuit d'approbation associé. Cette section supporte le format Markdown et vous pouvez exploiter tout son potentiel pour formater le texte, créer des en-têtes personnalisés et des listes de contrôle.
    Survolez votre souris sur l'icône "?" située en haut à droite de la zone de description pour voir comment vous pouvez utiliser toutes les fonctionnalités disponibles (mentionner les coéquipiers et lier les sujets existants) et les variables (telles que `approvalRequestDueDate`, `approvalRequestFileLink`, `approvalRequestLink`, `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName`, `topicCreator`) dans le cas du gabarit de sujet pour les approbations).

     <div class="intercom-container intercom-align-center"><img height="449" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-f3f078b5d2af.png" style="height: auto;" width="300"/></div>

Une fois que vous avez terminé la configuration de votre nouveau gabarit de sujet pour les approbations, vous pouvez cliquer sur le bouton "Enregistrer" en bas à droite.
