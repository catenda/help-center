# Examen de la conception et bons de commande dans un projet de construction en hauteur

> Secteur : Construction commerciale Persona : Maria, architecte de projet dans une grande entreprise.

### **Scénario :**

Maria supervise la conception architecturale d'un immeuble commercial de 30 étages. Le projet est en phase de construction et plusieurs disciplines d'ingénierie (structure, MEP, sécurité incendie) mettent constamment à jour leurs dessins.

Le plus grand défi de Maria est de gérer le volume considérable de révisions de dessins soumises par différentes équipes. Une modification mineure de l'ingénieur structural, comme le changement de position d'une poutre, peut avoir un effet en cascade sur le routage des conduits électriques et le placement des gaines de ventilation. Auparavant, son équipe superposait manuellement les nouveaux et anciens dessins sur une table lumineuse ou vérifiait laborieusement côte à côte sur un écran, un processus lent, sujet à l'erreur humaine et qui a entraîné des travaux de réfection coûteux sur le chantier lorsque les clashes ont été manqués.

### **Solution utilisant Catenda Hub :**

Maria utilise maintenant Catenda Hub pour centraliser et rationaliser l'ensemble du processus d'examen de la conception. Voici son nouveau flux de travail :

### **1. Identifier les modifications critiques avec PDF Compare :**

L'équipe d'ingénierie structurale télécharge une nouvelle révision du plan de charpente du 15e étage en PDF. Au lieu d'une vérification manuelle, Maria utilise la fonction **PDF Compare**. Elle sélectionne la nouvelle révision et la précédente. Le logiciel affiche instantanément une superposition des deux Documents.

- **L'ancienne géométrie** est affichée en **bleu**.
- **La nouvelle géométrie** est affichée en **rouge**.

En utilisant le curseur d'opacité, Maria peut clairement voir qu'une poutre de support clé a été décalée de 30 centimètres pour répondre à une nouvelle exigence structurale. Cette modification est immédiatement évidente, alors qu'elle aurait pu être manquée lors d'un examen manuel.

### **2. Annotation et création d'un problème pour action :**

En voyant le changement, Maria soupçonne qu'il y aura un clash avec la disposition du système de ventilation. Elle utilise les **outils d'annotation** directement sur la vue de comparaison PDF :

- Elle dessine une **forme de nuage** autour de la zone affectée.
- Elle ajoute une **annotation textuelle** : « Clash potentiel avec la gaine de ventilation principale. Veuillez vérifier l'espace libre. ».
- Elle utilise l'**outil de dessin libre** pour tracer une flèche indiquant la direction du trajet de ventilation.

Au lieu d'envoyer un e-mail qui pourrait se perdre, Maria enregistre ces annotations directement dans un nouveau **Problème** dans Catenda Hub. Le problème reçoit automatiquement le titre « Clash potentiel : Structure et ventilation du 15e étage » et est assigné à l'ingénieur structural principal et au coordinateur MEP. Le problème inclut automatiquement une capture d'écran de son annotation sur le dessin comparé (montrant les révisions n° 3 et n° 4), garantissant que tout le monde dispose du contexte complet.

### **3. Collaboration et résolution du problème :**

Le coordinateur MEP reçoit une notification. Il ouvre le problème et voit l'annotation précise de Maria sur le PDF comparé. Il n'a pas besoin de chercher les fichiers ni de deviner quelle poutre elle évoque. Il prévisualise le fichier DWG joint du système de ventilation directement dans la Visionneuse, confirmant le clash. Il ajoute un commentaire au problème : « Confirmé. Nous allons rediriger la gaine. Un nouveau dessin sera téléchargé avant la fin de la journée. » Il joint un croquis rapide du nouvel itinéraire proposé, également créé avec les outils d'annotation.

### **Résultats et avantages :**

En utilisant les fonctionnalités d'aperçu de Documents, d'annotation et de comparaison PDF de Catenda Hub, l'équipe de Maria a transformé un processus encombrant et sujet aux erreurs en un flux de travail efficace et collaboratif.

- **Réduction drastique des erreurs :** L'outil PDF Compare a rendu pratiquement impossible de manquer les modifications critiques de la conception, évitant au moins deux cas potentiels de réfection sur chantier qui auraient coûté des milliers de dollars et causé des retards importants.
- **Communication et responsabilité améliorées :** Toute la communication est centralisée dans le contexte du dessin et du problème spécifique. Il existe une piste claire et vérifiable de qui a dit quoi et quand, éliminant la confusion causée par les chaînes d'e-mails dispersées.
- **Cycles d'examen plus rapides :** Ce qui prenait auparavant à Maria et son Équipes une journée complète de vérification manuelle est maintenant réalisé en moins d'une heure. Cela accélère l'ensemble du calendrier du projet.

### **Clarté améliorée :**

Les annotations sont effectuées directement sur les Documents pertinents, fournissant un contexte visuel précis qui est beaucoup plus clair que les seules descriptions textuelles. Tous les intervenants, du bureau de conception au chantier, regardent les mêmes informations.
