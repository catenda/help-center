# Multi-Faktor-Authentifizierung

> Beschreibt, wie Sie MFA auf Ihrem Konto einrichten

Sie finden die **Multi-Faktor-Authentifizierung** (MFA)-Einstellungen auf der [Authentifizierungsseite](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f), die eine Unterseite der [Kontoseite](https://support.catenda.com/en/articles/6880968-account-page) ist.

**Multi-Faktor-Authentifizierung** (MFA) erfordert bei der Anmeldung bei Catenda Hub die Eingabe eines Codes, den Sie über Ihr Mobilgerät sowie Ihren Benutzernamen und Ihr Passwort erhalten. Wenn eine Organisation MFA erfordert, wird sie auf Organisationsebene angewendet. Alle Projekte, die dieser Organisation angehören, erfordern dann MFA für den Zugriff. Dies zwingt alle Benutzer, MFA zu aktivieren, um auf Projekte der Organisation zuzugreifen.

## 1. **MFA aktivieren**

Melden Sie sich bei Catenda Hub an und gehen Sie zur Seite **[Konto](https://hub.catenda.com/account/profile)**:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/01-enabling-mfa.png)

1. Klicken Sie auf die Registerkarte **[Authentifizierung](https://hub.catenda.com/account/authentication)**:
1. Scrollen Sie nach unten zum Bereich für MFA:
1. Klicken Sie auf **MFA aktivieren**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/02-enabling-mfa.png)

### 1.1 **Authentifizierungs-App**

Installieren Sie zunächst eine Anwendung auf einem Mobilgerät, die das TOTP-Protokoll (Time-based one-time password) unterstützt. Installieren Sie eine vertrauenswürdige Authentifizierungs-App auf einem Mobilgerät, um zu beginnen. Die Dauer, seit der eine Authentifizierungs-Anwendung existiert, und die Rechtsprechung, in der sich das Unternehmen befindet, das ihr gehört, sind oft gute Kriterien. Hier sind einige Beispiele empfohlener Authentifizierungs-Anwendungen:

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 139px; padding: 8px;"><h3 id="h_b56161ee38"><b>Sicherheitsgesetze für Auth-Apps</b></h3></td><td style="background-color: #e3e7fa80; width: 101px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_49bc31efe9">Unternehmen</h3></td><td style="background-color: #e3e7fa80; width: 119px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_46b679c81c">Gerichtsbarkeit</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_7699fa4ab6">Geltende Sicherheitsgesetze</h3></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_ae65255403">Aegis</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Beem</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Niederlande<br/>(Dordrecht)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>DSGVO<br/>9-Augen-Abkommen</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_42b556ff02">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Roland Moers</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Deutschland</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>DSGVO<br/>Bundesdatenschutzgesetz - BDSG <br/>14-Augen-Abkommen</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_5e0c03d260">Authentifizierung</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Google</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vereinigte Staaten<br/>(Kalifornien)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_918c12706e">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Microsoft</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vereinigte Staaten<br/>(Washington)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_b3a055f26d">Ente Auth</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ente</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vereinigte Staaten (Delaware)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_63d03979d2">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Internet Initiative Japan</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Japan</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Act on the Protection of Personal Information (APPI)</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_848afb2dfa">HENNGE Lock</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>HENNGE K.K.</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Japan</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Act on the Protection of Personal Information (APPI)</p></td></tr></tbody></table></div>

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 138px; padding: 8px;"><h3 id="h_5e28bb0eb3"><b>Funktionalität der Auth-App</b></h3></td><td style="background-color: #e3e7fa80; width: 88px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_6ed7d3e230">Veröffentlichungsdatum</h3></td><td style="background-color: #e3e7fa80; width: 180px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_f652151c66">Betriebssystem</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_824368384e">Code-Extraktion</h3></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_218c61c8b2">Aegis</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2019</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>In Klartext oder verschlüsselte Datei exportieren. JSON / TXT / QR</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_0274ada2cb">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>In proprietäre Datei exportieren / Geheimnis anzeigen</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_cc8ae8a27d">Authentifizierung</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2010</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Auf andere Google Authenticator-App mit Google-Konto übertragen</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_6d595cbd69">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Auf andere Microsoft Authenticator-App mit Microsoft-Konto übertragen.</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_9cbe3f20d2">Ente Auth</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>JSON / TXT</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_425ee9cdba">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS - 8.1+<br/>Android - 4.0+</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>QR-Code-Export pro Code.</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_10c8930b4e">HENNGE Lock</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS - Neueste 2 Hauptversionen <br/>Android - neueste 4 benannte Versionen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Keine</p></td></tr></tbody></table></div>

Theoretisch kann jede Anwendung verwendet werden, die MFA / Zwei-Faktor-Authentifizierung über das TOTP-Protokoll unterstützt. Es gibt sogar Desktop-Anwendungen, aber diese werden nicht empfohlen, da Desktop-Anwendungen oft immer mit demselben Netzwerk verbunden sind, in dem sich oft mehrere Geräte befinden, was das Risiko erhöht, dass ein böser Akteur Zugriff auf den Code erhält.

**App-Berechtigungen** Um den QR-Code mit der Kamera des Geräts scannen zu können, benötigt die Authentifizierungs-App Kameraberechtigung, um den Code zu scannen. Die Anwendung kann Sie möglicherweise auffordern, die Berechtigung zur Verwendung der Gerätekamera zu erteilen. Berechtigungsoptionen können Folgendes umfassen: "Nur während der App-Nutzung" - Die App hat Berechtigung während der Nutzung. "Jedes Mal fragen" - Die Berechtigung muss bei jeder Nutzung der App erteilt werden. "Nicht erlauben" - Die Berechtigung wird der App nicht erteilt oder widerrufen.

**Google Authenticator** Klicken Sie auf das Plus unten rechts und scannen Sie einen QR-Code. Hier scannen Sie den QR-Code, den die [Authentifizierungsseite](https://hub.catenda.com/account/authentication) bereitstellt. Alternativ können Sie Ihre Kamera zum Scannen des Codes verwenden und den Setup-Schlüssel eingeben, den Sie in der geöffneten URL sehen.

**Microsoft Authenticator** Stellen Sie sicher, dass Sie sich im Authenticator-Menü am unteren Rand befinden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/03-authentication-app.png)

> **Hinweis:** Stellen Sie sicher, dass Sie sich nicht im Menü Verified IDs befinden, da Sie hier einen QR-Code scannen können, dies aber nicht funktioniert.

Klicken Sie als Nächstes auf das Plus in der blauen Leiste oben rechts. Wählen Sie Anderes Konto (Google, Facebook, usw.) Wenn Ihre App keine Kameraberechtigung hat, werden Sie möglicherweise aufgefordert, der Kamera Zugriff zu gewähren.

Wenn Ihre App auf Ihre Kamera zugreifen kann, können Sie den QR-Code scannen, den die [Authentifizierungsseite](https://hub.catenda.com/account/authentication) bereitstellt.

Wenn Ihre App keinen Zugriff auf Ihre Kamera hat, werden Sie aufgefordert, manuell ein Konto zu erstellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/04-authentication-app.png)

Kontoname: Der Name, den Sie Ihrem Konto geben. Geheimer Schlüssel: Dies ist der Schlüssel, den Sie erhalten hätten, wenn Sie den QR-Code hätten scannen können. Sie können Ihre Kamera-App zum Scannen des Codes verwenden. Die URL, die beim Scannen des Codes geöffnet wird, kann folgendermaßen aussehen: `otpauth://totp/<Catenda-Konto-E-Mail-Adresse>?secret=<Geheimer Schlüssel>&issuer=Catenda&algorithm=SHA1&digits=6&period=30` Wenn Sie den Code nach "`secret=`" in den geheimen Schlüssel eingeben, den Sie in der geöffneten URL sehen, kann der Kontoname beliebig sein.

> **Hinweis:** Wenn Sie ein Konto mit dem falschen geheimen Schlüssel erstellen, generiert die App trotzdem Einmalcodes, aber Catenda akzeptiert den Code möglicherweise nicht, wenn der falsche geheime Schlüssel verwendet wurde.

### 1.2 **Erfolg oder Fehler**

**Erfolg** Nach erfolgreichem Aktivieren von MFA wird diese Meldung angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/05-success-or-fail.png)

Nach der Aktivierung müssen Sie bei jeder Anmeldung bei Catenda Hub Ihr Mobilgerät zur Hand haben. Die MFA kann durch Klicken auf MFA deaktivieren deaktiviert werden.

**Falscher Code** Wenn Sie den richtigen Code nicht eingegeben haben, wird die Meldung falscher Code angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/06-success-or-fail.png)

