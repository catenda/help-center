# Manuel d'exportation 3D DWG

Les programmes capables d'exporter des DWG 3D en IFC sont :

### **AutoCAD Architecture**

[Menu Exporter](#h_9ac38304dd)

### **AutoCAD MEP**

[Menu Exporter](#h_9ac38304dd)

### **AutoCAD Civil 3D**

[Menu Exporter](#h_9ac38304dd)

### **AutoCAD Plant 3D :**

Si vous utilisez AutoCAD Plant 3D, vous pouvez installer l'activateur d'objets pour la version de Plant 3D que vous utilisez. Avec l'activateur d'objets installé, vous pouvez ouvrir votre fichier dans n'importe lequel des programmes ci-dessus pour exporter en IFC. Si vous n'avez pas accès à l'un des logiciels ci-dessus, vous pouvez essayer d'utiliser un plug-in tiers tel que : Codemill IFC Export pour Autodesk® AutoCAD® Plant3D Bien que ce plug-in prétende également exporter IFC 4, ce qui n'est pas possible avec l'activateur d'objets, gardez à l'esprit qu'il ne s'agit pas d'un exportateur officiel et qu'il pourrait y avoir des problèmes d'importation.

### **Revit**

Il est possible d'importer un DWG 3D dans Revit. Bien que Revit offre beaucoup plus d'options en matière d'exportation en IFC, il n'est pas idéal d'exporter un DWG 3D importé en IFC. Si vous voulez essayer de le faire, la meilleure façon de procéder est d'importer le DWG dans une famille. Si vous essayez d'importer le DWG dans un projet, vous verrez que certains objets disparaissent si vous éclatez le DWG. Après avoir importé le DWG dans la famille, éclatez la famille que le DWG a créée. Cela permet de s'assurer que vous pouvez avoir des objets séparés dans l'IFC au lieu d'un seul grand objet. Ensuite, chargez la famille dans un projet et placez-la. Vous ne pourrez peut-être pas sélectionner la famille. Cela peut être parce que vous n'avez pas coché l'option Sélectionner les éléments de sous-couche dans le menu déroulant sous Modifier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/01-revit.png)

Avec votre famille placée sélectionnée, cliquez sur Créer des pièces dans le ruban supérieur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/02-revit.png)

Vous verrez maintenant que vous pouvez sélectionner chaque partie de la famille individuellement dans le projet. Maintenant, vous êtes prêt à exporter votre IFC en cliquant sur Exporter -> IFC dans le menu en haut à gauche. Dans la boîte de dialogue d'exportation IFC, cliquez sur Modifier la configuration. Dans la boîte de dialogue Modifier la configuration, accédez à l'onglet Avancé. Assurez-vous ici que l'option Exporter les pièces en tant qu'éléments de construction est cochée.

### **Navisworks**

À l'heure actuelle, il n'existe aucun moyen officiel d'exporter en IFC depuis Navisworks. Il est possible d'installer des plug-ins pour le faire avec des résultats variables : Codemill IFC Exporter CellBIM pour Excel et IFC Exporter Gardez à l'esprit que ceci n'est pas un exportateur officiel et qu'il pourrait y avoir des problèmes d'importation.

## 1. **Menu Exporter**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/03-export-menu.png)

1. Numéro de projet
1. Nom du projet
1. Enregistré dans - Écrivez le chemin du fichier ou cliquez sur Parcourir pour trouver le dossier dans lequel vous souhaitez enregistrer votre IFC
1. Sélectionnez les fichiers de dessin que vous souhaitez exporter en IFC
1. Options
   1. En-tête - Auteur, Organisation, etc.
      1. Sélectionnez le schéma IFC à exporter - IFC 2x3 et IFC 4
   1. Objets - Tous
   1. Vue - Inclure tous

> **Remarque :** Ifc 4x1 est retiré par BuildingSMART et par conséquent n'est pas non plus pris en charge par Catenda Hub. Voir [ici](https://support.catenda.com/en/articles/4670320-what-file-types-does-catenda-support) les types de fichiers pris en charge dans Catenda Hub

6\. Ressource et Attribution

1. Ressource - Clic droit pour ajouter une personne et une organisation de ressource
1. Attribution - Clic droit pour ajouter une personne et une organisation assignées
1. IfcBuilding - Choisir les propriétés

Exporter - Cliquez sur ce bouton quand vous êtes prêt à exporter vos fichiers
