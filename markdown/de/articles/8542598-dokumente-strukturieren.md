# Dokumente strukturieren

Es gibt mehrere Möglichkeiten, Ihre Ordner und Dokumente zu strukturieren und zu benennen. Je nach Art Ihres Projekts funktionieren unterschiedliche Strukturen und Namenskonventionen für Sie besser als andere. Dieser Artikel enthält einige hilfreiche Tipps bei der Entscheidung, wie Sie Ihre Datenumgebung einrichten.

## 1. **Elementnamen**

Es gibt mehrere Faktoren, die beeinflussen können, wie Elemente in einer Struktur benannt werden. Erkennbarkeit und Pfadlänge sind oft wichtige Faktoren.

### 1.1 **Eigentümerschaft**

Die Person, die den Namen festlegt, ist oft mit dem Inhalt des benannten Elements vertraut.

**Persönliche Dokumente** Beim Benennen von Elementen für persönliche Nutzung ist oft eine persönliche Benennungsweise am besten, da die Person, die das Dokument benennt, das Element später leicht durch Suche finden kann. Auch die Person, die das Element benennt, kann später Schwierigkeiten haben, ihre eigenen Informationen wiederzufinden.

**Kollaborationsdokumente** Beim Benennen von Elementen für die Zusammenarbeit werden mehrere Personen mit den verschiedenen Elementen arbeiten. Die Namen von Ordnern sind daher in Projekten oft vordefiniert, damit sie über verschiedene Projekte eines bestimmten Typs hinweg erkannt werden können, die zur selben Organisation gehören.

**Mindestanforderungen** Mindestanforderungen für die Dokumentbenennung werden oft vereinbart. Da verschiedene Wörter für verschiedene Personen unterschiedliche Bedeutungen haben können, ist es oft wichtig, mit dem Team zu diskutieren, wie Elemente benannt werden sollen, damit alle wissen, wie Elemente benannt und worauf gesucht werden soll.

### 1.2 **Namensschemas**

Die Befolgung bewährter Praktiken für die Benennung von Dokumenten ist immer hilfreich, aber jeder hat seine eigenen Vorlieben. Eine Benennungsstrategie, die für Sie sinnvoll ist, ist nicht immer für andere sinnvoll.

