# Manuel d'export 3D DWG

Les programmes capables d'exporter des DWG 3D vers IFC sont :

### **AutoCAD Architecture**

[Menu d'export](#export-menu)

### **AutoCAD MEP**

[Menu d'export](#export-menu)

### **AutoCAD Civil 3D**

[Menu d'export](#export-menu)

### **AutoCAD Plant 3D :**

Si vous utilisez AutoCAD Plant 3D, vous pouvez installer l'activateur d'objet pour la version de Plant 3D que vous utilisez. Avec l'activateur d'objet installé, vous pouvez ouvrir votre fichier dans l'un des programmes ci-dessus pour exporter vers IFC. Si vous n'avez pas accès à l'un des logiciels ci-dessus, vous pouvez essayer d'utiliser un plugin tiers comme : Codemill IFC Export pour Autodesk® AutoCAD® Plant3D. Bien que ce plugin prétende également exporter IFC 4, ce qui n'est pas possible avec l'activateur d'objet, gardez à l'esprit que ce n'est pas un exportateur officiel et qu'il pourrait y avoir des problèmes lors de l'importation.

### **Revit**

Il est possible d'importer un DWG 3D vers Revit. Bien que Revit offre beaucoup plus d'options pour exporter vers IFC, il n'est pas idéal d'exporter un DWG 3D importé vers IFC. Si vous voulez essayer, la meilleure façon de le faire est d'importer le DWG dans une famille. Si vous essayez d'importer le DWG dans un projet, vous verrez que certains objets disparaissent si vous éclatez le DWG. Après avoir importé le DWG dans la famille, éclatez la famille que le DWG a créée. Ceci est pour vous assurer que vous pouvez avoir des objets séparés dans le IFC au lieu d'un seul grand objet. Ensuite, chargez la famille dans un projet et placez-la. Vous pourriez ne pas être en mesure de sélectionner la famille. Cela peut être parce que vous n'avez pas coché « Sélectionner les éléments de calque » dans le menu déroulant sous modifier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/01-revit.png)

Avec votre famille placée sélectionnée, cliquez sur créer des pièces dans le ruban supérieur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/02-revit.png)

Vous verrez maintenant que vous êtes en mesure de sélectionner chaque partie de la famille individuellement dans le projet. Vous êtes maintenant prêt à exporter votre IFC en cliquant sur exporter -> IFC dans le menu supérieur gauche. Dans la boîte de dialogue d'export IFC, cliquez sur modifier la configuration. Dans la boîte de dialogue de modification de la configuration, accédez à l'onglet avancé. Ici, assurez-vous que l'option « Exporter les pièces en tant qu'éléments de construction » est cochée.

### **Navisworks**

Pour l'instant, il n'existe aucun moyen officiel d'exporter vers IFC depuis Navisworks. Il est possible d'installer des plugins pour le faire avec des résultats variables : Codemill IFC Exporter CellBIM for Excel et IFC Exporter. Gardez à l'esprit que ce n'est pas un exportateur officiel et qu'il pourrait y avoir des problèmes lors de l'importation.

## 1. **Menu d'export**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/03-export-menu.png)

1. Numéro de projet
2. Nom du projet
3. Enregistré dans - Écrivez le chemin du fichier ou cliquez sur parcourir pour trouver le dossier dans lequel vous souhaitez enregistrer votre IFC
4. Sélectionnez les fichiers de dessin que vous souhaitez exporter vers IFC
5. Options
   1. En-tête - Auteur, Organisation, etc.
      1. Sélectionnez le schéma IFC à exporter - IFC 2x3 et IFC 4
   2. Objets - Tous
   3. Affichage - Inclure tous

> **Remarque :** IFC 4x1 est retiré par BuildingSMART et n'est donc pas non plus pris en charge par Catenda Hub. Consultez [ici](https://support.catenda.com/en/articles/4670320-what-file-types-does-catenda-support) les types de fichiers pris en charge dans Catenda Hub

6\. Ressources et Attribution

1. Ressource - Clic droit pour ajouter une personne ressource et une organisation
2. Attribution - Clic droit pour ajouter une personne assignée et une organisation
3. IfcBuilding - Choisir les propriétés

Exporter - Cliquez sur ce bouton quand vous êtes prêt à exporter vos fichiers
