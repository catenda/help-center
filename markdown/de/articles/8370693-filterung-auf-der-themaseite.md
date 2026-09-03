# Filterung auf der Seite „Themen

Das Filtermenü in einem Themen-Board kann durch Klicken auf die Schaltfläche "Filter" links neben der Suchleiste in einem [Themen-Board](https://support.catenda.com/en/articles/4670271-issues-page) geöffnet werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/01-intro.png)

## 1. **Filter**

Klicken Sie oben links auf die Filterschaltfläche, um ein Bedienfeld auf der linken Seite anzuzeigen. Wenn ein Filter angewendet wird, ändert sich die im Browser sichtbare URL damit. In diesem Artikel werden Filter wie folgt angezeigt: _Filtername im Menü_ - `Filtername in der URL=Filteroption in der URL`

**Standardfilter** Der Standardfilter ist anfangs in der URL nicht sichtbar. Wenn die Seite zum ersten Mal aufgerufen wird, wird der folgende Filter angewendet. _Kein Filter_ - `status-type=all`

### 1.1 **Aktuellen Filter speichern und freigeben**

Gehen Sie zur URL einer gefilterten Seite, um diese Seite mit dem angewendeten Filter zu laden. Die angewendeten Filter können oben im Filtermenü gespeichert werden. Klicken Sie [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link), um mehr darüber zu erfahren, wie Sie Filter speichern und freigeben

### 1.2 **Leere Filter ausblenden**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über die Begrenzung der Filterergebnisse zu erfahren.

## 2. **Filterung im Filtermenü**

Hier finden Sie die folgenden Filter:

Die verschiedenen Filter im Filtermenü werden nur angezeigt, wenn es Themen gibt, bei denen das gefilterte Element konfiguriert wurde.

### 2.1 **Meine Themen**

Mir zugewiesen - `assigned-user=<User GUID>&assigned-team=<Team GUID>` _Benutzer zugewiesen_ - `assigned-user=<User GUID>` _Meine Teams_ - `assigned-team=<Team GUID>` _Mir angefordert_ - `requester-user=<Your GUID>` Themen _denen ich folge_ - `followed-by=me` _mich erwähnen_ - `mentioned=me`

> **Hinweis:** Wenn Sie einen Link mit den aktiven Filtern "Thema, das ich folge" oder "Erwähnung durch mich" freigeben, werden der Benutzer, der den Link öffnet, sein Themen-Board für Themen gefiltert haben, denen er folgt, und Themen, in denen er erwähnt wurde, und nicht für Themen, denen Sie folgen, und Themen, in denen Sie erwähnt wurden. Um Themen freizugeben, in denen Sie erwähnt wurden, verwenden Sie bitte [Textsuche](#h_7fc30a16f0)

_Erstellt von mir_ - `created-by=<User GUID>`

### 2.2 **Status/Typ**

_Alle offenen Status_ - `status-type=open` _Spezifischer offener Status_ - `status-type=<Status GUID>` _Alle geschlossenen Status_ - `status-type=closed` _Spezifischer geschlossener Status_ - `status-type=<Status GUID>` _Typ_ - `type=<Type GUID>`

### 2.3 **Fälligkeitsdatum**

_Überfällig_ - `due=overdue` _Alle mit Fälligkeitsdatum_ - `due=present` _Kein Fälligkeitsdatum_ - `due=none`

### 2.4 **Aktualisiert**

Mit dem Datumsfilter können Sie einen Zeitraum auswählen, in dem die Themen zuletzt aktualisiert wurden. _Aktualisiert_ - `updated-from=<Epoch Unix Timestamp>&updated-to=<Epoch Unix Timestamp>` Lesen Sie [diesen](https://support.catenda.com/en/articles/6511685-date-filter) Artikel, um zu erfahren, wie Sie auf der Seite einfach Daten auswählen können.

### 2.5 **Zugewiesen zu / Angefordert von**

_Niemandem zugewiesen_ - `assigned=unassigned` _Kein Team zugewiesen_ - `assigned-team=unassigned` _Dem Team zugewiesen_ - `assigned-team=<Team GUID>` _Nicht dem Benutzer zugewiesen_ - `assigned-user=unassigned` _Dem Benutzer zugewiesen_ - `assigned-user=<User GUID>` Zuweisungsoperator - `assigned-op=and` Standardmäßig können Sie nur nach dem zugewiesenen Benutzer ODER dem zugewiesenen Team suchen. In Catenda Hub können Sie einen Verantwortlichen als user@team festlegen. Um alle Themen dieser Art zu finden**,** filtern Sie nach dem Team und dem Benutzer und fügen Sie &assigned-op=and am Ende der URL hinzu.

_Nicht angefordert_ - `requester=unassigned` _Nicht vom Team angefordert_ - `requester-team=unassigned` _Nicht vom Benutzer angefordert_ - `requester-user=unassigned` _Vom Benutzer angefordert_ - `requester-user=<User GUID>`

### 2.6 **Erstellt von**

_Vom Benutzer erstellt_ - `created-by=<User GUID>`

### 2.7 **Meilenstein**

_Meilenstein_ - `milestone=<Milestone GUID>`

### 2.8 **Benutzerdefiniertes Feld**

_Benutzerdefiniertes Feld hat Wert_ - `custom-field-has-value-<Custom field GUID>=true` Mit der Option "hat Wert" im Filtermenü können alle Themen gefiltert werden, deren benutzerdefiniertes Feld einen konfigurierten Wert hat. Benutzerdefinierte Feldtypen, die nach "hat Wert" gefiltert werden können: Datum Dezimal Dropdown Ganzzahl Text

_Benutzerdefiniertes Feld spezifischer Wert_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Benutzerdefinierte Feldtypen, die nach spezifischem Wert aus dem Filtermenü gefiltert werden können: Dropdown

Einige Werte in benutzerdefinierten Feldern, in denen Werte konfiguriert werden können, können gefiltert werden. Filtern Sie nach Werten, indem Sie einen Suchausdruck in der Such- oder Filterleiste eingeben und das entsprechende benutzerdefinierte Feld auswählen. Benutzerdefinierte Feldtypen, die durch Eingabe in der Such- oder Filterleiste gefiltert werden können: Dezimal Dropdown Ganzzahl Text

_Benutzerdefiniertes Feld hat keinen Wert_ - `custom-field-has-value-<Custom field GUID>=false` Filtern Sie alle Themen, bei denen ein benutzerdefiniertes Feld keinen Wert hat. Benutzerdefinierte Feldtypen, die nach "hat keinen Wert" gefiltert werden können: Datum Dezimal Dropdown Ganzzahl Text

> **Hinweis:** Benutzerdefinierte Felder, die als erforderlich festgelegt sind, haben immer einen Wert. Sie können daher nicht nach "hat Wert" oder "hat keinen Wert" suchen und können daher nicht nach einem benutzerdefinierten Feld suchen, das als erforderlich festgelegt ist.

### 2.9 **Etikett**

_Etikett_ - `label=<Label GUID>` Etiketten in ihrer eigenen Etikettgruppe werden in einer separaten Liste angezeigt.

### 2.10 **Links**

Verlinkt - `associations=exists` Filtern Sie nach Themen, die mit Modelobjekten im 3D-Viewer verlinkt sind.

Nicht verlinkt - `associations=does-not-exist` Filtern Sie nach Themen, die nicht mit Modelobjekten im 3D-Viewer verlinkt sind.

Zu ausgewählten Objekten verlinkt - `link=backlink` Wenn das 3D-Panel nicht bereits geöffnet ist, wird es geöffnet. Wählen Sie Objekte aus einem Modell im 3D-Viewer aus, um nach Themen zu filtern, die mit den ausgewählten Objekten verlinkt sind.

## 3. **Filtern in der Such- oder Filterleiste**

Zusätzlich zum Filtermenü auf der linken Seite gibt es einige Funktionen, die nur über die Such- oder Filterleiste verfügbar sind. Wenn die Such- oder Filterleiste hervorgehoben ist, könnte sie so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/02-filtering-in-the-search-or-filter-bar.png)

Unter der Such- oder Filterleiste wird ein Menü mit vorgeschlagenen Filtern geöffnet. Der erste Filter im Filtermenü wird vorgeschlagen, nachdem die Such- oder Filterleiste hervorgehoben wurde. Drücken Sie die Eingabetaste, um diesen Filter anzuwenden, oder verwenden Sie die Pfeiltasten, um zwischen den verschiedenen Filtern zu navigieren.

### 3.1 **Gespeicherte Filter**

Wenn Sie gespeicherte Filter in einem Themen-Board haben, sind diese der erste verfügbare Filter im Filtermenü und werden vorgeschlagen, sobald die Such- oder Filterbox hervorgehoben wird:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/03-saved-filters.png)

Klicken Sie auf den Filter, um das Board nach dem gespeicherten Satz von Filtern zu filtern, denen ein Name gegeben wurde. Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr darüber zu erfahren, wie Sie einen Satz von Filtern speichern.

### 3.2 **Text-Suche**

_Text-Suche -_ `search=<Search phrase>` Nach Eingabe von Zeichen in die Such- oder Filterleiste ändert sich der erste vorgeschlagene Filter zur Text-Suche.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/04-text-search.png)

