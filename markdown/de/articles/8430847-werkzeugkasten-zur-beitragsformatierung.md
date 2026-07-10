# Werkzeugkasten zur Beitragsformatierung

> Wie Felder, in denen Beiträge erstellt werden können, formatiert werden können

Die gleichen Formatierungsregeln gelten für die verschiedenen Beiträge in Catenda Hub. Beiträge können Themabeschreibungen, Kommentare, Genehmigungsbeschreibungen und Genehmigungskommentare enthalten. Abweichungen können je nach unterschiedlichem Zugriff auf die Bearbeitung des Beitrags gelten. Catenda verwendet Markdown zur Textformatierung. Dies bedeutet, dass bestimmte Zeichen vor und nach Sätzen das Aussehen des Textes beeinflussen. So können eine Themakopfzeile und eine Beschreibung nach dem Absenden aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/01-intro.png)

## 1. Formatierungsverfügbarkeit

Es ist oft möglich, zu erkennen, dass übermittelte Felder formatiert werden können, indem der Werkzeugkasten angezeigt wird, der unter dem Feld angezeigt wird, wenn das Feld bearbeitet wird.

> **Hinweis:** Vergrößern Sie den Browserzoom-Maßstab ausreichend aus, um alle Tools zu sehen.

Die Formatierung ist in den folgenden Feldern verfügbar:

### 1.1 **Themabeschreibung und Kommentar**

Bearbeiten Sie die Beschreibung oder den Kommentar eines vorhandenen Themas oder beim Absenden eines neuen Themas, um den Werkzeugkasten zu sehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/02-topic-description-and-comment.png)

### 1.2 **Genehmigungsanforderungsbeschreibung**

Während der Werkzeugkasten nicht im Dialog für die neue Genehmigungsanforderung angezeigt wird, wird die Formatierung auf diese Beschreibung angewendet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/03-approval-request-description.png)

> **Hinweis:** Dieses Feld kann nach dem Absenden der Genehmigungsanforderung nicht bearbeitet werden.

### 1.3 Themabrettbeschreibung

Während der Werkzeugkasten in der neuen Themabrettbeschreibung angezeigt wird, ist es wichtig zu beachten, dass die Beschreibung nicht formatiert wird, wenn das Brett abgesendet wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/04-topic-board-description.png)

## 2. **Themakommentaranhang**

In Themakommentaren ist ein Anhang-Tool sichtbar. Klicken Sie auf die Schaltfläche + in einem Thema, um einen Anhang hinzuzufügen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/05-topic-comment-attachment.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_0e3c0059ae), um mehr über Kommentaranhänge zu erfahren.

## 3. **Text formatieren**

Die folgenden Methoden ermöglichen es Ihnen, Ihren Text zu formatieren:

### 3.1 **Fett, Kursiv, Durchgestrichen**

Fettdruck-, Kursiv- und Durchstreichungsformatierung können an einer beliebigen Stelle einer Zeile durchgeführt werden und funktionieren gut mit anderen Formatierungen, die am Anfang einer Zeile durchgeführt werden müssen.

<img alt="**This will be bold** __This will also be bold__ *This will be italics* _This will also be italics_ **This will be bold _combined with italics_** ~~This text will be struck through~~" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-b49c2f10b2de.png" width="290"/>   \<->   <img alt="This will be bold​This will also be bold​This will be italics​This will also be italics​This will be bold combined with italicsThis text will be struck through" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-ea38fb93f8ee.png" width="290"/>

### 3.2 **Überschriften**

Das Überschrift-Tool wendet Hashtags/Pfundzeichen am Anfang der Zeile an. Es gibt 5 Ebenen von Überschriften, die unterstützt werden: Die Formatierung, die die Überschrift erhält, hängt von der Anzahl der Hashtags/Pfundzeichen (`#`) am Anfang der Zeile ab.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-c21079ec7efb.png" width="290"/>   \<->   <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-557784a5d702.png" width="290"/>

### 3.3 **Links**

Die Link-Formatierung kann an einer beliebigen Stelle einer Zeile durchgeführt werden und funktioniert gut mit anderen Formatierungen, die am Anfang einer Zeile durchgeführt werden müssen. Links in Beschreibungen sind grün und unterstrichen. Ihr Text kann sich von der URL unterscheiden, auf die der Link zeigt. URLs werden automatisch in anklickbare Links umgewandelt

