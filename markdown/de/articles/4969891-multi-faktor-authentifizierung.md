# Multi-Faktor-Authentifizierung

> Beschreibt, wie Sie MFA auf Ihrem Konto einrichten

Die Einstellungen für **Multi-Faktor-Authentifizierung** (MFA) finden Sie auf der [Authentifizierungsseite](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f), die eine Unterseite der [Kontoseite](https://support.catenda.com/en/articles/6880968-account-page) ist.

Die **Multi-Faktor-Authentifizierung** (MFA) erfordert die Eingabe eines Codes, den Sie über Ihr Mobilgerät erhalten, sowie Ihren Benutzernamen und Ihr Passwort beim Anmelden bei Catenda Hub. Wenn eine Organisation MFA erfordert, wird sie auf Organisationsebene angewendet. Alle Projekte, die zu dieser Organisation gehören, erfordern dann MFA, um auf ihre Projekte zuzugreifen. Dies erzwingt, dass alle Benutzer MFA aktivieren müssen, um auf Projekte zuzugreifen, die zu dieser Organisation gehören.

## 1. **MFA aktivieren**

Melden Sie sich bei Catenda Hub an und gehen Sie zur **[Konto](https://hub.catenda.com/account/profile)**-Seite:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/01-enabling-mfa.png)

1. Klicken Sie auf die Registerkarte **[Authentifizierung](https://hub.catenda.com/account/authentication)**:
2. Scrollen Sie nach unten zum Abschnitt für MFA:
3. Klicken Sie auf **MFA aktivieren**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/02-enabling-mfa.png)

### 1.1 **Authentifizierungs-App**

Installieren Sie zunächst eine Anwendung auf einem Mobilgerät, das das TOTP-Protokoll (Time-based one-time password) unterstützt. Installieren Sie eine vertrauenswürdige Authentifizierungs-App auf einem Mobilgerät, um zu beginnen. Die Zeit, die eine Authentifizierungsanwendung schon existiert, und die Gerichtsbarkeit, in der sich das Unternehmen, dem sie gehört, ansässig ist, sind oft gute Anhaltspunkte. Hier sind einige Beispiele von empfehlenswerten Authentifizierungsanwendungen:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 139px;"><h3 id="h_b56161ee38"><b>Sicherheitsgesetze für Auth-Apps</b></h3></td><td style="background-color: #e3e7fa80; width: 101px;"><h3 id="h_49bc31efe9">Unternehmen</h3></td><td style="background-color: #e3e7fa80; width: 119px;"><h3 id="h_46b679c81c">Gerichtsbarkeit</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_7699fa4ab6">Geltende Sicherheitsgesetze</h3></td></tr><tr><td style="width: 139px;"><h3 id="h_ae65255403">Aegis</h3></td><td style="width: 101px;"><p>Beem</p></td><td style="width: 119px;"><p>Niederlande<br/>(Dordrecht)</p></td><td><p>DSGVO<br/>9-Augen-Abkommen</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_42b556ff02">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Roland Moers</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Deutschland</p></td><td style="background-color: #e8e8e880;"><p>DSGVO<br/>Bundesdatenschutzgesetz - BDSG <br/>14-Augen-Abkommen</p></td></tr><tr><td style="width: 139px;"><h3 id="h_5e0c03d260">Authenticator</h3></td><td style="width: 101px;"><p>Google</p></td><td style="width: 119px;"><p>Vereinigte Staaten<br/>(Kalifornien)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_918c12706e">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Microsoft</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Vereinigte Staaten<br/>(Washington)</p></td><td style="background-color: #e8e8e880;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="width: 139px;"><h3 id="h_b3a055f26d">Ente Auth</h3></td><td style="width: 101px;"><p>Ente</p></td><td style="width: 119px;"><p>Vereinigte Staaten (Delaware)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_63d03979d2">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Internet Initiative Japan</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Japan</p></td><td style="background-color: #e8e8e880;"><p>Gesetz zum Schutz personenbezogener Daten (APPI)</p></td></tr><tr><td style="width: 139px;"><h3 id="h_848afb2dfa">HENNGE Lock</h3></td><td style="width: 101px;"><p>HENNGE K.K.</p></td><td style="width: 119px;"><p>Japan</p></td><td><p>Gesetz zum Schutz personenbezogener Daten (APPI)</p></td></tr></tbody></table></div>

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 138px;"><h3 id="h_5e28bb0eb3"><b>Funktionalität der Auth-App</b></h3></td><td style="background-color: #e3e7fa80; width: 88px;"><h3 id="h_6ed7d3e230">Veröffentlichungsdatum</h3></td><td style="background-color: #e3e7fa80; width: 180px;"><h3 id="h_f652151c66">Betriebssystem</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_824368384e">Code-Extraktion</h3></td></tr><tr><td style="width: 138px;"><h3 id="h_218c61c8b2">Aegis</h3></td><td style="width: 88px;"><p>2019</p></td><td style="width: 180px;"><p>Android</p></td><td><p>In vollständige Textdatei oder verschlüsselte Datei exportieren. JSON / TXT / QR</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_0274ada2cb">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2020</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS</p></td><td style="background-color: #e8e8e880;"><p>In proprietäre Datei exportieren / Geheimnis anzeigen</p></td></tr><tr><td style="width: 138px;"><h3 id="h_cc8ae8a27d">Authenticator</h3></td><td style="width: 88px;"><p>2010</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>Auf andere Google Authenticator-App mit Google-Konto übertragen</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_6d595cbd69">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS<br/>Android</p></td><td style="background-color: #e8e8e880;"><p>Auf andere Microsoft Authenticator-App mit Microsoft-Konto übertragen.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_9cbe3f20d2">Ente Auth</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>JSON / TXT</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_425ee9cdba">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS - 8.1+<br/>Android - 4.0+</p></td><td style="background-color: #e8e8e880;"><p>QR-Code-Export pro Code.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_10c8930b4e">HENNGE Lock</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS - Neueste 2 Hauptversionen <br/>Android - Neueste 4 benannte Versionen</p></td><td><p>Keine</p></td></tr></tbody></table></div>

Theoretisch kann jede Anwendung verwendet werden, die MFA / Zwei-Faktor-Authentifizierung über das TOTP-Protokoll unterstützt. Es gibt auch Desktop-Anwendungen, diese werden jedoch nicht empfohlen, da Desktop-Anwendungen oft immer mit demselben Netzwerk verbunden sind, auf dem sich oft mehrere Geräte befinden, was das Risiko erhöht, dass ein Angreifer Zugriff auf den Code erhält.

**App-Berechtigungen** Um den QR-Code mit der Kamera des Geräts scannen zu können. Die Authentifizierungs-App benötigt Kameraberechtigung, um den Code scannen zu können. Die Anwendung kann Sie auffordern, die Berechtigung zur Verwendung der Gerätekamera zu erteilen. Berechtigungsoptionen können folgende sein: "Nur während der App-Nutzung" - Die App hat Berechtigung während der Nutzung. "Jedes Mal fragen" - Die Berechtigung muss bei jeder Verwendung der App erteilt werden. "Nicht zulassen" - Die Berechtigung wird der App nicht erteilt oder widerrufen.

**Google Authenticator** Klicken Sie auf das Pluszeichen unten rechts und scannen Sie einen QR-Code. Hier scannen Sie den QR-Code, den die [Authentifizierungsseite](https://hub.catenda.com/account/authentication) bereitstellt. Alternativ können Sie Ihre Kamera verwenden, um den Code zu scannen, und den Setup-Schlüssel eingeben, den Sie in der geöffneten URL sehen.

**Microsoft Authenticator** Stellen Sie sicher, dass Sie sich im Authenticator-Menü unten befinden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/03-authentication-app.png)

> **Hinweis:** Stellen Sie sicher, dass Sie sich nicht im Menü "Verified IDs" befinden, da Sie hier zwar einen QR-Code scannen können, dies jedoch nicht funktioniert.

Klicken Sie als Nächstes auf das Pluszeichen in der blauen Leiste oben rechts. Wählen Sie Anderes Konto (Google, Facebook, usw.) Wenn Ihre App keine Berechtigung für Ihre Kamera hat, werden Sie möglicherweise aufgefordert, die Berechtigung für Ihre Kamera zu erteilen.

Wenn Ihre App Zugriff auf Ihre Kamera hat, können Sie den QR-Code scannen, den die [Authentifizierungsseite](https://hub.catenda.com/account/authentication) bereitstellt.

Wenn Ihre App keinen Zugriff auf Ihre Kamera hat, werden Sie aufgefordert, manuell ein Konto zu erstellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/04-authentication-app.png)

Kontoname: Der Name, den Sie Ihrem Konto geben Geheimer Schlüssel: Dies ist der Schlüssel, den Sie erhalten hätten, wenn Sie den QR-Code hätten scannen können. Sie können Ihre Kamera-App verwenden, um den Code zu scannen. Die URL, die beim Scannen des Codes geöffnet wird, kann etwa so aussehen: `otpauth://totp/<Catenda-Konto-E-Mail-Adresse>?secret=<Geheimer Schlüssel>&issuer=Catenda&algorithm=SHA1&digits=6&period=30` Wenn Sie den Code nach "`secret=`" in den geheimen Schlüssel eingeben, den Sie in der geöffneten URL sehen, kann der Kontoname alles sein.

> **Hinweis:** Wenn Sie ein Konto mit dem falschen geheimen Schlüssel erstellen, generiert die App trotzdem Einmalcodes. Catenda akzeptiert den Code jedoch möglicherweise nicht, wenn der falsche geheime Schlüssel verwendet wurde.

### 1.2 **Erfolg oder Fehler**

**Erfolg** Nach erfolgreichem Aktivieren von MFA wird die folgende Meldung angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/05-success-or-fail.png)

Nach der Aktivierung müssen Sie jedes Mal, wenn Sie sich bei Catenda Hub anmelden, Ihr Mobilgerät zur Hand haben. Die MFA kann durch Klicken auf "MFA deaktivieren" wieder deaktiviert werden.

**Falscher Code** Wenn Sie nicht den richtigen Code eingegeben haben, erhalten Sie die Meldung "Falscher Code".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/06-success-or-fail.png)

