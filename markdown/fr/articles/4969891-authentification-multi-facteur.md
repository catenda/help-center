# Authentification Multi-Facteurs

> Décrit comment configurer le MFA sur votre compte

Vous pourrez trouver les paramètres **Authentification Multi-Facteurs** (MFA) sur la [page d'authentification](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f) qui est une sous-page de la [page du compte](https://support.catenda.com/en/articles/6880968-account-page).

**Authentification Multi-Facteurs** (MFA) nécessite d'entrer un code reçu via votre appareil mobile ainsi que votre nom d'utilisateur et votre mot de passe lors de la connexion à Catenda Hub. Quand une organisation exige le MFA, il est appliqué au niveau de l'organisation. Tous les projets appartenant à cette organisation exigeront alors le MFA pour accéder à leurs projets. Cela obligera tous les utilisateurs à activer le MFA pour accéder aux projets appartenant à cette organisation.

## 1. **Activation du MFA**

Connectez-vous à Catenda Hub et accédez à la page **[Compte](https://hub.catenda.com/account/profile)** :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/01-enabling-mfa.png)

1. Cliquez sur l'onglet **[Authentification](https://hub.catenda.com/account/authentication)** :
1. Faites défiler vers le bas jusqu'à la section MFA :
1. Cliquez sur **Activer le MFA**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/02-enabling-mfa.png)

### 1.1 **Application d'authentification**

Pour commencer, installez une application sur un appareil mobile qui supporte le protocole TOTP (Time-based one-time password). Installez une application d'authentification de confiance sur un appareil mobile pour démarrer. La durée pendant laquelle une application d'authentification existe et la juridiction où se trouve l'entreprise qui la possède sont souvent des éléments à considérer. Voici quelques exemples d'applications d'authentification recommandées :

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 139px; padding: 8px;"><h3 id="h_b56161ee38"><b>Lois de sécurité des applications d'authentification</b></h3></td><td style="background-color: #e3e7fa80; width: 101px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_49bc31efe9">Entreprise</h3></td><td style="background-color: #e3e7fa80; width: 119px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_46b679c81c">Juridiction</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_7699fa4ab6">Lois de sécurité qui s'appliquent</h3></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_ae65255403">Aegis</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Beem</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pays-Bas<br/>(Dordrecht)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGPD<br/>Accord des 9 yeux</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_42b556ff02">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Roland Moers</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Allemagne</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGPD<br/>Bundesdatenschutzgesetz - BDSG <br/>Accord des 14 yeux</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_5e0c03d260">Authentificateur</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Google</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>États-Unis<br/>(Californie)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Loi de clarification sur l'utilisation légale des données à l'étranger <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_918c12706e">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Microsoft</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>États-Unis<br/>(Washington)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Loi de clarification sur l'utilisation légale des données à l'étranger <i>(</i>CLOUD) Act</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_b3a055f26d">Ente Auth</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ente</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>États-Unis (Delaware)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Loi de clarification sur l'utilisation légale des données à l'étranger <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_63d03979d2">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Internet Initiative Japan</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Japon</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Loi sur la protection des informations personnelles (APPI)</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_848afb2dfa">HENNGE Lock</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>HENNGE K.K.</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Japon</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Loi sur la protection des informations personnelles (APPI)</p></td></tr></tbody></table></div>

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 138px; padding: 8px;"><h3 id="h_5e28bb0eb3"><b>Fonctionnalité de l'application d'authentification</b></h3></td><td style="background-color: #e3e7fa80; width: 88px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_6ed7d3e230">Date de sortie</h3></td><td style="background-color: #e3e7fa80; width: 180px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_f652151c66">Système d'exploitation</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_824368384e">Extraction de code</h3></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_218c61c8b2">Aegis</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2019</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Exporter en texte brut complet ou fichier chiffré. JSON / TXT / QR</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_0274ada2cb">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Exporter en fichier propriétaire / Afficher le secret</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_cc8ae8a27d">Authentificateur</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2010</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Transférer vers une autre application Google Authenticator avec un compte Google</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_6d595cbd69">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Transférer vers une autre application Microsoft Authenticator avec un compte Microsoft.</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_9cbe3f20d2">Ente Auth</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>JSON / TXT</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_425ee9cdba">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS - 8.1+<br/>Android - 4.0+</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Export de code QR par code.</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_10c8930b4e">HENNGE Lock</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS - 2 dernières versions majeures <br/>Android - 4 dernières versions nommées</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Aucun</p></td></tr></tbody></table></div>

Théoriquement, toute application qui supporte le MFA / l'authentification à deux facteurs via le protocole TOTP peut être utilisée. Il existe même des applications de bureau, mais celles-ci ne sont pas recommandées du fait que les applications de bureau sont souvent toujours connectées au même réseau qui a souvent plusieurs appareils dessus, ce qui augmente le risque qu'un mauvais acteur accède au code.

**Permissions de l'application** Pour que vous puissiez scanner le code QR avec l'appareil photo de l'appareil. L'application d'authentification aura besoin de permissions d'appareil photo pour pouvoir scanner le code. L'application peut demander à recevoir la permission d'utiliser l'appareil photo de l'appareil. Les options de permission peuvent inclure : "Uniquement pendant l'utilisation de l'application" - L'application a la permission pendant son utilisation. "Demander à chaque fois" - La permission doit être accordée à chaque utilisation de l'application. "Ne pas autoriser" - La permission n'est pas donnée ou révoquée de l'application.

**Google Authenticator** Cliquez sur le plus en bas à droite et scannez un code QR. Ici, vous scannerez le code QR que la [page d'authentification](https://hub.catenda.com/account/authentication) vous fournit. Vous pouvez également utiliser votre appareil photo pour scanner le code et taper la clé de configuration que vous voyez dans l'URL qui s'ouvre.

**Microsoft Authenticator** Assurez-vous que vous êtes dans le menu Authenticator en bas.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/03-authentication-app.png)

> **Note :** assurez-vous que vous ne soyez pas dans le menu Verified IDs car vous pouvez scanner un code qr ici mais cela ne fonctionnera pas.

Ensuite, cliquez sur le plus dans la barre bleue en haut à droite. Sélectionnez Autre compte (Google, Facebook, etc.) Si votre application n'a pas la permission pour votre appareil photo, vous pouvez ou non être invité à donner la permission pour votre appareil photo.

Si votre application a accès à votre appareil photo, vous pouvez scanner le code QR que la [page d'authentification](https://hub.catenda.com/account/authentication) vous fournit.

Si votre application n'a pas accès à votre appareil photo, vous serez invité à créer manuellement un compte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/04-authentication-app.png)

Nom du compte : Le nom que vous donnez à votre compte Clé secrète : C'est la clé que vous auriez obtenue si vous aviez pu scanner le code qr. Vous pouvez utiliser votre application appareil photo pour scanner le code. L'URL qui s'ouvre lorsque vous scannez le code peut ressembler à ceci : `otpauth://totp/<Catenda account email address>?secret=<Secret key>&issuer=Catenda&algorithm=SHA1&digits=6&period=30` Si vous tapez le code après "`secret=`" dans la clé secrète que vous voyez dans l'URL qui s'ouvre, le nom du compte peut être n'importe quoi.

> **Note :** Si vous créez un compte avec la mauvaise clé secrète, l'application générera quand même des codes à usage unique, donc Catenda risque de ne pas accepter le code si la mauvaise clé secrète a été utilisée.

### 1.2 **Succès ou échec**

**Succès** Après avoir activé avec succès le MFA, vous verrez ce message.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/05-success-or-fail.png)

Une fois activé, vous devrez avoir votre appareil mobile à portée de main chaque fois que vous vous connectez à Catenda Hub. Le MFA peut être désactivé à nouveau en cliquant sur Désactiver le MFA.

**Code incorrect** Si vous n'avez pas inséré le bon code, vous recevrez le message code incorrect.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/06-success-or-fail.png)

> **Note :** Si vous avez scanné le code QR, vous pouvez essayer d'entrer le code dans le délai imparti pour ce code pendant que ce menu est ouvert. Si vous fermez ce menu, vous devrez supprimer le code généré dans votre application d'authentification et scanner à nouveau le code QR pour configurer un nouvel appairage de code.

## 2. **Modification du MFA**

Après avoir connecté un code MFA, vous pouvez modifier en toute sécurité le nom du compte du code. Vous pouvez le faire de la manière suivante :

**Authentificateur Google**

1. Maintenez longtemps le code appuyé
1. Cliquez sur le crayon en haut à droite pour changer le nom.

**Authentificateur Microsoft**

1. Cliquez sur le code.
1. Cliquez sur le bouton d'engrenage en haut à droite
1. Cliquez sur le crayon pour changer le nom

## 3. **Transfert du MFA**

**Désactivation et réactivation** Il n'est possible d'utiliser qu'un appairage de code MFA à la fois. Si vous souhaitez passer à un appairage de code différent, peut-être parce que le vôtre a été compromis, vous suivez ces étapes : Vous devez également utiliser cette méthode si vous souhaitez changer l'application que vous utilisez pour le MFA.

1. Désactivez votre MFA sur la [page d'authentification](https://hub.catenda.com/account/authentication)
1. Préparez l'application que vous souhaitez utiliser pour reconnecter votre MFA
1. Générez un nouvel appairage de code en scannant le code QR comme dans la [section d'activation](#h_9e13fd06f5)

> **Note :** Soyez prudent avec cette méthode car votre compte sera temporairement vulnérable pendant qu'il est désactivé et vous ne pourrez pas accéder aux projets où le MFA est requis pendant cette période.

**Transfert par sauvegarde** Si vous souhaitez commencer à utiliser un nouvel appareil sans que votre code soit temporairement désactivé, vous pouvez utiliser une installation différente de la même application MFA et transférer le code de l'ancienne installation vers la nouvelle installation.

**Authentificateur Google** Ancien appareil :

1. Appuyez sur le menu hamburger en haut à droite
1. Appuyez sur Exporter les comptes
1. Sélectionnez les comptes que vous souhaitez exporter

Nouvel appareil :

1. Appuyez sur le menu hamburger en haut à droite
1. Appuyez sur importer les comptes
1. Appuyez sur scanner le code QR
1. Scannez le code QR affiché sur l'ancien appareil lorsque vous avez suivi le processus d'export.

**Authentificateur Microsoft** Ancien appareil :

1. Appuyez sur le menu hamburger en haut à droite
1. Activez la sauvegarde

Nouvel appareil :

1. Installez et ouvrez l'application Microsoft Authenticator sur votre nouvel appareil
1. Appuyez sur "Commencer la récupération."

> **Note 1 :** Ne configurez aucun compte à l'aide de Microsoft Authenticator avant d'avoir utilisé l'outil de récupération car il remplacera les comptes de site correspondants.

> **Note 2 :** Cette méthode nécessite que vous sauvegardiez vos codes MFA, ce qui signifie qu'ils sont stockés dans le service cloud de votre fournisseur d'applications. N'utilisez cette méthode que si vous faites confiance au service de sauvegarde de votre fournisseur d'applications. Si ce n'est pas le cas, il est préférable de désactiver et réactiver.

## 4. **Désactivation du MFA**

Vous pouvez désactiver le MFA en cliquant sur le bouton de désactivation montré ci-dessus, puis en entrant votre mot de passe pour confirmer. Après désactivation, vous ne serez plus en mesure d'accéder aux projets nécessitant le MFA.

Après avoir désactivé le code sur Catenda Hub, le code restera sur l'application avec laquelle vous vous êtes connecté. Ce code sera maintenant inutile et peut être supprimé en toute sécurité.

### 4.1 **Comment supprimer l'ancien code :**

**Authentificateur Google**

1. Maintenez longtemps le code appuyé
1. Cliquez sur la corbeille en haut à droite.

**Authentificateur Microsoft**

1. Cliquez sur le code.
1. Cliquez sur le bouton d'engrenage en haut à droite
1. Cliquez sur supprimer le compte

## 5. **MFA sur appareils non mobiles**

Les applications d'authentification sont plus sécurisées que les solutions de code SMS/Email car il n'y a pas de communication qui peut être interceptée entre les deux systèmes après la configuration initiale. Bien qu'il soit préférable d'utiliser une application sur une application mobile, voir la note ci-dessous, il est possible d'obtenir des codes MFA sur d'autres systèmes que les appareils mobiles. L'application de bureau recommandée pour cela est [Authy](https://authy.com/). Fonctionnellement, ces types d'applications utilisent le même protocole TOTP que l'application sur votre appareil mobile et devraient être tout aussi sûrs.

> **Avertissement :** Les applications de bureau peuvent être moins sécurisées car elles pourraient être plus faciles à pirater ou accéder. C'est parce que les systèmes de bureau sont souvent, sinon toujours, connectés au réseau local qui pourrait être infecté. Les appareils mobiles qui ne sont pas toujours connectés au réseau peuvent donc être plus difficiles à pénétrer.

## 6. **Qui peut appliquer le MFA sur les projets ?**

Les clients Enterprise peuvent demander qu'une [option d'organisation](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) soit activée, ce qui fait que tous les utilisateurs qui font partie de leurs projets doivent utiliser le MFA pour accéder au projet. Pour activer le MFA sur les projets de votre organisation, contactez le support Catenda. Lorsque le MFA est requis sur les projets d'une organisation, vous verrez ce message en tentant d'ouvrir le projet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/07-who-can-enforce-mfa-on-projects.png)
