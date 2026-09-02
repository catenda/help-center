# Journal des modifications 1 Catenda - Avril 2023

## 1. Articles

**Nouveaux articles :**

[Configuration requise du système et optimisation](https://intercom.help/bimsync-arena/en/articles/6921941-system-requirements-and-optimization)

[Intégration des modèles et documents Solibri](https://intercom.help/bimsync-arena/en/articles/6988148-solibri-models-and-documents-integration)

[Superposition 2D](https://intercom.help/bimsync-arena/en/articles/6921756-2d-overlay)

[Paramètres du compte](https://intercom.help/bimsync-arena/en/articles/6880968-account-settings)

[Redimensionnement des colonnes](https://intercom.help/bimsync-arena/en/articles/6887350-resizing-of-columns) [Support IFC dans Documents](https://intercom.help/bimsync-arena/en/articles/5658031-ifc-support-in-documents) [Quoi de neuf dans Catenda Hub ?](https://intercom.help/bimsync-arena/en/articles/7150907-what-s-new-in-catenda-hub) [Quoi de neuf dans Catenda Site ?](https://intercom.help/bimsync-arena/en/articles/7161448-what-s-new-in-catenda-site)

<a class="intercom-content-link" href="" target="_blank">Paramètres du projet</a>
[Affichage tableau dans un issue board](https://support.catenda.com/en/articles/6941099-table-view-in-an-issue-board)

[Affichage liste dans un issue board](https://support.catenda.com/en/articles/6941232-list-view-in-an-issue-board)

**Articles qui ont changé :**

[Paramètres de la Visionneuse 3D](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings)

[Approbation de documents](https://support.catenda.com/en/articles/5784717-document-approval)

[Authentification multifactorielle](https://support.catenda.com/en/articles/4969891-multi-factor-authentication)

## 2. Problèmes résolus

**Problèmes d'importation :**

- Les fichiers IFC avec entités manquantes exportés de MagiCAD peuvent maintenant être importés plus facilement.
- Les fichiers IFC avec caractères non Unicode dans IfcPerson et IfcOrganization ne feront plus échouer les grilles

**Problèmes de la Visionneuse :**

- Les modèles peuvent à nouveau être pivotés sans problème. (Le champ de rotation était vide pendant une courte période)
- Les objets peuvent à nouveau être supprimés (Les modèles ont été chargés deux fois pendant une courte période)
- Les grilles exportées de Revit avec l'exporteur IFC4 officiel sont maintenant visibles
  La première mesure effectuée est maintenant immédiatement visible en allant à l'inspection sur les écrans où il n'y a pas de place pour afficher le panneau d'inspection et la Visionneuse 3D en même temps.
- Les objets peuvent maintenant être rendus transparents à nouveau. (Rendre transparent aurait caché d'autres objets à la place pendant un certain temps)
- Les panneaux comme les propriétés restent maintenant ouverts même si vous cliquez sur un espace vide et revenez au même objet

**Autres problèmes :**

- Le déplacement de fichiers vous permet maintenant de naviguer à nouveau à partir du dossier racine (Le dossier racine n'affichait pas les contenus pendant une courte période)
- Le configurateur d'étages vous permet maintenant de placer à nouveau les dessins qui avaient des emplacements avant la refonte.
