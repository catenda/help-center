# Localisation 3D des modèles

## 1. **Exporter avec les mêmes coordonnées**

Dans les plateformes de création, vous pouvez exporter avec différentes coordonnées. Toutes les coordonnées fonctionnent correctement avec Catenda Hub. Il est recommandé que tout le monde dans le projet utilise le même système de coordonnées pour s'assurer que les objets ne se retrouvent pas éloignés les uns des autres et que les utilisateurs ne se demandent pas pourquoi ils voient certains objets tandis que les autres sont cachés alors qu'en réalité ils sont simplement très, très loin.

## 2. **Objets éloignés de l'origine**

Comparé à d'autres plateformes de création, le hub Catenda n'a pas de problèmes de précision lorsque les objets sont éloignés de 0. La localisation du modèle spécifiée dans le fichier IFC est utilisée pour décider où le modèle existe en 3D. La scène (taille de la zone chargée dans la Visionneuse 3D) n'est aussi grande que les objets qu'elle contient et n'a pas besoin d'inclure le point d'origine (0,0,0). Cela vous permet de zoomer facilement sur les objets sans avoir à calculer la distance qui les sépare par rapport à l'origine.

## 3. **Objets éloignés les uns des autres**

Si vous avez des objets séparés de plus de 10000 km les uns des autres, vous pouvez rencontrer des problèmes car la scène devient très grande. Si vous créez un plan de clipping horizontal, il coupera toute la scène et deviendra sensible lors du déplacement. Si un modèle est accidentellement importé avec les mauvaises coordonnées et se retrouve très loin, vous pouvez vouloir le transformer. Les modèles fonctionneront toujours bien individuellement, mais ensemble avec d'autres modèles très éloignés, vous pouvez rencontrer des problèmes.

## 4. **Transformer la localisation d'un modèle**

Il est possible de transformer la localisation 3D d'un modèle sur la page d'aperçu du modèle si vous l'avez chargé en 3D. Cela vous permet de déplacer le modèle en 3D après son importation dans Catenda Hub. Ce déplacement est uniquement visuel dans Catenda Hub. Si l'IFC est téléchargé, il sera de retour à sa localisation d'origine. Cette méthode n'est recommandée que pour transformer temporairement le modèle en attendant un fichier IFC avec la bonne localisation. C'est parce que certaines fonctionnalités ne fonctionneront pas correctement avec les modèles transformés, comme les sections de la Visionneuse 2D, les requêtes et les Captures de problèmes. Les mesures ne sont pas affectées et seront précises si le modèle est déplacé au bon endroit. Vous pouvez trouver plus d'informations sur la façon de procéder [ici](https://support.catenda.com/en/articles/4670270-model-overview-page#h_c10dbce6c8)
