# Paramètres de la visionneuse 3D

Les paramètres de la visionneuse 3D se trouvent en haut à droite de la [visionneuse 3D](https://support.catenda.com/en/articles/8227211-3d-viewer).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/01-intro.png)

> **Remarque :** Assurez-vous que le matériel et le logiciel sur lequel Catenda est ouvert sont configurés [comme recommandé](https://support.catenda.com/en/articles/6921941-hardware-recommendation), car cela peut affecter l'affichage de la visionneuse.

## 1. **Activation de la visionneuse 3D**

La visionneuse 3D peut être ouverte de l'une des manières suivantes : Activez le panneau 3D avec les boutons du panneau en haut à droite (Maj + 2).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/02-enabling-the-3d-viewer.png)

Activez un modèle 3D à partir de la page Tableau de bord.

Activez un modèle 3D à partir de la colonne visionneuse du tableau de modèles. (Image ci-dessus)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/03-enabling-the-3d-viewer.png)

Sélectionnez des modèles sur la page des modèles et utilisez l'action 3D avec les modèles sélectionnés sur la page des modèles.

Activez un document 3D à partir de la colonne visionneuse du tableau des documents sur la page des documents. Cliquez sur l'icône en forme d'engrenage pour afficher les **paramètres de la visionneuse 3D.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/04-enabling-the-3d-viewer.png)

## 2. **Rendu**

Voici à quoi peut ressembler le menu de rendu :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/05-rendering.png)

### 2.1 **Afficher les espaces**

