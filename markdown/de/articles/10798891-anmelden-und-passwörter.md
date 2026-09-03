# Anmelden und Passwörter

Es gibt mehrere Orte auf Catenda, an denen Sie aufgefordert werden, ein Passwort einzugeben. Dieser Artikel beschreibt die verschiedenen Herausforderungen, die Benutzer beim Eingeben ihrer Kontoinformationen erfahren können.

## 1. **Anmelden**

Auf der [Anmeldungsseite](https://support.catenda.com/en/articles/7891486-sign-in-page) werden Sie aufgefordert, Ihr Passwort einzugeben. Dieselbe Anmeldungsseite wird sowohl beim Anmelden über den Browser als auch beim Anmelden verwendet, um Ihrem Konto über die API Zugriff zu gewähren, wie Sie es bei vielen unserer Plugins tun. Während dieses Prozesses können folgende Herausforderungen auftreten:

### 1.1 **Benutzername oder Passwort falsch**

Bitte stellen Sie sicher, dass Sie die richtige Kombination aus Benutzername und Passwort eingeben. Ihr Benutzername ist immer die E-Mail-Adresse, die mit Ihrem Konto verbunden ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/01-wrong-username-or-password.png)

Wenn Sie sich nicht sicher sind, ob Sie erfolgreich ein Konto erstellt haben, registrieren Sie sich bitte erneut unter hub.catenda.com/signup und versuchen Sie, ein Konto zu erstellen, indem Sie auf den Link in der Kontenerstellungs-E-Mail klicken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/02-wrong-username-or-password.png)

Wenn ein Konto unter Ihrer E-Mail-Adresse vorhanden ist, wird eine Warnung angezeigt, die bestätigt, dass Ihr Konto vorhanden ist.

### 1.2 **Zu viele Anmeldeversuche**

Wenn Sie zu viele Male einen falschen Benutzernamen oder ein falsches Passwort eingeben, müssen Sie entweder eine Weile warten, bis Sie es erneut versuchen können, oder zu [https://hub.catenda.com/forgot-password](https://hub.catenda.com/forgot-password) gehen, um Ihr Passwort zurückzusetzen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/03-too-many-login-requests.png)

## 2. **Passwortbestätigung**

Wenn eine Änderung an Ihren Passwortinformationen vorliegt, werden Sie aufgefordert, Ihr Passwort einmal einzugeben und dann noch einmal als Bestätigung. Während dieses Prozesses können folgende Herausforderungen auftreten:

### 2.1 **Passwortanforderung**

Bitte stellen Sie sicher, dass Ihr Passwort

- mindestens 12 Zeichen lang ist

und mindestens eines der folgenden Elemente enthält:

- ein Großbuchstabe
- ein Kleinbuchstabe
- ein numerisches Zeichen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/04-password-requirement.png)

### 2.2 **Passwort vergessen**

Wenn Sie sich nicht anmelden können, können Sie ein neues Passwort anfordern, indem Sie zu [https://hub.catenda.com/forgot-password](https://hub.catenda.com/forgot-password) gehen

### 2.3 **Passwörter sind nicht gleich**

Wenn Sie Ihr neues Passwort zum zweiten Mal eingeben, um es zu bestätigen, stellen Sie bitte sicher, dass Sie dasselbe Passwort eingeben, das Sie gerade eingegeben haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/05-passwords-are-not-equal.png)

### 2.4 **Altes Passwort ungültig**

Wenn Sie sich anmelden können, können Sie zur [Seite für die Kontoauthentifizierung](https://support.catenda.com/en/articles/6880968-account-page) gehen, um Ihr Passwort zurückzusetzen. Dort werden Sie zunächst nach Ihrem alten Passwort gefragt. Dies ist das Passwort, das Sie zum Anmelden bei Ihrem Konto verwendet haben. Wenn Sie nicht das richtige Passwort eingeben, sehen Sie die folgende Meldung:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/06-old-password-not-valid.png)

### 2.5 **Neues Passwort ist identisch**

Wenn Sie Ihr Passwort ändern, stellen Sie bitte sicher, dass Sie ein neues Passwort eingeben, das nicht identisch mit Ihrem vorherigen Passwort ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/07-new-password-is-the-same.png)

### 2.6 500-Fehler bei Verwendung von SSO

Wenn Sie einen 500-Fehler nach der Anmeldung mit SSO erhalten, kann die von Ihrem Identitätsanbieter bereitgestellte E-Mail-Adresse von der auf Ihrem Catenda-Benutzerkonto registrierten E-Mail-Adresse abweichen. Da kein übereinstimmender Benutzer gefunden werden kann, schlägt die Anmeldung mit einem 500-Fehler fehl. Bitte wenden Sie sich an den IT-Administrator Ihrer Organisation, um zu überprüfen, welche E-Mail-Adresse über SSO gesendet wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/08-500-error-when-using-sso.png)
