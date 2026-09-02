# Flux d'approbation : Règles d'administration

> Guide destiné aux administrateurs détaillant les règles de configuration, les options de configuration flexible, les verrous de paramètres post-soumission et l'impact des modifications de configuration du projet sur les demandes d'approbation actives.

Les flux d'approbation établissent des processus structurés d'examen et de validation pour les révisions de documents partagés au sein d'un projet. La configuration des flux de travail nécessite d'équilibrer les règles de modèle pour les futures demandes d'examen avec les configurations d'équipe de projet qui pilotent les approbations actives et continues.

> **Remarque :** Seuls les administrateurs du projet peuvent accéder aux paramètres de configuration du flux de travail, créer de nouveaux flux d'approbation ou modifier les paramètres de flux de travail existants.

Les rubriques suivantes sont décrites dans cet article :

## 1. **1. Comment les modifications du projet affectent les flux d'approbation**

Lorsqu'un modèle de flux de travail est modifié ou que les configurations du projet sont ajustées (comme l'ajout ou la suppression de membres d'équipe dans les paramètres du projet), les modifications affectent différemment les demandes d'approbation futures et en cours :

### 1.1 **1.1 Éditions de modèle de flux de travail**

Les modifications apportées à un modèle de flux de travail (comme l'ajout d'équipes de soumetteurs) s'appliquent aux **futures** demandes d'approbation créées après la mise à jour. Elles ne réécrivent pas la structure des demandes actives déjà en cours.

### 1.2 **1.2 Mises à jour de l'adhésion aux équipes**

L'ajout ou la suppression de membres d'équipe dans les paramètres du projet prend effet immédiatement sur les approbations **actives et continues**. Si une étape d'examen est bloquée parce qu'une équipe est vide, l'ajout d'un utilisateur à cette équipe lui permet d'intervenir immédiatement et de reprendre l'examen.

### 1.3 **1.3 Dépendances rompues**

L'archivage d'un statut de document, la suppression d'une équipe ou l'archivage d'un modèle de rubrique d'approbation ailleurs dans les paramètres du projet peut entraîner des erreurs de validation lors de l'enregistrement des mises à jour du flux de travail ou arrêter la création de rubriques sur les approbations en cours.

## 2. **Configuration avant soumission (création initiale)**

Lorsqu'un nouveau flux d'approbation est créé pour la première fois, tous les paramètres fondamentaux doivent être configurés avant que le modèle puisse être enregistré et activé.

Les rubriques suivantes sont décrites dans cette section :

### 2.1 **2.1 Champs obligatoires et banneau d'avertissement avant soumission**

Si un champ obligatoire est incomplet lors de la tentative d'enregistrement d'un nouveau flux de travail, le système affiche un banneau d'avertissement avant soumission en haut de la page et bloque la création du modèle. Les champs obligatoires comprennent :

- **2.1.1 Titre du flux de travail**
  Un nom unique et descriptif pour le flux de travail.
- **2.1.2 Équipes de soumetteurs**
  Au moins une équipe de projet assignée pour lancer les demandes d'approbation.
- **2.1.3 Étapes d'examen**
  Au moins une étape d'examen contenant une équipe d'examinateurs assignée et une durée d'au moins **1 jour ouvrable**.
- **2.1.4 Approbation finale**
  Une équipe d'examen final assignée aux côtés de deux statuts de documents de projet actifs — un mappé pour les révisions approuvées et un pour les révisions rejetées.

### 2.2 **2.2 Limites du système et règles d'adhésion aux équipes**

**2.2.1 Limites de pipeline** Un seul flux de travail prend en charge jusqu'à **10 étapes d'examen séquentielles** et un total de **20 équipes d'examinateurs** dans le pipeline.

**2.2.2 Sélection d'équipe vs. présence de membres** Lors de la création initiale, le système valide que les équipes de soumetteurs, d'examinateurs et d'examinateurs finaux sont sélectionnées. Cependant, il **ne vérifie pas** si ces équipes contiennent réellement des membres.

**2.2.3 Exigences d'exécution et approbation automatique** Pour rendre une demande d'approbation complétable du début à la fin :

