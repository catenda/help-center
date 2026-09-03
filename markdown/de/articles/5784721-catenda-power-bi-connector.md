# Catenda Power BI Connector

> **Hinweis:** Die Installationsdatei für diese Anwendung finden Sie [hier](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

In diesem Artikel erklären wir, wie die Catenda HUB-Datenbank mit PowerBI verknüpft werden kann. Durch die Verknüpfung kann direkter Zugriff auf die Daten auf Catenda HUB in PowerBI erhalten werden. Diese Daten können dann zur Bewertung von Aufgaben, Dokumente oder beispielsweise Teammitglieder verwendet werden.

## 1. **Installation**

Wenn der Catenda Desktop Connector auf Windows installiert wird, befinden sich die Installationsdateien im folgenden Ordner.

`C:\Users\<Username>\Dokumente\Power BI Desktop\Custom connectors`

### 1.1 **Deinstallation**

Um das Plug-in zu deinstallieren, gehen Sie zum Installationsordner und führen Sie die folgende Datei aus:

`uninstall.exe`

Wenn der Ordner gelöscht wurde und das Plug-in noch aktiv ist, installieren Sie das Plug-in bitte neu und deinstallieren Sie es mit der erstellten Deinstallationsdatei.

## 2. **Daten abrufen und verbinden**

Um eine Verbindung von PowerBI zur Catenda HUB-Datenbank herzustellen, gehen Sie wie folgt vor: Öffnen Sie PowerBI und klicken Sie auf "Daten aus einer anderen Quelle abrufen" in der Mitte des Bildschirms oder verwenden Sie die Aktion "Daten abrufen" im Startmenü des oberen Menübands. Das Menüband muss möglicherweise erweitert werden, um die Aktion zu sehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/01-get-data-and-connect.png)

Wählen Sie die Zielquelle unter Sonstiges --> Catenda aus. Verwenden Sie "_Verbinden_", um die Verbindung zur Datenbank herzustellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/02-get-data-and-connect.png)

## 3. **Daten laden**

Ein Navigator wird geöffnet, in dem alle Projekte aufgelistet sind, auf die Sie Zugriff haben. Wählen Sie das entsprechende Projekt und die Tabelle aus, die verknüpft werden soll. In unserem Beispiel möchten wir [Themen](https://support.catenda.com/en/articles/4670271-topics-page) in PowerBI auswerten. Klicken Sie auf "_Laden_", um den Datensatz zu laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/03-load-data.png)

Hier können Sie aus den folgenden Datensätzen wählen: _Dokumente_

**Dokument-Etiketten**

**Etikette**

**Mitglied**

**Modell**

**Modellrevision**

**Produkte**

**Team**

**Teammitglieder**

**Token**

**Thema**

**Themen-Board**

**Themen-Etikette**

**Themen-Status**

**Thementyp**

Nach dem Klicken auf "Laden" beginnt der PowerBI Connector mit dem Abrufen der Themendaten aus der API.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/04-load-data.png)

Die Daten werden dann auf der rechten Seite angezeigt. Wählen Sie das entsprechende Datenfeld aus und erstellen Sie Ihre Analyse.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/05-load-data.png)

> **Hinweis:** Laden Sie verschiedene Datensätze und verknüpfen Sie diese miteinander. Damit können Sie interaktive Dashboards erstellen, die Ihnen einen vollständigen Überblick geben.

Abhängig von den in Ihrem Projekt vorhandenen Daten und den von Ihnen geladenen Daten werden automatisch verschiedene Beziehungen hergestellt.

## 4. **Tabellenansicht**

So können die Themendaten in der Tabellenansicht aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/06-table-view.png)

## 5. **Modellansicht**

Hier ist eine Karte, die zeigt, wie die Verbindungen in der Modellansicht aussehen, wenn alle Informationen in Ihrem Projekt vorhanden sind und Sie alle Projektdaten geladen haben:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/07-model-view.png)
