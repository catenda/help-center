# Options d'organisation

Il est possible de demander que les options suivantes soient définies pour votre organisation. Ces options s'appliqueront à tous les projets appartenant à l'organisation.

## 1. **Profil**

Veuillez contacter le support via le bouton de chat noir à côté de votre photo de profil en haut à droite ou à [support@catenda.com](mailto:support@catenda.com) si vous souhaitez modifier le nom de votre organisation.

## 2. **Plan**

Veuillez contacter [sales@catenda.com](mailto:sales@catenda.com) pour toute question concernant votre plan. Votre plan détermine le nombre de projets que vous pouvez avoir à tout moment dans une organisation. Votre plan détermine également la date d'expiration des nouveaux projets.

## 3. **Paramètres par défaut pour les nouveaux projets**

### 3.1 Option de titre de téléchargement de document

Si vous téléchargez un seul document, le nom de fichier sera toujours le nom de fichier original. Si vous téléchargez plusieurs documents, les noms de fichiers seront les noms des documents.

Avec cette option, vous pouvez configurer le nom de fichier que vous obtiendrez lors du téléchargement de plusieurs documents. Cela peut être utile en combinaison avec la convention de nommage et pour remplacer les documents qui ont le même nom au lieu d'avoir un numéro de révision différent à chaque fois.

**Exemple :** Le nom du projet est _testproject._ Deux fichiers sont téléchargés avec deux révisions chacun : _test01.pdf_ et _test02.pdf_ Les noms des documents sont ensuite modifiés en : _changed01.pdf_ et _changed02.pdf_

Comportement de téléchargement par défaut : Si vous téléchargez ces documents un par un, ils seront toujours nommés _test01.pdf_ et _test02.pdf_ Si vous téléchargez ces deux documents en même temps, ils seront par défaut appelés _changed01.pdf_ et _changed02.pdf_ C'est ce qui peut être modifié avec les options suivantes :

**Options :**

**Nom du fichier de révision** Notez que c'est la même chose que lors du téléchargement d'un seul fichier, les noms seront donc cohérents si vous choisissez cette option. \<Nom de fichier original>.\<Extension> _test01.pdf_ et _test02.pdf_

_Titre du document_ - par défaut \<Nom du document>.\<Extension> _changed01.pdf_ et _changed02.pdf_

**Titre du document avec numéro de révision** \<Nom du document>\<Numéro de révision>.\<Extension> _changed01.pdf #2_ et _changed02.pdf #2_

**Titre du projet avec titre du document et numéro de révision** \<Nom du projet>\<Nom du document>\<Numéro de révision>.\<Extension> _testproject changed01.pdf #2_ et _testproject changed02.pdf #2_

### 3.2 **Téléchargement de documents infectés**

Gestion de la mise en quarantaine des fichiers infectés dans les projets possédés. Si un document est trouvé infecté, par défaut, il peut être téléchargé. L'utilisateur recevra un avertissement indiquant que ce document contient un virus. Une option peut être définie par organisation pour que personne, pas même les administrateurs, ne puisse télécharger les documents infectés.

**Options :** _Avertir au téléchargement_ - par défaut

**Bloquer le téléchargement**

### 3.3 **Modèles en tant que documents**

Si cette fonctionnalité est activée, tous les nouveaux projets créés dans l'organisation auront la fonctionnalité [Modèles en tant que documents](https://support.catenda.com/en/articles/8064548-models-as-documents) activée.

> **Remarque :** 24 novembre : Cette fonctionnalité sera activée pour toutes les nouvelles organisations. Nous supporterons l'ancienne vue pendant environ un an avant que tous les projets ne soient migrés.

### 3.4 **Option de brouillon de téléchargement de document**

Si le flux d'approbation a été activé et qu'il y a des statuts de brouillon dans les paramètres de document, la case à cocher "télécharger en tant que brouillon" est cochée par défaut lors du téléchargement du document. Sur demande, cette case à cocher peut être définie comme décochée par défaut pour tous les projets dans une organisation.

## 4. **Membres**

Les utilisateurs peuvent être ajoutés en tant que Membres ou propriétaires d'une organisation.

### 4.1 **Propriétaires**

