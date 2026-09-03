# Filterung auf der Benachrichtigungsseite

Sowohl in Ihren [Benachrichtigungseinstellungen](https://support.catenda.com/en/articles/8272435-notification-settings) als auch in Ihren [projektspezifischen Benachrichtigungseinstellungen](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings) können Sie konfigurieren, welche Benachrichtigungen Sie erhalten möchten.

In welcher Situation eine Benachrichtigung für die verschiedenen Einstellungen gesendet wird, wird in diesem Artikel erläutert. Nachdem die Benachrichtigung gesendet wurde, kann sie auf der [Seite mit Kontobenachrichtigungen](https://support.catenda.com/en/articles/7439223-account-notifications-page) und der [Seite mit Projektbenachrichtigungen](https://support.catenda.com/en/articles/4670295-project-notifications-page) durch Öffnen des Filtermenüs auf der linken Seite gefunden werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/810mbm4a/01-intro.png)

## 1. **Benachrichtigungsverlauf**

Benachrichtigungen werden an ein Mitglied gesendet, sobald es einem Projekt beigetreten ist. Der Verlauf der Benachrichtigungen in einem Projekt geht daher auf den Zeitpunkt zurück, an dem dem Projekt beigetreten wurde. Mitglieder, die länger Teil des Projekts waren, können möglicherweise vergangene Ereignisse erfassen, die neue Mitglieder nicht haben.

## 2. **Filter**

Klicken Sie auf die Filterschaltfläche oben links, um ein Panel auf der linken Seite anzuzeigen. Wenn ein Filter angewendet wird, ändert sich die im Browser sichtbare URL entsprechend. In diesem Artikel werden Filter wie folgt angezeigt:

### 2.1 **_Filtername im Menü_ - `Filtername in URL=Filteroption in URL`**

**Standardfilter** Der Standardfilter ist anfangs nicht in der URL sichtbar. Wenn die Seite zum ersten Mal aufgerufen wird, wird der folgende Filter angewendet.

### 2.2 _Vor einem Monat_ - `dateFrom=last-month`

### 2.3 **Aktuellen Filter speichern und freigeben**

Gehen Sie zur URL einer gefilterten Seite, um diese Seite mit dem angewendeten Filter zu laden. Die angewendeten Filter können oben im Filtermenü gespeichert werden. Klicken Sie [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link), um mehr darüber zu erfahren, wie Sie Filter speichern und freigeben

### 2.4 **Leere Filter ausblenden**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über die Begrenzung der Filterergebnisse zu erfahren.

## 3. **Datumsfilter**

Mit dem Datumsfilter können Sie einen Zeitraum auswählen, für den Benachrichtigungen gesendet wurden.

### 3.1 **Vor einer Woche** - `dateFrom=last-week`

Benachrichtigungen der letzten Woche.

### 3.2 **Vor einem Monat** - `dateFrom=last-month`

Wenn Sie zur Seite mit Kontobenachrichtigungen navigieren, wird sie standardmäßig nach Benachrichtigungen des letzten Monats gefiltert.

### 3.3 **Vor einem Jahr** - `dateFrom=last-year`

Benachrichtigungen des letzten Jahres.

### 3.4 **Datum auswählen** - `date-from=<Epoch Unix Timestamp>&date-to=<Epoch Unix Timestamp>`

Lesen Sie [diesen](https://support.catenda.com/en/articles/6511685-date-filter) Artikel, um zu erfahren, wie Sie auf der Seite einfach Daten auswählen können.

### 3.5 **Alle Benachrichtigungen**

Um alle Benachrichtigungen anzuzeigen, die Sie je erhalten haben, entfernen Sie den dateFrom-Filter aus der URL.

## 4. **Typ**

Das Typmenü enthält alle filterbaren Benachrichtigungstypen.

Benachrichtigungen sind in die folgenden Typen unterteilt:

## 5. **Alle** - `type=all`

Alle Benachrichtigungen werden standardmäßig sowohl im Browser als auch per E-Mail gesendet. Wenn Sie zu einer Benachrichtigungsseite gehen, wird sie standardmäßig nach Benachrichtigungen des letzten Monats gefiltert. Wenn Sie den dateFrom-Filter aus der URL entfernen und den Filter type=all verwenden, können Sie alle Benachrichtigungen sehen, die Sie je erhalten haben.

## 6. **Modelle** - `type=models`

_Neues Modell -_ `type=new-model` Die Benachrichtigung zeigt den Namen des erstellten Modells an.

**Das Klicken auf eine Benachrichtigung führt Sie zu:** Modellübersichtsseite des Projekts, in dem das Modell erstellt wird.

**Benachrichtigungsoption:** Ein neues Modell wird erstellt

### 6.1 **Gesendet, auch wenn alle Kontrollkästchen in den Einstellungen deaktiviert sind**

_Einchecken fehlgeschlagen_ - `type=checkin-failed` Wenn das Format Ihrer IFC-Datei von unserem System nicht erkannt wird

_Import fehlgeschlagen_ - `type=import-failed` Kann vorkommen, wenn Ihre Verbindung während des Hochladens unterbrochen wurde.

_Import abgeschlossen_ - `type=import-completed` Wenn ein Modell die Verarbeitung beendet hat

**Benachrichtigungsoption:** Eine neue Version wird importiert

_Export erfolgreich_ - `type=export-completed` Wenn Ihr Modellexport erfolgreich gezippt wurde und zum Download bereit ist.

**Benachrichtigungsoption:** Ein neuer Export wird erstellt

## 7. **Themen** - `type=issues`

### 7.1 **Neues Thema** - `type=new-issue`

Dies ist die einzige Benachrichtigung, die Sie über ein Thema erhalten, wenn Sie das Thema nicht [verfolgen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e). Beauftragte, Anforderer und Mitglieder, die in Themen erwähnt werden, verfolgen das Thema automatisch und erhalten die folgenden Benachrichtigungen.

**Benachrichtigungsoption:** Ein neues Thema wird erstellt

### 7.2 **Neuer Kommentar** - `type=new-comment`

Wenn Sie weder der Beauftragte noch der Anforderer des Themas sind, aber das Thema [verfolgen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e), erhalten Sie diese Benachrichtigung.

Dies kann vorkommen, wenn Sie zuvor [beauftragt](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) waren, [angefordert](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [erwähnt](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) oder [manuell verfolgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) das Thema. Wenn Sie keine zukünftigen Benachrichtigungen zu diesem Thema erhalten möchten, können Sie das Thema in seinem [rechten Informationsfeld](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) nicht mehr verfolgen. _Benachrichtigungsoption: mir zugewiesen_ Ein Thema wird Ihnen zugewiesen

**Benachrichtigungsoption: von mir angefordert** Ein Thema wird von Ihnen angefordert

**Benachrichtigungsoption: von mir verfolgt** Ein Thema wird von Ihnen verfolgt

### 7.3 **Mir zugewiesen** - `type=issue-assigned`

**Benachrichtigungsoption:** Ein Thema wird mir zugewiesen

### 7.4 **Team zugewiesen** - `type=issue-team-assigned`

Wenn ein Team einem Thema zugewiesen wird

**Benachrichtigungsoption:** Ein Thema wird mir zugewiesen

### 7.5 Mich erwähnt - `type=issue-mentioned`

**Benachrichtigungsoptionen:** Ein Thema erwähnt mich oder eines meiner Teams

### 7.6 **Team erwähnt** - `type=issue-team-mentioned `

**Benachrichtigungsoptionen:** Ein Thema erwähnt mich oder eines meiner Teams

### 7.7 **Status aktualisiert** - `type=status-updated`

Wenn Sie weder der Beauftragte noch der Anforderer des Themas sind, aber das Thema [verfolgen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e), erhalten Sie diese Benachrichtigung.

Dies kann vorkommen, wenn Sie zuvor [beauftragt](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) waren, [angefordert](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [erwähnt](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) oder [manuell verfolgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) das Thema. Wenn Sie keine zukünftigen Benachrichtigungen zu diesem Thema erhalten möchten, können Sie das Thema in seinem [rechten Informationsfeld](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) nicht mehr verfolgen. _Benachrichtigungsoption: mir zugewiesen_ Ein Status wird in einem Thema aktualisiert, das Ihnen zugewiesen ist

**Benachrichtigungsoption: von mir angefordert** Ein Status wird in einem Thema aktualisiert, das von Ihnen angefordert wurde

**Benachrichtigungsoption: von mir verfolgt** Ein Status wird in einem Thema aktualisiert, das von Ihnen verfolgt wird

### 7.8 **Typ aktualisiert** - `type=type-updated`

Wenn Sie weder der Beauftragte noch der Anforderer des Themas sind, aber das Thema [verfolgen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e), erhalten Sie diese Benachrichtigung.

Dies kann vorkommen, wenn Sie zuvor [beauftragt](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) waren, [angefordert](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [erwähnt](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) oder [manuell verfolgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) das Thema. Wenn Sie keine zukünftigen Benachrichtigungen zu diesem Thema erhalten möchten, können Sie das Thema in seinem [rechten Informationsfeld](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) nicht mehr verfolgen. _Benachrichtigungsoptionen:_

Mir zugewiesen - Ein Typ wird in einem Thema aktualisiert, das Ihnen zugewiesen ist

Von mir angefordert - Ein Typ wird in einem Thema aktualisiert, das von Ihnen angefordert wurde

Von mir verfolgt - Ein Typ wird in einem Thema aktualisiert, das von Ihnen verfolgt wird

### 7.9 **Gesendet, auch wenn alle Kontrollkästchen in den Einstellungen deaktiviert sind**

### 7.10 **Verschieben erfolgreich** - `type=issues-move-success`

Zeigt die Anzahl der Themen an, die verschoben wurden, und auf welches Themenboard sie verschoben wurden.

### 7.11 **Verschieben fehlgeschlagen** - `type=issues-move-failed`

Zeigt die Anzahl der Themen an, die nicht verschoben werden konnten, und auf welches Themenboard sie nicht verschoben werden konnten.

### 7.12 **Import fehlgeschlagen** - `type=issues-import-failed`

Zeigt an, welche Art von Themenimport nicht importiert wurde und auf welches Themenboard der Import fehlgeschlagen ist. _Mögliche Themenimporttypen:_ BCF

### 7.13 **Import abgeschlossen** - `type=issues-import-success`

Zeigt an, welche Art von Themenimport erfolgreich importiert wurde und auf welches Themenboard es importiert wurde. _Mögliche Themenimporttypen:_ BCF

### 7.14 **Export fehlgeschlagen** - `type=issues-export-failed`

Zeigt an, welche Art von Themenexport fehlgeschlagen ist und von welchem Themenboard der Export fehlgeschlagen ist. _Mögliche Themenexporttypen:_ BCF 2.0, BCF 2.1, BCF 2.0, PDF, Excel

### 7.15 **Export erfolgreich** - `type=issues-export-success`

Zeigt an, welche Art von Themenexport erfolgreich importiert wurde und von welchem Themenboard es exportiert wurde. _Mögliche Themenexporttypen:_ BCF 2.0, BCF 2.1, BCF 2.0, PDF, Excel

## 8. **Dokumente** - `type=documents`

### 8.1 **Dokument hinzugefügt** - `type=document-created`

_Benachrichtigungsoption:_ Ein Dokument oder ein Ordner wird erstellt

### 8.2 **Neue Dokumentversion** - `type=document-revision-uploaded`

_Benachrichtigungsoption:_ Eine neue Dokumentversion wird hochgeladen

### 8.3 **Virus erkannt** - `type=document-file-infected`

Wenn ein Dokument mit einem Virus infiziert erkannt wird, erhält eine Benachrichtigung unabhängig von der E-Mail-Zusammenfassungseinstellung eine Benachrichtigung. Eine Benachrichtigung wird auch an die Administratoren im Projekt des infizierten Dokuments gesendet. Die Benachrichtigung enthält Angaben darüber, wer was wo hochgeladen hat.

Wenn Ihre E-Mail-Benachrichtigungen vollständig deaktiviert sind, wird diese Benachrichtigung nicht als E-Mail-Benachrichtigung gesendet. Sie erhalten die Benachrichtigung dennoch in Catenda Hub, auch wenn Catenda Hub-Benachrichtigungen deaktiviert sind.

> **Hinweis:** Diese Benachrichtigung wird gesendet, auch wenn alle Benachrichtigungen deaktiviert wurden

### 8.4 **Dokument entfernt** - `type=document-deleted`

_Benachrichtigungsoption:_ Ein Dokument oder ein Ordner wird gelöscht

### 8.5 **Dokumente entfernt** - `type=documents-deleted`

_Benachrichtigungsoption:_ Ein Dokument oder ein Ordner wird gelöscht

### 8.6 **Dokumente hochgeladen** - `type=documents-uploaded`

_Benachrichtigung gesendet, wenn:_ Ein Dokument wurde von einem anderen Benutzer hochgeladen

### 8.7 **Dokumentfreigabe**

**Benachrichtigungsoptionen:** Ich bin als Herausgeber in einer Freigabeanforderung festgelegt. Ein Team, dem ich angehöre, ist als Herausgeber in einer Freigabeanforderung festgelegt. Ich bin als Prüfer in einer Freigabeanforderung festgelegt. Neuer Kommentar in Freigabeanforderung

### 8.8 **Zip-Extraktion abgeschlossen**

_Benachrichtigung gesendet, wenn:_ Ein Zip-Ordner wird erfolgreich importiert.

> **Hinweis:** Diese Benachrichtigung wird gesendet, auch wenn alle Benachrichtigungen deaktiviert wurden

### 8.9 **Ihr Zip-Download ist fertig**

Wenn Sie mehrere Dokumente auf einmal heruntergeladen haben, wird eine Zip-Datei vorbereitet. Diese Zip-Datei kann jederzeit aus der Benachrichtigung heruntergeladen werden, auch wenn Sie den Browser schließen und erneut öffnen sollten.

Klicken Sie auf den Text "_Zum Herunterladen klicken (...MB)_" der Benachrichtigung, um die Zip-Datei herunterzuladen.

Wenn Sie nur auf die Benachrichtigung klicken, wird die Seite einfach aktualisiert.

Der Name der heruntergeladenen Zip-Datei lautet _\<Download GUID>.zip_ im Gegensatz zu dem Namen der Zip-Datei, die Sie automatisch erhalten, wenn Sie warten, bis das Zippen abgeschlossen ist, nachdem Sie auf "Download" geklickt haben, was \<Projektname>-\<Dokumente>-\<Zeitstempel>.zip ist Benachrichtigung gesendet an: _Der Benutzer, der die Dokumente heruntergeladen hat._

> **Hinweis:** Diese Benachrichtigung wird gesendet, auch wenn alle Benachrichtigungen deaktiviert wurden

## 9. **Sammlungen** - `type=document-collections`

### 9.1 **Sammlung finalisiert** - `type=library-item-collection-finalized`

**Benachrichtigung gesendet, wenn** Sie oder ein Team, dem Sie angehören, als Verfolger einer Sammlung festgelegt sind und die Sammlung abgeschlossen ist.

**Benachrichtigungsoption** Sammlung abgeschlossen

### 9.2 **Eine Sammlung verfolgt** - `type=library-item-collection-made-follower`

**Benachrichtigung gesendet, wenn** Sie oder ein Team, dem Sie angehören, als Verfolger zu einer Sammlung hinzugefügt wurden.

**Benachrichtigungsoption** Eine Sammlung verfolgt

### 9.3 **Eine Sammlung nicht verfolgt** - `type=library-item-collection-removed-follower`

**Benachrichtigung gesendet, wenn** Sie oder ein Team, dem Sie angehören, wurden aus einer Sammlung entfernt.

**Benachrichtigungsoption** Eine Sammlung nicht verfolgt

### 9.4 **Sammlung aktualisiert** - `type=library-item-collection-updated`

**Benachrichtigung gesendet, wenn** Eine Sammlung wird mit dem Projekt geteilt und Sie oder ein Team, dem Sie angehören, wurden als Verfolger festgelegt.

**Benachrichtigungsoption** Sammlung aktualisiert

### 9.5 **Sammlung privat** - `type=library-item-collection-made-private`

**Benachrichtigung gesendet, wenn** Sie oder ein Team, dem Sie angehören, sind als Verfolger einer Sammlung festgelegt, die mit dem Projekt geteilt wird, und die Sammlung wird privat gemacht.

**Benachrichtigungsoption** Sammlung privat

### 9.6 **Sammlung gelöscht** - `type=library-item-collection-deleted`

**Benachrichtigung gesendet, wenn** Sie sind ein Administrator und ein anderer Administrator löscht eine Sammlung im Projekt.

**Benachrichtigungsoption** Sammlung gelöscht

### 9.7 **Sammlung extern freigegeben** - `type=library-item-collection-shared-externally`

**Benachrichtigung gesendet, wenn** Sie sind ein Administrator und ein anderer Administrator gibt eine Sammlung im Projekt extern frei.

**Benachrichtigungsoption** Sammlung extern freigegeben

## 10. **Mitglieder** - `type=members`

### 10.1 **Neue Einladung** - `type=invite`

**Benachrichtigung gesendet, wenn:** Ein anderer Benutzer sendet Ihnen eine Einladung zu einem Projekt. Die Benachrichtigung beschreibt, wer Sie eingeladen hat und zu welchem Projekt Sie eingeladen wurden. Wenn Sie diese Benachrichtigung erhalten haben, sollten Sie auch eine E-Mail mit einem Einladungslink erhalten haben, auf den Sie klicken können, um die Einladung anzunehmen. Bitte überprüfen Sie [hier](https://support.catenda.com/en/articles/8417802-why-am-i-not-receiving-emails) zur Fehlerbehebung bei E-Mails.

> **Hinweis:** Die Benachrichtigung in Catenda Hub enthält auch den Einladungslink, sodass Sie auch auf die Benachrichtigung klicken können, um die Einladung anzunehmen. Wenn Sie noch kein Konto haben, müssen Sie möglicherweise ein Konto erstellen und erneut eingeladen werden, um auf die Benachrichtigung klicken zu können.

**Benachrichtigungsoption** Eine Person wird zum Projekt eingeladen.

### 10.2 **Neues Mitglied** - `type=member-accept-invitation`

**Benachrichtigung gesendet, wenn** Wenn ein Benutzer eine von einem anderen Mitglied gesendete Einladung akzeptiert, wird eine Benachrichtigung gesendet, dass ein neues Mitglied dem Projekt beigetreten ist.

**Benachrichtigungsoption** Ein neuer Benutzer ist dem Projekt beigetreten

### 10.3 **Zu Team hinzugefügt** - `type=member-added-to-team`

**Benachrichtigung gesendet, wenn** Sie wurden zu einem Team hinzugefügt.

### 10.4 **Neues Teammitglied** - `type=project-member-added-to-team`

**Benachrichtigungsoption** Ein Mitglied wird zu einem Team hinzugefügt

## 11. **Projekt**

### 11.1 **Projektname** - `projects=<Project GUID>`

## 12. **Limit**

### 12.1 **Anzahl der Benachrichtigungen pro Seite** - `limit=<Notification amount>`

_Hinweis:_ Das Laden der Seite kann länger dauern, wenn mehr Benachrichtigungen vorhanden sind.

## 13. **Seite**

### 13.1 **Aktuelle Seite der Benachrichtigungen** - `page=<Page number>`

## 14. **Obligatorische Benachrichtigungen**

Es gibt einige Benachrichtigungen, die gesendet werden, auch wenn Sie alle Kontrollkästchen in den Benachrichtigungseinstellungen deaktiviert haben.

### 14.1 **Gesendet, auch wenn alle Kontrollkästchen deaktiviert sind**

Jede Art von Import oder Export, der im Hintergrund verarbeitet wird, erzeugt eine Benachrichtigung über das Ergebnis des Imports, unabhängig davon, ob er importiert oder fehlgeschlagen ist. Wenn Sie Benachrichtigungen vollständig mit der Ein-/Ausschalt-Taste oben rechts deaktivieren, werden auch diese Benachrichtigungen nicht gesendet.

### 14.2 **Gesendet, auch wenn alle Benachrichtigungen deaktiviert sind**

Benachrichtigungen zu Links, die über die [Sharelink](https://support.catenda.com/en/articles/4728886-sharelink-notify-people-about-catenda-hub-content)-Funktion mit Benutzern geteilt werden, erstellen immer eine Benachrichtigung für den Benutzer, auch wenn der Benutzer Benachrichtigungen vollständig mit der Ein-/Ausschalt-Taste oben rechts auf der Einstellungsseite für Benachrichtigungen deaktiviert hat.
