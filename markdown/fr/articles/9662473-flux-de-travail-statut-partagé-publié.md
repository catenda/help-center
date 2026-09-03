# Flux de travail Statut Partagé -> Publié

## 1. **Disponibilité sur les projets**

Le nouveau flux de travail de statut est une fonctionnalité à la demande qui peut être demandée à être activée pour les projets en cours. Les nouveaux projets créés à partir d'un projet de modèle où le nouveau flux de travail de statut est activé auront également le nouveau flux de travail de statut activé.

**Les « brouillons » seront supprimés et ne seront plus disponibles.**

## 2. **Activation du flux de travail de statut avec révisions « partagées »**

L'ancien flux de travail de statut (hérité) avec « brouillons » sera remplacé par le nouveau flux de travail de statut (avec statuts partagés) pour les projets en cours qui n'utilisent pas le flux de travail de statut hérité. Les statuts partagés peuvent être activés dans le menu du flux de travail de statut de la page de paramètres du document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/01-enabling-status-workflow-with-shared-revisions.png)

La mise à niveau du flux de travail de statut avec « brouillons » au flux de travail de statut avec documents « partagés » produit ces effets ;

## 3. **Catenda Hub**

**Statut partagé** Les téléchargements commenceront tous avec un statut partagé, une fois que les statuts partagés seront disponibles dans le projet. Après le téléchargement, les documents partagés peuvent être publiés.

**Documents brouillon** Les brouillons seront supprimés, donc les nouveaux brouillons ne peuvent plus être téléchargés. Les brouillons existants peuvent toujours être utilisés dans les anciens projets (avec des limitations)

🖥️  _Espace de travail et_ ✔️ _onglets Publiés_ Des onglets séparés (espace de travail et publié) seront disponibles dans la zone de document, où l'onglet publié ne fournira que les révisions publiées.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/02-catenda-hub.png)

Une nouvelle numérotation de révision apparaîtra (majeure.mineure). #0.1, #0.2 et ainsi de suite pour les **révisions partagées** et #1, #2, #3 et ainsi de suite pour les **révisions publiées**.

### 3.1 _Contrôle d'accès_

Les droits d'accès peuvent être définis lors de la publication des révisions partagées. Cela permet aux utilisateurs de publier des révisions partagées et de modifier les statuts publiés. Le contrôle d'accès apparaîtra au niveau du dossier/document pour accorder aux utilisateurs le droit de publier les révisions de documents avec accès en écriture. Les droits d'accès pour l'affichage de la révision partagée seront disponibles. Ici, vous pouvez interdire aux utilisateurs ayant « accès en lecture » de voir les révisions partagées.

**Approbations** Seules les révisions partagées peuvent être ajoutées à une demande d'approbation

**Collections** Les collections ne peuvent être utilisées que pour les révisions publiées

**Modèles de document** La zone de modèle affichera les onglets (espace de travail et publié) comme dans la zone de document. Les droits d'accès seront hérités des documents.

> **Remarque :** Veuillez informer les membres de votre projet de ces modifications lorsque vous activez cette fonctionnalité sur les projets existants.

## 4. **Clients API**

**Dernière révision** La dernière révision du document (peut être partagée ou publiée) est récupérée sauf indication contraire dans l'appel API

**Paramètres de téléchargement par défaut** Les téléchargements via l'API utiliseront par défaut une révision partagée, une fois que les statuts partagés seront disponibles dans le projet.

**Modifications de numéro de révision** Les numéros de révision seront incompatibles avec les numéros de révision (majeure.mineure) sur Catenda Hub. Vous devrez mettre à jour votre application.

> **Remarque :** Veuillez informer les membres de votre projet de ces modifications lorsque vous activez cette fonctionnalité sur les projets existants.

Cliquez [ici](https://support.catenda.com/en/articles/12289689-status-workflow-api-updates) pour en savoir plus sur les modifications de l'API