_Désactivé par défaut_ - [Activer et désactiver les espaces](https://support.catenda.com/en/articles/4670315-how-can-i-show-spaces-in-catenda-hub). Les espaces restent sélectionnables dans la visionneuse 2D s'ils se trouvent dans le modèle.

### 2.2 **Qualité de l'affichage**

Le rapport entre le nombre de pixels que le port de vue affiche et le nombre de pixels qui font physiquement partie de votre écran est souvent identique. Dans ce cas, l'option de qualité d'affichage ne fait pas beaucoup de différence. Si le nombre de pixels que le port de vue indique et le nombre de pixels sur lequel le port de vue est affiché sur un écran est différent, la qualité d'affichage peut affecter la netteté de l'image. Pour les écrans des types suivants, le rapport entre le nombre de pixels que le port de vue indique et le nombre de pixels que l'écran a réellement peut être différent :

- Appareils mobiles
- Technologies d'affichage qui affectent la densité de pixels comme Apple Retina.
- Affichages haute résolution

> **Remarque :** Assurez-vous que le matériel et le logiciel sur lequel Catenda est ouvert sont configurés [comme recommandé](https://support.catenda.com/en/articles/6921941-hardware-recommendation), car cela peut affecter la précision de la visionneuse.

**Qualité standard** Avec la qualité d'affichage standard, les pixels que le port de vue indique sont le même nombre de pixels physiques qui affichent le port de vue sur l'écran. Pour les écrans qui offrent d'afficher le port de vue sur plus de pixels physiques que le port de vue n'en indique, ce paramètre peut rendre l'image moins précise. Ce mode est plus rapide et moins exigeant pour votre appareil.

**Haute qualité** Avec la qualité d'affichage élevée, le port de vue est affiché sur l'ensemble des pixels physiques disponibles sur la partie de l'écran qui affiche le port de vue. Pour les écrans qui permettent au port de vue d'être affiché sur plus de pixels qu'il ne l'indique, cela offre la meilleure qualité visuelle mais peut être plus exigeant en termes de performances.

### 2.3 **Lissage des contours**

Précision des pixels dans le lissage des lignes diagonales par ordre de précision. Notez que plus la précision est élevée, plus il sera difficile d'afficher pour le système.

- FXAA
- 2x MSAA
- 4x MSAA
- 8x MSAA

> **Remarque :** Assurez-vous que le matériel et le logiciel sur lequel Catenda est ouvert sont configurés [comme recommandé](https://support.catenda.com/en/articles/6921941-hardware-recommendation), car cela peut affecter la précision des lignes diagonales.

### 2.4 **Rendu incrémentiel**

Lors de la rotation, les objets non vitaux comme le verre dans les fenêtres et les petites garnitures sont temporairement masqués pour améliorer les performances. Cela permet de faire tourner des modèles énormes avec peu de décalage. Lorsque de nombreux objets sont chargés dans la visionneuse 3D, cette option est indispensable.

### 2.5 **Ombres ambiantes**

Lorsque cette option est activée, des ombres d'un rayon d'environ 5 cm s'affichent entre le chevauchement des objets. Assurez-vous d'avoir vos objets à l'échelle réelle pour que cela ait un meilleur effet. Avec de grandes surfaces comme là où un mur rencontre un sol, ce n'est pas très visible jusqu'à ce que la caméra se rapproche de l'intersection. Avec une petite géométrie comme les meubles, les poutres en acier et les garnitures métalliques, c'est un élément qui change la donne. Cette option a généralement peu d'effet sur les performances.

### 2.6 **Plage de vision étendue**

Avec des modèles massifs de plusieurs kilomètres de long, les objets finissent souvent en dehors de la distance de découpe par défaut de 2 kilomètres. Lorsque le modèle est activé, la caméra tente de se positionner suffisamment loin pour afficher tout et si les objets sont suffisamment éloignés, ils pourraient être découpés et rien ne s'affichera jusqu'à ce que la caméra se rapproche des objets. Avec cette option, les objets jusqu'à 50 kilomètres de distance de la caméra deviennent visibles ! Notez que cela peut affecter les performances. Dans les projets d'infrastructure, cette option est souvent indispensable !

### 2.7 **Niveau de transparence**

_5% Par défaut_ - Quantité de transparence visible à travers les objets translucides

### 2.8 **Paramètres du nuage de points**

Budget de points : _1000000 Par défaut_ - Nombre de points du nuage de points qui peuvent être affichés à la fois. La valeur par défaut est plus que suffisante pour la plupart des nuages de points, mais le paramètre est là au cas où vous en auriez besoin de plus.

## 3. **Navigation**

Voici à quoi peut ressembler le menu de navigation :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/06-navigation.png)

### 3.1 **Mode marche**

_1,6 mètre par défaut_ - Attache la visionneuse au sol en dessous lorsque vous traversez le modèle en mode promenade. Vous permet de monter les escaliers.

### 3.2 **Vitesse de marche**

_3 m/s par défaut_ - Vitesse à laquelle la visionneuse se déplace en mode promenade. À titre de référence, un tableau des vitesses générales est inclus ci-dessous.

### 3.3 **Vitesse d'élévation**

_1,5 m/s par défaut_ - Vitesse du mouvement vertical lors du déplacement vers le haut et vers le bas à l'aide de X et C.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Méthode de déplacement</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Vitesse typique (m/s)</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Vitesse typique (mph)</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Marche à pied</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>1,5</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3,4</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Par défaut</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>6,7</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Course</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>5</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>11</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Cyclisme</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>7</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>15</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voiture</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>13 - 30</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>29 - 67</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Train</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>56</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>125</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Avion</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>250</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>560</p></td></tr></tbody></table></div>

### 3.4 **Vitesse de rotation**

_40°/s par défaut_ - Vitesse à laquelle la visionneuse tourne autour de la caméra lorsque vous faites glisser sur l'écran

### 3.5 **Angle de vue**

_60° par défaut_ - Ce paramètre peut être bon à agrandir dans les espaces intérieurs comme les petites pièces pour que vous puissiez voir plus. Il peut également être bon de limiter ce paramètre dans les modèles avec de grandes distances 2 km (1,2 miles) et plus car cela vous permettra de voir plus précisément les objets qui sont plus éloignés.

### 3.6 **Réinitialiser les paramètres de navigation**

Rétablissez tous les paramètres de navigation à leur position par défaut

## 4. **Environnement**

Voici à quoi peut ressembler le menu d'environnement :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/07-environment.png)

### 4.1 **Paramètre d'environnement**

Le paramètre d'environnement choisi détermine quel ciel s'affiche lorsque vous regardez vers le haut et quel sol s'affiche lorsque vous regardez vers le bas. Notez que l'horizon est souvent plus prononcé lorsque l'option de vue en perspective est choisie car avec le point de vue orthogonal, l'horizon est infiniment éloigné, donc il n'est visible que lorsque la caméra fait face exactement à la direction horizontale.

**Dégagé** Avec le paramètre dégagé, un ciel dégagé lorsque vous regardez vers le haut et un plan de sol herbeux lorsque vous regardez vers le bas s'affichent en arrière-plan du port de vue.

**Partiellement nuageux** Avec le paramètre partiellement nuageux, un ciel nuageux lorsque vous regardez vers le haut et un plan de sol herbeux lorsque vous regardez vers le bas s'affichent en arrière-plan du port de vue.

**Neutre** Avec le paramètre neutre, un ciel gris clair lorsque vous regardez vers le haut et un plan de sol gris foncé lorsque vous regardez vers le bas s'affichent en arrière-plan du port de vue. Ce paramètre est excellent pour les modèles qui ont des couleurs claires et sont difficiles à distinguer d'un arrière-plan clair.

**Aucun** Avec le paramètre aucun, un dégradé qui passe d'un ciel vert clair lorsque vous regardez vers le haut à un plan de sol blanc lorsque vous regardez vers le bas s'affichent en arrière-plan du port de vue.

### 4.2 **Élévation du sol**

Les options d'élévation du sol sont grisées pour le paramètre Aucun, car celui-ci n'a pas de plan de sol. Dans les paramètres où le plan de sol est affiché, une surface devient visible à une élévation définie qui reçoit des ombres des objets chargés dans la visionneuse 3D.

_Sous le modèle -_ Par défaut Avec cette option, la surface du plan de sol s'affiche à une hauteur de 0 mètre au-dessus du niveau de la mer.

_À l'élévation_ Avec cette option, la surface du plan de sol peut être déplacée vers le haut avec des valeurs positives et vers le bas avec des valeurs négatives. C'est excellent dans les situations où la surface traverse un sous-sol ou pour les objets qui sont autrement sous le niveau de la mer.