**Inhalt, der durchsucht werden kann** Themantitel Themabeschreibung Themakommentare

**Großschreibung** Die Text-Suche unterscheidet nicht zwischen Groß- und Kleinbuchstaben.

**Zeichenanzahl** Einzelnes Zeichen Inhalte, die das gesuchte Zeichen enthalten, werden abgeglichen, es sei denn, es ist ein Unicode-Buchstabe mit einem Wert von 58 oder höher am Anfang des Inhalts.

Zwei Zeichen Inhalte mit einem einzelnen Wort, getrennt durch ein Trennzeichen wie ein Leerzeichen, das dem Suchausdruck entspricht, sind in den Ergebnissen enthalten.

Drei oder mehr Zeichen Inhalte, die dem Suchausdruck überall im Inhalt entsprechen, sind in den Ergebnissen enthalten.

**Leerzeichen** Leerzeichenzeichen am Anfang eines Suchausdrucks werden entfernt.

**Suche nach erwähnten Mitgliedern oder Teams** Themen, in denen ein Mitglied oder Team in einem Kommentar oder einer Beschreibung erwähnt wurde, können mit der Text-Suche gefunden werden:

Mitglieds- oder Teamname Suchen Sie nach dem Namen des Mitglieds oder Teams, um alle reinen Textvorkommen dieses Mitglieds oder Teams zu finden.

