# Filterung auf der Themaseite

Das Filtermenü in einem Themabrett kann durch Klicken auf die Filterschaltfläche links neben der Suchleiste in einem [Themabrett](https://support.catenda.com/en/articles/4670271-issues-page) geöffnet werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/01-intro.png)

## 1. **Filter**

Klicken Sie auf die Filterschaltfläche oben links, um ein Panel auf der linken Seite anzuzeigen. Wenn ein Filter angewendet wird, ändert sich die im Browser sichtbare URL entsprechend. In diesem Artikel werden Filter wie folgt angezeigt: _Filtername im Menü_ - `Filtername in URL=Filteroption in URL`

**Standardfilter** Der Standardfilter ist zunächst nicht in der URL sichtbar. Wenn die Seite zum ersten Mal aufgerufen wird, wird der folgende Filter angewendet. _Kein Filter_ - `status-type=all`

### 1.1 **Aktuellen Filter speichern und freigeben**

Gehen Sie zur URL einer gefilterten Seite, um diese Seite mit angewendetem Filter zu laden. Die angewendeten Filter können oben im Filtermenü gespeichert werden. Klicken Sie [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link), um mehr über das Speichern und Freigeben von Filtern zu erfahren

### 1.2 **Leere Filter ausblenden**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über die Begrenzung von Filterergebnissen zu erfahren.

## 2. **Filterung im Filtermenü**

Hier können die folgenden Filter gefunden werden:

Die verschiedenen Filter im Filtermenü werden nur angezeigt, wenn es Themen gibt, für die das gefilterte Element konfiguriert wurde.

### 2.1 **Meine Themen**

Mir zugewiesen - `assigned-user=\<User GUID>&assigned-team=\<Team GUID>` _Zugewiesener Benutzer_ - `assigned-user=\<User GUID>` _Meine Teams_ - `assigned-team=\<Team GUID>` _Angefordert von mir_ - `requester-user=\<Your GUID>` Themen _denen ich folge_ - `followed-by=me` _die mich erwähnen_ - `mentioned=me`

> **Hinweis:** Wenn Sie einen Link mit den aktiven Filtern "Thema, dem ich folge" oder "Erwähnung von mir" freigeben, werden die Themen auf dem Thema-Board des Benutzers gefiltert, dem der Benutzer folgt, und Themen, in denen der Benutzer erwähnt wurde, und nicht auf Themen, denen Sie folgen, und Themen, in denen Sie erwähnt wurden. Um Themen freizugeben, bei denen Sie erwähnt wurden, verwenden Sie bitte [Textsuche](#text-search)

_Erstellt von mir_ - `created-by=\<User GUID>`

### 2.2 **Status / Typ**

_Alle offenen Status_ - `status-type=open` _Spezifischer offener Status_ - `status-type=\<Status GUID>` _Alle geschlossenen Status_ - `status-type=closed` _Spezifischer geschlossener Status_ - `status-type=\<Status GUID>` _Typ_ - `type=\<Type GUID>`

### 2.3 **Fälligkeitsdatum**

_Überfällig_ - `due=overdue` _Alle mit Fälligkeitsdatum_ - `due=present` _Kein Fälligkeitsdatum_ - `due=none`

### 2.4 **Aktualisiert**

Mit dem Datumsfilter können Sie einen Zeitrahmen auswählen, für den die Themen zuletzt aktualisiert wurden. _Aktualisiert_ - `updated-from=\<Epoch Unix Timestamp>&updated-to=\<Epoch Unix Timestamp>` Lesen Sie [diesen](https://support.catenda.com/en/articles/6511685-date-filter) Artikel, um zu erfahren, wie Sie Datumsangaben auf der Seite leicht auswählen können.

### 2.5 **Zugewiesen an / Angefordert von**

_Niemandem zugewiesen_ - `assigned=unassigned` _Keinem Team zugewiesen_ - `assigned-team=unassigned` _Dem Team zugewiesen_ - `assigned-team=\<Team GUID>` _Nicht dem Benutzer zugewiesen_ - `assigned-user=unassigned` _Dem Benutzer zugewiesen_ - `assigned-user=\<User GUID>` Zuweisungsoperator - `assigned-op=and` Standardmäßig können Sie nur nach dem zugewiesenen Benutzer ODER dem zugewiesenen Team suchen. In Catenda Hub können Sie einen Bevollmächtigten als user@team festlegen. Um alle Themen dieses Typs zu finden\*\*,\*\* filtern Sie nach dem Team und dem Benutzer und fügen Sie &assigned-op=and am Ende der URL hinzu.

_Nicht angefordert_ - `requester=unassigned` _Nicht von Team angefordert_ - `requester-team=unassigned` _Nicht von Benutzer angefordert_ - `requester-user=unassigned` _Von Benutzer angefordert_ - `requester-user=\<User GUID>`

### 2.6 **Erstellt von**

_Vom Benutzer erstellt_ - `created-by=\<User GUID>`

### 2.7 **Meilenstein**

_Meilenstein_ - `milestone=\<Milestone GUID>`

### 2.8 **Benutzerdefiniertes Feld**

_Benutzerdefiniertes Feld hat Wert_ - `custom-field-has-value-\<Custom field GUID>=true` Mit der Option "Hat Wert" im Filtermenü können alle Themen gefiltert werden, bei denen ein Wert für dieses benutzerdefinierte Feld konfiguriert ist. Benutzerdefinierte Feldtypen, die auf "Hat Wert" gefiltert werden können: Datum Dezimal Dropdown Ganzzahl Text

_Benutzerdefiniertes Feld spezifischer Wert_ - `custom-field-item-\<Custom field GUID>=\<Value GUID>` Benutzerdefinierte Feldtypen, die im Filtermenü auf spezifischen Wert gefiltert werden können: Dropdown

Einige Werte in benutzerdefinierten Feldern, bei denen Werte konfiguriert werden können, können gefiltert werden. Filtern Sie nach Werten, indem Sie eine Suchphrase in der Such- oder Filterleiste eingeben und das entsprechende benutzerdefinierte Feld auswählen. Benutzerdefinierte Feldtypen, die durch Eingabe in der Such- oder Filterleiste gefiltert werden können: Dezimal Dropdown Ganzzahl Text

_Benutzerdefiniertes Feld hat keinen Wert_ - `custom-field-has-value-\<Custom field GUID>=false` Filtern Sie alle Themen, bei denen ein benutzerdefiniertes Feld keinen Wert hat. Benutzerdefinierte Feldtypen, die auf "Kein Wert" gefiltert werden können: Datum Dezimal Dropdown Ganzzahl Text

> **Hinweis:** Benutzerdefinierte Felder, die als erforderlich festgelegt sind, haben immer einen Wert. Sie können daher nicht nach "Hat Wert" oder "Hat keinen Wert" suchen und können daher nicht nach einem benutzerdefinierten Feld suchen, das als erforderlich festgelegt ist.

### 2.9 **Etikett**

_Etikett_ - `label=\<Label GUID>` Etiketten in ihrer eigenen Etikettgruppe werden in einer separaten Liste angezeigt.

### 2.10 **Links**

Verlinkt - `associations=exists` Filtern Sie Themen, die mit Modellobjekten im 3D-Viewer verlinkt sind.

Nicht verlinkt - `associations=does-not-exist` Filtern Sie Themen, die nicht mit Modellobjekten im 3D-Viewer verlinkt sind.

Mit ausgewählten Objekten verlinkt - `link=backlink` Wenn nicht bereits geöffnet, wird das 3D-Panel geöffnet. Wählen Sie Objekte aus einem Modell im 3D-Viewer aus, um Themen zu filtern, die mit den ausgewählten Objekten verlinkt sind.

## 3. **Filterung in der Such- oder Filterleiste**

Zusätzlich zum Filtermenü auf der linken Seite gibt es einige Funktionen, die nur über die Such- oder Filterleiste verfügbar sind. So kann die Such- oder Filterleiste aussehen, wenn sie hervorgehoben ist:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/02-filtering-in-the-search-or-filter-bar.png)

Unter der Such- oder Filterleiste wird ein Menü mit vorgeschlagenen Filtern geöffnet. Der erste Filter im Filtermenü wird vorgeschlagen, nachdem Sie das Such- oder Filtermenü hervorgehoben haben. Drücken Sie die Eingabetaste, um diesen Filter anzuwenden, oder verwenden Sie die Pfeiltasten, um zwischen den verschiedenen Filtern zu navigieren.

### 3.1 **Gespeicherte Filter**

Wenn Sie gespeicherte Filter in einem Themabrett haben, werden diese als erste verfügbare Filter im Filtermenü angezeigt und werden vorgeschlagen, sobald das Such- oder Filterfeld hervorgehoben wird:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/03-saved-filters.png)

Klicken Sie auf den Filter, um das Board nach dem gespeicherten Satz von Filtern zu filtern, denen ein Name gegeben wurde. Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über das Speichern eines Satzes von Filtern zu erfahren.

### 3.2 **Textsuche**

_Textsuche -_ `search=\<Search phrase>` Nach der Eingabe von Zeichen in die Such- oder Filterleiste ändert sich der erste vorgeschlagene Filter zur Textsuche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/04-text-search.png)

