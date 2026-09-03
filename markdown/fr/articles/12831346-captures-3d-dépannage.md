# Captures 3D - Dépannage

## 1. **Paramètres de viewpoint**

### 1.1 **Objets**

Les objets ayant le même ID et qui ont été sélectionnés, masqués ou isolés seront sélectionnés, masqués ou isolés lorsque la capture sera recréée. Si deux modèles partagent des IfcProject GUIDs (Identificateurs globaux) identiques, des conflits peuvent entraîner des problèmes de visibilité, empêchant Catenda Hub de déterminer quels éléments du modèle doivent apparaître lors de la recréation de la capture.

### 1.2 **Objets masqués**

Si plus de la moitié des objets d'un modèle sont visibles, les objets avec des identifiants nouveaux seront masqués.

Cela signifie que si vous ajoutez un nouveau modèle avec le sélecteur de modèle dans une capture de commentaire de sujet où plus de la moitié des objets d'un modèle sont visibles, le modèle ajouté pourrait être complètement masqué. Pour afficher les objets avec de nouveaux identifiants, vous pouvez utiliser l'option « afficher tout » pour afficher le modèle après la recréation de la capture. Pour dépanner et forcer les modèles masqués à devenir visibles, vous pouvez utiliser l'option « afficher tout » dans la Visionneuse 3D. Cliquez avec le bouton droit dans la zone d'affichage 3D, sélectionnez « afficher tout » dans le menu contextuel, et cela devrait résoudre temporairement les problèmes de visibilité causés par des conflits de configuration.

## 2. **Refaire la capture**

Lors de la relecture d'une capture 3D d'un sujet, certains modèles peuvent ne pas apparaître. Ce problème peut provenir de problèmes de projet tels que les IfcProject GUIDs en double. Pour résoudre ce problème, assurez-vous que chaque modèle du projet utilise un identifiant unique. De plus, utilisez l'option « Afficher tout » dans la Visionneuse 3D comme solution temporaire.

### 2.1 **Sélecteur de modèle de capture**

Dans ce menu, vous ne reliez la capture qu'aux modèles Catenda. Si les modèles appropriés n'ont pas été trouvés automatiquement, ils peuvent être liés manuellement ici. Même si plusieurs modèles ont le même GUID, vous pouvez sélectionner pour les activer tous au lieu de seulement le premier. Cela ne change pas le contenu du BCF, donc les objets pourraient toujours être masqués lorsqu'ils sont ouverts dans des outils externes.

Selon les paramètres de visibilité des objets de la Capture, les modèles ajoutés pourraient être complètement masqués. Ouvrez le sélecteur de révision ou la page des modèles pour voir quels modèles ont le bouton 3D activé pour voir quels modèles sont chargés dans la Visionneuse 3D après la recréation de la Capture. Bien qu'ils puissent être chargés, tous les objets du modèle pourraient être masqués. Utilisez l'action « afficher tout » pour révéler les objets masqués..

## 3. **Importation BCF de capture**

Lorsqu'un sujet BCF est importé, les identifiants des modèles du projet sont comparés avec les identifiants des modèles configurés dans la capture. Seuls les modèles dont les identifiants sont présents au moment de l'importation seront chargés dans la Visionneuse 3D lorsque la capture sera recréée.

Si deux modèles ont le même identifiant, seul le premier est activé. Pour s'assurer que les modèles appropriés sont activés, il est important que chacun ait son propre identifiant.

Si vous exportez plusieurs fichiers différents à partir de votre logiciel d'édition, c'est une bonne idée d'utiliser un identifiant unique pour chaque modèle différent que vous souhaitez exporter. Il est recommandé que chaque modèle du projet se voie attribuer un IfcProject GUID unique pour éviter les conflits lors de la recréation de captures. Cela garantit que Catenda Hub peut afficher avec précision les configurations dans la Visionneuse 3D.

Voici un article de BuildingSMART qui décrit comment cela se fait dans Revit [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/)

Assurez-vous de garder une trace de quel identifiant a été utilisé pour quel modèle afin que les sujets futurs créés le reconnaissent.
