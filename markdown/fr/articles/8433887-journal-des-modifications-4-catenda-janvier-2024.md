# Journal des modifications 4 Catenda - janvier 2024

> Nouvelles informations et modifications mineures

Bonjour à tous,

cela fait quelques beaux mois depuis le dernier journal des modifications. Nous espérons que vous avez tous passé de bonnes vacances d'hiver ! 🎄🤶🧑‍🎄❄️ Et bienvenue en 2024!🎇 Nous espérons que nous serons en mesure d'apporter de nombreuses modifications et améliorations cette année aussi ! Dans cet article, vous trouverez des mises à jour sur les sujets suivants : [Articles](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_5be2a02999) - [Sujets résolus](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_d238d9111d) - [Nouvelles versions](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_d238d9111d)

## 1. **Articles**

Lorsque de nouvelles fonctionnalités sont déployées et que des bogues sont corrigés, les articles sont mis à jour avec les modifications apportées. Veuillez trouver les articles suivants qui ont été créés et modifiés depuis le dernier journal des modifications.

### 1.1 **Nouveaux articles :**

**Démarrage et FAQ** [Ordre de tri des listes](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) [Structuration des documents](https://support.catenda.com/en/articles/8542598-structuring-documents)

**Page d'accueil** [Page Organisations](https://support.catenda.com/en/articles/8281910-organizations-page)

**Sujets** [Historique du sujet](https://support.catenda.com/en/articles/8613038-issue-history)

**Documents** [Documents](https://support.catenda.com/en/articles/8461918-documents) [Comparaison PDF](https://support.catenda.com/en/articles/8461650-pdf-compare) [Filtrage sur la page des approbations](https://support.catenda.com/en/articles/8551740-filtering-on-the-approvals-page)

**Modèles et 3D** [Signet](https://support.catenda.com/en/articles/8471481-bookmark)

**Paramètres du projet** [Création d'un champ personnalisé](https://support.catenda.com/en/articles/8445575-creating-a-custom-field) [Page Champ personnalisé](https://support.catenda.com/en/articles/8445588-custom-field-page)

### 1.2 **Articles qui ont changé :**

Démarrage et FAQ [Enregistrement des filtres](https://support.catenda.com/en/articles/8551755-saving-filters)

Sujets [ACL des tableaux de sujets](https://support.catenda.com/en/articles/4670296-issue-boards-acl)

Documents [Page Documents](https://support.catenda.com/en/articles/8204673-documents-page) [Modèles en tant que documents](https://support.catenda.com/en/articles/8064548-models-as-documents) [Filtrage sur la page des documents](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page)

Modèles [Page Signets](https://support.catenda.com/en/articles/4670281-bookmarks-page) [Création d'un nouveau signet](https://support.catenda.com/en/articles/4670269-creating-a-new-bookmark) [Modèles en tant que documents](https://support.catenda.com/en/articles/8064548-models-as-documents)

Bibliothèques <a class="intercom-content-link" href="" target="_blank">Bibliothèque de liens</a>

Paramètres [Page Membres](https://support.catenda.com/en/articles/4670291-members-page)

## 2. **Bogues résolus**

Grâce à vos précieux commentaires, nous avons pu corriger de nombreux sujets que vous aviez peut-être ou non remarqué. Voici une liste des petits changements qui ont été apportés par l'équipe de développement suite à des conversations avec les utilisateurs.

### 2.1 **Sujets**

- Les champs personnalisés déroulants comptant jusqu'à 10 valeurs requises peuvent désormais également être filtrés.
- Les exportations PDF des sujets n'affichent plus certaines images en double.
- Les filtres des champs personnalisés sont maintenant affichés même si le champ personnalisé est défini comme obligatoire.
- Les images jointes aux commentaires de sujet après le 16 novembre s'affichent maintenant dans le même ordre que celui des commentaires de sujet dans la boîte de dialogue d'aperçu.
- L'heure d'exportation dans l'exportation PDF indique maintenant UTC derrière, de sorte que l'utilisateur peut savoir dans quel fuseau horaire se trouve l'horodatage.
- Les modèles qui sont supprimés dans la plage horaire entre la préparation et l'activation d'une migration de modèles en tant que documents seront maintenant correctement supprimés lors de la migration.

### 2.2 **Documents**

- Les lettres lituaniennes dans les documents importés à partir d'importations ZIP ne seront plus corrompues à la suite d'une attaque par fichier ZIP.
- Les bulles de texte peuvent à nouveau être placées pour les utilisateurs dont l'application MFA est appliquée.
- Les annotations en surbrillance des fichiers pdf s'affichent maintenant correctement dans la visionneuse pdf après leur téléchargement.
- Les fichiers PDF peuvent à nouveau être enregistrés avec des annotations et des commentaires.
- Les documents qui ne se chargeaient pas pour les utilisateurs dont l'application MFA est appliquée se chargent maintenant à nouveau.

### 2.3 **Modèles**

- Le bouton Supprimer le modèle est à nouveau visible.
- Il n'existe maintenant aucun moyen de masquer les modèles si les modèles en tant que documents étaient activés sans migrer le projet.
- L'e-mail de notification d'importation du modèle terminée indique maintenant l'importation terminée sur \<model> au lieu de nouvelle révision dans le modèle pour plus de clarté.
- Il est maintenant possible de sélectionner uniquement les documents pdf dans le configurateur d'étage où pdf.
- Il n'est plus possible d'ajouter des documents non-pdf au configurateur d'étage. (qui n'accepte que les PDF de toute façon)

## 3. **Voix des utilisateurs complétées**

### 3.1 **Sujets**

- Vous recevez maintenant une notification lorsqu'une équipe dont vous faites partie est mentionnée dans un sujet
- Si vous cliquez sur afficher le marqueur en 2D à l'emplacement d'un sujet, votre visionneuse 2D se centrera maintenant sur ce marqueur au lieu d'afficher simplement le marqueur sélectionné sur l'étage de droite.
- La largeur de la boîte de dialogue de sélection du modèle dans le commentaire d'un sujet s'adapte maintenant à la largeur du nom du modèle. Auparavant, les longs noms de modèle étaient coupés et devaient être survolés pour être vus.
- Il est maintenant possible de voir à quoi ressemblait une description avant sa modification en cliquant sur la zone de description modifiée dans l'historique du sujet.
- Les images n'apparaissent plus deux fois dans les exportations PDF des sujets plus anciens

### 3.2 **Documents**

- L'ACL du document est maintenant reflétée dans la section modèles pour les projets qui ont les modèles activés en tant que documents
- Vous pouvez maintenant voir combien de documents se trouvent dans une collection.
- Il est maintenant possible de s'accrocher aux points médians et extrémité des lignes dans les dessins PDF.
- Il est maintenant possible d'afficher un aperçu des formats de fichier .odt et .ods.

### 3.3 **Modèles**

- Il est maintenant possible de définir l'ACL par modèle au lieu de pour tous les modèles.

Cela signifie que vous pouvez masquer les modèles des personnes dans la section modèles.

- Avec les modèles en tant que documents, vous pouvez ajouter des étiquettes aux modèles.
- Avec les modèles en tant que documents, vous pouvez structurer les modèles dans des dossiers de la section documents.
- Avec les modèles en tant que documents, vous pouvez voir la taille du fichier du modèle
- Avec les modèles en tant que documents, vous pouvez utiliser la fonction de convention de nommage avec les modèles
- Il est à nouveau possible de voir les révisions précédentes des modèles dans le sélecteur de révision

### 3.4 **Paramètres du projet**

- Les groupes d'étiquettes peuvent maintenant être supprimés.
- Il est maintenant possible de supprimer les étiquettes connectées aux sujets/documents.
- Les groupes d'étiquettes peuvent être modifiés.
  Vous pouvez trouver le crayon de modification dans le menu d'information de droite après avoir sélectionné le groupe d'étiquettes dans l'onglet groupes.
- Il est maintenant possible de créer plusieurs étiquettes à la fois.
  Notez le bouton d'importation multiple dans le nouveau menu d'étiquette.
- Il est maintenant possible de supprimer plusieurs étiquettes à la fois.
- Les étiquettes peuvent être filtrées et les filtres peuvent être enregistrés.
- Il est maintenant possible d'ajouter de nouveaux groupes d'étiquettes
- Il est possible d'ajouter des groupes d'étiquettes sans les ajouter d'abord à une étiquette.
- Il est maintenant possible de rechercher sur la page des étiquettes.
- Les administrateurs pourront maintenant fusionner les étiquettes. L'option se trouve en sélectionnant plus d'une étiquette sur la page des étiquettes.

### 3.5 **Général**

- La création de nouveaux projets à partir de projets de modèle a été améliorée. Il est maintenant possible d'apporter les parties suivantes d'un projet à un nouveau projet :
  - Structure des dossiers
  - Configuration du statut du document
  - Contrôle d'accès du tableau des documents et des sujets
  - Champs personnalisés et conventions de nommage

## 4. **Nouvelles versions** - Catenda Site, Plugins et intégrations

**Catenda Hub :**

- Les modèles en tant que documents ont maintenant été entièrement publiés.
- Les problèmes ont été renommés en sujets.

_Catenda Site :_ [App store](https://apps.apple.com/us/app/catenda-site/id1449579790) [Play store](https://play.google.com/store/apps/details?id=no.catenda.bimsyncmobile)

**Nouvelle version 3.3.1**

- Corrections de bogues

**Nouvelle version 3.3.0**

- _Liens profonds_ - Les URL du site Web Hub s'ouvriront directement dans l'application Site.
- _Filtrage des sujets_ - Nouvelle option de filtrage par jalon.
- _Mention d'utilisateur_ - Trouvez et sélectionnez rapidement un utilisateur à mentionner dans les sujets à partir de la barre d'outils.
- _Balisage du texte_ - Appliquez facilement du texte enrichi à vos sujets à partir de la barre d'outils.
- _Centrer le marqueur 2D_ - L'ouverture d'un marqueur à partir d'un sujet centrera la vue sur l'emplacement du marqueur.
- Support de la langue vietnamienne. 🇻🇳

**Nouvelle version 3.4.0**

- Les problèmes ont été renommés en sujets
- Corrections de bogues

**Intégration Sharepoint :**

- Vous pouvez maintenant vous connecter à votre compte Catenda via une fenêtre contextuelle du navigateur au lieu d'attendre un e-mail.