- Au moins un membre d'une équipe de soumetteurs doit être présent dans une équipe de soumetteurs assignée pour lancer la demande.
- Au moins un membre d'une équipe d'examinateurs doit être présent dans une équipe d'examinateurs assignée, sauf si l'approbation automatique est activée pour cette étape.
- Si l'approbation automatique est configurée, une étape assignée à une équipe vide approuvera automatiquement et progressera une fois que la date d'échéance de l'étape sera atteinte.
- Si l'approbation automatique n'est pas configurée, une équipe d'examinateurs vide arrêtera la demande d'approbation jusqu'à ce qu'un membre soit ajouté à cette équipe.
- Au moins un membre d'une équipe d'examinateurs finaux doit être présent pour rendre le résultat final.

**2.2.4 Droits d'administrateur** Les administrateurs du projet ne disposent pas de droits opérationnels automatiques. Pour effectuer des actions lors d'une approbation, un administrateur doit être un membre explicite de l'équipe concernée :

- **Équipe de soumetteurs**
  Obligatoire pour lancer une demande d'approbation.
- **Équipe d'examinateurs**
  Obligatoire pour indiquer ou soumettre une validation d'examen.
- **Équipe d'examinateurs finaux**
  Obligatoire pour rendre la décision finale et clôturer l'approbation.

## 3. **3.** **Opérations flexibles (avant et après soumission)**

Certaines opérations restent flexibles et peuvent être ajustées lors de la configuration initiale ou mises à jour à tout moment après l'activation d'un flux de travail. Ces opérations flexibles se divisent en deux catégories distinctes : **Paramètres de modèle de flux de travail** (modifiés directement sur la page de configuration du flux de travail) **Gestion des membres de l'équipe du projet** (modifiés sur la page Équipes du projet pour tous les rôles du flux de travail).

Les rubriques suivantes sont décrites dans cette section :

### 3.1 **3.1** **Modifications de modèle de flux de travail**

Ces paramètres peuvent être modifiés dans le menu de configuration du flux de travail à tout moment, affectant directement les futures demandes d'approbation :

**3.1.1 Équipes de soumetteurs** Les administrateurs peuvent ajouter ou supprimer des équipes de soumetteurs après soumission pour contrôler quelles équipes de projet sont autorisées à lancer de nouvelles demandes d'approbation selon ce flux de travail.

**3.1.2 Modèles de rubriques d'approbation** Les modèles de rubriques d'approbation liés à des résultats spécifiques (_Approuvé_, _Approuvé avec commentaires_ ou _Rejeté_) peuvent être ajoutés, mis à jour ou dissociés à tout moment pour contrôler le suivi des problèmes lors des examens.

### 3.2 **3.2** **Gestion des membres de l'équipe du projet (s'applique à tous les types d'équipes)**

L'ajout ou la suppression d'utilisateurs individuels s'effectue sur la page **Équipes du projet** et ne nécessite pas de modifier ou de réenregistrer le modèle de flux de travail. De façon cruciale, la gestion des membres s'applique à **tous les trois types d'équipes de flux de travail**, impactant directement qui peut effectuer des actions :

**3.2.1 Équipes de soumetteurs** L'ajout ou la suppression de membres modifie qui peut sélectionner le flux de travail pour lancer de nouvelles demandes d'approbation.

**3.2.2 Équipes d'examinateurs** L'ajout ou la suppression de membres modifie qui peut accéder aux étapes d'examen actives, ajouter des annotations/commentaires et soumettre des indications de validation d'étape.

**3.2.3 Équipes d'examinateurs finaux** L'ajout ou la suppression de membres modifie qui peut rendre la décision finale et clôturer une demande d'approbation active.

## 4. **4.** **Règles de post-soumission et verrouillage des paramètres**

Une fois qu'un modèle de flux de travail est enregistré et soumis pour la première fois, les paramètres structurels clés se verrouillent pour assurer des règles d'évaluation cohérentes dans les demandes d'approbation.

Les rubriques suivantes sont décrites dans cette section :

### 4.1 **4.1 Paramètres verrouillés vs. modifiables**

**4.1.1 Paramètres verrouillés** Les paramètres de temps, les étapes d'examen, les équipes d'examinateurs assignées, les durées des étapes, les bascules d'approbation automatique, les équipes d'approbation finale et les statuts de documents finals mappés ne peuvent pas être modifiés après la soumission initiale.

