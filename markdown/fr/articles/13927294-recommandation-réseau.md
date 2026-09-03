# Recommandation réseau

La configuration du réseau auquel le système est connecté peut affecter les performances que vous expérimentez sur Catenda.

## 1. **Vitesse réseau**

Contrôlez la qualité de votre réseau, de sorte que le rapport entre le téléchargement et le chargement soit environ 1:10 ou supérieur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4f22q5zf/01-network-speed.png)

(ce test réseau est un exemple, pas une exigence réelle)

## 2. **Proxies et pare-feu :**

Les utilisateurs accédant à Catenda Hub derrière un pare-feu, un proxy ou un autre intermédiaire ont besoin d'accès aux domaines et ports suivants pour que l'application fonctionne correctement.

### 2.1 **Domaines :**

(`*` signifie wildcard DNS et `.` est un séparateur de niveau de domaine, ne traitez pas le contenu ci-dessous comme des expressions régulières).

- Domaines Catenda :
  - `catenda.com`
  - `*.catenda.com`
    - `webviewer.catenda.com`
      Ce sous-domaine doit être autorisé dans le pare-feu pour afficher l'aperçu des Documents sur la page d'aperçu des documents.
  - `*.*.catenda.com`

Nous vous encourageons à utiliser ce nouveau nom de domaine. Vous ne devriez pas rencontrer de problèmes avec des sous-domaines supplémentaires comme `*.*.*.catenda.com`, mais si c'est le cas, il pourrait être plus facile d'autoriser tout depuis `catenda.com`

**Domaines maintenus** Les domaines suivants seront maintenus dans un avenir prévisible mais ne seront pas référencés dans la littérature technique.

- `bimsync.com`
- `*.bimsync.com`
- `*.*.bimsync.com`

**Services** Catenda Hub utilise les services suivants :

- `*.google-analytics.com`
- `*.googletagmanager.com`
- `*.intercom.io`
- `*.intercomcdn.com`
- `*.sentry.io`

**Plugins** Si vous n'envisagez d'utiliser Catenda Hub que par l'intermédiaire de l'un de nos plugins, ce sont les seuls domaines que vous devez autoriser à travers votre pare-feu.

- Pour l'authentification des plugins et des intégrations
  - `hub.catenda.com`
  - `api.catenda.com`
  - `bimsync.com`
  - `api.bimsync.com`
- Pour l'utilisation du plugin
  - Plugin Revit
    - [`https://revit.plugins.catenda.com`](https://revit.plugins.catenda.com)
    - [`https://revit.plugins.bimsync.com`](https://revit.plugins.bimsync.com)
  - Plugin Archicad
    - [`https://archicad.plugins.catenda.com`](https://archicad.plugins.catenda.com)
    - [`https://archicad.plugins.bimsync.com`](https://archicad.plugins.bimsync.com)
  - Plugin Navisworks
    - [`https://navisworks.plugins.catenda.com`](https://navisworks.plugins.catenda.com)
    - [`https://navisworks.plugins.bimsync.com`](https://navisworks.plugins.bimsync.com)
  - Plugin Tekla
    - [`https://tekla.plugins.catenda.com`](https://tekla.plugins.catenda.com)
    - [`https://tekla.plugins.bimsync.com`](https://tekla.plugins.bimsync.com)
- Pour l'utilisation de plugins et d'intégrations qui utilisent les sujets listés [ici](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)
  - [`https://bcf.bimsync.com/`](https://bcf.bimsync.com/)
  - [`https://opencde.bimsync.com/`](https://opencde.bimsync.com/)

## 3. **Configuration des ports**

### 3.1 **Port 80**

Ce port est facultatif mais recommandé pour une meilleure expérience utilisateur in-browser. Protocole : TCP (Pour hub.catenda.com et [www.hub.catenda.com](http://www.hub.catenda.com) uniquement) Les clients qui tentent de faire une demande sur le port 80 sont redirigés pour effectuer l'appel chiffré équivalent sur le port 443.

### 3.2 **Port 443**

Protocole : TCP + UDP Tout le trafic Catenda Hub est chiffré en TLS sur ce port. UDP est facultatif mais recommandé pour une meilleure expérience utilisateur car il permet aux navigateurs compatibles et aux autres clients de tirer parti des avancées du protocole HTTP, telles que HTTP/3 (anciennement QUIC) que nous déployons sur l'ensemble de la plateforme.
