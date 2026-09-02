# Organisationsoptionen

Es ist möglich, die folgenden Optionen für Ihre Organisation festzulegen. Diese Optionen gelten für alle Projekte, die der Organisation gehören.

## 1. **Profil**

Bitte kontaktieren Sie den Support über die schwarze Chat-Schaltfläche neben Ihrem Profilbild oben rechts oder unter [support@catenda.com](mailto:support@catenda.com), wenn Sie den Namen Ihrer Organisation ändern möchten.

## 2. **Plan**

Bitte kontaktieren Sie [sales@catenda.com](mailto:sales@catenda.com) für Fragen zu Ihrem Plan. Ihr Plan bestimmt, wie viele Projekte Sie jederzeit in einer Organisation haben können. Ihr Plan bestimmt auch, wann neue Projekte ablaufen.

## 3. **Standards für neue Projekte**

### 3.1 Option für Dokumentdownload-Titel

Wenn Sie ein einzelnes Dokument herunterladen, ist der Dateiname immer der ursprüngliche Dateiname. Wenn Sie mehrere Dokumente herunterladen, sind die Dateinamen die Namen der Dokumente.

Mit dieser Option können Sie konfigurieren, welchen Dateinamen Sie beim Herunterladen mehrerer Dokumente erhalten. Dies kann in Kombination mit der Namenskonvention und zum Überschreiben von Dokumenten mit demselben Namen statt mit einer anderen Revisionsnummer jedes Mal nützlich sein.

**Beispiel:** Der Name des Projekts ist _testproject._ Zwei Dateien werden mit je zwei Versionen hochgeladen: _test01.pdf_ und _test02.pdf_ Die Namen der Dokumente werden dann geändert in: _changed01.pdf_ und _changed02.pdf_

Standardmäßiges Download-Verhalten: Wenn Sie diese Dokumente einzeln herunterladen, werden sie immer _test01.pdf_ und _test02.pdf_ genannt. Wenn Sie beide Dokumente gleichzeitig herunterladen, werden sie standardmäßig _changed01.pdf_ und _changed02.pdf_ genannt. Dies können Sie mit den folgenden Optionen ändern:

**Optionen:**

**Revisionsdateiname** Beachten Sie, dass dies dem Download einer einzelnen Datei entspricht. Die Namen sind konsistent, wenn Sie diese Option wählen. \<Original file name>.\<Extension> _test01.pdf_ und _test02.pdf_

_Dokumenttitel_ - Standard \<Document name>.\<Extension> _changed01.pdf_ und _changed02.pdf_

**Dokumenttitel mit Revisionsnummer** \<Document name>\<Revision number>.\<Extension> _changed01.pdf #2_ und _changed02.pdf #2_

**Projekttitel mit Dokumenttitel und Revisionsnummer** \<Project name>\<Document name>\<Revision number>.\<Extension> _testproject changed01.pdf #2_ und _testproject changed02.pdf #2_

### 3.2 **Download von infizierten Dokumenten**

Quarantäne-Handling für infizierte Dateien in Projekten im Besitz der Organisation. Wenn ein Dokument als infiziert befunden wird, kann es standardmäßig heruntergeladen werden. Der Benutzer erhält eine Warnung, dass dieses Dokument ein Virus enthält. Eine Option kann pro Organisation festgelegt werden, die dazu führt, dass niemand, nicht einmal Administratoren, infizierte Dokumente herunterladen kann.

**Optionen:** _Bei Download warnen_ - Standard

**Download blockieren**

### 3.3 **Modelle als Dokumente**

