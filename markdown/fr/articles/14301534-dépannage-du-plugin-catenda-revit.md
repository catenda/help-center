# Dépannage du plugin Catenda Revit

Les erreurs qui peuvent être rencontrées avec le plugin Catenda Revit et comment les résoudre sont expliquées dans cet article.

## 1. **Télécharger IFC**

Dans les champs de nom de fichier et de commentaires de la boîte de dialogue de téléchargement du modèle, seuls les caractères ASCII sont pris en charge pour le téléchargement. Pour savoir quels caractères sont dans l'ensemble ASCII, consultez [cet article Wikipedia](https://en.wikipedia.org/wiki/ASCII).

Les caractères non-ASCII peuvent être ajoutés aux champs de fichier et de commentaires comme suit :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/01-upload-ifc.png)

En cliquant sur Télécharger, le message d'erreur suivant s'affichera :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/02-upload-ifc.png)

```
Une exception non gérée s'est produite dans un composant de votre application. Si vous cliquez sur Continuer, l'application ignorera cette erreur et tentera de continuer. Les en-têtes de demande doivent contenir uniquement des caractères ASCII.
```

Veuillez redémarrer Revit après avoir rencontré cette erreur pour continuer le téléchargement.

## 2. **Fenêtre Gérer les Liens**

Après l'installation du plugin Catenda Revit dans un Revit 2025 qui a été mis à jour après mars 2026, Revit se bloquera lors de la tentative d'ouverture de la fenêtre Gérer les Liens. Ceci est dû à une modification d'Autodesk. Cliquez [ici](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Program-crash-on-certain-machines-when-opening-the-Manage-Links-dialog-in-Revit.html) pour obtenir une solution de contournement. Veuillez noter que seul Revit 2025 est affecté. Ce problème n'existe pas dans Revit 2026.

## 3. **Éditions Revit prises en charge**

Le complément Catenda est compatible avec les éditions Revit qui prennent en charge l'API Revit (Application Programming Interface). L'intégration est possible dans les environnements suivants :

**Revit Standard** Un support complet est fourni pour la version multidisciplinaire du logiciel, englobant les jeux d'outils **Architecture**, **Structure** et **MEP** (Mécanique, Électricité et Plomberie).

**Version Éducative** Les licences émises pour les étudiants et les éducateurs prennent en charge l'installation de compléments tiers, à condition que l'installation soit la version complète du logiciel et non la version LT.

### 3.1 **Édition non prise en charge : Revit LT**

Il est important de noter que [Revit LT ne prend pas en charge les compléments ou plugins tiers](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Revit-LT-Is-it-possible-to-use-plugin-or-addins-in-Revit-LT.html), y compris le complément Catenda Revit. Ceci est une limitation de l'architecture logicielle de la plateforme LT, car elle ne dispose pas du cadre API requis. Par conséquent, il n'est pas possible d'installer le complément ou d'utiliser l'automatisation basée sur Dynamo dans l'environnement Revit LT.

### 3.2 **Compatibilité des versions**

Pour assurer l'alignement avec les dernières mises à jour logicielles et améliorations de performances, les intégrations sont mises à jour régulièrement. Pour une liste complète des versions d'années actuellement prises en charge pour le complément Revit et le package Dynamo, veuillez consulter l'article [Plugins et Intégrations](https://support.catenda.com/en/articles/8396532-catenda-plugins-integrations).

## 4. Package Dynamo Catenda Hub

Pour les flux de travail nécessitant une automatisation personnalisée, un package spécialisé est disponible pour Dynamo de base. Ce n'est pas une application séparée mais une collection de nœuds à utiliser dans l'environnement Dynamo standard.

**Licence** Aucune licence Autodesk supplémentaire n'est requise pour utiliser Dynamo, car elle est incluse en tant que capacité essentielle dans la licence Revit standard.

**Accès API** L'utilisation de ce package nécessite un accès à l'API Catenda. Bien que cela ne soit pas inclus par défaut pour tous les clients, l'accès peut être demandé via le portail de support Catenda. Une fois accordé, l'accès API permet des interactions sur tous les projets au sein d'une organisation.

**Installation** Le déploiement du package nécessite une installation manuelle en spécifiant l'emplacement du fichier dans l'interface Dynamo.

### 4.1 **Avertissement opérationnel pour les utilisateurs de Dynamo**

Avant l'utilisation de ce package, un avertissement est émis selon lequel ces outils permettent des actions au sein d'un projet comme si l'acteur était une application plutôt qu'un utilisateur individuel. À de grandes capacités correspond une grande responsabilité. Les actions effectuées au niveau de l'application, telles que les suppressions, sont traitées différemment des actions utilisateur standard. Les éléments ou les données supprimés par une application ne peuvent pas être restaurés. Une extrême prudence est recommandée lors de l'utilisation de ces outils dans un environnement de projet. Pour demander l'accès API ou le package Dynamo, veuillez contacter [support@catenda.com](mailto:support@catenda.com) ou via la bulle de chat noire vers le coin supérieur droit de la plateforme.