> **Hinweis:** Wenn Sie den QR-Code gescannt haben, können Sie versuchen, den Code innerhalb des vorgesehenen Zeitraums einzugeben, während dieses Menü offen ist. Wenn Sie dieses Menü schließen, müssen Sie den Code, der in Ihrer Authentifizierungs-App generiert wird, entfernen und den QR-Code erneut scannen, um eine neue Code-Pairing einzurichten.

## 2. **MFA ändern**

Nach dem Verbinden eines MFA-Codes können Sie den Kontonamen des Codes sicher bearbeiten. Dies können Sie auf folgende Weise tun:

**Google Authenticator**

1. Halten Sie den Code lange gedrückt
2. Klicken Sie auf das Stiftsymbol oben rechts, um den Namen zu ändern.

**Microsoft Authenticator**

1. Klicken Sie auf den Code.
2. Klicken Sie auf das Zahnradsymbol oben rechts
3. Klicken Sie auf das Stiftsymbol, um den Namen zu ändern

## 3. **MFA übertragen**

**Deaktivieren und neu aktivieren** Es ist jeweils nur möglich, eine MFA-App-Code-Pairing zu verwenden. Wenn Sie zu einer anderen Code-Pairing wechseln möchten, vielleicht weil Ihre aktuelle kompromittiert wurde, folgen Sie diesen Schritten: Sie sollten diese Methode auch verwenden, wenn Sie die App, die Sie für MFA verwenden, ändern möchten.