**Team-weit gültige Namensschemas** Innerhalb eines Teams einigen sich Mitwirkende an einer Dateistruktur oft auf ein Namensschema. Dies kann eine mündliche Anregung sein, z. B. Menschen aufzufordern, das Datum in den Namen einzufügen, oder es kann erzwungen werden, indem eine [Namenskonvention](https://support.catenda.com/en/articles/7832559-naming-conventions-page) erstellt wird, nach der Personen ihre Dateien benennen müssen, um sie überhaupt hochladen zu können.

**Projektweite Namensschemas** In einer gemeinsamen Datenumgebung kommen oft mehrere Teams zusammen. Teams haben möglicherweise noch keine Benennungsregel eingeführt oder sind nicht bereit, ihre zu ändern, aber wenn sie ihre Dokumente bereits sehr lange auf eine bestimmte Weise benannt haben, kann es schwierig sein, sie zu etwas anderem zu überreden. In diesem Fall ist eine gute Lösung, es Personen zu ermöglichen, Dateien mit ihrem bevorzugten Namen hochzuladen, solange sie den Namen des Dokuments, das die Datei enthält, in die vom Projekt vereinbarte Konvention ändern. Auf diese Weise können Teammitglieder ihr Dokument anhand des [ursprünglichen Namens der Datei](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page) finden, während ein Projektmitglied es anhand seines [Dokumentnamens](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page) finden kann.

### 1.3 **Namenslänge**

Deskriptiv zu sein und vollständige Wörter auszuschreiben kann dabei helfen, da Sie das Wort lesen und auf einen Blick den Inhalt des Dokuments verstehen können. Das bedeutet jedoch nicht, dass der Dokumentname ein vollständiger Satz sein sollte. Dokumentnamen, die zu lang zum Lesen sind, können wie eine Textwand aussehen und werden schnell überblättert. Es wird daher empfohlen, Namen auf 1 bis 5 Wörter zu begrenzen.

**Externe Einschränkungen** Innerhalb von Catenda können Ordnerstrukturen beliebiger Pfadlänge importiert und exportiert werden. Andere Software, mit der diese Informationen ausgetauscht werden, kann Beschränkungen für die Gesamtanzahl der Zeichen der übergeordneten Ordner und des Dokumentnamens haben, die den Pfad zu einem Dokument innerhalb der Struktur bilden. ZIP-Dateien werden häufig zum Austausch von Ordnerstrukturen verwendet. Unter Windows beträgt die Pfadlänge für ZIP-Dateien beispielsweise 260 Zeichen. In OneDrive und SharePoint wird diese Grenze erhöht, ist aber auf 400 Unicode-Einheiten begrenzt.

### 1.4 **Versionskontrolle**

Eine typische Situation, in die Menschen geraten, ist, dass sie ihr Dokument etwa so nennen:

**Presentation\_Final** Wenn sie dann eine Änderung vornehmen müssen, wird es zu: _Presentation\_Final\_Final, Final\_Final\_For real, Final\_LastOneIPromise._ Dann geben Sie auf und nennen die nächste einfach: _Presentation\_Submitted_ Diese Situation kann vermieden werden, indem man sich von Anfang an auf eine Versionierungskonvention einigt. Sie könnten Ihre Datei mit _Presentation\_v1_, _Presentation\_v2_ usw. beginnen. Dies stellt sicher, dass verschiedene Versionen derselben Datei in logischer Reihenfolge vorliegen. Obwohl es auf Catenda ein gutes Revisionssystem gibt, kann es dennoch sinnvoll sein, eine Versionsnummer hinzuzufügen. Manchmal unterscheidet sich Ihre lokale Revisionszählung von der hochgeladenen. Angenommen, Sie haben v3 der Präsentation hochgeladen, aber die nächste, die Sie hochgeladen haben, war v5. Die Revision auf Catenda wird um eins inkrementiert, während Ihre lokale Revision um 2 inkrementiert wurde. Auf diese Weise können Sie nachverfolgeln, welche Version die richtige ist.

### 1.5 **Informationen trennen**

Historisch gesehen hatten Systeme Probleme mit Leerzeichen in Dokumentnamen. Während viele Systeme heutzutage mit Leerzeichen in Dokumentnamen umgehen können, gibt es möglicherweise immer noch Gründe, Leerzeichen aus Dokumentnamen zu entfernen. Sie möchten möglicherweise nach zwei Wörtern zusammen suchen können, die nicht zwei separate Wörter sind. Sie könnten auch hoffen, die Anzahl der Zeichen in einem Namen zu verringern, indem Sie die Leerzeichen entfernen. Wenn Sie einen normalen Dateinamen wie diesen nehmen:

**this is a normal file name that is very long with many words.png** und Sie entfernen die Leerzeichen, wird es zu einem unlesbaren Durcheinander, da Sie visuelle Hinweise benötigen, wo die Wortgrenzen liegen:

**thisisanormalfilenamethatisverylongwithmanywords.png** Wenn Kompression Ihr Ziel ist, möchten Sie kein weiteres Zeichen einführen, um jedes Wort zu trennen, da Sie zur gleichen Länge wie zuvor zurückkehren würden. Stattdessen können Sie jeden Buchstaben großschreiben.

**ThisIsANormalFileNameThatIsVeryLongWithManyWords.png** Obwohl dies bereits etwas besser ist, ist es bei längeren Namen immer noch ziemlich schwer zu lesen. Wenn das Ziel darin besteht, Platz zu sparen, können Sie versuchen, zusammengehörige Wörter zu gruppieren:

**ThisIs\_ANormalFileName\_ThatIs\_VeryLong\_WithManyWords.png** Jetzt beginnen wir, uns in das Gebiet eines guten, kurzen, lesbaren Dateinamens zu begeben. Auch wenn die Dateilänge keinen Sinn macht, ist es sinnvoll, über die Komprimierung von Wörtern auf diese Weise nachzudenken, da es einfacher ist, gruppierte Wörter auf einen Blick zu verstehen. Wenn Sie sich nicht kümmern, wie lange Ihr Dateiname wird, können Sie folgendes tun, um es noch besser zu machen: Führen Sie einen sekundären Trennzeichen ein. Sehen Sie hier, wie gruppierte Wörter auf eine Weise getrennt werden, während die Wörter in jeder Gruppe auf andere Weise getrennt werden.

**This-is\_A-normal-File-name\_That-is\_Very-long\_With-many-words.png** Beachten Sie, dass es durch das Trennen jedes Wortes möglich war, jeden ersten Buchstaben zu großschreiben und die nächsten kleinzuschreiben.

### 1.6 **Informationen komprimieren**

In Fällen, in denen es viele verschiedene Dokumente gibt, die sich alle geringfügig unterscheiden, macht es keinen Sinn, die gleichen 4 Wörter immer wieder zu wiederholen, nur um eine Variation im 5. Wort hinzuzufügen. In diesem Fall möchten Sie möglicherweise eine Abkürzung für jedes Wort verwenden. Beispiel: _Architecture_ kann sich in _ARC_ umwandeln, erstes Stockwerk kann sich in 1st. umwandeln. Die Tatsache, dass Sie auf diese Weise mehr Informationen auf weniger Platz haben können, ist sowohl eine Stärke als auch eine Schwäche. Obwohl es leicht ist, mit den Dateiinformationen 100% korrekt zu sein, ist dies nicht immer die beste Art, Ihre Dateien zu benennen. Wenn Sie Abkürzungen hinzufügen, werden Ihre Dateinamen schnell zu einem unlesbaren Durcheinander. Nehmen Sie zum Beispiel: _20110101\_ARC\_BLDG1\_BLCK2\_FLR4\_Q4\_Wa3\_Win4\_S\_C\_v4_ Obwohl es für den Dateiautor sinnvoll sein könnte, dass dies eine Datei vom 1. Januar 2011 über die vierte Version einer Betonschwelle in Fenster 4 an Wand 3 auf Etage 4 in Block 2 in Gebäude 1 des Architekten war. Ich bin mir ziemlich sicher, dass niemand sonst im Projekt sich die Zeit nehmen wird, es zu lesen. Besonders nicht, wenn das, wonach der Suchende wirklich suchte, war:

**20110101\_ARC\_BLDG1\_BLCK1\_FLR4\_Q4\_Wa2\_Win3\_S\_C\_V4** Dies ist eine völlig andere Fensterbank! Wenn es auf diese Ebene kommt, ist es besser, Ihre Dateien in Ordnern aufzuteilen.

### 1.7 **Sortierreihenfolge**

Der Dokumentbereich wird automatisch nach Name sortiert. Es kann daher eine gute Idee sein, einige Zeichen am Anfang des Dokuments hinzuzufügen, damit das relevanteste Dokument zuerst angezeigt wird.

**Chronologische Reihenfolge** Um einen historischen Überblick über Catenda Hub zu erhalten, können Sie jederzeit nach veröffentlicht oder erstellt sortieren. Standardmäßig werden die Dokumente nach Name sortiert. Wenn ein Mitglied einen Ordner zum ersten Mal öffnet, kann das neueste Dokument daher möglicherweise nicht oben stehen. Um diesem entgegenzuwirken, können Sie das Datum des Dokuments am Anfang des Dokuments hinzufügen: _20110101_ würde der 1. Januar 2011 sein. Dies kann auch hilfreich sein, wenn Sie Dokumente haben, die vor langer Zeit erstellt und dann in Catenda Hub importiert wurden. Obwohl dieser Name geändert werden kann, kann er nützliche Informationen sein, wenn Sie nach einem Dokument suchen. Auf diese Weise können Sie auch die Namensspalte nach Datum sortieren.

**Alphanumerische Reihenfolge** Um herauszufinden, welche Zeichen vor anderen Zeichen stehen, beziehen Sie sich bitte auf die [Sortierreihenfolge von Listen](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) auf Catenda. Um Ihre Dokumente in der Reihenfolge der Wichtigkeit zu erhalten, können Sie immer nach Etiketten oder der Anzahl der Revisionen sortieren. Standardmäßig werden die Dokumente nach Name sortiert. Wenn ein Mitglied einen Ordner zum ersten Mal öffnet, kann das wichtigste Dokument daher möglicherweise nicht oben stehen. Um diesem entgegenzuwirken, können Sie ein Zeichen am Anfang des Namens hinzufügen, das dafür sorgt, dass es zuerst angezeigt wird. Beispielsweise können Sie Ihre Dateien folgendermaßen benennen: _1.0 Most important. 1.1 Less important, 1.2 etc..._ Dann könnten Sie feststellen, dass einige Ihre Regel verletzen, indem Sie versehentlich ein Dokument mit einer 0 vorne hochladen, das am Anfang angezeigt wird. Was Sie dann tun könnten, ist, ein \_ am Anfang des Namens hinzuzufügen, um sicherzustellen, dass es vor jedem Element angezeigt wird. Dieser Kampf darüber, wer zuerst ist, kann endlos erscheinen. Es kann daher hilfreich sein, die [Sortierreihenfolge von Listen](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) anzusehen, um zu sehen, welche Zeichen vor anderen angezeigt werden, um zu sehen, was in Ihrem Fall sinnvoll ist.

## 2. **Unterordner**

Es kann schwierig sein, Informationen zu finden, wenn es viele Informationen in einer Liste gibt und Sie weit nach unten scrollen müssen, um die gesuchten Informationen zu finden.

### 2.1 **Wann Dokumente in Ordner verschieben**

Wenn es zu viele Dokumente oder Ordner in einem Ordner gibt, können sie schwer zu finden sein, da Sie weit nach unten in der Liste scrollen müssen, um das gesuchte Dokument zu finden. An diesem Punkt macht es oft Sinn, einen Unterordner in dieser Liste hinzuzufügen und die Dokumente nach ihrer wichtigsten Eigenschaft zu unterteilen.

Dies kann eine Reihe von Eigenschaften sein, wie:

**Art des Dokuments (Zeichnung, Bild, Tabellenkalkulation)**

**Verwandtes Thema (Wände und Fenster)**

**Studienbereich (ARC, MEP, STR)**

**Partei, die es hochgeladen hat (Gruppe 1, Gruppe 2, Gruppe 3)**

**Datum des Uploads (20110101, 20231225)**

**Reife (Entwurf, eingereicht, genehmigt, abgelehnt)**

Gründe, die die Entscheidung beeinflussen können, wie Sie Ihre Dokumente unterteilen, können sein:

**Erkennbarkeit**

**Zugangskontrolle**

### 2.2 **Wann Dokumente aus Ordnern verschieben**

Nach einiger Zeit mit einer Dokumentstruktur werden Sie feststellen, dass Sie viele Unterordner erstellen. Wenn es viele Klicks dauert, um in den Unterordner zu gelangen, haben Sie das Problem, das Sie mit der Erstellung von Unterordnern lösen wollten, nicht gelöst, da die Informationen immer noch schwer zu finden sind. Es wird empfohlen, bei der Erstellung von Unterordnern nicht tiefer als 3 Ebenen zu gehen. Dies liegt daran, dass sich die meisten Menschen die letzten zwei Ordner merken können, in denen sie waren, aber je tiefer Sie gehen, desto mehr vergessen Sie, woher Sie gekommen sind. Um dies zu vermeiden, können Sie Ihre Unterordner eine Ebene höher verschieben.

**Hier ist ein Beispiel für einen Ordner, der 4 Ebenen tief ist:** 01\_Models-and-drawings 0101\_Models 010101\_ARC 01010101\_Window 01010102\_Wall 010102\_MEP 01010201\_Ducts 01010202\_Vents 010103\_STR 0102\_Drawings

**Dieser Ordner kann vereinfacht werden zu:** 0101\_Models\_ARC 010101\_Window 010102\_Wall 0102\_Models\_MEP 010201\_Ducts 010202\_Vents 0103\_Models\_\_STR 0201\_Drawings

**Oder vielleicht noch simpler:** 010101\_Models\_ARC\_Window 010102\_Models\_ARC\_Wall 010201\_Models\_MEP\_Ducts 010202\_Models\_MEP\_Vents 010301\_Models\_\_STR 020101\_Drawings

Wie Sie sehen, können Sie durch Hinzufügen mehrerer ähnlicher Ordner auf der gleichen Ebene die Anzahl der Klicks verringern, die zum Abrufen des Ordners mit den gesuchten Dokumenten erforderlich sind. Eine weitere Sache, die Sie bemerken könnten, ist, dass je mehr Sie die Ordnerstruktur vereinfachen, desto länger werden die Dateinamen. Wenn Dateinamen zu lang werden, werden sie schwer zu lesen. Es ist daher wichtig, ein Gleichgewicht zwischen [Dateinamenlänge](#h_7549bd95d9) und [Ordnertiefe](#h_e27bb794b2) zu bewahren.

## 3. **Ordnerstruktur**

### 3.1 **Art des Dokuments**

In dieser Dokumentstruktur strukturieren Sie Ihre Dateien nach der Art des Dokuments. Alle Grundrisse gehen in den Grundrisse-Ordner, alle Besprechungsprotokolle gehen in den Zusammenfassungs-Ordner usw. Diese Dateistruktur ist für den Kunden einfacher zu verwenden, da alle von Beratern bereitgestellten Dateien an einem Ort zusammengefasst werden. Diese Dateistruktur ist für die Berater schwächer zu verwenden, da sie viele verschiedene Orte haben, an denen sie ihre Dateien liefern.

**Beispiel einer Dateistruktur** Ein Beispiel für diese Art von Dokumentstruktur kann sein:

0101\_Information 010101\_Admin 010102\_Contracts 0201\_Images\_Presentations YYMMDD\_Presentation-title.ppt 0202\_Images\_Site-visits YYMMDD\_Site-visit-title.jpg 0301\_2D 03010101\_Plan\_Floor 030101010101\_DWG\_ARC YYMMDD\_Drawing-title.dwg 030101010102\_DWG\_STR 030101010103\_DWG\_MEP 030101010103\_DWG\_LAN 030101010201\_PDF\_ARK YYMMDD\_Drawing-title.pdf 030101010202\_PDF\_STR 030101010203\_PDF\_MEP 030101010203\_PDF\_LAN 03010102\_Plan\_Ceiling 03010103\_Plan\_Fire-escape 03010201\_Section 03010301\_Elevation 0302\_3D 03020101\_Models\_Archicad 030201010101\_PLN\_ARC 030201010102\_PLN\_STR YYMMDD\_Drawing-title.ifc 030201010103\_PLN\_MEP 030201010104\_PLN\_LAN 030201010201\_IFC\_ARC 030201010202\_IFC\_STR 030201010203\_IFC\_MEP 030201010204\_IFC\_LAN 03020102\_Models\_Navisworks 03020103\_Models\_Revit 030201030101\_RVT\_ARC 030201030201\_IFC\_ARC 03020104\_Models\_Rhinoceros 03020105\_Models\_Solibri 03020106\_Models\_Point-clouds 03020201\_Visualization\_Renderings 03020202\_Visualization\_Images-high-resolution

### 3.2 **Art des Feldes**

In dieser Dokumentstruktur trennen Sie zunächst die verschiedenen Studienbereiche, die an Ihrem Projekt beteiligt sind. Diese Art von Ordnerstruktur kann gut sein, wenn Sie Ihren Benutzern vollständigen Zugriff auf ihren eigenen Bereich geben möchten, in dem sie frei Dateien verschieben können. Diese Dateistruktur ist für die Berater einfacher zu verwenden, da sie ihren eigenen Bereich haben, in dem sie die Kontrolle über alle Dateien behalten können, die sie hochladen. Diese Dateistruktur ist für den Kunden schwieriger zu verwenden, da Dateien von verschiedenen Beratern über jeden ihre eigenen Ordner verteilt sind.

_Beispiel einer Dateistruktur_

0101\_Information 010101\_Admin 010102\_Contracts 0201\_ARC 02010101\_2D 02010201\_3D\_Archicad 0201020101\_PLN 0201020102\_IFC YYMMDD\_Drawing-title.ifc 02010202\_3D\_Navisworks 02010203\_3D\_Revit 0201020301\_RVT 0201020301\_IFC 02010204\_3D\_Rhinoceros 02010205\_3D\_Solibri 02010206\_3D\_Point-clouds 02010307\_Contracts 0202\_MEP 020201\_2D 020202\_3D 020203\_Contracts 0203\_STR 0204\_LAN

## 4. **Modellordner**

Wenn Modelle als Dokumente aktiviert sind, ist es möglich, Modelle aus dem Modellbereich mit Dokumenten im Dokumentbereich zu verbinden. Wenn neue Modelle im Modellbereich erstellt werden, werden sie in einem Ordner namens Modellordner angezeigt. Modelle können aus dem Modellordner verschoben und an die gewünschte Position in der Dokumentstruktur verschoben werden.

Ähnlich wie bei den obigen Beispielen können Sie Ihre Modelle entweder nach Typ strukturieren: 01\_Models -> 0101\_ARC -> YYMMDD\_Model-title.ifc

Oder Sie können Ihre Modelle nach Studienbereich strukturieren: 01\_ARC -> 0101\_Models -> YYMMDD\_Model-title.ifc

Die beste Option hängt davon ab, ob Sie denken, dass Ihre Benutzer den [Modellfilter](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page#h_1723ca8291) verwenden werden. Wenn Sie Modelle pro Studienbereich trennen, kann es schwierig sein, dass Benutzer die 3D-Modelle finden, die mit den anderen Dokumenten eines jeden Studienbereichs vermischt sind. Wenn Sie zuversichtlich sind, dass Ihre Benutzer den [Modellfilter](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page#h_1723ca8291) finden, können Sie diese Option verwenden. Wenn Sie nicht davon ausgehen, dass Ihre Benutzer diesen Filter verwenden, ist es besser, alle Ihre Modelle in ihrem eigenen Modellordner zu haben, damit der Benutzer weiß, dass dieser Ordner Modelle enthält, die in 3D geöffnet werden können.
