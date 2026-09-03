# Notifications Équipes Microsoft

> Restez à jour sans changer d'onglet. Connectez Catenda Hub à Microsoft Équipes pour recevoir des Notifications en temps réel directement dans vos canaux préférés.

Recevez des Notifications en temps réel d'un compte Catenda directement dans un canal Microsoft Équipes en configurant un flux de travail Microsoft Équipes dans les paramètres de Notifications Catenda. _Accès requis :_ Un compte **Microsoft Équipes** avec les permissions de création de canal et de gestion des flux de travail Microsoft Équipes.

L'onglet Notifications Microsoft Équipes se trouve vers le haut de la [page des paramètres de Notifications de compte](https://support.catenda.com/en/articles/8272435-account-notification-settings) qui est une sous-page de la [page des Notifications de compte](https://support.catenda.com/en/articles/7439223-account-notifications-page) :

![Paramètres de notification Catenda Hub Notifications Microsoft Équipes Projets avec paramètres Équipes propres](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/01-intro.png)

Voici ce que les Notifications Catenda peuvent ressembler dans Microsoft Équipes après qu'un flux de travail Microsoft Équipes ait été configuré.

![Canal Microsoft Équipes Publications Prêt pour examen topic créé une nouvelle révision a été importée dans le modèle](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/02-intro.png)

---

### Étape 1 : Préparer un canal dédié

Les utilisateurs peuvent organiser les mises à jour de leur projet en créant un espace spécifique pour les Notifications Catenda. 1\. Dans **Microsoft Équipes**, sélectionnez l'onglet **Équipes** ou **Conversation**. 2\. Utilisez une équipe existante (ignorez cette étape) ou **créez une équipe**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/03-step-1-prepare-a-dedicated-channel.png)

Entrez un nom et créez l'équipe.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/04-step-1-prepare-a-dedicated-channel.png)

Quand une équipe est créée, un canal appelé général est automatiquement ajouté. 3\. Utilisez un canal existant (ignorez cette étape) ou ajoutez un canal. Cliquez avec le bouton droit sur une équipe et sélectionnez Ajouter un canal dans le menu d'action ou cliquez sur l'équipe et cliquez sur **Ajouter un canal** vers le haut à droite. _Accès requis :_ Propriétaire ou Membre de l'équipe.

![Microsoft Équipes Intégration Catenda Discussion Canaux Ajouter un canal Membres Analytique Applications Étiquettes Masquer tous les canaux Ajouter un membre Gérer l'équipe Gérer les étiquettes Copier le lien Quitter l'équipe](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/05-step-1-prepare-a-dedicated-channel.png)

> **Remarque :** Avec un accès invité ou externe, les canaux ne peuvent pas être créés. Dans ce cas, veuillez demander à un administrateur de canal de vous fournir une url pour que les Notifications soient envoyées à un canal.

Après avoir cliqué sur Créer un canal, la boîte de dialogue Créer un canal apparaît :

![Créer un canal Nom du canal Les lettres, chiffres et espaces sont autorisés Description Choisir un type de canal Standard Privé Discussions Publications](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/06-step-1-prepare-a-dedicated-channel.png)

**4. Nommez votre canal** : Utilisez quelque chose de clair comme "Notifications Catenda" ou "Projet-A-Notifications".

**5. Choisissez la confidentialité** : Les Notifications Catenda peuvent être livrées à la fois aux canaux standard et privés.

- Sélectionnez **Standard** si vous voulez que toute l'équipe voie les mises à jour.
- Sélectionnez **Privé** si les Notifications sont uniquement pour vous ou un groupe spécifique.

6\. Cliquez sur **Créer**.

---

### Étape 2 : Générer votre URL Webhook Équipes

Par le passé, les Notifications Catenda Équipes étaient configurées via une application Webhook Connector qui était configurée pour le canal. L'application Webhook Connector a depuis été abandonnée. Le moyen actuel de créer une URL webhook est de créer un flux de travail Microsoft Équipes.

Suivez ces étapes pour créer un nouveau webhook **Flux de travail** Microsoft Équipes. 1\. Ouvrez **Microsoft Équipes** 2\. Pointez sur l'équipe désirée et cliquez sur les trois points ou cliquez sur les trois points en haut à droite après avoir ouvert le canal. 3\. Sélectionnez **Flux de travail** Microsoft Équipes dans le menu d'action

<img alt="Menu d'action du canal Microsoft Équipes, Workflows en surbrillance." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Menu d'action dans le canal Microsoft Équipes, Workflows en surbrillance." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-1a6a43fe9eec.png" width="290"/>

