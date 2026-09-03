# Paramètres de notification de compte

La page des paramètres de notification se trouve en tant que sous-page de la [page notifications](https://hub.catenda.com/notifications). Dans les [paramètres de notification](https://bimsync.com/notifications/settings), il est possible de configurer les notifications que vous recevez.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/01-intro.png)

Chaque onglet correspond à une méthode différente d'envoi de notifications.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/02-intro.png)

L'onglet sur lequel vous êtes actuellement sera souligné d'une barre verte.

## 1. **Commutateur de notification**

Pour chaque méthode de notification, vous pouvez complètement activer ou désactiver les notifications. Par défaut, les notifications Catenda Hub et e-mail seront activées, tandis que les notifications Slack et Équipes seront désactivées. Pour activer ou désactiver complètement les notifications pour un onglet, appuyez sur ce commutateur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/03-notification-switch.png)

Lorsqu'une méthode de notification a été désactivée, le cercle à côté de l'onglet devient gris.

> **Remarque :** Si vous désactivez les notifications par e-mail, vous pouvez toujours recevoir les e-mails d'invitation de projet et de lien de partage.

Cliquez à nouveau sur le commutateur pour réactiver les notifications.

## 2. **Cases à cocher de notification**

Pour chaque méthode de notification, vous pouvez choisir les types de notifications que vous souhaitez recevoir pour cette méthode. Cliquez [ici](https://support.catenda.com/en/articles/8304417-untitled-article) pour voir quand chaque type de notification est envoyé.

## 3. **Notifications dans le navigateur**

L'onglet Catenda Hub vous permet de configurer les notifications que vous recevez dans le navigateur. Ce sont les notifications que vous voyez sur la [page notifications](https://hub.catenda.com/notifications). Lorsque vous recevez une notification, vous verrez un nombre rouge de notifications non lues sur l'icône de notification en haut à droite. Lorsque vous cliquez sur ce bouton, le badge de notifications non lues disparaîtra.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/04-in-browser-notifications.png)

## 4. **Notifications par e-mail**

L'onglet e-mail vous permet de configurer les notifications que vous recevez par e-mail. Par défaut, vous recevez un e-mail par notification sur Catenda Hub. Si vous modifiez vos notifications par e-mail, vous recevrez toujours toutes les notifications sur Catenda Hub comme vous l'avez configuré [ci-dessus](#h_e4a9ba5c0c)

### 4.1 **Résumé par e-mail**

Avec les notifications par e-mail, vous pouvez choisir de recevoir un résumé quotidien à la place.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/05-br-email-summary.png)

Chaque fois qu'un résumé est envoyé, il contiendra toutes les notifications qui se sont produites depuis le dernier résumé.

## 5. **Notifications Slack**

L'onglet Slack vous permet de recevoir les notifications qui ont été envoyées à votre compte dans un canal Slack. Cette méthode de notification est désactivée par défaut et doit être configurée et activée si vous souhaitez l'utiliser. Vous pourrez trouver le paramètre de l'URL du webhook en bas de la page des onglets.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/06-slack-notifications.png)

La configuration de « Slack webhook URL » postera les notifications Catenda Hub sur Slack. Pour configurer, allez sur ([https://api.slack.com/incoming-webhooks](https://api.slack.com/incoming-webhooks)) et cliquez sur le lien `intégration du webhook entrant`. Choisissez le canal où vous souhaitez que les messages soient envoyés et copiez le champ `URL webhook` dans Catenda.

## 6. **Notifications Microsoft Équipes**

L'onglet Microsoft Équipes vous permet de recevoir les notifications qui ont été envoyées à votre compte dans un canal Microsoft Équipes. Cette méthode de notification est désactivée par défaut et doit être configurée et activée si vous souhaitez l'utiliser. Vous pourrez trouver le paramètre de l'URL du webhook en bas de la page des onglets.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/07-microsoft-teams-notifications.png)

Dans votre canal Équipes, sélectionnez **"Connecteurs"** dans le menu principal. Recherchez **"Webhook entrant"** et sélectionnez **"Configurer"**. Définissez le nom sur Catenda, utilisez **"[https://hub.catenda.com/img/logo-192x192.png](https://hub.catenda.com/img/logo-192x192.png)"** comme image, puis appuyez sur **"Créer"**.

Copiez l'URL dans **"URL webhook"** ci-dessus. Assurez-vous que les notifications sont activées en haut, puis vérifiez les types de notifications que vous souhaitez envoyer dans le canal Équipes

## 7. **Notifications par projet**

Si vous avez défini des notifications spécifiques au projet, vous pourrez les voir dans le menu de navigation de gauche d'un projet. Vous pouvez cliquer sur le nom du projet pour accéder aux [paramètres de notification du projet](https://support.catenda.com/en/articles/4670262-project-notification-settings) de ce projet. Ces paramètres vous seront spécifiques et ne sont pas des paramètres pour l'ensemble du projet.