Les propriétaires d'organisations peuvent voir un aperçu de l'organisation dans l'[outil d'organisation](http://hub.catenda.com/orgs). Dans cet outil, ils seront en mesure de : Déplacer des projets vers d'autres organisations qu'ils possèdent (Les Archives sont souvent une organisation séparée) Créer de nouveaux projets au sein de l'organisation si votre plan le permet. Supprimer les projets appartenant à l'organisation. Ajouter des Membres de l'organisation aux projets sans les inviter. Inviter les utilisateurs aux projets de l'organisation sans avoir à faire partie du projet. Il est recommandé de garder peu de propriétaires de cette organisation car les projets n'ont pas besoin d'être déplacés souvent.

### 4.2 **Membres**

Les Membres des organisations peuvent être facilement ajoutés aux projets de l'organisation par les propriétaires de l'organisation.

## 5. **Règles du propriétaire du projet**

### 5.1 **Exiger que tous les utilisateurs utilisent MFA**

Les clients Enterprise peuvent demander l'application de MFA pour les utilisateurs participant à leurs projets. Avec cette option, tous les utilisateurs sont tenus d'avoir MFA configuré pour rejoindre les projets appartenant à votre organisation.

### 5.2 **Les utilisateurs SSO internes ne sont pas tenus d'utiliser MFA**

Les clients Enterprise peuvent demander de configurer [l'authentification unique](https://en.wikipedia.org/wiki/Single_sign-on). Un frais est applicable car cela prend du temps à nos développeurs pour configurer la configuration.

_Que fait cette règle ?_ Par défaut, les utilisateurs qui se connectent avec SSO et les utilisateurs qui se connectent normalement sont traités de la même manière. Si MFA est appliquée pour une organisation, les utilisateurs réguliers et les utilisateurs SSO doivent donc insérer le code MFA pour se connecter et accéder au projet. Si cette option est cochée pour une organisation, les utilisateurs SSO n'ont pas besoin d'utiliser MFA pour accéder au projet. Les utilisateurs réguliers devraient toujours avoir à saisir le code MFA tandis que les utilisateurs SSO pourraient se connecter sans avoir à utiliser le code.

_Qu'est-ce que SSO ?_ [L'authentification unique](https://en.wikipedia.org/wiki/Single_sign-on) permet à l'utilisateur de se connecter une fois et d'accéder aux services sans réentrer les facteurs d'authentification. Avec cette option, vous pouvez faire en sorte que les utilisateurs de votre organisation n'aient pas besoin de configurer MFA. Les utilisateurs d'autres organisations qui font partie de vos projets d'organisation devront toujours avoir MFA activée si l'option ci-dessus est activée.

_Configuration de SSO :_ Il est possible de configurer SSO avec n'importe quel fournisseur SSO car c'est un processus standardisé. Veuillez trouver ci-dessous certains des fournisseurs SSO les plus courants :

_Microsoft Active Directory :_ Pour configurer SSO avec Microsoft Active Directory, une nouvelle application d'entreprise Azure doit être configurée dans l'environnement Azure AD. Généralement, c'est l'administrateur système de l'entité qui effectue cette configuration. Dans l'environnement Azure AD, les champs suivants doivent être remplis avec l'authentification SAML par l'administrateur système : ID d'entité : [https://hub.catenda.com/metadata.xml](https://hub.catenda.com/metadata.xml) Ce fichier XML est disponible au téléchargement, mais généralement seule l'URL doit être collée dans le champ. URL du service client d'assertion (ACS) : [https://hub.catenda.com/sso/saml/v2/attribute](https://hub.catenda.com/sso/saml/v2/attribute) Ce lien doit également être publié dans le champ et n'est pas accessible en l'ouvrant dans un navigateur. Une fois configuré, le fournisseur d'identité émettra une demande POST vers ce point de terminaison. Si ce point de terminaison est appelé à partir d'un navigateur normal (demande GET) ou via une demande POST sans les données correctes, la page ne se chargera pas. URL de connexion [https://hub.catenda.com/signin](https://hub.catenda.com/signin) Ceci est la page de connexion qui redirigera vers le fournisseur d'identité configuré avant d'accorder l'accès à Catenda.

Quand c'est fait, votre administrateur système devra nous recontacter avec l'URL des métadonnées de fédération d'application et le XML des métadonnées de fédération pour la nouvelle application.

**GSuite :** Configurez SSO comme dans [cet article](https://support.google.com/a/answer/12032922?hl=en)

**Utilisateurs de test :** Une fois la configuration SSO configurée, veuillez fournir une liste des utilisateurs de test pour lesquels SSO peut être activé en premier afin que vous puissiez voir comment SSO fonctionnera pour eux. Une fois que les utilisateurs de test ont été testés, le reste des utilisateurs peut être activé.

**Liste noire et liste blanche :** Il est également possible de configurer une liste noire/liste blanche : Par exemple : Tous les utilisateurs sauf : X, Y, etc. devraient être autorisés à se connecter avec SSO ou, Seuls X, Y, etc. devraient être autorisés à se connecter avec SSO Cette information devra être fournie en plus du fichier XML tel que spécifié ci-dessus.

### 5.3 **Désactiver la fonctionnalité de partage public**

Cette option vous permet de désactiver la fonctionnalité de partage public pour tous les projets de votre organisation. Si cette option est activée, il ne sera plus possible de :

- [Activer les URL publiques pour les Signets](https://support.catenda.com/en/articles/6423215-public-bookmarks-short-video).
- [Activer les URL publiques pour les collections de documents](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).
- [Partager les collections de documents par email](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).

## 6. **Domaines**

Vous pouvez demander qu'un domaine soit ajouté à votre organisation. Si un domaine a été enregistré auprès de votre organisation, l'option "ajouter à partir du domaine" apparaîtra sur la page des utilisateurs de votre organisation dans l'[outil d'organisation](http://hub.catenda.com/orgs). Cela vous permettra d'ajouter des utilisateurs de votre organisation à vos projets sans avoir à les inviter via des [invitations par email](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project). Si vous ne trouvez pas un utilisateur de votre organisation, c'est très probablement parce qu'il n'a pas encore créé de compte Catenda et nous ne l'avons pas dans notre système. Les utilisateurs de votre domaine qui n'ont pas encore de compte devront être [invités](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project) de la manière habituelle afin qu'ils puissent rejoindre le projet et créer un compte. Les utilisateurs des domaines qui n'ont pas été ajoutés devront toujours être invités avec l'[invitation par email](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project) habituelle.
