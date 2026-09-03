# Aktivierung der Catenda SharePoint-App

> **Hinweis:** Die Installationsdatei für das Plugin finden Sie in [diesem Artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Die Catenda SharePoint-Anwendung kann von einem Systemadministrator für eine SharePoint-Umgebung aktiviert und dann von einem Websitebesitzer zu einer Website hinzugefügt werden. Mit dieser App können SharePoint-Benutzer Dokumente in Catenda zusammen mit anderen Mitgliedern des Bauprojekts anzeigen, verwalten und daran zusammenarbeiten.

Um die App für Ihre Umgebung zu aktivieren, finden Sie den entsprechenden Eintrag hier: [Microsoft AppSource](https://appsource.microsoft.com/en-us/marketplace/apps?search=Catenda&page=1), der etwa so aussehen kann:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/01-intro.png)

Nach dem Klicken auf "Jetzt abrufen" werden Sie aufgefordert, sich in Ihr SharePoint-Konto anzumelden, falls Sie noch nicht angemeldet sind. Sie werden dann zum SharePoint Store-Eintrag weitergeleitet. Der SharePoint Store kann auch durch Klicken auf Ihr Profil oben rechts in SharePoint und dann durch Klicken auf "App hinzufügen" gefunden werden

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/02-intro.png)

Im SharePoint Store können Sie auch nach der Catenda SharePoint-Anwendung suchen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/03-intro.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/\_layouts/15/appStore.aspx/sharePointStore?entry=ClassicAppCatalog&sorting=7&search=catenda**

Der SharePoint Store-Eintrag kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/04-intro.png)

**https://\<Tenant>.sharepoint.com/\_layouts/15/appStore.aspx/appDetail/WA200005981**

## 1. **Normale SharePoint-Benutzer**

Normale SharePoint-Benutzer können die Aktivierung der Catenda SharePoint-App anfordern, indem sie auf die Schaltfläche "Zur App-Website hinzufügen" klicken. Sie können sehen, ob Ihre Anfrage auf der Seite "Meine Anfragen" im SharePoint Store genehmigt wurde. Wenn Sie ein Administrator sind, können Sie die Anfrage aus dem App-Katalog genehmigen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/05-regular-sharepoint-users.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/SitePages/Home.aspx**

## 2. **SharePoint-Administratoren**

Als Administrator in einer SharePoint-Umgebung können Sie die App durch Klicken auf "Zur App-Website hinzufügen" aktivieren. Hier werden Sie aufgefordert, den Datenzugriff zu bestätigen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/06-sharepoint-administrators.png)

### 2.1 **Datenzugriff bestätigen**

Die App, die Sie gleich aktivieren werden, hat Zugriff auf Daten unter Verwendung der Identität der Person, die sie nutzt. Aktivieren Sie diese App nur, wenn Sie dem Entwickler oder Herausgeber vertrauen. Die App benötigt diese Berechtigung, um zu wissen, welche Dateien des Benutzers veröffentlicht werden sollen, wenn dieser sich entschließt, sie zu veröffentlichen. Der Endpunkt ist: [https://sharepoint.plugins.catenda.com/1.0.0.0/](https://sharepoint.plugins.catenda.com/1.0.0.0/)

### 2.2 **API-Zugriff**

Wenn der API-Zugriff zuvor nicht aktiviert wurde, muss er aktiviert werden, damit die Anwendung funktioniert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/07-api-access.png)

Um den API-Zugriff zu genehmigen, rufen Sie die Seite "API-Zugriff" in Ihrem Admin Center auf: https://\<Tenant>.sharepoint.com/\_layouts/15/online/AdminHome.aspx#/webApiPermissionManagement

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/08-api-access.png)

Der API-Zugriff ist erforderlich, damit SharePoint-Administratoren ihr Catenda-Konto verbinden müssen, um die Veröffentlichung von Dokumenten zu aktivieren. Benutzer werden auch aufgefordert, sich mit ihrem Catenda-Konto anzumelden, wenn sie versuchen, etwas in Catenda zu veröffentlichen, da jeder Benutzer unterschiedliche Berechtigungen in Catenda haben kann.

Ohne API-Zugriff kann die Catenda SharePoint-Anwendung aktiviert werden, wobei sowohl die Listenaktion als auch das Webpart sichtbar sind, aber nicht nutzbar, da keine Daten ausgetauscht werden können, ohne Ihr Catenda-Konto zu verbinden. _Erforderlicher Zugriff:_ Rolle "Globaler Administrator" oder Rolle "Anwendungsadministrator" in Microsoft 365.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/09-api-access.png)

