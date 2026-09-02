# Link-Aktion kopieren

Mit der Link-Aktion kopieren kann ein Link kopiert werden, der nur die ausgewählten Tabellenzeilen anzeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/01-intro.png)

Wählen Sie eine oder mehrere Zeilen in einer Tabelle aus und klicken Sie auf das Symbol Link kopieren oder öffnen Sie das Aktionsmenü und klicken Sie auf die Aktion Link kopieren.

## 1. **Link in Modellen kopieren**

Wählen Sie Modelltabellenelemente aus und verwenden Sie die Aktion Link kopieren, um einen Link zu kopieren, der die Modelltabelle öffnet, die nur auf diese Elemente gefiltert ist.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-036d3ef692a4.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-d473a08316d9.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-93f9ec98b273.png" width="190"/>

In der URL sieht der Themenfilter wie folgt aus:

`https://hub.catenda.com/project/<Project-GUID>/models?items=<Model-GUID>,<Model-GUID>,<Model-GUID>`

_Erforderlicher Zugriff:_ Benutzer, die den Link öffnen, benötigen Lesezugriff auf die Dokumente, die in jedem Modell im kopierten Link verknüpft sind.

## 2. **Link in Themen kopieren**

Wählen Sie Elemente aus einem beliebigen Themenbrett aus und verwenden Sie die Aktion Link kopieren, um einen Link zu kopieren, der die Thementabelle öffnet, gefiltert nur auf diese Elemente.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-8ff62194b021.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-bfe92aebbad0.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-d5d860aee52d.png" width="190"/>

In der URL sieht der Themenfilter wie folgt aus:

[`https://hub.catenda.com/project/<Project-GUID>/issues?issues=<Topic-number>,<Topic-number>&status-type=all&board=<Topic-board-GUID>,<Topic-board-GUID`](https://hub.catenda.com/project/<Project-GUID>/issues?issues=<Topic-number>,<Topic-number>&status-type=all&board=<Topic-board-GUID>,<Topic-board-GUID)`>`

_Erforderlicher Zugriff:_ Benutzer, die den Link öffnen, benötigen Lesezugriff auf die Themenbretter, in denen sich die verknüpften Themen befinden.

> **Hinweis:** Links mit bis zu 100 Themen können erstellt werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/02-copy-link-in-topics.png)

## 3. **Link in Dokumenten kopieren**

Wählen Sie Dokumenttabellenelemente aus und verwenden Sie die Aktion Link kopieren, um einen Link zu kopieren, der die Dokumenttabelle öffnet, gefiltert nur auf diese Elemente.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-3e8ac1581a38.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-adfb4a0cfa24.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-eadb7abae0a4.png" width="190"/>

In der URL sieht der Themenfilter wie folgt aus:

[`https://hub.catenda.com/project/<Project-GUID>/libraries/<Document-library-GUID>/items?items=<Library-item-GUID>,<Library-item-GUID`](https://hub.catenda.com/project/<Project-GUID>/libraries/<Document-library-GUID>/items?items=<Library-item-GUID>,<Library-item-GUID)`>`

_Erforderlicher Zugriff:_ Benutzer, die den Link öffnen, benötigen Lesezugriff auf die Ordner/Dokumente

> **Hinweis:** Suchen oder filtern Sie, um einen Link zu Dokumenten aus mehreren Ordnern freizugeben.