Erwähntes Mitglied Suchen Sie nach der E-Mail eines Mitglieds, um alle reinen Textvorkommen dieser Mitglieds-E-Mail zu finden. Dies umfasst auch die Stellen, an denen es erwähnt wurde. Suchen Sie nach `#[<Email of member>]`, um nur die Vorkommen zu finden, an denen dieses Mitglied erwähnt wird.

Erwähntes Team Erwähnte Teams können durch Suche nach der GUID dieses Teams durchsucht werden. Um die GUID eines Teams zu finden, gehen Sie zur [Seite des Teams](https://support.catenda.com/en/articles/7891755-team-page), indem Sie auf dessen Namen auf der [Registerkarte Teams der Seite Mitglieder und Teams](https://support.catenda.com/en/articles/4670291-members-and-teams-page) klicken. Die URL sollte etwa so aussehen: [https://hub.catenda.com/project/\<Project](https://hub.catenda.com/project/<Project) GUID>/members/\<Member GUIID>

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/05-text-search.png)

Suchen Sie nach der Team-GUID, um alle reinen Textvorkommen dieser Team-GUID zu finden. Dies umfasst auch die Stellen, an denen es erwähnt wurde. Suchen Sie nach `#[<team GUID>]`, um nur die Vorkommen zu finden, an denen dieses Team erwähnt wird.