**Zugriff genehmigen** Wählen Sie Catenda aus der Liste der ausstehenden Anfragen aus und klicken Sie oben auf "Genehmigen". Damit die Catenda-Anwendung funktioniert, benötigt sie die Berechtigung: Zugriff

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/10-api-access.png)

**Zugriff entfernen** Wählen Sie Catenda auf der Seite "API-Zugriff" aus und klicken Sie oben auf "Entfernen".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/11-api-access.png)

Klicken Sie im nächsten Menü auf "Entfernen"

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/12-api-access.png)

Obwohl die Catenda-Anwendung möglicherweise aktiviert ist, können Benutzer sich nach dem Entfernen dieses Zugriffs nicht mit Catenda verbinden.

## 3. **App-Verfügbarkeit**

### 3.1 **Diese App nur aktivieren**

Diese Option aktiviert die App für die SharePoint-Umgebung, die es Websitebesitzern in Ihrer Umgebung ermöglicht, die App von der Seite "Meine Apps" hinzuzufügen. Die App tut nichts, bis sie zu einer Website hinzugefügt wird. Obwohl diese Option großartig ist, können Sie damit bessere Kontrolle darüber erhalten, von welchen Websites Benutzer Dokumente in Catenda veröffentlichen können. Dies kann jedoch verwirrend für Benutzer sein, wenn einige Websites die Veröffentlichungsoption haben, andere aber nicht. Für noch mehr Kontrolle können Sie den [Websitesammlungs-App-Katalog](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog) aktivieren, der es Ihnen ermöglicht, zu wählen, welche Apps Websitebesitzer installieren können. Mit dieser Option ist die App auch nicht standardmäßig auf neuen Websites aktiviert, was bedeutet, dass es mehr Arbeit erfordert, eine neue Website zu konfigurieren, wenn sie erstellt wird.

### 3.2 **Diese App aktivieren und zu allen Websites hinzufügen**

Mit dieser Option wird die App automatisch zu allen Websites hinzugefügt. Der einzige visuelle Unterschied, den der Benutzer sieht, wenn die App zu seiner Website hinzugefügt wird, ist, dass er den Listenbefehl in seiner Liste und im Hamburger-Menü beim Auswählen eines Dokuments hat. Webparts und vollständige Seiten müssen später hinzugefügt werden. Dies kann auch später auf der Seite "Apps verwalten" erfolgen.

### 3.3 **Zu Teams hinzufügen**

Mit dieser Option wird die App auch zu Teams hinzugefügt. Dies ermöglicht es Benutzern, die Teams-Registerkarte zu sehen. Dies kann auch später auf der Seite "Apps verwalten" erfolgen.

## 4. **Apps verwalten**

Nach der Aktivierung der App können SharePoint-Administratoren Ihre App im Bereich "Apps verwalten" sehen: https://\<Tenant>.sharepoint.com/sites/appcatalog/AppCatalog/Forms/AllItems.aspx

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/13-manage-apps.png)

Nach Auswahl der App kann sie zu verschiedenen Teilen von SharePoint hinzugefügt werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/14-manage-apps.png)

### 4.1 **Zu allen Websites hinzufügen:**

Dies fügt die App zu allen Websites und allen neu erstellten Websites hinzu. Wenn die App aktiviert ist, können Websitebesitzer die App auch einzeln zu einer Website hinzufügen. Wenn Sie nicht mehr die App zu neuen Websites hinzufügen möchten, können Sie dies beenden, indem Sie auf "Nicht mehr zu neuen Websites hinzufügen" klicken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/15-add-to-all-sites.png)

Die von der App bereitgestellte Funktionalität bleibt auf allen Websites verfügbar, zu denen sie hinzugefügt wurde, und der Websitebesitzer kann diese App weiterhin zu seinen Websites hinzufügen.

### 4.2 **Zu Teams hinzufügen:**

Dies aktiviert die Teams-Registerkarte für die App.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/16-add-to-teams.png)

Damit die App zu Teams hinzugefügt werden kann, muss sie zunächst zu allen Websites hinzugefügt werden.

## 5. **Weitere Informationen**

Weitere Informationen zur Funktionsweise dieser Anwendung nach der Installation finden Sie [hier](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application). Weitere Informationen zur Nützlichkeit dieser Anwendung finden Sie [hier](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq).
