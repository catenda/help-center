# Flux de travail Catenda Hub - Solibri

Ceci est un document qui expliquera le flux de travail optimal lors de l'utilisation du serveur BCF entre Solibri et Catenda Hub.

1\. Commencez par vous connecter à votre projet Catenda Hub. [( voir ici )](https://intercom.help/bimsync-arena/en/articles/4670340-solibri-model-checker-and-bimsync-bcf-connection) 2\. Une fois connecté, commencez par exécuter votre détection de clash dans Solibri et créez une présentation. Il existe plusieurs façons de créer une présentation dans Solibri, mais je vais expliquer le meilleur type pour communiquer avec Catenda Hub. A. Exécutez la vérification avec votre ensemble de règles. B. Trouvez un problème Solibri que vous souhaitez ajouter à votre présentation. C. Au lieu d'aller à la communication et d'ajouter la diapositive à votre présentation là, cliquez avec le bouton droit sur le problème dans les résultats de vérification et appuyez sur le bouton "Ajouter une diapositive". En procédant de cette façon, tous les objets de ce problème seront automatiquement inclus dans le problème de Catenda Hub et plus faciles à localiser. Combiné avec masquer les autres, rendre les autres  translucides dans Catenda Hub est un bon moyen de ne jamais perdre de vue quels objets sont inclus dans les problèmes. Lors de la création d'une diapositive de cette façon, vous obtiendrez toujours le même type de mise en page de problème que dans la communication où vous pouvez ajouter un titre, ajouter une description, ajouter des images et des commentaires supplémentaires. Il en va de même pour l'assignation de personnes au problème.

![Workflow_Solibri_-_Bimsync.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/01-intro.png)

D. Lorsque vous avez terminé votre vérification, allez à la communication et créez une présentation à partir des "résultats de vérification". Tous les problèmes que vous avez créés dans les résultats de vérification apparaîtront dans votre nouvelle présentation. Si vous souhaitez ajouter ces diapositives à une présentation existante, vous pouvez cliquer avec le bouton droit sur cette présentation et appuyer sur "mettre à jour la présentation à partir des résultats", de cette façon toutes les diapositives créées dans les résultats seront incluses dans cette présentation.

![Workflow_Solibri_-Bimsync__1.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/02-intro.png)

3\. Maintenant, après avoir créé la présentation, vous pouvez commencer à synchroniser avec Catenda Hub. Lorsque vous appuyez sur "Synchroniser la présentation", un menu contextuel apparaît. Dans celui-ci, vous pouvez cocher des cases pour décider de la façon dont vous souhaitez synchroniser. Si vous allez à "Conversion de valeur", vous pouvez définir différentes valeurs pour correspondre aux valeurs de votre projet Catenda Hub.

![Workflow_Solibri_-Bimsync__2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/03-intro.png)

4\. Conversion de valeur. Si, par exemple, vous avez assigné un problème à une personne directement dans Solibri et qu'il n'assigne pas le problème dans Catenda Hub, c'est parce que la conversion de valeur n'est pas définie correctement.

![Snag_62f59e4.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/04-intro.png)

Ces responsabilités définies dans le problème peuvent être définies pour correspondre aux utilisateurs du projet Catenda Hub. Ceci est fait dans la conversion de valeur ici :

![Snag_62c9ad3.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/05-intro.png)

Le bouton de conversion de valeur apparaît dans le menu contextuel lorsque vous cliquez avec le bouton droit sur la présentation et appuyez sur "Synchroniser la présentation". Lorsque ces problèmes sont assignés dans Solibri et synchronisés avec le projet Catenda Hub, les utilisateurs assignés recevront des Notifications si les Notifications sont activées. De cette façon, vous n'avez pas à assigner les problèmes manuellement dans Catenda Hub après la synchronisation avec Solibri.
