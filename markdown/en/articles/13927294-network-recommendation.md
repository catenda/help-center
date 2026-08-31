# Network recommendation

The configuration of the network that the system is connected to can affect ther performance experienced on Catenda.

## 1. **Network speed**

Control the quality of your network, so that the ratio between Download and Upload is around 1:10 or above.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4f22q5zf/01-network-speed.png)

(this network test is an example, not actual requirement)

## 2. **Proxies and firewall:**

Users accessing Catenda Hub behind a firewall, proxy or other intermediary need access to the following domains and ports for the application to function properly.

### 2.1 **Domains:**

(`*` means DNS wildcard and `.` is a domain level separator, don't treat the below as regexes).

- Catenda domains:
    - `catenda.com`
    - `*.catenda.com`
        - `webviewer.catenda.com`
This subdomain is required to be permitted in the firewall to view the preview of documents on the document preview page.
    - `*.*.catenda.com`

We encourage you to use this new domain name. You should not run into problems with more sub-domains like `*.*.*.catenda.com` but if you do it might be easier to allow everything from `catenda.com`

**Maintained domains** The following domains will be maintained in the foreseeable future but not referenced in technical literature.

- `bimsync.com`
- `*.bimsync.com`
- `*.*.bimsync.com`

**Services** Catenda Hub uses the following services:

- `*.google-analytics.com`
- `*.googletagmanager.com`
- `*.intercom.io`
- `*.intercomcdn.com`
- `*.sentry.io`

**Plugins** If you only intend to use Catenda Hub through one of our plugins you these are the only domains you need to allow through your firewall.

- For authentication of plugins and integrations
    - `hub.catenda.com`
    - `api.catenda.com `
    - `bimsync.com`
    - `api.bimsync.com`
- For use of plugin
    - Revit plugin
        - [`https://revit.plugins.catenda.com`](https://revit.plugins.catenda.com)
        - [`https://revit.plugins.bimsync.com`](https://revit.plugins.bimsync.com)
    - Archicad plugin
        - [`https://archicad.plugins.catenda.com`](https://archicad.plugins.catenda.com)
        - [`https://archicad.plugins.bimsync.com`](https://archicad.plugins.bimsync.com)
    - Navisworks plugin
        - [`https://navisworks.plugins.catenda.com`](https://navisworks.plugins.catenda.com)
        - [`https://navisworks.plugins.bimsync.com`](https://navisworks.plugins.bimsync.com)
    - Tekla plugin
        - [`https://tekla.plugins.catenda.com`](https://tekla.plugins.catenda.com)
        - [`https://tekla.plugins.bimsync.com`](https://tekla.plugins.bimsync.com)
- For use of plugins and integrations that use topics listed [here](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)
    - [`https://bcf.bimsync.com/`](https://bcf.bimsync.com/)
    - [`https://opencde.bimsync.com/`](https://opencde.bimsync.com/)

## 3. **Port configuration**

### 3.1 **Port 80**

This port is optional but recommended for best in-browser user experience. Protocol: TCP (For hub.catenda.com and [www.hub.catenda.com](http://www.hub.catenda.com) only) Clients that attempt to make a request on 80 are redirected to make the equivalent encrypted call on port 443.

### 3.2 **Port 443**

Protocol: TCP + UDP All Catenda Hub traffic is TLS-encrypted on this port. UDP is optional but recommended for best user experience as it allows compatible browsers and other clients to take advantage of advances in the HTTP protocol, such as HTTP/3 (formerly QUIC) which we are rolling out across the platform.
