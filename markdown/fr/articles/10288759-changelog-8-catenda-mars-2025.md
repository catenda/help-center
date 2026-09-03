# Changelog 8 Catenda - Mars 2025

Bonjour à tous, j'espère que vous avez tous pu survivre aux froids mois d'hiver. Le soleil a heureusement commencé à briller de plus en plus et nous nous préparons pour le printemps ! Depuis le dernier changelog, vous utilisez Catenda plus que jamais. Cela nous a permis de nous concentrer sur la garantie que tout fonctionne correctement, même lorsque des personnes du monde entier sont actives avec leurs projets en même temps ! De nombreuses pages de Catenda s'ouvrent maintenant plus rapidement qu'avant. Certaines même 10 à 100 fois plus rapides ! Beaucoup d'entre vous nous laissez savoir que vous remarquez des ralentissements dans certaines situations et nous surveillons maintenant cela plus que jamais pour vous assurer la meilleure expérience possible. Si vous remarquez que quelque chose prend plus longtemps que prévu, veuillez nous faire savoir sur quelle page vous l'avez remarqué et quand vous l'avez remarqué pour que nous puissions vous aider. 🚅📈✈️🌍

Dans cet article, vous trouverez des mises à jour sur les points suivants :

_[Articles](https://support.catenda.com/en/articles/9285880-changelog-6-catenda-august-2024#h_a8cc7b1921) - [Bogues résolus](https://support.catenda.com/en/articles/9285880-changelog-6-catenda-august-2024#h_58dfb1b852) - [Nouvelles versions](https://support.catenda.com/en/articles/9285880-changelog-6-catenda-august-2024#h_25203946b2)_

## 1. **Articles**

À mesure que de nouvelles fonctionnalités sont déployées et que les bogues sont corrigés, les articles sont mis à jour avec les modifications apportées. Veuillez trouver les articles suivants qui ont été créés et modifiés depuis le dernier changelog.

### 1.1 **Nouveaux articles :**

**Commencer et FAQ** [FAQ de l'outil d'organisation](https://support.catenda.com/en/articles/10475849-organization-tool-faq)

**Sujets** [Contrôle d'accès à la liste de sujets](https://support.catenda.com/en/articles/4670296-topic-board-access-control) [Paramètres de la liste de sujets](https://support.catenda.com/en/articles/4670277-topic-board-settings)

**Plugins et intégrations** [Application SharePoint Catenda - WebPart](https://support.catenda.com/en/articles/10538168-catenda-sharepoint-application-webpart) [Catenda en tant qu'application](https://support.catenda.com/en/articles/10695677-catenda-as-an-application) [Ajouter à l'écran d'accueil](https://support.catenda.com/en/articles/10741601-add-to-home-screen) [Support du navigateur système écran d'accueil](https://Home-screen%20system-browser%20support)

### 1.2 **Articles qui ont changé :**

**Commencer** [Commencer sur Catenda Hub](https://support.catenda.com/en/articles/9030303-getting-started-on-catenda-hub) [Instantanés](https://support.catenda.com/en/articles/10345863-snapshots) [Recommandation matérielle](https://support.catenda.com/en/articles/6921941-hardware-recommendation) [Filtrage des notifications et fonctionnalités](https://support.catenda.com/en/articles/8304417-notification-filtering-and-functionality) [Accepter une invitation pour rejoindre un projet](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project) [Créer un compte](https://support.catenda.com/en/articles/8412895-creating-an-account)

**Questions fréquemment posées** [Y a-t-il une limite de taille pour les fichiers IFC ?](https://support.catenda.com/en/articles/4670324-is-there-a-size-limit-for-ifc-files)

**Page principale** [Page Utilisateurs - Outil d'organisation](https://support.catenda.com/en/articles/8508311-users-page-organization-tool) [Localisation et fonctionnalité de la bulle d'assistance](https://Support%20button%20location%20and%20functionality)

**Sujets** [Affichage en liste dans une liste de sujets](https://support.catenda.com/en/articles/6941232-list-view-in-a-topic-board) [Affichage en tableau dans une liste de sujets](https://support.catenda.com/en/articles/6941099-table-view-in-an-topic-board) [Corps du sujet - Le contenu d'un sujet](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic)

**Documents** [Actions dans un document](https://support.catenda.com/en/articles/9323521-actions-in-a-document) [Codes QR sur les PDF dans Catenda](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda)

**Plugins et intégrations** [Plugins et intégrations Catenda](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations) [Application SharePoint Catenda](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application)

## 2. **Bogues résolus**

Grâce à vos précieux commentaires, nous avons pu éliminer de nombreux sujets que vous ayez ou non remarqué. Voici une liste des petites modifications apportées par l'équipe de développement à la suite de conversations avec les utilisateurs.

### 2.1 **Documents**

- Les documents de plus de 1 Go peuvent désormais être téléchargés à nouveau sans erreur
- Correction d'un problème où les révisions de document créées exactement au même moment ne montraient aucun document. Les documents sont maintenant chargés dans une carte au lieu d'un par un, ce qui réduit considérablement les temps de chargement. Cela rend la page rapide à charger et permet à nos serveurs de mieux gérer toutes vos demandes lorsque beaucoup de personnes utilisent Catenda en même temps.
- Les nuages de points peuvent à nouveau être importés et seront traités correctement
- Il est à nouveau possible de cliquer sur des objets liés aux documents dans le menu d'informations de droite pour les sélectionner dans la visionneuse 3D.
- Si l'heure de dernière consultation du lien public d'une collection a une milliseconde différente, vous ne recevrez plus d'erreur.
- Les caractères spéciaux ne seront plus corrompus lorsqu'un document est téléchargé depuis Safari sur Mac.
- Les annotations de texte contenant des caractères pleine largeur placés sur des documents qui sont ensuite téléchargés ne seront plus mises à l'échelle de manière disproportionnée par rapport aux caractères de largeur simple.
- Les documents image plus grands que 10000x5000 pixels généreront maintenant correctement un aperçu du document.

### 2.2 **Modèles**

- Les couleurs appliquées aux objets maillés s'affichent désormais correctement. Les modèles devront être réimportés pour voir la différence.
- Une refonte complète de notre système de gestion de modèles - nous chargeons maintenant les informations du modèle uniquement si nécessaire, au lieu de tout charger d'avance. Cela rend la page rapide à charger et permet à nos serveurs de mieux gérer toutes vos demandes lorsque beaucoup de personnes utilisent Catenda en même temps.
- Il est à nouveau possible de voir les propriétés dans les révisions précédentes des modèles dans le panneau d'inspection
- Vous ne verrez plus les modèles auxquels vous n'avez pas accès dans le sélecteur de révisions.
  De cette manière, les modèles utilisés pour les appels d'offres peuvent rester anonymes en utilisant le contrôle d'accès.
- Il est à nouveau possible (et une meilleure expérience qu'auparavant) de mesurer entre les points dans les nuages de points.

### 2.3 **Sujets**

- Le tableau de tous les sujets n'affiche plus les filtres du tableau précédent sur lequel vous étiez et affiche à nouveau correctement les filtres appartenant au tableau de tous les sujets.
- Améliorations de l'exportation des sujets :
  - Les exportations de sujets qui prennent longtemps vont maintenant expirer.
  - Jusqu'à 10000 images peuvent maintenant être incluses dans une exportation PDF.

### 2.4 **Paramètres du projet**

- Membres - La page des membres se charge maintenant beaucoup plus rapidement.

## 3. **Nouvelles versions** - Catenda Site, Plugins et intégrations

_Catenda Site v3.5.2 :_ [App store](https://apps.apple.com/us/app/catenda-site/id1449579790) [Play store](https://play.google.com/store/apps/details?id=no.catenda.bimsyncmobile) Il n'est plus possible de voir le contenu des sujets qui ont été supprimés sur Catenda Hub. Si vous aviez chargé des marqueurs dans la visionneuse 2D, ceux-ci resteront visibles. La tentative d'ouverture d'un sujet supprimé via la liste de sujets ou le marqueur n'affichera plus le contenu du sujet et déchargera le marqueur de la visionneuse 2D.
