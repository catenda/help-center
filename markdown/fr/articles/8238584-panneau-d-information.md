# Panneau d'information

Vous pourrez trouver le panneau d'information comme l'un des quatre panneaux principaux qui peuvent être ouverts en haut à droite de votre écran. Vous pouvez soit appuyer sur l'icône i pour ouvrir ce panneau, soit appuyer sur [shift+4](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=Inspect%20panel-,Shift%20%2B%204,-Show/hide%20last).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/01-intro.png)

Dans le panneau d'information, vous pourrez trouver les sections suivantes :

Les rubriques suivantes sont décrites dans cet article :

## 1. **Inspection**

Cela vous permet de voir les informations sur les objets que vous avez sélectionnés. Cliquez [ici](https://support.catenda.com/en/articles/4670285-inspect-panel) pour en savoir plus sur le panneau d'inspection.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/02-inspect.png)

## 2. **Quantitatif**

Cela vous permet de créer et d'exporter une liste d'objets et de calculer les sommes de valeurs associées aux différents objets sélectionnés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/03-quantity-take-off.png)

Cliquez [ici](https://support.catenda.com/en/articles/6673929-quantity-take-off-qto) pour en savoir plus sur le Quantitatif

## 3. **4D**

Dans cette section, vous pourrez suivre la progression des modèles avec la 4ème dimension. Temps. Si votre fichier IFC contient un IFCWORKPLAN, vous pourrez voir un calendrier pour les objets de votre fichier.

> **Remarque :** La 4D dans Catenda n'est disponible que pour les fichiers ifc exportés à partir de [SYNCHRO](https://www.bentley.com/software/synchro/). Ces fichiers peuvent inclure un IfcWorkPlan et IfcTasks

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/04-4d.png)

Au début de la période, tous les objets seront cachés et en fonction de la progression du temps, les objets avec les bons paramètres apparaîtront. Voici un exemple de ce à quoi la section 4D peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/05-4d.png)

### 3.1 **Colonnes 4D**

## 4. - Le numéro de tâche

_ID de tâche_ - L'ID de la tâche

_Nom_ - Le nom de la tâche

_Durée_ - La durée de la tâche

**Début** La date de début de la tâche. C'est à ce moment que l'objet apparaîtra en 3D. Les objets apparaîtront également sélectionnés. Entre la date de début et la date de fin d'une tâche, la barre de tâche sera orange. Cliquez sur l'icône d'horloge à côté de la date pour accéder à ce point dans le temps.

Fin La date de fin de la tâche - Après la date de fin, les objets resteront en 3D mais seront désélectionnés. Après cette date, la barre de tâche sera verte. Cliquez sur l'icône d'horloge à côté de la date pour accéder à ce point dans le temps.

**Produits** Les objets connectés à cette tâche. Les objets peuvent être isolés et sélectionnés en cliquant sur isoler et sélectionner.

### 4.1 **Signets 4D**

Il est possible de créer un signet où le plan de travail 4D a été activé. Si vous accédez à ce signet, vous verrez quels objets ont été rendus visibles à ce jour selon le plan. Dans Catenda Hub, vous pourrez ajuster l'échelle de temps à votre convenance. Si vous partagez le signet en externe, la partie externe accédant au signet ne verra que les objets qui ont été rendus visibles jusqu'à présent.

### 4.2 **Comment savoir si mon IFC contient des informations 4D ?**

Si votre fichier ifc contient des IFCTASKs, vous pourrez les voir dans le panneau 4D. Si votre fichier ifc contient des IFCRELASSIGNSTOPROCESSes, ces tâches seront également connectées aux objets. Un programme que vous pouvez utiliser pour vérifier si ces entités sont présentes est [OpenIFCViewer](https://openifcviewer.com/). Ici, vous pouvez vérifier les statistiques de votre modèle.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/06-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

Où vous pouvez trouver l'entité dans le panneau de statistiques :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/07-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

## 5. **Sélections**

Cela vous permet de créer un ensemble d'objets qui peuvent ensuite être stylisés et colorisés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/08-selections.png)

En haut du menu Sélection, vous verrez combien d'éléments vous avez actuellement sélectionnés dans la Visionneuse 3D et le panneau d'arborescence. Les sélections peuvent être enregistrées en créant une [Capture](https://support.catenda.com/en/articles/8053352-issue-body#h_1ba7f8873f) ou un [Signet](https://support.catenda.com/en/articles/8471481-bookmark) et en le relisant plus tard. Parce que les sélections sont stockées dans la Capture d'une rubrique, elles peuvent être importées et exportées vers d'autres programmes via BCF. Un exemple est que les rubriques avec des sélections du panier de sélection qui sont synchronisées via le connecteur BCF en direct dans Solibri contiendront des données de sélection lors de la lecture de la Capture.

Les rubriques suivantes sont décrites dans cette section :

### 5.1 **Nouvelle sélection**

Après avoir sélectionné un objet, vous pourrez cliquer sur Nouvelle sélection

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/09-new-selection.png)

### 5.2 **Icône de crayon**

Cliquez sur l'icône de crayon pour modifier le nom de votre sélection

### 5.3 **Nombre d'objets**

Après l'icône de crayon, vous verrez le nombre d'objets actuellement dans cette sélection.

### 5.4 **Mettre à jour**

Cliquez sur le bouton de mise à jour pour définir les objets de la sélection sur les objets que vous avez actuellement sélectionnés dans la Visionneuse 3D et le panneau d'arborescence.

### 5.5 **Sélecteur d'objet**

Cliquez sur le bouton de sélection pour sélectionner les éléments de votre sélection

### 5.6 **Couleur**

Avec le bouton de couleur, vous pouvez modifier la couleur des objets de votre sélection. Le sélecteur de couleur peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/10-color.png)

Sélectionnez la couleur avec le curseur de couleur, la palette ou spécifiez votre couleur souhaitée avec un code hexadécimal. Le deuxième curseur détermine la transparence où 1 signifie 100 % opaque et 0 signifie 100 % transparent. En bas à droite, vous verrez la couleur résultante.

### 5.7 **Supprimer**

Cliquez sur le bouton de suppression pour supprimer cette sélection

### 5.8 **Développer/réduire**

Développez la sélection pour voir quels objets font partie de la sélection.

## 6. **Mesures**

Cela vous permet de voir les mesures qui ont été créées dans la Visionneuse 3D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/11-measurements.png)

Cliquez [ici](https://support.catenda.com/en/articles/4670294-measuring-features) pour en savoir plus sur les mesures