> **Hinweis:** Wenn Sie den QR-Code gescannt haben, können Sie versuchen, den Code innerhalb des für diesen Code vorgesehenen Zeitraums einzugeben, während Sie dieses Menü offen haben. Wenn Sie dieses Menü schließen, müssen Sie den Code entfernen, der in Ihrer Authenticator-App generiert wird, und den QR-Code erneut scannen, um eine neue Code-Kopplung einzurichten.

## 2. **MFA ändern**

Nach dem Verbinden eines MFA-Codes können Sie den Kontonamen des Codes sicher bearbeiten. Sie können dies auf folgende Weise tun:

**Google Authenticator**

1. Halten Sie den Code lange gedrückt
1. Klicken Sie auf den Stift oben rechts, um den Namen zu ändern.

**Microsoft Authenticator**

1. Klicken Sie auf den Code.
1. Klicken Sie oben rechts auf die Schaltfläche mit dem Zahnrad
1. Klicken Sie auf den Stift, um den Namen zu ändern

## 3. **MFA übertragen**

**Deaktivieren und Reaktivieren** Es ist nur möglich, eine MFA-App-Code-Kopplung gleichzeitig zu verwenden. Wenn Sie zu einer anderen Code-Kopplung wechseln möchten, möglicherweise weil Ihre aktuelle kompromittiert wurde, führen Sie diese Schritte aus: Sie sollten diese Methode auch verwenden, wenn Sie die App ändern möchten, die Sie für MFA verwenden.