Wenn diese Funktion aktiviert ist, haben alle neuen Projekte, die in der Organisation erstellt werden, die Funktion [Modelle als Dokumente](https://support.catenda.com/en/articles/8064548-models-as-documents) aktiviert.

> **Hinweis:** 24. November: Diese Funktion wird für alle neuen Organisationen aktiviert. Wir werden die alte Ansicht etwa ein Jahr lang unterstützen, bevor alle Projekte migriert werden.

### 3.4 **Option für Dokumentupload-Entwurf**

Wenn der Genehmigungsworkflow aktiviert wurde und es in den Dokumenteinstellungen Entwurfsstatus gibt, ist das Kontrollkästchen "Entwurf hochladen" standardmäßig beim Hochladen von Dokumenten aktiviert. Auf Anfrage kann dieses Kontrollkästchen standardmäßig für alle Projekte in einer Organisation deaktiviert werden.

## 4. **Mitglieder**

Benutzer können als Mitglieder oder Inhaber einer Organisation hinzugefügt werden.

### 4.1 **Inhaber**

Inhaber von Organisationen können einen Überblick über die Organisation im [Organisations-Tool](http://hub.catenda.com/orgs) sehen. In diesem Tool können sie: Projekte zu anderen Organisationen verschieben, die sie besitzen (Archive sind oft separate Organisationen). Neue Projekte innerhalb der Organisation erstellen, wenn Ihr Plan das erlaubt. Projekte löschen, die der Organisation gehören. Organisationsmitglieder zu Projekten hinzufügen, ohne sie einzuladen. Benutzer zu Organisationsprojekten einladen, ohne Teil des Projekts zu sein. Es wird empfohlen, dass die Anzahl dieser Organisationsinhalber gering bleibt, da Projekte nicht oft verschoben werden müssen.

### 4.2 **Mitglieder**

Mitglieder von Organisationen können leicht von Organisationsinhabern zu den Projekten der Organisation hinzugefügt werden.

## 5. **Projektinhaber-Regeln**

### 5.1 **Erzwingen, dass alle Benutzer MFA benötigen**

Enterprise-Kunden können die Erzwingung von MFA für Benutzer anfordern, die an ihren Projekten teilnehmen. Mit dieser Option müssen alle Benutzer MFA einrichten, um an Projekten teilzunehmen, die von Ihrer Organisation gehören.

### 5.2 **Interne SSO-Benutzer benötigen kein MFA**

Enterprise-Kunden können anfordern, [Single Sign-On](https://en.wikipedia.org/wiki/Single_sign-on) einzurichten. Es fallen Gebühren an, da es unsere Entwickler Zeit kostet, die Konfiguration einzurichten.

_Was macht diese Regel?_ Standardmäßig werden Benutzer, die sich mit SSO anmelden, und Benutzer, die sich normal anmelden, gleich behandelt. Wenn MFA für eine Organisation erzwungen wird, müssen sowohl normale Benutzer als auch SSO-Benutzer den MFA-Code eingeben, um sich anzumelden und auf das Projekt zuzugreifen. Wenn diese Option für eine Organisation aktiviert ist, müssen SSO-Benutzer MFA nicht verwenden, um auf das Projekt zuzugreifen. Normale Benutzer müssten immer noch den MFA-Code eingeben, während SSO-Benutzer sich ohne Verwendung des Codes anmelden könnten.

_Was ist SSO?_ [Single Sign-On](https://en.wikipedia.org/wiki/Single_sign-on) ermöglicht es dem Benutzer, sich einmal anzumelden und auf Dienste zuzugreifen, ohne Authentifizierungsfaktoren erneut eingeben zu müssen. Mit dieser Option können Sie sicherstellen, dass Benutzer Ihrer Organisation MFA nicht einrichten müssen. Benutzer aus verschiedenen Organisationen, die Teil Ihrer Organisationsprojekte sind, müssen weiterhin MFA aktiviert haben, wenn die obige Option aktiviert ist.

_SSO einrichten:_ Es ist möglich, SSO mit einem beliebigen SSO-Anbieter einzurichten, da es sich um einen standardisierten Prozess handelt. Bitte finden Sie unten einige der häufigsten SSO-Anbieter:

_Microsoft Active Directory:_ Um SSO mit Microsoft Active Directory zu konfigurieren, muss eine neue Azure Enterprise-Anwendung in der Azure AD-Umgebung konfiguriert werden. In der Regel führt der Systemadministrator der Entität diese Konfiguration durch. In der Azure AD-Umgebung müssen die folgenden Felder vom Systemadministrator mit SAML-Authentifizierung ausgefüllt werden: Entity ID: [https://hub.catenda.com/metadata.xml](https://hub.catenda.com/metadata.xml) Diese XML-Datei ist zum Download verfügbar, aber normalerweise sollte nur die URL in das Feld eingefügt werden. Assertion Consumer Service (ACS) URL: [https://hub.catenda.com/sso/saml/v2/attribute](https://hub.catenda.com/sso/saml/v2/attribute) Dieser Link ist auch in das Feld einzufügen und ist nicht zugänglich, wenn Sie ihn in einem Browser öffnen. Nach der Konfiguration gibt der Identitätsanbieter eine POST-Anfrage an diesen Endpunkt aus. Wenn dieser Endpunkt von einem normalen Browser (GET-Anfrage) oder über eine POST-Anfrage ohne die richtigen Daten aufgerufen wird, lädt die Seite nicht. Sign-on URL [https://hub.catenda.com/signin](https://hub.catenda.com/signin) Dies ist die Anmeldeseite, die vor der Gewährung des Zugriffs auf Catenda an den konfigurierten Identitätsanbieter weitergeleitet wird.

Wenn das erledigt ist, muss Ihr Systemadministrator uns die App Federation Metadata URL und Federation Metadata XML für die neue Anwendung zurückgeben.

**GSuite:** Richten Sie SSO wie in [diesem Artikel](https://support.google.com/a/answer/12032922?hl=en) ein

**Testbenutzer:** Nachdem die SSO-Einrichtung konfiguriert wurde, geben Sie bitte eine Liste von Testbenutzern an, für die SSO zunächst aktiviert werden kann, um zu sehen, wie SSO für sie funktioniert. Nachdem die Testbenutzer getestet wurden, können die übrigen Benutzer aktiviert werden.

**Schwarze und Whitelist:** Es ist auch möglich, eine schwarze/Whitelist zu konfigurieren: Zum Beispiel: Alle Benutzer außer: X, Y usw. sollten sich mit SSO anmelden dürfen, oder: Nur X, Y usw. sollten sich mit SSO anmelden dürfen. Diese Informationen müssen zusätzlich zur oben angegebenen XML-Datei bereitgestellt werden.

### 5.3 **Öffentliche Sharing-Funktion deaktivieren**

Mit dieser Option können Sie die öffentliche Sharing-Funktion für alle Projekte in Ihrer Organisation deaktivieren. Wenn diese Option aktiviert ist, ist es nicht mehr möglich:

- [Öffentliche URLs für Lesezeichen aktivieren](https://support.catenda.com/en/articles/6423215-public-bookmarks-short-video).
- [Öffentliche URLs für Dokumentsammlungen aktivieren](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).
- [Dokumentsammlungen per E-Mail teilen](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).

## 6. **Domänen**

Sie können anfordern, dass eine Domäne zu Ihrer Organisation hinzugefügt wird. Wenn eine Domäne bei Ihrer Organisation registriert wurde, wird die Option "Aus Domäne hinzufügen" auf der Benutzerseite Ihrer Organisation im [Organisations-Tool](http://hub.catenda.com/orgs) angezeigt. Dies ermöglicht es Ihnen, Benutzer aus Ihrer Organisation zu Ihren Projekten hinzuzufügen, ohne sie über [E-Mail-Einladungen](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project) einladen zu müssen. Wenn Sie einen Benutzer aus Ihrer Organisation nicht finden, liegt dies höchstwahrscheinlich daran, dass diese Person noch kein Catenda-Konto erstellt hat und wir diese Person nicht in unserem System haben. Benutzer aus Ihrer Domäne, die noch keine Konten haben, müssen auf reguläre Weise [eingeladen](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project) werden, damit sie dem Projekt beitreten und ein Konto erstellen können. Benutzer aus Domänen, die nicht hinzugefügt wurden, müssen immer noch mit der regulären [E-Mail-Einladung](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project) eingeladen werden.