```
https://hub.catenda.com
```

wird zu [https://hub.catenda.com](https://hub.catenda.com) und

```
[Catenda Hub](https://hub.catenda.com)
```

wird zu: [Catenda Hub](https://hub.catenda.com)

> **Hinweis:** Seien Sie vorsichtig beim Anklicken von Links, da der Text [aus den Klammern] zwar einen Link anzeigen kann, der eigentliche Link (aus den Klammern) jedoch unterschiedlich sein kann. Es wird empfohlen, den Mauszeiger über einen Link zu bewegen und zu prüfen, wo der Browser umleitet, bevor Sie auf einen Link klicken.

### 3.4 **Formatierung verhindern**

Durch das Einwickeln von Wörtern in Nicht-Buchstaben- oder Zahlenzeichen können Sie sie unterschiedlich aussehen lassen. Dies ist nicht immer gewünscht. Wenn Sie ein `\` vor solch ein Zeichen setzen, wird das `\` verschwinden. Jede Formatierung, die für diese Zeichen angewendet würde, funktioniert dann nicht mehr. Wenn Sie ein `\` auf eine leere Zeile setzen, die nicht Teil einer [Liste](#lists) ist, bleibt das Ergebnis dennoch eine leere Zeile.

## 4. **Text untergliedern und strukturieren**

Die folgenden Methoden ermöglichen es Ihnen, Ihren Text zu verbessern, indem Sie ihn untergliedern und strukturieren:

### 4.1 **Bilder**

Bilder in Beschreibungen können einen Link enthalten. Um Bilder einzubinden, können Sie diese Syntax verwenden

```
![text](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

um dieses Bild mit dem Wort Text dahinter zu erhalten.

![text](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/06-images.png)

Damit das Bild richtig angezeigt wird, muss Catenda auf den bereitgestellten Link zugreifen können.

> **Hinweis:** \+ Das Bild kann zu einer Beschreibung hinzugefügt werden \+ Das Bild kann mit Text vermischt werden, sodass Sie vor und nach dem Bild in denselben Kommentaren oder der Beschreibung Text haben können. \+ Bilder wie diese können mit Tabellen und Listen kombiniert werden. Sie könnten beispielsweise ein Häkchenbild in der Mitte eines Satzes/einer Tabelle anstelle des Formatierungskontrollkästchens hinzufügen, das nur am Anfang eines Satzes funktioniert \- Sie können nicht garantieren, dass der Link zum Bild in Zukunft verfügbar bleibt.

_Catenda-Bilddokumentlink abrufen_ Wenn Sie auf die [Download-Aktionsschaltfläche nach Auswahl eines Dokuments](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) oder auf die [Download-Schaltfläche für die neueste Revision nach dem Öffnen eines Dokuments](https://support.catenda.com/en/articles/9323521-actions-in-a-document) rechtsklicken, können Sie den Download-Link des Dokuments kopieren. Wenn Sie diesen Link in Ihrem Thema wie oben verwenden, können Sie Catenda-Dokumente in Themen verwenden.

> **Hinweis:** \+ Wenn Sie einen Link zu einem Catenda-Bilddokument hinzufügen, können Sie Bilder hinzufügen, die nur auf Catenda angezeigt werden und in anderen Plattformen, mit denen das Thema ausgetauscht werden kann, nicht verfügbar sind. \+ Durch das Hinzufügen von Links zu einem Catenda-Bilddokument können nur Personen mit Zugriff auf das Dokument das Bild sehen. \- Wenn Sie einen Link zu einem Catenda-Bilddokument hinzufügen, ist es in anderen Plattformen, mit denen das Thema möglicherweise synchronisiert wurde, und für Personen ohne Zugriff auf das Dokument nicht sichtbar.

### 4.2 **Listen**

**Ungeordnete Listen** Starten Sie eine ungeordnete Liste mit einer leeren Zeile darüber, dann entweder Bindestrich (`-`), Plus (`+`) oder Sternchen (`*`) gefolgt von einem Leerzeichen. Fügen Sie 4 Leerzeichen oder ein Tabulatorzeichen am Anfang der Zeile ein, um eine Unterliste zu erstellen.

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

Alle werden zu folgendem:

- Erstes Element
- Zweites Element
  - Fügen Sie 4 Leerzeichen am Anfang der Zeile ein, um eine Unterliste zu erstellen.

> **Hinweis:** Damit eine ungeordnete Liste korrekt formatiert wird, muss über der Liste eine leere Zeile vorhanden sein.

**Geordnete Listen** Starten Sie eine geordnete Liste mit einer leeren Zeile darüber, einer Nummer, einem Punkt und einem Leerzeichen (`1. `) Die Nummer davor spielt keine Rolle, nur dass es eine Nummer gefolgt von einem Punkt ist. Fügen Sie 4 Leerzeichen oder ein Tabulatorzeichen am Anfang der Zeile ein, um eine Unterliste zu erstellen.

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

Alle werden zu folgendem:

1. Element eins
2. Element zwei
3. Element drei

4. Element vier

> **Hinweis:** Damit eine geordnete Liste korrekt formatiert wird, muss über der Liste eine leere Zeile vorhanden sein.

Die Nummer, mit der Sie beginnen, wirkt sich nicht auf den Beginn der Nummerierung aus

```
23. dreiundzwanzig 1. vierundzwanzig 1. fünfundzwanzig     1. sechsundzwanzig
```

Wird zu:

1. dreiundzwanzig
2. vierundzwanzig
3. fünfundzwanzig

4. sechsundzwanzig

Wenn Sie die Nummerierung zurücksetzen und in einer zweiten Liste im selben Beitrag erneut von eins beginnen möchten, können Sie eine leere Zeile oder eine [Trennlinie](#dividers) einfügen.

Um [sicherzustellen, dass die Liste nicht formatiert wird](#preventing-formatting), damit Sie Ihre eigene Nummerierung verwenden können: Platzieren Sie ein Zeichen über der Liste. Eine gute Wahl ist `\`, da es verschwindet.

```
\23. dreiundzwanzig 24. vierundzwanzig 25. fünfundzwanzig     26. sechsundzwanzig
```

Setzen Sie einen Backslash (`\`) vor den Punkt (`.`):

```
23\. dreiundzwanzig 24\. vierundzwanzig 25\. fünfundzwanzig     26\. sechsundzwanzig
```

Alle werden zu folgendem:

23\. dreiundzwanzig 24\. vierundzwanzig 25\. fünfundzwanzig 26\. sechsundzwanzig

### 4.3 **Trennlinien**

Drei Bindestriche `---` oder mehr auf ihrer eigenen Zeile erstellen eine Trennlinie:

---

### 4.4 **Checklisten**

Diese können in der Beschreibung eines Themas aktiviert werden. _Erforderlicher Zugriff:_ Schreibzugriff auf das Themabrett.

```
- [ ] erstes Element - [x] zweites Element     - [ ] Unterlisten-Element
```

Wird zu folgendem:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/07-checklists.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/5036461-check-lists-within-issues), um ein kurzes Video anzusehen, wie Checklisten im Projekt verwendet werden können. Wenn Sie `- [ ]` oder `- [x]` schreiben, wird das Feld immer noch nicht aktiviert und aktiviert angezeigt, wenn der Kommentar abgesendet oder nach der Bearbeitung gespeichert wird.

**Kontrollkästchen in Kommentaren** In Kommentaren können Kontrollkästchen nur durch Formatierung aktiviert werden. Kontrollkästchen in Kommentaren können nicht angeklickt werden, um sie zu aktivieren. _Erforderlicher Zugriff -_ Der Kommentarverfasser hat Zugriff auf die Bearbeitung des erstellten Kommentars

### 4.5 **Tabellen**

Text in Beschreibungen kann in Tabellen angeordnet werden.

```
|            | Windows            ||             | |            | Typ 1   | Typ 2   | Summe gesamt   | |----------- | -------- | -------- | ----------- | | **Preis**  | 500,-    | 400,-    |             | | **Menge** | 10       | 4        |             | | **Summe**    | 5 000,-  | 1 600,-  | **6 600,-** |
```

ergibt folgendes

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p></p></td><td><p class="intercom-align-right">Win</p></td><td><p>dows</p></td><td><p></p></td></tr><tr><td><p></p></td><td><p>Typ 1</p></td><td><p>Typ 2</p></td><td><p>Summe gesamt</p></td></tr><tr><td><p><b>Preis</b></p></td><td><p>500,-</p></td><td><p>400,-</p></td><td><p></p></td></tr><tr><td><p><b>Menge</b></p></td><td><p>10</p></td><td><p>4</p></td><td><p></p></td></tr><tr><td><p><b>Summe</b></p></td><td><p>5 000,-</p></td><td><p>1 600,-</p></td><td><p><b>6 600,-</b></p></td></tr></tbody></table></div>

### 4.6 **Codeblöcke**

Sie können einzelne Codezeilen so einfügen: Zwei \`\`\` umgeben Text, sehen so aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/08-code-blocks.png)

Drei Backticks `\`\\`\`\` über und unter einem bisschen Text sehen so aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/09-code-blocks.png)

Es ist nicht möglich, Tabellen in Codeblöcken hinzuzufügen

### 4.7 **Markdown-Dialekt**

Wenn Sie mehr darüber erfahren möchten, wie Text in Kommentaren und Beschreibungen formatiert wird, verwenden wir den Markdown-Dialekt "flexmark" zum Formatieren dieses Textes. Erfahren Sie mehr über flexmark auf ihrer [Github-Seite](https://github.com/vsch/flexmark-java).

## 5. **@ Erwähnte Mitglieder und Teams**

Klicken Sie auf das `@`-Tool oder schreiben Sie `@` in einer Beschreibung oder einem Kommentar, um ein Mitglied zu erwähnen. Nach dem Eingeben von `@` wird eine Dropdown-Liste mit Mitgliedern und Teams angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/10-mentioned-members-and-teams.png)

Suchen Sie in der Liste, indem Sie mit der E-Mail-Adresse, dem Mitgliedsnamen oder dem Teamnamen beginnen zu tippen. Navigieren Sie in der Liste mit den Pfeiltasten nach oben und unten und klicken Sie oder drücken Sie die Eingabetaste, um ein Mitglied oder ein Team auszuwählen. Damit ein Mitglied oder Team in dieser Liste angezeigt wird, muss das Mitglied oder Team mindestens Lesezugriff auf das Themabrett haben. Nach Auswahl eines Mitglieds oder eines Teams in der Liste erhält `@` zusätzlichen Text, der wie folgt aussehen kann:

`@[<E-Mail-Adresse des Mitglieds>]` oder `@[<Teamname>]`

### 5.1 **Eine Erwähnung in einem Thema speichern oder absenden**

Wenn die Beschreibung gespeichert oder der Kommentar abgesendet wird, erhalten zugehörige Mitglieder mit Zugriff auf das Themabrett eine Benachrichtigung. Wenn die E-Mail des Mitglieds oder der Name des Teams bekannt ist, kann es auch manuell geschrieben werden, aber wenn sie nicht Teil des Themabretts sind, werden die zugehörigen Mitglieder nicht benachrichtigt, dass sie erwähnt werden.

**Benachrichtigung bei Erwähnung eines Mitglieds** Mitglieder mit Zugriff auf das Themabrett, die erwähnt werden, erhalten eine Benachrichtigung, dass sie in einem Thema erwähnt werden.

**Benachrichtigung bei Teamerwähnung** Mitglieder mit Zugriff auf das Themabrett, die Teil eines erwähnten Teams sind, erhalten eine Benachrichtigung, dass ein Team, dem sie angehören, in einem Thema erwähnt wird.

**Benachrichtigungen über zukünftige Themenereignisse** Mitglieder von Teams, die in Themabeschreibungen und Kommentaren erwähnt werden, erhalten nur die eine Benachrichtigung bei der gespeicherten Beschreibung oder dem abgesendeten Kommentar.

Zusätzlich zu der Benachrichtigung, dass sie erwähnt werden, werden Mitglieder, die in Beiträgen erwähnt werden, automatisch auf [folgen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) zum Thema gesetzt und erhalten Benachrichtigungen über Themenereignisse wie neue Kommentare und Statusänderungen. Dies ist eine großartige Möglichkeit, um sicherzustellen, dass nicht nur der [Verantwortliche](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) und der [Anfragsteller](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7) Benachrichtigungen über zukünftige Änderungen eines Themas erhalten. Wenn ein Mitglied das Thema nicht mehr verfolgen möchte, muss es es manuell entfolgen.

### 5.2 **Erwähnung im Beitrag**

Erwähnungen in Beiträgen können an der grünen Textfarbe erkannt werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/11-mention-in-post.png)

Im Hintergrund wird die eindeutige ID des erwähnten Projektbeteiligten gespeichert. Es ist der Name des Beteiligten, der in diesem grünen Text angezeigt wird. Auch wenn sich das Mitglied oder Team umbenennt, bleibt es im Beitrag erwähnt, aber unter seinem neuen Namen.

Erwähnte Mitglieder haben einen anklickbaren Link, der zur [Mitgliedsseite](https://support.catenda.com/en/articles/8228836-member-page) dieses Mitglieds führt. Erwähnte Teams haben einen anklickbaren Link, der zur [Teamseite](https://support.catenda.com/en/articles/7891755-team-page) dieses Teams führt.

**Nicht vorhandenes Mitglied** Wenn es im Projekt kein Mitglied mit der erwähnten E-Mail-Adresse gibt, sieht der Beitrag stattdessen so aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/12-mention-in-post.png)

Dies kann daran liegen, dass die E-Mail falsch formatiert wurde oder das Mitglied nicht mehr Teil des Projekts ist. Sollte in Zukunft ein Mitglied mit dieser E-Mail-Adresse Teil des Projekts werden, ändert sich der Beitrag zur Anzeige des Namens dieses Mitglieds.

**Nicht vorhandenes Team** Wenn ein Team aus dem Projekt entfernt wurde und ein neues Team erstellt wird, wird dieses neue Team nicht erwähnt. Um das neue Team zu erwähnen, muss der Beitrag erneut abgesendet werden.

## 6. **# Themen mit Tags versehen**

Klicken Sie auf das `#`-Tool oder schreiben Sie `#` in einer Beschreibung oder einem Kommentar, um ein Thema mit Tags zu versehen. Nach dem Eingeben von `#` wird eine Dropdown-Liste mit Themen aus allen Themabretten angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/13-tagged-topics.png)

Suchen Sie in der Liste, indem Sie mit dem Titel oder der Themennummer beginnen zu tippen. Navigieren Sie in der Liste mit den Pfeiltasten nach oben und unten und klicken Sie oder drücken Sie die Eingabetaste, um ein Thema auszuwählen. Damit ein Thema in dieser Liste angezeigt wird, muss das Mitglied, das das Tag zuweist, Zugriff auf das Brett haben, auf dem sich das Thema befindet. Nach Auswahl eines Themas in der Liste erhält `#` zusätzlichen Text, der wie folgt aussehen kann:

`#[<Themennummer>]`

### 6.1 **Ein mit Tags versehenes Thema speichern oder absenden**

Wenn die Beschreibung gespeichert oder der Kommentar abgesendet wird, wird eine Themabeziehung erstellt. Das verknüpfte Thema wird dann zur Liste der [verknüpften Themen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) im [rechten Menü](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) des Themas hinzugefügt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/14-saving-or-submitting-a-tagged-topic.png)

Zusätzlich zu dem Thema, in dem ein anderes Thema mit Tags versehen wurde, erhält das mit Tags versehene Thema selbst einen Link zurück zu dem Thema, bei dem es zur Liste der [verknüpften Themen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) im [rechten Menü](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) hinzugefügt wurde.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/15-saving-or-submitting-a-tagged-topic.png)

Der Themalink kann später entweder aus dem Thema mit dem mit Tags versehenen Thema in der Beschreibung oder aus dem Thema, das mit Tags versehen wurde, entfernt werden, indem zu jedem Thema gegangen und die Liste der [verknüpften Themen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) im [rechten Menü](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) bearbeitet wird.

### 6.2 **Mit Tags versehenes Thema im Beitrag**

Mit Tags versehene Themen können dadurch erkannt werden, dass sie zunächst einen Kreis mit der Farbe des aktuellen Status des mit Tags versehenen Themas zusammen mit dem Namen dieses Status haben. Danach wird der Thematitel gefolgt von der Themennummer angezeigt.

Zusammen mit den Kontrollkästchen zählen mit Tags versehene Themen, die geschlossen sind, zu dem Fortschritt im Fortschrittsbalken, der oben angezeigt wird, während mit Tags versehene Themen, die offen sind, zu den Gesamtelementen zählen, auf die der Fortschritt gezählt wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/16-tagged-topic-in-post.png)

Mit Tags versehene Themen haben einen anklickbaren Link, der das mit Tags versehene Thema in seinem Themabrett öffnet.
