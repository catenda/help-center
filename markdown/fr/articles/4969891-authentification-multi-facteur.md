# Authentification multifactorielle

> Décrit comment configurer l'authentification multifactorielle sur votre compte

Vous trouverez les paramètres **Authentification multifactorielle** (MFA) sur la [page d'authentification](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f) qui est une sous-page de la [page de compte](https://support.catenda.com/en/articles/6880968-account-page).

**Authentification multifactorielle** (MFA) nécessite de saisir un code reçu via votre appareil mobile ainsi que votre nom d'utilisateur et votre mot de passe, lors de la connexion à Catenda Hub. Lorsqu'une organisation exige l'authentification multifactorielle, celle-ci est appliquée au niveau de l'organisation. Tous les projets appartenant à cette organisation nécessiteront alors une authentification multifactorielle pour accéder à leurs projets. Cela obligera tous les utilisateurs à activer l'authentification multifactorielle pour accéder aux projets appartenant à cette organisation.

Les thèmes suivants sont décrits dans cet article :

## 1. **Activation de l'authentification multifactorielle**

Connectez-vous à Catenda Hub et accédez à la page **[Compte](https://hub.catenda.com/account/profile)** :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/01-enabling-mfa.png)

1. Cliquez sur l'onglet **[Authentification](https://hub.catenda.com/account/authentication)** :
2. Faites défiler vers le bas jusqu'à la section Authentification multifactorielle :
3. Cliquez sur **Activer l'authentification multifactorielle**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/02-enabling-mfa.png)

Les thèmes suivants sont décrits dans cette section :

### 1.1 **Application d'authentification**

Pour commencer, installez une application sur un appareil mobile qui prend en charge le protocole TOTP (mot de passe à usage unique basé sur le temps). Installez une application d'authentification de confiance sur un appareil mobile pour commencer. La durée pendant laquelle une application d'authentification existe et la juridiction dans laquelle se trouve l'entreprise qui la possède sont souvent des éléments importants à considérer. Voici quelques exemples d'applications d'authentification recommandées :

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 139px;"><h3 id="h_b56161ee38"><b>Lois de sécurité des applications d'authentification</b></h3></td><td style="background-color: #e3e7fa80; width: 101px;"><h3 id="h_49bc31efe9">Entreprise</h3></td><td style="background-color: #e3e7fa80; width: 119px;"><h3 id="h_46b679c81c">Juridiction</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_7699fa4ab6">Lois de sécurité applicables</h3></td></tr><tr><td style="width: 139px;"><h3 id="h_ae65255403">Aegis</h3></td><td style="width: 101px;"><p>Beem</p></td><td style="width: 119px;"><p>Pays-Bas<br/>(Dordrecht)</p></td><td><p>RGPD<br/>Accord des 9 yeux</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_42b556ff02">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Roland Moers</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Allemagne</p></td><td style="background-color: #e8e8e880;"><p>RGPD<br/>Bundesdatenschutzgesetz - BDSG <br/>Accord des 14 yeux</p></td></tr><tr><td style="width: 139px;"><h3 id="h_5e0c03d260">Authentificateur</h3></td><td style="width: 101px;"><p>Google</p></td><td style="width: 119px;"><p>États-Unis<br/>(Californie)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_918c12706e">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Microsoft</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>États-Unis<br/>(Washington)</p></td><td style="background-color: #e8e8e880;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="width: 139px;"><h3 id="h_b3a055f26d">Ente Auth</h3></td><td style="width: 101px;"><p>Ente</p></td><td style="width: 119px;"><p>États-Unis (Delaware)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_63d03979d2">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Internet Initiative Japan</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Japon</p></td><td style="background-color: #e8e8e880;"><p>Act on the Protection of Personal Information (APPI)</p></td></tr><tr><td style="width: 139px;"><h3 id="h_848afb2dfa">HENNGE Lock</h3></td><td style="width: 101px;"><p>HENNGE K.K.</p></td><td style="width: 119px;"><p>Japon</p></td><td><p>Act on the Protection of Personal Information (APPI)</p></td></tr></tbody></table></div>

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 138px;"><h3 id="h_5e28bb0eb3"><b>Fonctionnalités de l'application d'authentification</b></h3></td><td style="background-color: #e3e7fa80; width: 88px;"><h3 id="h_6ed7d3e230">Date de sortie</h3></td><td style="background-color: #e3e7fa80; width: 180px;"><h3 id="h_f652151c66">Système d'exploitation</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_824368384e">Extraction de code</h3></td></tr><tr><td style="width: 138px;"><h3 id="h_218c61c8b2">Aegis</h3></td><td style="width: 88px;"><p>2019</p></td><td style="width: 180px;"><p>Android</p></td><td><p>Exporter vers un fichier texte brut complet ou chiffré. JSON / TXT / QR</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_0274ada2cb">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2020</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS</p></td><td style="background-color: #e8e8e880;"><p>Exporter vers fichier propriétaire / Afficher le secret</p></td></tr><tr><td style="width: 138px;"><h3 id="h_cc8ae8a27d">Authentificateur</h3></td><td style="width: 88px;"><p>2010</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>Transférer vers une autre application Google Authenticator avec un compte Google</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_6d595cbd69">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS<br/>Android</p></td><td style="background-color: #e8e8e880;"><p>Transférer vers une autre application Microsoft Authenticator avec un compte Microsoft.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_9cbe3f20d2">Ente Auth</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>JSON / TXT</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_425ee9cdba">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS - 8.1+<br/>Android - 4.0+</p></td><td style="background-color: #e8e8e880;"><p>Exportation de code QR par code.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_10c8930b4e">HENNGE Lock</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS - Les 2 dernières versions majeures <br/>Android - les 4 dernières versions nommées</p></td><td><p>Aucun</p></td></tr></tbody></table></div>

Théoriquement, toute application qui prend en charge l'authentification multifactorielle ou l'authentification à deux facteurs via le protocole TOTP peut être utilisée. Il existe même des applications de bureau, mais elles ne sont pas recommandées car les applications de bureau sont souvent toujours connectées au même réseau, qui contient souvent plusieurs appareils, ce qui augmente le risque qu'un acteur malveillant accède au code.

**Permissions de l'application** Pour pouvoir scanner le code QR avec la caméra de l'appareil. L'application d'authentification aura besoin de permissions d'accès à la caméra pour pouvoir scanner le code. L'application peut vous demander la permission d'utiliser la caméra de l'appareil. Les options de permission peuvent inclure : "Seulement pendant l'utilisation de l'application" - L'application a la permission pendant l'utilisation. "Demander chaque fois" - La permission doit être accordée à chaque utilisation de l'application. "Ne pas autoriser" - La permission n'est pas accordée ou est révoquée de l'application.

**Google Authenticator** Cliquez sur le plus en bas à droite et scannez un code QR. Ici, vous allez scanner le code QR que la [page d'authentification](https://hub.catenda.com/account/authentication) vous fournit. Vous pouvez également utiliser votre caméra pour scanner le code et saisir la clé de configuration que vous voyez dans l'URL qui s'ouvre.

**Microsoft Authenticator** Assurez-vous que vous êtes dans le menu Authentificateur en bas.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/03-authentication-app.png)

> **Remarque :** assurez-vous que vous n'êtes pas dans le menu Identifiants vérifiés, car vous pouvez scanner un code qr ici, mais cela ne fonctionnera pas.

Ensuite, cliquez sur le plus dans la barre bleue en haut à droite. Sélectionnez Autre compte (Google, Facebook, etc.) Si votre application n'a pas la permission d'accéder à votre caméra, vous pouvez ou non être invité à accorder la permission à votre caméra.

Si votre application a accès à votre caméra, vous pouvez scanner le code QR que la [page d'authentification](https://hub.catenda.com/account/authentication) vous fournit.

Si votre application n'a pas accès à votre caméra, vous serez invité à créer manuellement un compte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/04-authentication-app.png)

Nom du compte : Le nom que vous donnez à votre compte Clé secrète : C'est la clé que vous auriez obtenue si vous aviez pu scanner le code qr. Vous pouvez utiliser votre application de caméra pour scanner le code. L'URL qui s'ouvre lorsque vous scannez le code peut ressembler à ceci : `otpauth://totp/<Adresse e-mail du compte Catenda>?secret=<Clé secrète>&issuer=Catenda&algorithm=SHA1&digits=6&period=30` Si vous saisissez le code après "`secret=`" dans la clé secrète que vous voyez dans l'URL qui s'ouvre, le nom du compte peut être n'importe quoi.

> **Remarque :** Si vous créez un compte avec la mauvaise clé secrète, l'application générera des codes à usage unique de toute façon, donc Catenda pourrait ne pas accepter le code si la mauvaise clé secrète a été utilisée.

### 1.2 **Succès ou échec**

**Succès** Après avoir activé avec succès l'authentification multifactorielle, vous verrez ce message.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/05-success-or-fail.png)

Une fois activée, vous devrez avoir votre appareil mobile à portée de main chaque fois que vous vous connectez à Catenda Hub. L'authentification multifactorielle peut être désactivée à nouveau en cliquant sur Désactiver l'authentification multifactorielle.

**Code incorrect** Si vous n'avez pas saisi le bon code, vous recevrez le message code incorrect.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/06-success-or-fail.png)

> **Remarque :** Si vous avez scanné le code QR, vous pouvez essayer d'entrer le code dans le délai imparti pour ce code pendant que ce menu est ouvert. Si vous fermez ce menu, vous devrez supprimer le code généré dans votre application d'authentification et scanner le code QR à nouveau pour configurer un nouvel appairage de code.

## 2. **Modification de l'authentification multifactorielle**

Après avoir connecté un code d'authentification multifactorielle, vous pouvez modifier en toute sécurité le nom du compte du code. Vous pouvez le faire de les façons suivantes :

**Google Authenticator**

1. Appuyez longuement sur le code
2. Cliquez sur le crayon en haut à droite pour modifier le nom.

**Microsoft Authenticator**

1. Cliquez sur le code.
2. Cliquez sur le bouton d'engrenage en haut à droite
3. Cliquez sur le crayon pour modifier le nom

## 3. **Transfert de l'authentification multifactorielle**

**Désactivation et réactivation** Il n'est possible d'utiliser qu'un seul appairage de code d'authentification multifactorielle à la fois. Si vous souhaitez passer à un appairage de code différent, peut-être parce que votre appairage actuel a été compromis, vous suivez ces étapes : Vous devriez également utiliser cette méthode si vous souhaitez modifier l'application que vous utilisez pour l'authentification multifactorielle.

1. Désactivez votre authentification multifactorielle sur la [page d'authentification](https://hub.catenda.com/account/authentication)
2. Préparez l'application que vous souhaitez utiliser pour reconnecter votre authentification multifactorielle
3. Générez un nouvel appairage de code en scannant le code QR comme dans la [section activation](#enabling-mfa)

> **Remarque :** Soyez prudent avec cette méthode car votre compte sera temporairement vulnérable pendant qu'il est désactivé et vous ne pourrez pas accéder aux projets qui nécessitent l'authentification multifactorielle pendant cette période.

**Transfert via sauvegarde** Si vous souhaitez commencer à utiliser un nouvel appareil sans que votre code soit temporairement désactivé, vous pouvez utiliser une installation différente de la même application d'authentification multifactorielle et transférer le code de l'ancienne installation à la nouvelle.

**Google Authenticator** Ancien appareil :

1. Appuyez sur le menu hamburger en haut à droite
2. Appuyez sur Exporter les comptes
3. Sélectionnez les comptes que vous souhaitez exporter

Nouvel appareil :

1. Appuyez sur le menu hamburger en haut à droite
2. Appuyez sur Importer les comptes
3. Appuyez sur scanner le code QR
4. Scannez le code QR affiché sur l'ancien appareil lorsque vous avez suivi le processus d'exportation.

**Microsoft Authenticator** Ancien appareil :

1. Appuyez sur le menu hamburger en haut à droite
2. Activez la sauvegarde

Nouvel appareil :

1. Installez et ouvrez l'application Microsoft Authenticator sur votre nouvel appareil
2. Appuyez sur "Commencer la récupération."

> **Remarque 1 :** Ne configurez aucun compte à l'aide de Microsoft Authenticator avant d'avoir utilisé l'outil de récupération, car cela remplacera les comptes de site correspondants.

> **Remarque 2 :** Cette méthode nécessite que vous sauvegardiez vos codes d'authentification multifactorielle, ce qui signifie qu'ils sont stockés dans le service cloud de votre fournisseur d'applications. N'utilisez cette méthode que si vous faites confiance au service de sauvegarde de votre fournisseur d'applications. Sinon, il est préférable de désactiver et de réactiver.

## 4. **Désactivation de l'authentification multifactorielle**

Vous pouvez désactiver l'authentification multifactorielle en cliquant sur le bouton Désactiver ci-dessus, puis en saisissant votre mot de passe pour confirmer. Après désactivation, vous ne pourrez plus accéder aux projets qui nécessitent l'authentification multifactorielle.

Après la désactivation du code sur Catenda Hub, le code restera sur l'application avec laquelle vous l'avez connecté. Ce code sera désormais inutile et peut être supprimé en toute sécurité.

### 4.1 **Comment supprimer l'ancien code :**

**Google Authenticator**

1. Appuyez longuement sur le code
2. Cliquez sur la corbeille en haut à droite.

**Microsoft Authenticator**

1. Cliquez sur le code.
2. Cliquez sur le bouton d'engrenage en haut à droite
3. Cliquez sur Supprimer le compte

## 5. **Authentification multifactorielle sur appareils non mobiles**

Les applications d'authentification sont plus sécurisées que les solutions de code SMS/Email car il n'y a aucune communication qui peut être interceptée entre les deux systèmes après la configuration initiale. Bien qu'il soit préférable d'utiliser une application sur une application mobile, voir la remarque ci-dessous, il est possible d'obtenir des codes d'authentification multifactorielle sur d'autres systèmes que les appareils mobiles. L'application de bureau recommandée pour cela est [Authy](https://authy.com/). Fonctionnellement, ces types d'applications utilisent le même protocole TOTP que l'application sur votre appareil mobile et devraient être tout aussi sécurisés.

> **Avertissement :** Les applications de bureau peuvent être moins sécurisées car elles peuvent être plus faciles à pirater ou auxquelles accéder. Cela s'explique par le fait que les systèmes de bureau sont souvent, sinon toujours, connectés au réseau local qui pourrait être infecté. Les appareils mobiles qui ne sont pas toujours connectés au réseau peuvent donc être plus difficiles à pénétrer.

## 6. **Qui peut appliquer l'authentification multifactorielle sur les projets ?**

Les clients entreprise peuvent demander qu'une [option d'organisation](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) soit activée, ce qui fait que tous les utilisateurs faisant partie de ses projets doivent utiliser l'authentification multifactorielle pour accéder au projet. Pour activer l'authentification multifactorielle sur les projets de votre organisation, contactez le support Catenda. Lorsque l'authentification multifactorielle est requise sur les projets d'une organisation, ce message s'affiche lorsque vous tentez d'ouvrir le projet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/07-who-can-enforce-mfa-on-projects.png)
