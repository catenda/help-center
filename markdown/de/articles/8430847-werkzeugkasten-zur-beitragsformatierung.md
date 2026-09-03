# Toolbox für Beitragformatierung

> Wie Felder, in denen Beiträge erstellt werden können, formatiert werden

Die gleichen Formatierungsregeln gelten für die verschiedenen Beiträge in Catenda Hub. Beiträge können Themenbeschreibungen, Kommentare, Freigabebeschreibungen und Freigabekommentare enthalten. Unterschiedliche Zugriffe auf die Bearbeitung des Beitrags können zu Abweichungen führen. Catenda verwendet Markdown zur Textformatierung. Dies bedeutet, dass bestimmte Zeichen vor und nach Sätzen die Gestaltung des Textes beeinflussen. So können eine Themenüberschrift und Beschreibung nach der Übermittlung aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/01-intro.png)

## 1. Formatierungsverfügbarkeit

Häufig können Sie erkennen, dass übermittelte Felder formatiert werden können, indem Sie die Toolbox unterhalb des Felds sehen, wenn das Feld bearbeitet wird.

> **Hinweis:** Zoomen Sie mit der Browser-Zoomskala ausreichend heraus, um alle Tools zu sehen.

Formatierung ist in den folgenden Feldern verfügbar:

### 1.1 **Themenbeschreibung und Kommentar**

Bearbeiten Sie die Beschreibung oder den Kommentar eines vorhandenen Themas oder beim Einreichen eines neuen Themas, um die Toolbox zu sehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/02-topic-description-and-comment.png)

### 1.2 **Freigabeanfrage-Beschreibung**

Obwohl die Toolbox nicht in der Beschreibung des neuen Freigabeanfrage-Dialogs angezeigt wird, wird die Formatierung auf diese Beschreibung angewendet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/03-approval-request-description.png)

> **Hinweis:** Dieses Feld kann nach dem Einreichen der Freigabeanfrage nicht bearbeitet werden.

### 1.3 Beschreibung des Themen-Boards

Obwohl die Toolbox in der neuen Themenbrettbeschreibung angezeigt wird, ist es wichtig zu beachten, dass die Beschreibung nicht formatiert wird, wenn das Board eingereicht wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/04-topic-board-description.png)

## 2. **Themenkommentar-Anhang**

In Themenkommentaren ist ein Anhang-Tool sichtbar. Klicken Sie auf die Schaltfläche + in einem Thema, um einen Anhang hinzuzufügen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/05-topic-comment-attachment.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_0e3c0059ae), um mehr über Kommentar-Anhänge zu erfahren.

## 3. **Text formatieren**

Die folgenden Methoden ermöglichen es Ihnen, Ihren Text zu formatieren:

### 3.1 **Fett, Kursiv, Durchgestrichen**

Fett-, Kursiv- und Durchstreichungsformatierung können an jeder Stelle einer Zeile erfolgen und funktionieren gut mit anderen Formatierungen, die am Anfang einer Zeile sein müssen.

<img alt="**Dies wird fett** __Dies wird auch fett__ *Dies wird kursiv* _Dies wird auch kursiv_ **Dies wird fett _kombiniert mit kursiv_** ~~Dieser Text wird durchgestrichen~~" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-b49c2f10b2de.png" width="290"/>   \<->   <img alt="Dies wird fett​Dies wird auch fett​Dies wird kursiv​Dies wird auch kursiv​Dies wird fett kombiniert mit kursivDieser Text wird durchgestrichen" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-ea38fb93f8ee.png" width="290"/>

### 3.2 **Überschriften**

Das Überschriftentool fügt am Anfang der Zeile Hashtags/Pfund-Zeichen hinzu. Es werden 5 Überschriftsebenen unterstützt: Die Formatierung, die die Überschrift erhält, hängt von der Anzahl der Hashtags/Pfund-Zeichen (`#`) am Anfang der Zeile ab.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-c21079ec7efb.png" width="290"/>   \<->   <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-557784a5d702.png" width="290"/>

### 3.3 **Links**

Die Link-Formatierung kann an jeder Stelle einer Zeile erfolgen und funktioniert gut mit anderen Formatierungen, die am Anfang einer Zeile sein müssen. Links in Beschreibungen sind grün und unterstrichen. Ihr Text kann sich von der URL unterscheiden, auf die der Link verweist. URLs werden automatisch in anklickbare Links umgewandelt

