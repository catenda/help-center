# Recommandation sur le matériel

> Découvrez les spécifications matérielles recommandées et les conseils d'optimisation pour une expérience optimale avec Catenda Hub.

Cet article contient des informations sur la configuration recommandée pour l'utilisation de Catenda Hub. Catenda Hub est accessible via le navigateur et ne doit pas être installé.

Cet article contient des informations sur les sujets suivants :

## 1. Recommandation matérielle :

**(juin 2024)**

Pour les projets réguliers (jusqu'à LOD 300) :

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p></p><p class="intercom-align-center"><b>Processeur</b></p><p></p></td><td><p></p><p class="intercom-align-center"><b>MÉMOIRE VIVE</b></p><p></p></td><td><p></p><p class="intercom-align-center"><b>GPU</b></p><p></p></td></tr><tr><td><p></p><p class="intercom-align-center">Intel Core i5 ou eq.</p><p></p></td><td><p></p><p class="intercom-align-center">8 à 16 Go</p><p></p></td><td><p></p><p class="intercom-align-center">intégré / 4 Go</p><p></p></td></tr></tbody></table></div>

Pour les projets de géométrie dense (LOD 400 et plus) :

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p></p><p class="intercom-align-center"><b>Processeur</b></p><p></p></td><td><p></p><p class="intercom-align-center"><b>MÉMOIRE VIVE (RAM)</b></p><p></p></td><td><p></p><p class="intercom-align-center"><b>GPU</b></p><p></p></td></tr><tr><td><p></p><p class="intercom-align-center">Intel Core i7 ou eq.</p><p></p></td><td><p></p><p class="intercom-align-center">32 GO</p><p></p></td><td><p></p><p class="intercom-align-center">8GB</p><p></p></td></tr></tbody></table></div>

[Définition LOD](https://www.gsa.gov/real-estate/design-and-construction/3d4d-building-information-modeling/bim-software-guidelines/document-guides/level-of-detail)

### 1.1 GPU dédié vs GPU intégré

Assurez-vous d'utiliser le GPU dédié de votre système et non le GPU intégré. Sous Windows 10, vous pouvez vous assurer que vous utilisez le GPU dédié en suivant [ces](https://superuser.com/questions/1439471/how-can-i-force-my-dedicated-gpu-to-handle-all-applications-or-disable-my-integr#:~:text=use%20these%20steps%3A-,Open%20Settings.,-Click%20on%20System) étapes

## 2. optimisation de la visionneuse 3D :

Bien que Catenda Hub soit bien optimisé et puisse faire fonctionner la plupart des modèles, certains utilisateurs voudront peut-être se préparer au mieux pour réussir. Voici donc quelques stratégies qui peuvent être utilisées pour optimiser votre flux de travail dans Catenda Hub :

### 2.1 Beaucoup d'objets :

Bien sûr, charger moins de modèles signifie moins d'objets et donc de meilleures performances

Activer le [rendu incrémental](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings#:~:text=Incremental%20rendering%3A) accélère la rotation autour des modèles avec beaucoup de géométrie car tous les objets ne doivent pas être chargés lors de la rotation.

La dernière étape consiste à [interroger](https://intercom.help/bimsync-arena/en/articles/4854514-queries) la section dans laquelle vous travaillez. Habituellement, lorsque vous découpez une partie du modèle, les objets sont toujours en mémoire et simplement cachés. Avec une requête, ces objets sont complètement supprimés et il sera donc plus facile de travailler avec le modèle. Gardez à l'esprit que vous ne pourrez pas utiliser les bibliothèques de propriétés avec les requêtes car tous les objets ne sont pas chargés.

### 2.2 Nuages de points

Si vous utilisez une [taille de point fixe](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=Adaptive%20(default)%2C%20or-,Fixed%20size,-.%20The%20slider%20below), vous risquez d'obtenir un faible taux d'images par seconde lorsqu'un grand nombre de points a été chargé. Il se peut également que le chargement des points prenne plus de temps lorsque le budget mémoire de votre système est atteint. Les points les plus proches de la caméra sont chargés en premier. Si vous souhaitez charger des points à un endroit spécifique, il est préférable de naviguer jusqu'à cette position, puis d'activer le nuage de points afin qu'il commence à charger les points à cet endroit en premier.

Pour éviter d'atteindre la limite de mémoire et de réduire le nombre d'images par seconde, vous pouvez réduire le [budget de points de](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=with%20your%20PC.-,Point%20Budget%3A,-Using%20the%20viewer) manière à ce que moins de points soient chargés.

## 3. Paramètres du navigateur

### 3.1 Configuration requise :

Catenda Hub est disponible sur différents navigateurs.

Configuration requise pour les navigateurs pouvant être utilisés pour accéder à Catenda Hub :

_Chrome :_ _ _[https](https://support.google.com/chrome/answer/95346?hl=en&co=GENIE.Platform%3DDesktop&sjid=15879972061287151057-EU)://support.google.com/chrome/answer/95346?hl=en&co=GENIE.Platform%3DDesktop&sjid=15879972061287151057-EU _firefox :_ h[ttps://](https://www.mozilla.org/en-US/firefox/114.0.2/system-requirements/)www.mozilla.org/en-US/firefox/114.0.2/system-requirements/ _microsoft Edge :_ Configuration requise pour Windows 11 : h[ttps://](https://www.microsoft.com/en-in/windows/windows-11-specifications)www.microsoft.com/en-in/windows/windows-11-specifications

Safari :

[https://support.apple.com/en-us/112653](https://support.apple.com/en-us/112653)

_Opera :_ h[ttps://](https://www.opera.com/download/requirements)www.opera.com/download/requirements _vivaldi :_ h[ttps://](https://help.vivaldi.com/desktop/install-update/install-the-vivaldi-browser/)help.vivaldi.com/desktop/install-update/install-the-vivaldi-browser/

### 3.2 Accélération matérielle

Veuillez vous assurer que vous utilisez l'accélération matérielle. Les options d'accélération matérielle pour les différents navigateurs sont disponibles ici :

**Chrome :**

<a class="intercom-content-link" target="_blank">chrome://settings/?search=hardware+acceleration</a>
_firefox :_
h[ttps://](https://support.mozilla.org/en-US/kb/performance-settings?as=u&utm_source=inproduct)support.mozilla.org/en-US/kb/performance-settings?as=u&utm\_source=inproduct
_microsoft Edge :_
<a class="intercom-content-link" target="_blank">edge://settings/?search=hardware%20acceleration</a>
_safari :_

[https://support.apple.com/en-us/102894](https://support.apple.com/en-us/102894)

_Opera :_ h[ttps://](https://blogs.opera.com/news/2015/07/advanced-settings-in-opera/)blogs.opera.com/news/2015/07/advanced-settings-in-opera/

_Vivaldi :_ h[ttps://](https://forum.vivaldi.net/topic/1207/hardware-acceleration)forum.vivaldi.net/topic/1207/hardware-acceleration

### 3.3 facteurs externes

Veuillez vérifier si vous avez des extensions de navigateur ou d'autres programmes qui pourraient ralentir votre expérience du Catenda Hub.

**meilleur navigateur selon l'utilisation de la mémoire sur Windows :**

1. Firefox
1. Chrome
1. Microsoft Edge

### 3.4 Cookies

Les données stockées dans les cookies permettent à votre navigateur de savoir si vous êtes connecté et de connaître certaines de vos préférences pour les projets Catenda. Certaines préférences peuvent varier d'un projet à l'autre, tandis que d'autres seront identiques pour tous les projets. Si vous modifiez vos préférences, par exemple en fermant un menu, elles seront conservées dans toutes les fenêtres et tous les onglets du navigateur. Si, par exemple, vous fermez le menu de filtrage dans un onglet, puis actualisez la même page dans un autre onglet, le menu de filtrage sera également fermé dans cet onglet.

De cette manière, le navigateur se souvient également si vous étiez connecté ou non. Si vous vous déconnectez d'un onglet pour vous connecter à un autre compte et que vous actualisez ensuite la page d'un autre onglet, vous vous retrouverez connecté avec l'autre compte qui n'aura peut-être pas accès au projet dans lequel vous étiez.

**Recherche de cookies**

Sur chrome, vous pourrez gérer vos cookies comme suit : Cliquez sur Cookies et données de site

![](https://downloads.intercomcdn.com/i/o/1143829455/e1b8867e01930b24ef529e47/image.png?expires=1781092800&signature=e2930701f16f0bb3a0bf73c281e38f6f67c644391db6ed32ee93ea59a6d53707&req=dSEjFcF8lIVaXPMW3nq%2BgUEUCAtZlI0OymkGwvXwPbIdriySEnhYe5MnX9rH%0AEYoxZWV%2FwN%2FD9WGf%2BN6T8rLpu6U%3D%0A)

Cliquez sur Gérer les données du site sur l'appareil

![](https://downloads.intercomcdn.com/i/o/1143829543/42d74782920e4a35a660e546/image.png?expires=1781092800&signature=772bcce3cf9b467dbc597b9d51e83558d486f87ddb35ea6b96af416fc21e8b5a&req=dSEjFcF8lIRbWvMW3nq%2BgURf0KbK%2BNuvBfcmFwNBFGl1BsOYkzIeKVHfYp9q%0Ax43X05BUHahlsi1ikzCV75TMgJk%3D%0A)

_Autoriser les cookies_ Pour utiliser Catenda Hub, vous devez au moins autoriser le stockage de données pour hub.catenda.com pendant votre session.

![](https://downloads.intercomcdn.com/i/o/1143829607/ca12dcb2003b5cb363d40567/image.png?expires=1781092800&signature=f3a187e05e4ba985f1ae0ec66d8fb2a99a1057a2881e8a657ddac3758f562e70&req=dSEjFcF8lIdfXvMW3nq%2BgckeVuXJSA5nST8uRqQYtlpUuNArxqJhicAjHiaF%0APs4KS9lyB2p5JX1IIKTovtvmSMA%3D%0A)

Si vous choisissez de supprimer les données en fermant toutes les fenêtres, vos données seront réinitialisées chaque fois que vous utiliserez Catenda.

Si vous supprimez vos données à chaque fois que vous fermez toutes les fenêtres, vos préférences seront réinitialisées à chaque fois que vous fermerez toutes les fenêtres de votre navigateur.

_Suppression des cookies_ les données des cookies peuvent être supprimées manuellement en cliquant sur l'icône de la corbeille.

![](https://downloads.intercomcdn.com/i/o/areracg3/1523271853/e56637a54f93758be3b8418f22e9/image.png?expires=1781092800&signature=b0e72ef5f94e2289a511e7d049687661651b7c65dd537083a6cef716234e2298&req=dSUlFct5nIlaWvMW3nq%2BgdNYIPm0MvEz2pbNbsb8f65Ak2B85xaTdfQkj1lr%0AZeFhZedw7WUklevLVmbveQfpFbo%3D%0A)

Il vous sera alors demandé de recharger la page. Après avoir rechargé la page, vous devrez vous reconnecter à Catenda car vous avez supprimé vos informations de connexion.

## 4. Vitesse du réseau

Contrôlez la qualité de votre réseau, de manière à ce que le rapport entre le téléchargement et l'envoi soit d'au moins 1:10

soit d'environ 1:10 ou plus.

![](https://downloads.intercomcdn.com/i/o/748569163/86b6c411513b1d918f971664/5e52d40f-4227-418f-b23b-20fa30a307e2?expires=1781092800&signature=1ba0773f7dc7c9af736408f4089c2adccac66a67a0b7737730ea980132976063&req=cyQvE893nIdcFb4V1XW4gbNVrM1pna2WNERr2HdEoh49FtF8K3i%2F%2BKq6uCKu%0AYfEqJDh3SgD2pd%2FhWLATN81jAg%3D%3D%0A)

(il s'agit d'un exemple et non d'une exigence réelle)

## 5. Proxy et pare-feu :

Les utilisateurs qui accèdent à Catenda Hub derrière un pare-feu, un proxy ou un autre intermédiaire doivent avoir accès aux domaines et aux ports suivants pour que l'application fonctionne correctement.

### 5.1 Domaines :

`(\*` signifie un joker DNS et `.` est un séparateur de niveau de domaine, ne traitez pas les éléments ci-dessous comme des expressions rationnelles).

- Domaines de Catenda :
    - `catenda.com`
    - `\*.catenda.com`
        - `webviewer.catenda.com`
    - `\*.\*.catenda.com`

Nous vous encourageons à utiliser ce nouveau nom de domaine.

Vous ne devriez pas rencontrer de problèmes avec d'autres sous-domaines comme `\*.\*.\*.catenda.com`, mais si c'est le cas, il peut être plus facile de tout autoriser à partir de `catenda.com`

**Domaines maintenus**

Les domaines suivants seront maintenus dans un avenir proche mais ne seront pas référencés dans la littérature technique.

- `bimsync.com`
- `\*.bimsync.com`
- `\*.\*.bimsync.com`

**Services**

Catenda Hub utilise les services suivants :

- `\*.google-analytics.com`
- `\*.googletagmanager.com`
- `\*.intercom.io`
- `\*.intercomcdn.com`
- `\*.sentry.io`

**Plugins**

Si vous n'avez l'intention d'utiliser Catenda Hub qu'à travers l'un de nos plugins, ce sont les seuls domaines que vous devez autoriser à travers votre pare-feu.

- Pour l'authentification des plugins et des intégrations
    - `hub.catenda.com`
    - `api.catenda.com `
    - `bimsync.com`
    - `api.bimsync.com`
- Pour l'utilisation du plugin
    - Plugin Revit
        - `https://revit.plugins.catenda.com`
        - `https://revit.plugins.bimsync.com`
    - Plugin Archicad
        - `https://archicad.plugins.catenda.com`
        - `https://archicad.plugins.bimsync.com`
    - Plugin Navisworks
        - `https://navisworks.plugins.catenda.com`
        - `https://navisworks.plugins.bimsync.com`
    - Plugin Tekla
        - `https://tekla.plugins.catenda.com`
        - `https://tekla.plugins.bimsync.com`
- Pour l'utilisation de l'intégration
    - Connecteur Solibri BCF Live
        - `https://bcf.bimsync.com/`
        - h`ttps://` opencde.bimsync.com/

## 6. Ports :

**80 :** Ce port est optionnel mais recommandé pour une meilleure expérience utilisateur dans le navigateur. Protocole : TCP (uniquement pour hub.catenda.com et [www.hub.catenda.com](http://www.hub.catenda.com) )

Les clients qui tentent d'effectuer une demande sur le port 80 sont redirigés vers un appel chiffré équivalent sur le port 443.

**443 :**

Protocole : TCP + UDP Tout le trafic du Hub Catenda est crypté par TLS sur ce port.

L'UDP est facultatif mais recommandé pour une meilleure expérience utilisateur, car il permet aux navigateurs compatibles et à d'autres clients de profiter des avancées du protocole HTTP, telles que HTTP/3 (anciennement QUIC) que nous sommes en train de déployer sur toute la plateforme.