4\. Recherchez **"Envoyer des alertes webhook à un canal"** et sélectionnez-le.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/07-step-2-generate-your-teams-webhook-url.png)

5\. Suivez les étapes d'installation pour sélectionner votre Équipe et Canal. **6. Copiez l'URL** : Une fois que le flux de travail Microsoft Équipes est créé, copiez l'URL webhook générée dans votre presse-papiers en cliquant sur Copier le Lien webhook vers le haut.

> **Remarque :** 💡**Conseil** : Gardez cette URL privée. N'importe qui ayant ce Lien peut envoyer des messages à votre canal Équipes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/08-step-2-generate-your-teams-webhook-url.png)

---

### Étape 3 : Se connecter à Catenda Hub

Suivez ces étapes pour configurer le Lien webhook dans Catenda. De cette façon, Catenda sait où envoyer les Notifications du projet.

1. Connectez-vous à **Catenda Hub**.
1. Accédez à vos **Notifications > Paramètres** (au niveau du compte ou au niveau du projet).
1. Sélectionnez l'onglet "Microsoft Équipes" et faites défiler jusqu'au bas.
1. Collez votre URL copiée dans le champ **URL du Webhook**.
1. Cliquez sur **Enregistrer**.

    <div class="intercom-container intercom-align-center"><img height="320" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a60f9c2dbac8.png" style="height: auto;" width="500"/></div>

1. **Activer les Notifications** : Assurez-vous que le bouton bascule en haut de la page est basculé sur **Activé**.

    <div class="intercom-container intercom-align-center"><img height="159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a3e9aa9365d2.png" style="height: auto;" width="500"/></div>

---

### Étape 4 : Personnaliser vos alertes

Adaptez les informations que vous recevez pour éviter la fatigue de notification. 1\. Dans le même menu **Paramètres des Notifications**, parcourez la liste des types de Notifications. **2. Cochez les cases** pour les mises à jour spécifiques que vous souhaitez recevoir dans votre canal Équipes. Voici ce que le menu des Notifications Microsoft Équipes peut ressembler :

![Choisir les Notifications que vous souhaitez recevoir Catenda Hub Email Notifications Microsoft Équipes Sujets Documents Approbations Collections Modèles Utilisateurs Un nouveau topic est créé Un topic m'est assigné Un topic me mentionne ou mentionne mes Équipes Nouveau commentaire dans un topic qui m'est assigné mentionné par moi suivi par moi Statut modifié dans un topic Type modifié dans un topic Je suis défini comme l'éditeur dans une demande d'approbation Une équipe dont je suis membre est définie comme l'éditeur dans une demande d'approbation Une demande d'approbation est fermée Un membre de l'équipe de soumission Une nouvelle demande d'approbation a été soumise Un document a été rejeté Une demande d'approbation est fermée Une nouvelle demande d'approbation a été soumise Une nouvelle demande d'approbation m'a été assignée Une nouvelle demande d'approbation est prête à être examinée par mon équipe Tous les examens ont été soumis par mon équipe Un document a été rejeté Une demande d'approbation est fermée En tant que membre de l'équipe d'examen pour l'approbation finale Une nouvelle demande d'approbation a été soumise Une nouvelle demande d'approbation a été assignée à mon équipe Une nouvelle demande d'approbation est prête à être examinée par mon équipe Tous les examens ont été soumis par mon équipe Tous les examens ont été soumis par mon équipe Une étape d'examen a été complétée Un document a été rejeté Une demande d'approbation est fermée Un nouveau modèle est créé Une nouvelle révision est importée.](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/09-step-4-customize-your-alerts.png)

Les cases de Notifications grisées sont désactivées pour les Équipes Microsoft et sont uniquement disponibles pour d'autres méthodes de Notifications. Les cases de Notifications pour les approbations deviennent disponibles si les révisions partagées sont activées dans les [paramètres du document](https://support.catenda.com/en/articles/7831371-document-settings-page) d'un projet.

---

### Étape 5 : Vérification

Assurez-vous qu'une Notification est envoyée à votre compte et également envoyée aux Équipes Microsoft.

1\. Effectuez une action dans Catenda Hub.

> **Avertissement :** ⚠️ **Remarque :** Pas chaque Notification n'est disponible pour être envoyée à Microsoft Équipes et les Notifications Microsoft Équipes ne sont généralement pas envoyées pour les actions que les utilisateurs effectuent eux-mêmes. Téléchargez un model ou demandez à un coéquipier de créer une topic ou de vous mentionner dans une description ou un commentaire pour vérifier le Lien.

2\. Vérifiez votre **Canal Microsoft Équipes**. 3\. Un message devrait apparaître instantanément via le bot **Flux de travail** Microsoft Équipes.