```
https://hub.catenda.com
```

wird zu [https://hub.catenda.com](https://hub.catenda.com) und

```
[Catenda Hub](https://hub.catenda.com)
```

wird zu: [Catenda Hub](https://hub.catenda.com)

> **Hinweis:** Seien Sie vorsichtig beim Klicken auf Links, da der Text [in den Klammern] möglicherweise einen Link anzeigt, der eigentliche Link (in den Klammern) jedoch unterschiedlich sein kann. Es wird empfohlen, über einen Link zu fahren und zu überprüfen, wohin der Browser weitergeleitet wird, bevor Sie auf einen Link klicken.

### 3.4 **Formatierung verhindern**

Durch das Umhüllen von Wörtern mit Nicht-Buchstaben- oder Zahlenzeichen können Sie diese unterschiedlich aussehen lassen. Das ist nicht immer erwünscht. Wenn Sie ein `\` vor so ein Zeichen setzen, verschwindet das `\`. Jede Formatierung, die für diese Zeichen hätte angewendet werden würde, wird dann nicht mehr funktionieren. Wenn Sie ein `\` auf einer leeren Zeile setzen, die nicht Teil einer [Liste](#h_6da4949f8c) ist, ergibt sich immer noch eine leere Zeile.

## 4. **Text aufteilen und Struktur hinzufügen**

Die folgenden Methoden ermöglichen es Ihnen, Ihren Text durch das Aufteilen und Hinzufügen von Struktur zu verbessern:

### 4.1 **Bilder**

Bilder in Beschreibungen können einen Link haben. Zum Einbetten von Bildern können Sie diese Syntax verwenden

```
![text](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

um dieses Bild mit dem Wort Text dahinter zu erhalten.

![text](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/06-images.png)

Damit das Bild ordnungsgemäß angezeigt wird, muss Catenda auf den bereitgestellten Link zugreifen können.

> **Hinweis:** \+ Das Bild kann einer Beschreibung hinzugefügt werden \+ Das Bild kann mit Text gemischt werden, sodass Sie Text sowohl vor als auch nach dem Bild in denselben Kommentaren oder Beschreibungen haben können. \+ Bilder wie diese können mit Tabellen und Listen kombiniert werden. Sie können beispielsweise ein Häkchenbild in der Mitte eines Satzes/einer Tabelle hinzufügen, anstatt das Formatierungskontrollkästchen zu verwenden, das nur am Anfang eines Satzes funktioniert \- Sie können nicht garantieren, dass der Link zum Bild in Zukunft verfügbar bleibt.

_Catenda-Bild-Dokumentenlink abrufen_ Wenn Sie mit der rechten Maustaste auf die [Download-Aktionsschaltfläche nach Auswahl eines Dokuments](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) oder mit der rechten Maustaste auf die [Download-Schaltfläche für die neueste Überarbeitung klicken, nachdem Sie ein Dokument geöffnet haben](https://support.catenda.com/en/articles/9323521-actions-in-a-document), können Sie den Download-Link des Dokuments kopieren. Wenn Sie diesen Link in Ihrem Thema wie oben verwenden, können Sie Catenda-Dokumente in Themen verwenden.

> **Hinweis:** \+ Wenn Sie einen Link zu einem Catenda-Bilddokument hinzufügen, können Sie Bilder hinzufügen, die nur auf Catenda angezeigt werden und nicht auf anderen Plattformen verfügbar sind, mit denen das Thema möglicherweise ausgetauscht wird. \+ Durch das Hinzufügen von Links zu einem Catenda-Bilddokument können nur Personen mit Zugriff auf das Dokument das Bild sehen. \- Wenn Sie einen Link zu einem Catenda-Bilddokument hinzufügen, ist es auf anderen Plattformen, mit denen das Thema möglicherweise synchronisiert wurde, und für Personen ohne Zugriff auf das Dokument nicht sichtbar.

### 4.2 **Listen**

**Ungeordnete Listen** Starten Sie eine ungeordnete Liste mit einer leeren Zeile darüber, dann entweder Bindestrich (`-`), Plus (`+`) oder Sternchen (`*`) gefolgt von einem Leerzeichen. Fügen Sie am Anfang der Zeile 4 Leerzeichen oder einen Tabulator ein, um eine Unterliste zu erstellen.

```
 - Erstes Element - Zweites Element     - Fügen Sie 4 Leerzeichen am Anfang der Zeile ein, um eine Unterliste zu erstellen.
```

Oder

```
 + Erstes Element + Zweites Element     + Fügen Sie 4 Leerzeichen am Anfang der Zeile ein, um eine Unterliste zu erstellen.
```

Oder

```
 * Erstes Element * Zweites Element     * Fügen Sie 4 Leerzeichen am Anfang der Zeile ein, um eine Unterliste zu erstellen.
```

Alle werden dies werden sich daraus ergeben:

- Erstes Element
- Zweites Element
  - Fügen Sie 4 Leerzeichen am Anfang der Zeile ein, um eine Unterliste zu erstellen.

> **Hinweis:** Damit eine ungeordnete Liste korrekt formatiert wird, muss über der Liste eine leere Zeile vorhanden sein.

**Geordnete Listen** Starten Sie eine geordnete Liste mit einer leeren Zeile darüber, einer Zahl, einem Punkt und einem Leerzeichen (`1. `). Welche Zahl vorne steht, ist egal, nur dass es eine Zahl gefolgt von einem Punkt ist. Fügen Sie am Anfang der Zeile 4 Leerzeichen oder einen Tabulator ein, um eine Unterliste zu erstellen.

```
1. Element eins 2. Element zwei 3. Element drei     4. Element vier
```

Oder

```
1. Element eins 1. Element zwei 1. Element drei     1. Element vier
```

Oder

```
1. Element eins 10. Element zwei 1. Element drei     1000. Element vier
```

Alle werden dies werden sich daraus ergeben:

1. Element eins
1. Element zwei
1. Element drei

1. Element vier

> **Hinweis:** Damit eine geordnete Liste korrekt formatiert wird, muss über der Liste eine leere Zeile vorhanden sein.

Die Anfangszahl beeinflußt nicht, wo die Nummerierung beginnt

```
23. dreiundzwanzig 1. vierundzwanzig 1. fünfundzwanzig     1. sechsundzwanzig
```

Wird sich daraus ergeben:

1. dreiundzwanzig
1. vierundzwanzig
1. fünfundzwanzig

1. sechsundzwanzig

Wenn Sie die Nummerierung zurücksetzen und auf einer zweiten Liste im gleichen Beitrag von vorne beginnen möchten, können Sie eine leere oder eine [Trennlinie](#h_3a36cfbc61) dazwischen setzen.

Um [sicherzustellen, dass die Liste nicht formatiert wird](#h_2ec17c688b), damit Sie Ihre eigene Nummerierung verwenden können: Setzen Sie ein Zeichen auf die Zeile über der Liste. Eine gute Wahl ist `\`, da es verschwinden wird.

```
\23. dreiundzwanzig 24. vierundzwanzig 25. fünfundzwanzig     26. sechsundzwanzig
```

Setzen Sie einen Backslash (`\`) vor den Punkt (`.`):

```
23\. dreiundzwanzig 24\. vierundzwanzig 25\. fünfundzwanzig     26\. sechsundzwanzig
```

Alle werden dies werden sich daraus ergeben:

23\. dreiundzwanzig 24\. vierundzwanzig 25\. fünfundzwanzig 26\. sechsundzwanzig

### 4.3 **Trennlinien**

Drei Bindestriche `---` oder mehr auf ihrer eigenen Zeile erstellen eine Trennlinie:

---

### 4.4 **Checklisten**

Diese können in der Beschreibung eines Themas überprüft werden. _Erforderlicher Zugriff:_ Schreibzugriff auf das Themen-Board.

```
- [ ] erstes Element - [x] zweites Element     - [ ] Unterlisten-Element
```

Wird sich daraus ergeben:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/07-checklists.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/5036461-check-lists-within-issues), um ein kurzes Video darüber zu sehen, wie Checklisten im Projekt verwendet werden können. Wenn Sie `- [ ]` oder `- [x]` schreiben, wird das Kontrollkästchen immer noch als nicht aktiviert und aktiviert angezeigt, wenn der Kommentar eingereicht oder nach der Bearbeitung gespeichert wird.

**Kontrollkästchen in Kommentaren** In Kommentaren können Kontrollkästchen nur durch Formatierung überprüft werden. Kontrollkästchen in Kommentaren können nicht angeklickt werden, um überprüft zu werden. _Erforderlicher Zugriff -_ Der Kommentarverfasser hat Zugriff auf die Bearbeitung des erstellten Kommentars

### 4.5 **Tabellen**

Text in Beschreibungen kann in Tabellen organisiert werden.

```
|            | Windows            ||             | |            | Typ 1    | Typ 2    | Summe gesamt   | |----------- | -------- | -------- | ----------- | | **Preis**  | 500,-    | 400,-    |             | | **Menge** | 10       | 4        |             | | **Summe**    | 5 000,-  | 1 600,-  | **6 600,-** |
```

wird sich daraus ergeben

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right">Win</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>dows</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Typ 1</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Typ 2</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Summe gesamt</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Preis</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>500,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>400,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Menge</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>10</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>4</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Summe</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>5 000,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>1 600,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>6 600,-</b></p></td></tr></tbody></table></div>

### 4.6 **Codeblöcke**

Sie können einzelne Codezeilen wie folgt einfügen: Zwei `` ` `` um Text ergibt folgende Ansicht:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/08-code-blocks.png)

Drei Backticks ` ``` ` über und unter etwas Text sieht so aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/09-code-blocks.png)

Es ist nicht möglich, Tabellen in Codeblöcken hinzuzufügen

### 4.7 **Markdown-Dialekt**

Wenn Sie mehr darüber erfahren möchten, wie Text in Kommentaren und Beschreibungen formatiert wird, verwenden wir den Markdown-Dialekt "flexmark" zum Formatieren dieses Textes. Erfahren Sie mehr über flexmark auf ihrer [Github-Seite](https://github.com/vsch/flexmark-java).

## 5. **@ Erwähnte Mitglieder und Teams**

Klicken Sie auf das `@`-Tool oder schreiben Sie `@` in eine Beschreibung oder einen Kommentar, um ein Mitglied zu erwähnen. Nach Eingabe von `@` wird eine Dropdown-Liste mit Mitgliedern und Teams angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/10-mentioned-members-and-teams.png)

Durchsuchen Sie die Liste, indem Sie die E-Mail, den Mitgliedernamen oder den Teamnamen eingeben. Navigieren Sie mit den Pfeiltasten nach oben und unten in der Liste und klicken Sie oder drücken Sie Enter, um ein Mitglied oder Team auszuwählen. Damit ein Mitglied oder Team in dieser Liste angezeigt wird, müssen das Mitglied oder das Team mindestens Lesezugriff auf das Themen-Board haben. Nach Auswahl eines Mitglieds oder Teams in der Liste erhält das `@` einen zusätzlichen Text, der folgendermaßen aussehen kann:

`@[<E-Mail-Adresse des Mitglieds>]` oder `@[<Teamname>]`

### 5.1 **Speichern oder Einreichen einer Erwähnung in einem Thema**

Wenn die Beschreibung gespeichert oder der Kommentar eingereicht wird, erhalten verwandte Mitglieder mit Zugriff auf das Themen-Board eine Benachrichtigung. Wenn die E-Mail des Mitglieds oder der Name des Teams bekannt ist, kann es auch manuell geschrieben werden, aber wenn sie nicht Teil des Themen-Boards sind, werden die verwandten Mitglieder nicht benachrichtigt, dass sie erwähnt werden.

**Benachrichtigung bei Mitglied-Erwähnung** Mitglieder mit Zugriff auf das Themen-Board, die erwähnt werden, erhalten eine Benachrichtigung, dass sie in einem Thema erwähnt werden.

**Benachrichtigung bei Team-Erwähnung** Mitglieder mit Zugriff auf das Themen-Board, die Teil eines erwähnten Teams sind, erhalten eine Benachrichtigung, dass ein Team, dem sie angehören, in einem Thema erwähnt wird.

**Benachrichtigungen über zukünftige Themenereignisse** Mitglieder von Teams, die in Themenbeschreibungen und Kommentaren erwähnt werden, erhalten nur die eine Benachrichtigung nach der gespeicherten Beschreibung oder dem eingereichten Kommentar.

Zusätzlich zu der Benachrichtigung, dass sie erwähnt werden, werden Mitglieder, die in Beiträgen erwähnt werden, automatisch auf [Folgen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) des Themas eingestellt und erhalten Benachrichtigungen über Themenereignisse wie neue Kommentare und Statusänderungen. Dies ist eine großartige Möglichkeit, um sicherzustellen, dass nicht nur der [Bevollmächtigte](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) und [Anfragender](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7) Benachrichtigungen über zukünftige Änderungen an einem Thema erhalten. Wenn ein Mitglied das Thema nicht mehr abonnieren möchte, muss es es manuell abbestellen.

### 5.2 **Erwähnung in Beitrag**

Erwähnungen in Beiträgen können an der grünen Textfarbe erkannt werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/11-mention-in-post.png)

Im Hintergrund wird die eindeutige ID des erwähnten Projektbeteiligten gespeichert. Es ist der Name des Teilnehmers, der in diesem grünen Text angezeigt wird. Auch wenn das Mitglied oder das Team seinen Namen ändert, bleibt es im Beitrag erwähnt, aber unter seinem neuen Namen.

Erwähnte Mitglieder haben einen anklickbaren Link, der zur [Mitgliederseite](https://support.catenda.com/en/articles/8228836-member-page) dieses Mitglieds führt. Erwähnte Teams haben einen anklickbaren Link, der zur [Teamseite](https://support.catenda.com/en/articles/7891755-team-page) dieses Teams führt.

**Nicht vorhandenes Mitglied** Wenn kein Mitglied im Projekt eine erwähnte E-Mail-Adresse hat, sieht der Beitrag stattdessen so aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/12-mention-in-post.png)

Dies kann entweder daran liegen, dass die E-Mail falsch formatiert wurde oder weil das Mitglied nicht mehr Teil des Projekts ist. Sollte ein Mitglied mit dieser E-Mail-Adresse in Zukunft Teil des Projekts werden, ändert sich der Beitrag so, dass der Name dieses Mitglieds angezeigt wird.

**Nicht vorhandenes Team** Wenn ein Team aus dem Projekt entfernt wurde und ein neues Team erstellt wird, wird dieses neue Team nicht erwähnt. Um das neue Team zu erwähnen, muss der Beitrag erneut eingereicht werden.

## 6. **# Markierte Themen**

Klicken Sie auf das `#`-Tool oder schreiben Sie `#` in eine Beschreibung oder einen Kommentar, um ein Thema zu markieren. Nach Eingabe von `#` wird eine Dropdown-Liste mit Themen aus allen Themen-Boards angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/13-tagged-topics.png)

Durchsuchen Sie die Liste, indem Sie den Titel oder die Themennummer eingeben. Navigieren Sie mit den Pfeiltasten nach oben und unten in der Liste und klicken Sie oder drücken Sie Enter, um ein Thema auszuwählen. Damit ein Thema in dieser Liste angezeigt wird, muss das Mitglied, das das Tag setzt, Zugriff auf das Board haben, auf dem sich das Thema befindet. Nach Auswahl eines Themas in der Liste erhält das `#` einen zusätzlichen Text, der folgendermaßen aussehen kann:

`#[<Themennummer>]`

### 6.1 **Speichern oder Einreichen eines markierten Themas**

Wenn die Beschreibung gespeichert oder der Kommentar eingereicht wird, wird eine Themenrelation erstellt. Das verknüpfte Thema wird dann zur Liste der [verknüpften Themen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) im [rechten Menü](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) des Themas hinzugefügt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/14-saving-or-submitting-a-tagged-topic.png)

Zusätzlich zu dem Thema, in dem ein anderes Thema markiert wurde, erhält das markierte Thema selbst einen Link zurück zu dem Thema, in dem es zur Liste der [verknüpften Themen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) im [rechten Menü](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) hinzugefügt wurde.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/15-saving-or-submitting-a-tagged-topic.png)

Der Themen-Link kann später von entweder dem Thema mit dem markierten Thema in der Beschreibung oder vom markierten Thema entfernt werden, indem Sie zu jedem Thema gehen und die Liste der [verknüpften Themen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) im [rechten Menü](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) bearbeiten.

### 6.2 **Markiertes Thema in Beitrag**

Markierte Themen können an einem Kreis mit der Farbe des aktuellen Status des markierten Themas zusammen mit dem Namen dieses Status erkannt werden. Danach wird der Thementitel gefolgt von der Themennummer angezeigt.

Zusammen mit den Kontrollkästchen zählen geschlossene markierte Themen zum Fortschritt in der Fortschrittsleiste, die oben angezeigt wird, während offene markierte Themen zum Gesamtanzahl der Elemente zählen, auf die der Fortschritt angerechnet wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/16-tagged-topic-in-post.png)

Markierte Themen haben einen anklickbaren Link, der das markierte Thema in seinem Themen-Board öffnet.
