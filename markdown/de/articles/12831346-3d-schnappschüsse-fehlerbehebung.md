# 3D-Schnappschüsse - Fehlerbehebung

## 1. **Viewpoint-Einstellungen**

### 1.1 **Objekte**

Objekte mit derselben ID, die ausgewählt, verborgen oder isoliert waren, werden bei der Neuerstellung des Schnappschusses ausgewählt, verborgen oder isoliert. Wenn zwei Modelle identische IfcProject-GUIDs (Global Identifiers) verwenden, können Konflikte zu Sichtbarkeitsproblemen führen und verhindern, dass Catenda Hub bestimmt, welche Modellelemente während der Neuerstellung des Schnappschusses angezeigt werden sollen.

### 1.2 **Verborgene Objekte**

Wenn mehr als die Hälfte der Objekte in einem Modell sichtbar sind, werden Objekte mit neuen IDs ausgeblendet.

Das bedeutet, dass wenn Sie ein neues Modell mit der Modellauswahl in einem Themen-Kommentar-Schnappschuss hinzufügen, in dem mehr als die Hälfte der Objekte in einem Modell sichtbar sind, das hinzugefügte Modell möglicherweise vollständig verborgen ist. Um die Objekte mit neuen IDs anzuzeigen, können Sie "Alles anzeigen" verwenden, um das Modell nach der Neuerstellung des Schnappschusses anzuzeigen. Um Fehler zu beheben und verborgene Modelle sichtbar zu machen, können Sie die Option "Alles anzeigen" im 3D-Viewer verwenden. Klicken Sie mit der rechten Maustaste in den 3D-Ansichtsbereich, wählen Sie "Alles anzeigen" aus dem Kontextmenü, und dies sollte Sichtbarkeitsprobleme vorübergehend beheben, die durch Konfigurationskonflikte verursacht werden.

## 2. **Schnappschuss neu erstellen**

Wenn Sie einen 3D-Schnappschuss eines Themas wiedergeben, werden möglicherweise bestimmte Modelle nicht angezeigt. Dieses Problem kann von Projektproblemen wie doppelten IfcProject-GUIDs herrühren. Um dies zu beheben, stellen Sie sicher, dass jedes Modell im Projekt eine eindeutige Kennung verwendet. Verwenden Sie zusätzlich die Option "Alles anzeigen" im 3D-Viewer als vorübergehende Lösung.

### 2.1 **Schnappschuss-Modellauswahl**

In diesem Menü verknüpfen Sie den Schnappschuss nur mit Catenda-Modellen. Wenn die richtigen Modelle nicht automatisch gefunden wurden, können sie hier manuell verknüpft werden. Auch wenn mehrere Modelle die gleiche GUID haben, können Sie auswählen, alle zu aktivieren, anstatt nur das erste. Dies ändert den Inhalt der BCF nicht, daher können die Objekte bei Öffnung in externen Tools immer noch verborgen sein.

Je nach Objektsichtbarkeitseinstellungen des Schnappschusses können hinzugefügte Modelle vollständig verborgen sein. Öffnen Sie die Revisions-Auswahl oder die Modellseite, um zu sehen, welche Modelle die 3D-Schaltfläche aktiviert haben, um zu sehen, welche Modelle nach der Neuerstellung des Schnappschusses in den 3D-Viewer geladen werden. Auch wenn sie geladen sein könnten, können alle Objekte aus dem Modell verborgen sein. Verwenden Sie die Aktion "Alles anzeigen", um verborgene Objekte anzuzeigen..

## 3. **BCF-Import von Schnappschuss**

Wenn ein BCF-Thema importiert wird, werden die IDs der Modelle im Projekt mit den IDs der Modelle verglichen, die im Schnappschuss konfiguriert sind. Nur die Modelle mit IDs, die zum Zeitpunkt des Imports vorhanden sind, werden im 3D-Viewer geladen, wenn der Schnappschuss erneut erstellt wird.

Wenn zwei Modelle die gleiche ID haben, wird nur das erste aktiviert. Um sicherzustellen, dass die richtigen Modelle aktiviert werden, ist es wichtig, dass jedes seine eigene ID hat.

Wenn Sie verschiedene mehrere Dateien aus Ihrer Autoren-Software exportieren, kann es sinnvoll sein, für jedes unterschiedliche Modell, das Sie exportieren möchten, eine eindeutige ID zu verwenden. Es wird empfohlen, dass jedem Modell im Projekt eine eindeutige IfcProject-GUID zugewiesen wird, um Konflikte bei der Neuerstellung von Schnappschüssen zu vermeiden. Dies stellt sicher, dass Catenda Hub die Konfigurationen im 3D-Viewer genau anzeigen kann.

Hier ist ein Artikel von BuildingSMART, der beschreibt, wie dies in Revit erfolgt [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/)

Stellen Sie sicher, dass Sie verfolgen, welche ID für welches Modell verwendet wurde, damit zukünftige Themen, die erstellt werden, es erkennen.