**4.1.2 Paramètres modifiables** Seuls le titre du flux de travail, les assignations des équipes de soumetteurs et les modèles de rubriques d'approbation liés restent modifiables après soumission.

### 4.2 **4.2 Dépendances externes rompues et résolutions**

L'enregistrement de **toute** modification post-soumission d'un flux de travail existant (comme la mise à jour du titre) déclenche une vérification complète de revalidation dans l'ensemble du modèle. Si un élément utilisé dans le flux de travail a été archivé ou supprimé dans les paramètres du projet après la création initiale, la revalidation échoue jusqu'à résolution.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 130px; padding: 8px;"><h3 id="h_5956ae53a6"><b>Problème de dépendance (Blocage)</b></h3></td><td style="background-color: #e3e7fa80; width: 244px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_9b11612daf"><b>Impact et comportement du système</b></h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_f245fc1acb"><b>Résolution</b></h3></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_aac48f326c"><b>Statuts de documents archivés</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Le champ de statut mappé apparaît vide dans la configuration du flux de travail. Les documents publiés reçoivent le statut archivé (affiché en barré). Les mises à jour du flux de travail sont bloquées.</p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Récupérer (désarchiver) le statut</b> dans les paramètres de document.<br/>Les statuts verrouillés ne peuvent pas être modifiés ou remplacés dans le flux de travail après soumission.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_c963d16fb5"><b>Équipes de projet supprimées</b></h3></td><td style="background-color: #e8e8e880; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Une équipe de soumetteurs, d'examinateurs ou d'approbation finale a été supprimée sur la page Équipes du projet.</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Équipes de soumetteurs</b><br/>Modifiez le flux de travail directement pour assigner une nouvelle équipe active.<br/>​</p><p><b>Équipes d'examinateurs / Équipes finales</b><br/>Verrouillées. Si aucune équipe ne reste dans une étape et que l'approbation automatique est désactivée, les approbations en cours se figent indéfiniment. Archivez le flux de travail, supprimez les documents et créez un nouveau flux de travail.</p></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_8d948d5649"><b>Modèles de rubriques d'approbation archivés</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Un modèle de rubrique d'approbation lié à un résultat de flux de travail a été archivé sur la page Modèles de rubriques.</p><p></p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Récupérer (désarchiver)</b> le modèle sur la page Modèles de rubriques <b>OU</b> modifiez le flux de travail directement pour sélectionner/ajouter un nouveau modèle de remplacement actif.</p></td></tr></tbody></table></div>

### 4.3 **4.3 Archivage et restauration des flux de travail**

**4.3.1 Archivage des flux de travail** Masque le flux de travail actif dans les menus de création afin que les membres du projet ne puissent pas le sélectionner pour de nouvelles demandes.

**4.3.2 Restauration des flux de travail** Réactive un flux de travail archivé dans les menus de création pour les équipes de soumetteurs assignées.

## 5. **5.** **Impact sur les approbations en cours et les cycles de vie des équipes**

Lorsque les paramètres du projet ou les adhésions aux équipes changent pendant que les demandes d'approbation sont activement en cours, le système gère l'accès, la création de rubriques et la progression du flux de travail selon des règles spécifiques.

Les rubriques suivantes sont décrites dans cette section :

### 5.1 **Ajout et suppression de membres d'équipe**

Les membres du projet peuvent être ajoutés ou supprimés des équipes de flux de travail sur la page **Équipes du projet** à tout moment sans modifier le modèle de flux de travail lui-même.

**5.1.1 Membres d'équipe de soumetteurs** L'ajout d'un utilisateur à une équipe de soumetteurs lui permet de créer de nouvelles demandes à l'avenir. Cependant, l'adhésion à une équipe de soumetteurs n'accorde jamais une visibilité partagée dans les demandes créées par des collègues — l'accès à une demande soumise reste strictement personnel au créateur individuel.

**5.1.2 Membres d'équipe d'examinateurs** L'ajout d'un utilisateur à une équipe d'examinateurs lui accorde immédiatement l'accès aux demandes d'approbation actives actuellement à cette étape d'examen. La suppression de tous les membres d'une équipe d'examinateurs figera les demandes en cours à cette étape jusqu'à l'ajout d'un nouveau membre — à moins que l'**approbation automatique** soit activée pour cette étape, auquel cas la demande approuvera automatiquement et progressera lorsque la date limite de l'étape passera.