**Inhalte, die durchsucht werden können** Themantitel Themabeschreibung Themakommentare

**Großschreibung** Die Textsuche unterscheidet nicht zwischen Groß- und Kleinbuchstaben.

**Zeichenmengen** Einzelnes Zeichen Inhalte, die das gesuchte Zeichen enthalten, werden abgeglichen, es sei denn, es ist ein Unicode-Buchstabe mit einem Wert, der am Anfang des Inhalts 58 oder höher ist.

Zwei Zeichen Inhalte, die ein einzelnes Wort haben, getrennt durch ein Trennzeichen wie ein Leerzeichen, das der Suchphrase entspricht, sind in den Ergebnissen enthalten.

Drei oder mehr Zeichen Inhalte, die der Suchphrase in irgendeinem Teil des Inhalts entsprechen, sind in den Ergebnissen enthalten.

**Leerzeichen** Leerzeichen am Anfang einer Suchphrase werden entfernt.

**Suche nach erwähnten Mitgliedern oder Teams** Themen, bei denen ein Mitglied oder Team in einem Kommentar oder einer Beschreibung erwähnt wurde, können mit der Textsuche gefunden werden:

Mitglieds- oder Teamname Suchen Sie nach dem Namen des Mitglieds oder Teams, um alle einfachen Textvorkommen dieses Mitglieds- oder Teamnamens zu finden.

