# Filterung auf der Genehmigungsseite - Erbschaft

Das Filterpanel kann auf der Genehmigungsseite geöffnet werden, indem Sie auf die Filterschaltfläche links neben der Suchleiste auf der [Genehmigungsseite](https://support.catenda.com/en/articles/8349340-approvals-page) klicken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vcqjvqcc/01-intro.png)

Dieser Artikel enthält Informationen zu den folgenden Themen

## 1. **Filter**

Klicken Sie auf die Filterschaltfläche oben links, um ein Panel auf der linken Seite anzuzeigen. Wenn ein Filter angewendet wird, ändert sich die im Browser sichtbare URL entsprechend. In diesem Artikel werden Filter wie folgt angezeigt: _Filtername im Menü_ - `Filtername in URL=Filteroption in URL`

**Standardfilter** Der Standardfilter ist in der URL zunächst nicht sichtbar. Wenn die Seite zum ersten Mal aufgerufen wird, wird der folgende Filter angewendet. _Kein Filter_ - `state=all`

### 1.1 **Aktuellen Filter speichern und freigeben**

Navigieren Sie zur URL einer gefilterten Seite, um diese Seite mit angewendetem Filter zu laden. Die angewendeten Filter können oben im Filtermenü gespeichert werden. Klicken Sie [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link), um mehr darüber zu erfahren, wie Sie Filter speichern und freigeben können

### 1.2 **Leere Filter ausblenden**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über die Einschränkung von Filterergebnissen zu erfahren.

### 1.3 **Meine Genehmigungen**

_Ich bin Herausgeber_ - `publisher=<Member GUID>` _Von mir erstellt_ - `created-by=<Member GUID>`

### 1.4 **Status**

_Offen_ - `state=pending` - Standard _Veröffentlicht_ - `state=published` _Verworfen_ - `state=discarded`

### 1.5 **Prüfer**

_Mitgliedername_ - `reviewers=<Member GUID>`

### 1.6 **Fälligkeit**

_Überfällig_ - `due=overdue` _Weniger als ein Tag_ - `due=2d` _Weniger als eine Woche_ - `due=1w` _Weniger als zwei Wochen_ - `due=2w` _Weniger als einen Monat_ - `due=1m` _Alle mit Fälligkeit_ - `due=present` _Keine Fälligkeit_ - `due=none`

### 1.7 **Textsuche**

_Textsuche -_ `search=<Search phrase>`

**Inhalte, die durchsucht werden können** Titel der Genehmigungsanfrage

**Großschreibung** Die Textsuche unterscheidet nicht zwischen Groß- und Kleinbuchstaben.

**Zeichenmenge** Beliebig viele Zeichen Inhalte, die den gesuchten Ausdruck enthalten, werden abgeglichen.