### 3.3 **Benutzerdefinierte Felder - Text**

Wenn ein Suchausdruck mit einem Unicode-Zeichen mit einem Unicode-Wert von 58 oder höher beginnt, werden die folgenden Filter am unteren Ende der Liste der vorgeschlagenen Filter angezeigt.

_Text benutzerdefiniertes Feld -_ `custom-field-<Custom field GUID>=<Search phrase>` Wenn ein Text-Benutzerdefiniertes Feld im Themen-Board aktiviert ist, kann der Inhalt von Text-Benutzerdefinierten Feldern in allen Themen im Board mit diesem Filter gefiltert werden.

### 3.4 **Zahlensuchausdruck**

Wenn ein Suchausdruck mit einem Unicode-Zeichen mit einem Unicode-Wert zwischen 33 und 57 beginnt, werden die folgenden Filter am unteren Ende der Liste der vorgeschlagenen Filter angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/06-number-search-phrase.png)

Dies umfasst die folgenden Zeichen: `!`,`"`,`#`,`$`,`%`,`&`,`'`,`(`,`)`,`*`,`+`,`,`,`-`,`.`,`/`,`0`,`1`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`

_Thema -_ `issues=<issue number>` Wenn ein Suchausdruck mit einer Zahl beginnt, wird die Thema-Zahlensuche als Vorschlag in der Such- oder Filterleiste angezeigt. Der vorgeschlagene Filter könnte etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/07-number-search-phrase.png)

Obwohl es möglich ist, ein Board nach Themenummern mit mehr als nur Zahlen zu filtern, können Themen nur mit ihrer Nummer mit diesem Filter gefunden werden. Wenn mehr als nur Zahlen angegeben werden, wird der Filter aus dem Menü ausgeblendet, das Board wird jedoch weiterhin nach dem eingegebenen Ausdruck gefiltert.

Filtern nach einer oder mehreren Themen nach Nummer Es ist nur möglich, jeweils ein Thema aus der Such- oder Filterleiste zu durchsuchen. Wenn das Thema mit der Catenda-Themenummer 123 im Board vorhanden ist, hat die URL `&issues=123`, wenn Sie nach Themenummer 123 filtern. Es ist möglich, weitere Themenummern in der URL einzugeben, zum Beispiel: `&issues123,124,125` würde alle drei Themen anzeigen, wenn sie im Board vorhanden sind. Das Filtern nach mehreren Themen auf diese Weise ist nur durch Bearbeiten der URL möglich.

### 3.5 **Benutzerdefinierte Felder - Zahl**

_Ganzzahl benutzerdefiniertes Feld -_ `custom-field-<Custom field GUID>=<Search phrase>` Wenn ein Ganzzahl-Benutzerdefiniertes Feld im Themen-Board aktiviert ist, kann der Inhalt von Ganzzahl-Benutzerdefinierten Feldern in allen Themen im Board mit diesem Filter gefiltert werden.

_Dezimal benutzerdefiniertes Feld -_ `custom-field-<Custom field GUID>=<Search phrase>` Wenn ein Dezimal-Benutzerdefiniertes Feld im Themen-Board aktiviert ist, kann der Inhalt von Dezimal-Benutzerdefinierten Feldern in allen Themen im Board mit diesem Filter gefiltert werden.

### 3.6 **Benutzerdefinierte Felder - Dropdown**

Wenn ein Suchausdruck mit dem Namen eines Wertes in einem Filter übereinstimmt, wird der beste Filter in der Suggestionbox vorgeschlagen.

_Dropdown benutzerdefiniertes Feld_ _-_ `custom-field-item-<Custom field GUID>=<Dropdown value GUID>` Wenn der Suchausdruck mit einem Wert in einem Dropdown-Benutzerdefinierten Feld mit bis zu 10 Werten übereinstimmt, wird vorgeschlagen, nach diesem Dropdown-Wert zu suchen.
