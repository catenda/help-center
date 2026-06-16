# Multi-Faktor-Authentifizierung

Die Einstellungen für die Multi-Faktor-Authentifizierung (MFA) finden Sie auf der Authentifizierungsseite, die eine Unterseite der Kontoseite ist.

Die Multi-Faktor-Authentifizierung (MFA) erfordert die Eingabe eines Codes, den Sie über Ihr mobiles Gerät erhalten haben, sowie die Eingabe Ihres Benutzernamens und Passworts, wenn Sie sich bei Catenda Hub anmelden. Wenn eine Organisation MFA verlangt, wird sie auf Organisationsebene angewendet. Alle Projekte, die zu dieser Organisation gehören, benötigen dann MFA, um auf ihre Projekte zuzugreifen. Dadurch werden alle Benutzer gezwungen, MFA zu aktivieren, um auf Projekte dieser Organisation zuzugreifen.

## Aktivieren von MFA

Loggen Sie sich in Catenda Hub ein und gehen Sie auf die Seite Konto:

![](https://downloads.intercomcdn.com/i/o/710942054/f2239e2186f2107afadd66a3/image.png?expires=1781092800&signature=f38bc42351fd302ec7396fa6cf12192e80e28a0d7f3432cf1ef011332c36b874&req=cyEnH818nYRbFb4V1XW4gc7BaZEBKtWdCLphfgCiOK%2Bew%2FThhA88vrm%2FPJq5%0APAs7mDo6nKHLBwYjCUY3Kyp9%2Bg%3D%3D%0A)

1. Klicken Sie auf die Registerkarte Authentifizierung:
1. Blättern Sie nach unten zum Abschnitt für MFA:
1. Klicken Sie auf MFA aktivieren

![](https://downloads.intercomcdn.com/i/o/710944230/ebe37c5fb2379afe1d58d515/image.png?expires=1781092800&signature=bb1b215bf932a3da6fd9efd65031aa089830c4fa92090872b305802d5370aa61&req=cyEnH816n4JfFb4V1XW4gTVsh%2FWNq4RWV4OD%2BiH2LjOrUp6WWcpjxhq9folB%0A%2BuwHJKhvj1SGgt1qEKhqKE8VEQ%3D%3D%0A)

### Authentifizierungs **App**

Sie müssen eine Authentifizierungsanwendung, der Sie vertrauen, auf Ihrem Mobilgerät installieren.

Wir empfehlen den Google Authenticator und den Microsoft Authenticator, aber Sie können theoretisch jede Anwendung verwenden, die die Verbindung von MFA/Zwei-Faktor-Authentifizierung unterstützt.

App-Berechtigungen

Damit Sie den QR-Code mit Ihrer Kamera scannen können, müssen Sie Ihrer Authentifizierungs-App die Berechtigung für Ihre Kamera erteilen.

Wenn Sie die Anwendung installieren, werden Sie möglicherweise gefragt, ob Sie der Kamera nur während der Verwendung der App die Erlaubnis erteilen möchten, jedes Mal fragen oder nicht zulassen. Wenn Sie "jedes Mal fragen" auswählen, werden Sie jedes Mal um Erlaubnis gebeten, wobei Sie "nicht zulassen" wählen können, wodurch die Erlaubnis für die App deaktiviert wird.

Google-Authentifikator

Klicken Sie auf das Plus unten rechts und scannen Sie einen QR-Code.

Hier scannen Sie den QR-Code, den Sie auf der Authentifizierungsseite erhalten.

Alternativ können Sie den Code auch mit Ihrer Kamera scannen und den Einrichtungsschlüssel eingeben, den Sie in der geöffneten URL sehen.

_Microsoft_ Authentifikator

Vergewissern Sie sich, dass Sie sich im Authenticator-Menü am unteren Rand befinden.

![](https://downloads.intercomcdn.com/i/o/825376957/d0ca2f4ff3122f26c2dd335e/image.png?expires=1781092800&signature=be1fcb59fb1bfa4b45e2cd97b6ea4639f51a97ac61ba103a8b19816235d2ee72&req=fCIiFc54lIRYFb4V1XW4gStU4QZFJuspH3Amx6IfbI1PH8Ta9AUUSD4f5PCO%0AAP4KnLWAE5JAwe0UK5S1t71eeA%3D%3D%0A)

> **Note:** **Hinweis**: Vergewissern Sie sich, dass Sie sich nicht im Menü "Verifizierte IDs" befinden, da Sie hier zwar einen QR-Code scannen können, dieser aber nicht funktioniert. Klicken Sie anschließend auf das Plus in der blauen Leiste oben rechts. Wählen Sie Anderes Konto (Google, Facebook, etc.) Wenn Ihre App keine Berechtigung für Ihre Kamera hat, werden Sie möglicherweise nicht dazu aufgefordert, Ihre Kamera freizugeben.

Wenn Ihre App Zugriff auf Ihre Kamera hat, können Sie den QR-Code scannen, den Sie auf der Authentifizierungsseite erhalten.

Wenn Ihre App keinen Zugriff auf Ihre Kamera hat, werden Sie aufgefordert, manuell ein Konto zu erstellen.

![](https://downloads.intercomcdn.com/i/o/1073587443/5a6dda006a38943a4c11fc28/image.png?expires=1781092800&signature=6859b1a2a4081eacf5fe3e3b2cbc8cbc20fe23ba599c13b94523c6aef1a0d697&req=dSAgFcx2moVbWvMW3nq%2BgQ2uGk1EdfhU4hASnzRRD%2FCNPzlrB1T21b5PfCNs%0AoaOKhDzf4%2BW06huquS6IL07Iqqg%3D%0A)

Kontoname: Der Name, den Sie Ihrem Konto gebenGeheimer Schlüssel: Dies ist der Schlüssel, den Sie erhalten hätten, wenn Sie den QR-Code hätten scannen können.

Die URL, die sich beim Scannen des Codes öffnet, kann etwa so aussehen: `otpauth://totp/\<Catenda account email address>?secret=\<Secret key>&issuer=Catenda&algorithm=SHA1&digits=6&period=30`

If you type in the code after "`secret=`" in den geheimen Schlüssel, den Sie in der geöffneten URL sehen, kann der Kontoname beliebig sein.

> **Note:** **Hinweis**: Wenn Sie ein Konto mit dem falschen geheimen Schlüssel erstellen, generiert die App trotzdem einmalige Codes, so dass Catenda den Code möglicherweise nicht akzeptiert, wenn der falsche geheime Schlüssel verwendet wurde.

Nach erfolgreicher Aktivierung von MFA sehen Sie diese Meldung.

![](https://downloads.intercomcdn.com/i/o/710945944/2427619ae9caca4960e1a387/image.png?expires=1781092800&signature=637d0ef63b4155743ee6d632d2567b662b28783b6fcea173963ba6bf19a0f4bf&req=cyEnH817lIVbFb4V1XW4gQAh7zS29CfgBClTPyOHvLzyOrF2cnqmwXqeBNFn%0AvIKMxKQUufVZJ2jjzM9m6U1pww%3D%3D%0A)

Nach der Aktivierung müssen Sie Ihr Mobilgerät bei jeder Anmeldung bei Catenda Hub zur Hand haben.

Die MFA kann wieder deaktiviert werden, indem Sie auf MFA deaktivieren klicken.

## Ändern von **MFA**

Nachdem Sie einen MFA-Code verbunden haben, können Sie den Kontonamen des Codes sicher bearbeiten.

Sie können dies auf die folgenden Arten tun:

Google-Authentifikator

1. Langes Drücken des Codes
1. Klicken Sie auf den Bleistift oben rechts, um den Namen zu ändern.

_Microsoft_ Authentifikator

1. Klicken Sie auf den Code.
1. Klicken Sie oben rechts auf die Schaltfläche "Zahnrad
1. Klicken Sie auf den Bleistift, um den Namen zu ändern

## Übertragende MFA

Es kann immer nur ein Gerät gleichzeitig verwendet werden. Wenn Sie ein neues Gerät verwenden möchten, können Sie die gleiche MFA-App auf dem neuen Gerät verwenden und den Code vom alten Gerät übertragen.

_Google_ Authentifikator

Altes Gerät:

1. Tippen Sie auf das Hamburger-Menü oben rechts
1. Tippen Sie auf Konten exportieren
1. Wählen Sie die Konten aus, die Sie exportieren möchten

Neues Gerät:

1. Tippen Sie auf das Hamburger-Menü oben rechts
1. Tippen Sie auf Konten importieren
1. Tippen Sie auf QR-Code scannen
1. Scannen Sie den QR-Code, der auf dem alten Gerät angezeigt wird, wenn Sie den Exportvorgang durchlaufen haben.

_Microsoft_ Authentifikator

Altes Gerät:

1. Tippen Sie auf das Hamburger-Menü oben rechts
1. Backup einschalten

Neues Gerät:

1. Installieren und öffnen Sie die Microsoft Authenticator-App auf Ihrem neuen Gerät
1. Tippen Sie auf "Wiederherstellung beginnen".

> **Note:** **Hinweis**: Richten Sie keine Konten mit Microsoft Authenticator ein, bevor Sie das Wiederherstellungstool verwendet haben, da es passende Website-Konten überschreibt.

## Deaktivieren von MFA

Sie können MFA deaktivieren, indem Sie auf die oben gezeigte Schaltfläche "Deaktivieren" klicken und dann Ihr Passwort zur Bestätigung eingeben. Nach der Deaktivierung können Sie nicht mehr auf Projekte zugreifen, die MFA erfordern.

Nach der Deaktivierung des Codes auf Catenda Hub verbleibt der Code in der Anwendung, mit der Sie sich verbunden haben. Dieser Code ist nun nutzlos und kann sicher gelöscht werden.

### So löschen Sie den alten Code:

_Google_ Authentifikator

1. Langes Drücken des Codes
1. Klicken Sie auf den Mülleimer oben rechts.

_Microsoft_ Authentifikator

1. Klicken Sie auf den Code.
1. Klicken Sie oben rechts auf die Schaltfläche "Zahnrad
1. Klicken Sie auf Konto entfernen

## MFA auf nicht-mobilen Geräten

Authenticator-Apps sind sicherer als SMS-/E-Mail-Code-Lösungen, da es keine Kommunikation gibt, die nach der ursprünglichen Konfiguration zwischen den beiden Systemen abgefangen werden kann.

Es ist zwar besser, eine App auf einer mobilen Anwendung zu verwenden (siehe Hinweis unten), aber es ist auch möglich, MFA-Codes auf anderen Systemen als nur mobilen Geräten zu erhalten.

Die empfohlene Desktop-Anwendung für diesen Zweck ist Authy.

Diese Art von Anwendungen verwendet das gleiche TOTP-Protokoll wie die App auf Ihrem mobilen Gerät und sollte genauso sicher sein.

> **Note:** **Hinweis**: Desktop-Anwendungen können weniger sicher sein, da sie leichter zu hacken sind oder man sich Zugang zu ihnen verschaffen kann. Das liegt daran, dass Desktop-Systeme oft, wenn auch nicht immer, mit dem lokalen Netzwerk verbunden sind, das infiziert sein könnte. Mobile Geräte, die nicht immer mit dem Netzwerk verbunden sind, können daher schwerer zu knacken sein.

## Wer kann die MFH bei Projekten durchsetzen?

Unternehmenskunden können die Aktivierung einer Organisationsoption beantragen, die dafür sorgt, dass alle Benutzer, die Teil ihrer Projekte sind, MFA verwenden müssen, um das Projekt zu betreten.

Um MFA für die Projekte Ihrer Organisation zu aktivieren, kontaktieren Sie den Catenda-Support. Wenn MFA für die Projekte einer Organisation erforderlich ist, wird diese Meldung angezeigt, wenn Sie versuchen, das Projekt zu öffnen.

![](https://downloads.intercomcdn.com/i/o/710237963/cc33c301cac2faaeaf8abb7e/image.png?expires=1781092800&signature=0a241c1b7d754dac6ac7f3fbfb908a97d6aad26a98db0773434988edd6c61515&req=cyEnFMp5lIdcFb4V1XW4geDBTPE7FEI38r7z7CIHG0OMPqmboH9ClY59uD%2F2%0APKhzmnNJ76NXpaOhL%2BVeRBzIhw%3D%3D%0A)
