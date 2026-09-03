# Dépannage de l'aperçu des documents

## 1. **1. Impossible de se connecter au serveur**

Lorsqu'un document est ouvert, l'aperçu du document peut être grisé avec un message centré qui indique:

`Impossible de se connecter au serveur`

Ce problème peut également ressembler à une lenteur sévère de la plateforme ou à des roues de chargement qui ne s'arrêtent jamais, en particulier sur la page **Collections** ou lors du chargement de la **Liste des modèles** dans la Visionneuse 3D.

### 1.1 **1.1 Pourquoi cela se produit**

Il existe une restriction sur le réseau Internet spécifique ou la connexion VPN utilisée. Les paramètres de sécurité du réseau permettent au site Web principal de Catenda de se charger, mais bloquent ou rejettent complètement les connexions en arrière-plan que la plateforme utilise pour envoyer et recevoir des données de projet volumineuses et des modèles 3D. Parce que ces flux de données en arrière-plan sont coupés, le système ne peut pas charger les informations, ce qui fait que la plateforme se fige indéfiniment ou affiche une erreur de connexion.

### 1.2 **1.2 Étape de dépannage**

Confirmez si le réseau cause le blocage, essayez de charger la plateforme ou l'aperçu du document tout en étant connecté à un réseau différent, par exemple un point d'accès de réseau mobile cellulaire. Si la page et les données se chargent normalement, la configuration du réseau principal bloque le trafic.

### 1.3 **1.3 Correctif permanent pour les administrateurs réseau**

Pour résoudre ce problème de manière permanente, la configuration du réseau doit être mise à jour pour soutenir pleinement le trafic en arrière-plan de Catenda, y compris tous les sous-domaines et les ports requis. Cliquez [ici](https://support.catenda.com/en/articles/13927294-network-recommendation) pour en savoir plus sur les exigences de liste blanche et les spécifications des ports (y compris les configurations obligatoires du port 443 TCP/UDP).

## 2. **2. Erreur lors du chargement du document (Délai d'expiration du délai)**

Lorsqu'un document est ouvert, la visionneuse Web qui affiche l'aperçu du document peut afficher un message qui indique: **"Délai d'expiration du délai"**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hq07qt4s/01-2-error-loading-document-read-timed-out.png)

`Délai d'expiration du délai`

### 2.1 **2.1 Pourquoi cela se produit**

Les paramètres de sécurité du réseau utilisé permettent uniquement à l'adresse du site Web principal de Catenda de passer. Le pare-feu du réseau ne reconnaît pas ou n'autorise pas un paramètre de caractère générique (qui autorise automatiquement toutes les adresses se terminant par `.catenda.com`), il bloque donc l'adresse en arrière-plan spécifique et distincte qui gère les aperçus de documents (`webviewer.catenda.com`). Au lieu de rejeter la connexion instantanément, le pare-feu ignore la demande jusqu'à ce que le navigateur abandonne l'attente, ce qui entraîne une erreur de délai d'expiration.

### 2.2 **2.2 Étape de dépannage**

Confirmez si la configuration du réseau cause le délai d'expiration, essayez de charger l'aperçu du document tout en étant connecté à un réseau différent, par exemple un point d'accès de réseau mobile cellulaire. Si l'aperçu se charge normalement, la configuration du pare-feu du réseau principal bloque le trafic.

### 2.3 **2.3 Correctif permanent pour les administrateurs réseau**

Pour résoudre ce problème de manière permanente, la configuration du pare-feu du réseau doit être mise à jour pour autoriser explicitement l'adresse spécifique utilisée pour les aperçus de documents (`webviewer.catenda.com`). Cliquez [ici](https://netw) pour en savoir plus sur les règles de liste blanche et les spécifications des ports.