Erwähntes Mitglied Suchen Sie nach der E-Mail eines Mitglieds, um alle einfachen Textvorkommen dieser Mitglieds-E-Mail zu finden. Dies schließt Orte ein, an denen sie erwähnt wurden. Suchen Sie nach `#[\<Email of member>]`, um nur die Vorkommen zu finden, bei denen dieses Mitglied erwähnt wird.

Erwähntes Team Erwähnte Teams können durch Suche nach der GUID dieses Teams durchsucht werden. Um die GUID eines Teams zu finden, gehen Sie zur [Inhaltsseite dieses Teams](https://support.catenda.com/en/articles/7891755-team-page), indem Sie auf seinen Namen auf der [Registerkarte "Teams" der Seite "Mitglieder und Teams"](https://support.catenda.com/en/articles/4670291-members-and-teams-page) klicken. Die URL sollte ungefähr so aussehen: [https://hub.catenda.com/project/\<Project](https://hub.catenda.com/project/<Project) GUID>/members/\<Member GUIID>

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/05-text-search.png)

Suchen Sie nach der Team-GUID, um alle einfachen Textvorkommen dieser Team-GUID zu finden. Dies schließt Orte ein, an denen sie erwähnt wurden. Suchen Sie nach `#[\<team GUID>]`, um nur die Vorkommen zu finden, bei denen dieses Team erwähnt wird.

