# Optimisation de la Visionneuse 3D

Bien que Catenda Hub soit bien optimisé et puisse exécuter la plupart des modèles, certains utilisateurs pourraient vouloir se préparer au mieux pour réussir.

Cet article contient des informations sur les sujets suivants :

Voici quelques stratégies qui peuvent être utilisées pour optimiser votre flux de travail dans Catenda Hub

## 1. **Nombreux objets**

Bien sûr, charger moins de modèles signifie moins d'objets et donc de meilleures performances. L'activation du [rendu progressif](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings#:~:text=Incremental%20rendering%3A) accélère la rotation autour des modèles avec beaucoup de géométrie, car tous les objets n'ont pas besoin d'être chargés lors de la rotation. Comme dernière étape, vous pouvez effectuer une [requête](https://intercom.help/bimsync-arena/en/articles/4854514-queries) de la section sur laquelle vous travaillez. Généralement, lorsque vous séparez une partie du modèle, les objets restent en mémoire et sont simplement masqués. Avec une requête, ces objets sont complètement supprimés et il sera donc plus facile de travailler avec le modèle. Gardez à l'esprit que vous ne pourrez pas utiliser les Bibliothèques de propriétés avec les requêtes car tous les objets ne sont pas chargés.

## 2. **Nuée de points**

Si vous utilisez une [taille de point fixe](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=Adaptive%20(default)%2C%20or-,Fixed%20size,-.%20The%20slider%20below), vous risquez de rencontrer des images par seconde basses lorsqu'un grand nombre de points ont été chargés. Vous pouvez également remarquer que les points prennent plus de temps à charger lorsque le budget mémoire de votre système est atteint. Les points les plus proches de la caméra sont chargés en premier, donc si vous souhaitez charger des points à un endroit spécifique, il est préférable de naviguer à cette position, puis d'activer le nuée de points pour qu'il commence à charger les points à partir de là d'abord. Pour éviter d'atteindre la limite de mémoire et d'obtenir des images par seconde plus basses, vous pouvez réduire le [budget de points](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=with%20your%20PC.-,Point%20Budget%3A,-Using%20the%20viewer) afin que moins de points soient chargés.

## 3. **Échelle de zoom du navigateur**

Assurez-vous que l'échelle de zoom de votre navigateur est définie correctement, car une grande échelle de zoom peut rendre certains menus si grands que d'autres sont masqués. Alors que les graphiques définis par la largeur et la hauteur peuvent s'adapter à l'échelle du navigateur, les graphiques définis par des pixels peuvent devenir plus pixelisés lorsque l'échelle de zoom augmente. Une petite échelle de zoom peut faire en sorte que les graphiques deviennent si petits qu'ils sont invisibles et l'affichage précis des ressources réduites peut être plus exigeant pour l'appareil.