**5.1.3 Membres d'équipe d'examinateurs finaux** L'ajout d'un utilisateur à une équipe d'examinateurs finaux lui accorde immédiatement l'accès pour rendre les décisions finales sur les demandes actives atteignant l'étape d'approbation finale. La suppression de tous les membres d'une équipe d'examinateurs finaux gèle les demandes en cours à l'étape finale jusqu'à l'ajout d'un utilisateur (l'approbation automatique n'est pas disponible pour les étapes d'examen final).

### 5.2 **5.2** **Suppression d'équipes à partir des paramètres du projet**

Les équipes de projet supprimées ne peuvent pas être récupérées. Si une équipe assignée à un flux de travail est supprimée des paramètres du projet, l'impact opérationnel dépend du rôle de l'équipe dans le cycle de vie du flux de travail :

**5.2.1 Équipes de soumetteurs supprimées** Les équipes de soumetteurs restent modifiables après soumission. Un administrateur peut modifier directement la configuration du flux de travail et assigner une nouvelle équipe de soumetteurs active.

**5.2.2 Équipes d'examinateurs supprimées** Les étapes d'examen sont verrouillées après soumission.

- **Si d'autres équipes assignées restent**
  L'étape d'examen continue à fonctionner pour les équipes restantes.
- **Si aucune équipe ne reste et que l'approbation automatique est ACTIVÉE**
  L'étape approuve automatiquement et progresse une fois que la date d'échéance de l'étape est atteinte.
- **Si aucune équipe ne reste et que l'approbation automatique est DÉSACTIVÉE**
  Les demandes d'approbation en cours se figent indéfiniment à cette étape d'examen.

**5.2.3 Équipes d'examinateurs finaux supprimées** Les équipes d'approbation finale sont verrouillées après soumission, et l'approbation automatique **n'est pas** disponible pour les étapes d'examen final. Si toutes les équipes d'examinateurs finaux sont supprimées, les demandes d'approbation en cours sont figées indéfiniment.

**5.2.4 Action recommandée pour les flux de travail bloqués ou non réalisables** Lorsqu'une étape d'examen se bloque sans équipes restantes (et que l'approbation automatique est désactivée), ou lorsque toutes les équipes d'examinateurs finaux sont supprimées, la recommandation est d'archiver le flux de travail d'approbation cassé et de supprimer tous les documents strictement à partir des demandes d'approbation ouvertes qui suivent ce flux de travail spécifique. Optionnellement, un nouveau flux de travail d'approbation peut être créé si un remplacement est nécessaire.

### 5.3 **5.3** **Archivage et reconfiguration du modèle de rubrique d'approbation**

Les modèles de rubriques d'approbation sont configurés séparément pour chaque résultat de décision (par exemple, _Approuvé_, _Approuvé avec commentaires_ ou _Rejeté_). Le système traite les modifications du modèle de rubrique d'approbation indépendamment par résultat :

**5.3.1 Isolation spécifique au résultat** L'archivage ou la modification d'un modèle de rubrique d'approbation pour un résultat de décision n'affecte que ce résultat spécifique. Tous les autres résultats avec des modèles de rubriques d'approbation intacts continuent à créer des rubriques comme prévu.

**5.3.2 Archivage d'un modèle de rubrique d'approbation lié** Si un modèle de rubrique d'approbation assigné à un résultat est archivé, les demandes d'approbation en cours suivant ce flux de travail (et les nouvelles demandes soumises sans lien) **ne génèreront pas** de rubriques si ce résultat est sélectionné.

**5.3.3 Restauration d'un modèle de rubrique d'approbation archivé** La récupération (désarchivage) du modèle de rubrique d'approbation original réactive automatiquement la création de rubriques selon ce modèle sur toutes les demandes d'approbation associées.

**5.3.4 Configuration d'un modèle de rubrique d'approbation différent** Si un administrateur met à jour le flux de travail après soumission pour assigner un modèle de rubrique d'approbation **différent** actif, les demandes d'approbation en cours initiées avant la modification **ne génèreront pas** de rubriques en utilisant le nouveau modèle. Seules les nouvelles demandes d'approbation soumises après la reconfiguration généreront des rubriques selon le modèle nouvellement assigné.