### 3.3 **Benutzerdefinierte Felder - Text**

Wenn eine Suchphrase mit einem Unicode-Zeichen beginnt, das einen Unicode-Wert hat, der 58 oder höher ist, werden die folgenden Filter am unteren Ende der Liste der vorgeschlagenen Filter angezeigt.

_Benutzerdefiniertes Textfeld -_ `custom-field-\<Custom field GUID>=\<Search phrase>` Wenn ein benutzerdefiniertes Textfeld in dem Themabrett aktiviert ist, kann der Inhalt von benutzerdefinierten Textfeldern in allen Themen des Bretts mit diesem Filter gefiltert werden.

### 3.4 **Zahlensuchphrase**

Wenn eine Suchphrase mit einem Unicode-Zeichen beginnt, das einen Unicode-Wert zwischen 33 und 57 hat, werden die folgenden Filter am unteren Ende der Liste der vorgeschlagenen Filter angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/06-number-search-phrase.png)

Dies umfasst die folgenden Zeichen: `!`,`"`,`#`,`$`,`%`,`&`,`'`,`(`,`)`,`\*`,`+`,`,`,`-`,`.`,`/`,`0`,`1`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`

_Thema -_ `issues=\<issue number>` Wenn eine Suchphrase mit einer Zahl beginnt, wird die Themennummernsuche als Vorschlag in der Such- oder Filterleiste angezeigt. Der vorgeschlagene Filter kann ungefähr so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/07-number-search-phrase.png)

Obwohl es möglich ist, ein Board nach Themennummern mit mehr als nur Zahlen zu filtern, können Themen mit diesem Filter nur mit ihrer Nummer gefunden werden. Wenn mehr als nur Zahlen bereitgestellt werden, verschwindet der Filter aus dem Menü, aber das Board wird immer noch nach der eingegebenen Phrase gefiltert.

Filterung nach einer oder mehreren Themen nach Nummer Es ist nur möglich, jeweils ein Thema in der Such- oder Filterleiste zu durchsuchen. Wenn das Thema mit der Catenda-Themennummer 123 im Board vorhanden ist, hat die URL `&issues=123` darin, wenn sie nach Themennummer 123 gefiltert wird. Es ist möglich, mehr Themennummern in die URL einzugeben. Beispiel: `&issues123,124,125` würde dazu führen, dass alle drei Themen angezeigt werden, falls sie im Board vorhanden sind. Die Filterung nach mehreren Themen auf diese Weise ist nur durch Bearbeitung der URL möglich.

### 3.5 **Benutzerdefinierte Felder - Zahl**

_Benutzerdefiniertes Ganzzahlfeld -_ `custom-field-\<Custom field GUID>=\<Search phrase>` Wenn ein benutzerdefiniertes Ganzzahlfeld in dem Themabrett aktiviert ist, kann der Inhalt von benutzerdefinierten Ganzzahlfeldern in allen Themen des Bretts mit diesem Filter gefiltert werden.

_Benutzerdefiniertes Dezimalfeld -_ `custom-field-\<Custom field GUID>=\<Search phrase>` Wenn ein benutzerdefiniertes Dezimalfeld in dem Themabrett aktiviert ist, kann der Inhalt von benutzerdefinierten Dezimalfeldern in allen Themen des Bretts mit diesem Filter gefiltert werden.

### 3.6 **Benutzerdefinierte Felder - Dropdown**

Wenn eine Suchphrase mit dem Namen eines Wertes in einem Filter übereinstimmt, wird der beste übereinstimmende Filter im Vorschlagsfeld vorgeschlagen.

_Benutzerdefiniertes Dropdown-Feld_ _-_ `custom-field-item-\<Custom field GUID>=\<Dropdown value GUID>` Wenn die Suchphrase mit einem Wert in einem benutzerdefinierten Dropdown-Feld mit bis zu 10 Werten übereinstimmt, wird vorgeschlagen, nach diesem Dropdown-Wert zu suchen.
