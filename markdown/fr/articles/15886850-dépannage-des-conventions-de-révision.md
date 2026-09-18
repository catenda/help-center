# Dépannage des conventions de révision

> Résolvez les échecs d'envoi et les erreurs d'empilement de révisions dans les dossiers avec conventions de nommage. Corrigez les problèmes dus à un identificateur de document mal activé et repérez les valeurs de champs autorisées dans l'aperçu

Lorsqu'une convention de nommage est activée sur un dossier, les échecs de téléchargement de fichiers ou les erreurs d'empilement de révisions proviennent généralement de deux problèmes de configuration courants.

## 1. **1. Basculement d'identificateur de document incorrect**

Un problème fréquent se produit lorsque l'**identificateur de document** est incorrectement défini sur **Activé** pour un bloc qui change à chaque révision. Lorsque cette option est active, le champ de variable changeant est intégré au nom de document permanent plutôt que d'être isolé aux métadonnées de révision.

Par conséquent, bien que la révision initiale soit téléchargée avec succès, tout fichier suivant avec une valeur de variable modifiée ne correspondra pas au nom de document établi. Cette incohérence amène le système à rejeter le fichier, indiquant qu'il ne suit pas la convention. Pour résoudre ce problème, la configuration du bloc doit être mise à jour pour mettre l'identificateur de document sur **Désactivé**. _Accès requis :_ Administrateur

## 2. **2. Valeurs de champs non correspondantes**

Les échecs de téléchargement peuvent également se produire si le texte dans le bloc dynamique ne correspond pas aux règles de validation ou aux valeurs spécifiques établies pour le champ personnalisé sous-jacent. Par exemple, l'insertion de caractères alphabétiques dans un champ personnalisé entier, ou l'entrée d'une phrase qui n'a pas été explicitement définie dans un champ personnalisé de liste déroulante, entraînera une incohérence de convention.

### 2.1 **2.1 Comment identifier les valeurs autorisées**

Pour vérifier les exigences exactes d'un bloc de convention de nommage, la configuration de la règle peut être examinée directement à partir de l'interface de document :

1. Développez le menu d'informations de droite pour un document existant dans le dossier concerné.
1. Consultez la section **Aperçu de la convention de nommage**, qui fournit une répartition visuelle en temps réel de ce que la règle de nommage attend.
1. Passez la souris sur le bloc de version spécifique ou de statut pour afficher ses règles de configuration.
1. Identifiez le champ personnalisé exact alimentant le bloc pour découvrir quelles valeurs spécifiques sont autorisées, ce qui permet d'ajuster le nom de fichier local pour qu'il corresponde.