1. Deaktivieren Sie Ihre MFA auf der [Authentifizierungsseite](https://hub.catenda.com/account/authentication)
2. Bereiten Sie die App vor, die Sie verwenden möchten, um Ihre MFA erneut zu verbinden
3. Generieren Sie eine neue Code-Pairing, indem Sie den QR-Code wie im [Aktivierungsabschnitt](#enabling-mfa) scannen

> **Hinweis:** Seien Sie vorsichtig mit dieser Methode, da Ihr Konto während der Deaktivierung vorübergehend anfällig ist und Sie während dieser Zeit nicht auf Projekte zugreifen können, die MFA erfordern.

**Übertragung durch Sicherung** Wenn Sie ein neues Gerät verwenden möchten, ohne dass Ihr Code vorübergehend deaktiviert wird, können Sie eine andere Installation derselben MFA-App verwenden und den Code von der alten Installation zur neuen Installation übertragen.

**Google Authenticator** Altes Gerät:

1. Tippen Sie auf das Hamburger-Menü oben rechts
2. Tippen Sie auf "Konten exportieren"
3. Wählen Sie die Konten aus, die Sie exportieren möchten

Neues Gerät:

1. Tippen Sie auf das Hamburger-Menü oben rechts
2. Tippen Sie auf "Konten importieren"
3. Tippen Sie auf "QR-Code scannen"
4. Scannen Sie den QR-Code, der auf dem alten Gerät angezeigt wird, wenn Sie den Exportvorgang durchgeführt haben.

**Microsoft Authenticator** Altes Gerät:

1. Tippen Sie auf das Hamburger-Menü oben rechts
2. Sicherung aktivieren

Neues Gerät:

1. Installieren und öffnen Sie die Microsoft Authenticator-App auf Ihrem neuen Gerät
2. Tippen Sie auf "Wiederherstellung starten."

> **Hinweis 1:** Richten Sie keine Konten mit Microsoft Authenticator ein, bis Sie das Wiederherstellungstool verwendet haben, da dies übereinstimmende Site-Konten überschreibt.

> **Hinweis 2:** Diese Methode erfordert, dass Sie Ihre MFA-Codes sichern, was bedeutet, dass sie im Cloud-Service Ihres App-Anbieters gespeichert werden. Verwenden Sie diese Methode nur, wenn Sie dem Sicherungsdienst Ihres App-Anbieters vertrauen. Falls nicht, ist es besser, die Deaktivierung und Wiederaktivierung zu verwenden.

## 4. **MFA deaktivieren**

Sie können MFA deaktivieren, indem Sie auf die oben gezeigte Schaltfläche "Deaktivieren" klicken und Ihr Passwort eingeben, um zu bestätigen. Nach dem Deaktivieren können Sie nicht mehr auf Projekte zugreifen, die MFA erfordern.

Nach dem Deaktivieren des Codes in Catenda Hub bleibt der Code in der Anwendung, mit der Sie eine Verbindung hergestellt haben. Dieser Code ist jetzt nutzlos und kann sicher gelöscht werden.

### 4.1 **So löschen Sie den alten Code:**

**Google Authenticator**

1. Halten Sie den Code lange gedrückt
2. Klicken Sie auf das Papierkorbsymbol oben rechts.

**Microsoft Authenticator**

1. Klicken Sie auf den Code.
2. Klicken Sie auf das Zahnradsymbol oben rechts
3. Klicken Sie auf "Konto entfernen"

## 5. **MFA auf Nicht-Mobilgeräten**

Authentifizierungs-Apps sind sicherer als SMS/E-Mail-Code-Lösungen, da es nach der ursprünglichen Konfiguration keine Kommunikation gibt, die zwischen den beiden Systemen abgefangen werden kann. Obwohl es besser ist, eine App auf einem Mobilgerät zu verwenden, siehe Hinweis unten, ist es möglich, MFA-Codes auf anderen Systemen als nur Mobilgeräten zu erhalten. Die empfohlene Desktop-Anwendung hierfür ist [Authy](https://authy.com/). Funktionell verwenden diese Arten von Anwendungen dasselbe TOTP-Protokoll wie die App auf Ihrem Mobilgerät und sollten genauso sicher sein.

> **Warnung:** Desktop-Apps können weniger sicher sein, da sie leichter gehackt oder darauf zugegriffen werden können. Dies liegt daran, dass Desktop-Systeme oft immer mit dem lokalen Netzwerk verbunden sind, das infiziert sein könnte. Mobilgeräte, die nicht immer mit dem Netzwerk verbunden sind, können daher schwerer zu knacken sein.

## 6. **Wer kann MFA auf Projekten durchsetzen?**

Enterprise-Kunden können eine [Organisationsoption](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) anfordern, die aktiviert werden kann, damit alle Benutzer, die zu ihren Projekten gehören, MFA verwenden müssen, um auf das Projekt zuzugreifen. Um MFA auf den Projekten Ihrer Organisation zu aktivieren, kontaktieren Sie den Catenda-Support. Wenn MFA auf den Projekten einer Organisation erforderlich ist, wird beim Öffnen des Projekts die folgende Meldung angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/07-who-can-enforce-mfa-on-projects.png)