1. Deaktivieren Sie Ihre MFA auf der [Authentifizierungsseite](https://hub.catenda.com/account/authentication)
1. Bereiten Sie die App vor, die Sie verwenden möchten, um Ihre MFA erneut zu verbinden
1. Generieren Sie ein neues Code-Paar durch Scannen des QR-Codes wie im [Aktivierungsbereich](#h_9e13fd06f5)

> **Hinweis:** Seien Sie vorsichtig mit dieser Methode, da Ihr Konto während der Deaktivierung vorübergehend anfällig ist und Sie während dieser Zeit nicht auf Projekte zugreifen können, für die MFA erforderlich ist.

**Übertragung durch Sicherung** Wenn Sie ein neues Gerät verwenden möchten, ohne dass Ihr Code vorübergehend deaktiviert wird, können Sie eine andere Installation derselben MFA-App verwenden und den Code von der alten Installation zur neuen Installation übertragen.

**Google Authenticator** Altes Gerät:

1. Tippen Sie oben rechts auf das Hamburger-Menü
1. Tippen Sie auf Konten exportieren
1. Wählen Sie die Konten aus, die Sie exportieren möchten

Neues Gerät:

1. Tippen Sie oben rechts auf das Hamburger-Menü
1. Tippen Sie auf Konten importieren
1. Tippen Sie auf QR-Code scannen
1. Scannen Sie den QR-Code, der auf dem alten Gerät angezeigt wird, wenn Sie den Exportvorgang durchlaufen haben.

**Microsoft Authenticator** Altes Gerät:

1. Tippen Sie oben rechts auf das Hamburger-Menü
1. Sicherung aktivieren

Neues Gerät:

1. Installieren und öffnen Sie die Microsoft Authenticator-App auf Ihrem neuen Gerät
1. Tippen Sie auf "Wiederherstellung starten."

> **Hinweis 1:** Richten Sie keine Konten mit Microsoft Authenticator ein, bis Sie das Wiederherstellungstool verwendet haben, da es übereinstimmende Site-Konten überschreibt.

> **Hinweis 2:** Diese Methode erfordert, dass Sie Ihre MFA-Codes sichern, was bedeutet, dass sie im Cloud-Service Ihres App-Anbieters gespeichert sind. Verwenden Sie diese Methode nur, wenn Sie dem Sicherungsdienst Ihres App-Anbieters vertrauen. Wenn nicht, ist es besser, zu deaktivieren und zu reaktivieren.

## 4. **MFA deaktivieren**

Sie können MFA deaktivieren, indem Sie auf die oben angezeigte Schaltfläche "Deaktivieren" klicken und dann Ihr Passwort eingeben, um dies zu bestätigen. Nach der Deaktivierung können Sie nicht mehr auf Projekte zugreifen, für die MFA erforderlich ist.

Nach der Deaktivierung des Codes bei Catenda Hub bleibt der Code in der Anwendung, mit der Sie sich verbunden haben. Dieser Code ist jetzt nutzlos und kann sicher gelöscht werden.

### 4.1 **So löschen Sie den alten Code:**

**Google Authenticator**

1. Halten Sie den Code lange gedrückt
1. Klicken Sie oben rechts auf die Löschtaste.

**Microsoft Authenticator**

1. Klicken Sie auf den Code.
1. Klicken Sie oben rechts auf die Schaltfläche mit dem Zahnrad
1. Klicken Sie auf Konto entfernen

## 5. **MFA auf Nicht-Mobilgeräten**

Authentifizierungs-Apps sind sicherer als SMS/E-Mail-Codelösungen, da nach der ursprünglichen Konfiguration keine Kommunikation zwischen den beiden Systemen abgefangen werden kann. Obwohl es besser ist, eine App auf einem Mobilgerät zu verwenden, siehe Hinweis unten, ist es möglich, MFA-Codes auf anderen Systemen als nur Mobilgeräten zu erhalten. Die empfohlene Desktop-Anwendung dafür ist [Authy](https://authy.com/). Funktionell verwenden diese Arten von Anwendungen das gleiche TOTP-Protokoll wie die App auf Ihrem Mobilgerät und sollten genauso sicher sein.

> **Warnung:** Desktop-Apps können weniger sicher sein, da sie möglicherweise leichter gehackt oder zugegriffen werden können. Dies liegt daran, dass Desktop-Systeme oft, wenn nicht immer, mit dem lokalen Netzwerk verbunden sind, das möglicherweise infiziert ist. Mobilgeräte, die nicht immer mit dem Netzwerk verbunden sind, können daher schwerer zu hacken sein.

## 6. **Wer kann MFA auf Projekten erzwingen?**

Enterprise-Kunden können anfordern, dass eine [Organisationsoption](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) aktiviert wird, wodurch alle Benutzer, die Teil ihrer Projekte sind, MFA verwenden müssen, um auf das Projekt zuzugreifen. Um MFA auf den Projekten Ihrer Organisation zu aktivieren, wenden Sie sich an den Catenda-Support. Wenn MFA für die Projekte einer Organisation erforderlich ist, wird diese Meldung angezeigt, wenn Sie versuchen, das Projekt zu öffnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/07-who-can-enforce-mfa-on-projects.png)
