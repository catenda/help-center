# Dépannage des notifications Microsoft Équipes

Cet article contient des informations sur les erreurs qui peuvent survenir lors de la configuration des notifications Microsoft Équipes avec Catenda via les workflows Microsoft Équipes.

Cet article contient des informations sur les sujets suivants : [Pas de Notifications](#h_42fb432d1c)

## 1. **Pas de Notifications dans le canal Microsoft Équipes**

Si une URL de workflow Microsoft Équipes a été configurée dans Catenda et qu'une Notification Catenda pour l'une des cases de Notifications qui sont cochées dans l'onglet Microsoft Équipes des paramètres de Notification a été reçue, mais qu'il n'y a pas de message dans le canal Microsoft Équipes qui a été configuré, il est probable qu'il y ait un problème avec le workflow Microsoft Équipes.

Pour vérifier si quelque chose s'est mal passé avec le workflow Microsoft Équipes, sélectionnez Workflows en survolant le canal et en cliquant sur les trois points, ou en cliquant sur les trois points en haut à droite d'un canal.

<img alt="Menu d'action du canal Microsoft Teams, Workflows en surbrillance." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Menu d'action dans le canal Microsoft Teams, Workflows en surbrillance." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-1a6a43fe9eec.png" width="290"/>

Si quelque chose ne va pas avec le workflow, une erreur peut s'afficher dans le workflow Envoyer les alertes webhook à un canal du menu Vos workflows.

![Équipes Microsoft Un problème de connexion s'est produit et nécessite votre attention](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/01-no-notifications-in-microsoft-teams-channel.png)

Une erreur peut être : `Un problème de connexion s'est produit et nécessite votre attention`

Cliquez sur le workflow pour l'ouvrir dans le navigateur préféré, ou cliquez sur les détails pour voir plus d'informations dans Microsoft Équipes. Voici à quoi peuvent ressembler les détails du workflow Webhook dans Microsoft Équipes en cas d'erreur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/02-no-notifications-in-microsoft-teams-channel.png)

Ici, vous pouvez voir l'heure et la date auxquelles l'erreur s'est produite. Cliquez sur l'heure et la date de l'échec pour ouvrir le workflow dans Power Automate dans le navigateur préféré. Voici à quoi peut ressembler l'échec dans Power Automate :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/03-no-notifications-in-microsoft-teams-channel.png)

L'alerte dans Power Automate nous donne une meilleure indication de ce qui pourrait ne pas aller. Dans ce cas, le message d'erreur suivant a été affiché :

`Alerte : La connexion de votre <email> ne fonctionne pas : Il semble que la connexion <email> de votre flux doit être reconnectée. La cause la plus courante est un mot de passe modifié ou une politique définie par votre administrateur client. Les connexions peuvent également nécessiter une nouvelle authentification si l'authentification multifacteur a été récemment activée pour votre compte.`

Pour vous réauthentifier, cliquez sur le workflow dans Équipes et ouvrez le workflow dans Power Automate. Il est également possible d'accéder à la page de connexion dans Power Automate et d'établir une connexion à partir de là.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/04-no-notifications-in-microsoft-teams-channel.png)

Dans la boîte de dialogue Action requise, cliquez sur Réauthentifier. Après une authentification réussie, la connexion devrait s'afficher sur la page Connexions.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/05-no-notifications-in-microsoft-teams-channel.png)
