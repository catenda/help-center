# Changelog 1 Catenda - April, 2023

## 1. Artikel

**Neue Artikel:**

[Systemanforderungen und Optimierung](https://intercom.help/bimsync-arena/en/articles/6921941-system-requirements-and-optimization)

[Solibri-Modelle und Dokumentenintegration](https://intercom.help/bimsync-arena/en/articles/6988148-solibri-models-and-documents-integration)

[2D-Overlay](https://intercom.help/bimsync-arena/en/articles/6921756-2d-overlay)

[Kontoeinstellungen](https://intercom.help/bimsync-arena/en/articles/6880968-account-settings)

[Größe von Spalten ändern](https://intercom.help/bimsync-arena/en/articles/6887350-resizing-of-columns) [IFC-Unterstützung in Dokumente](https://intercom.help/bimsync-arena/en/articles/5658031-ifc-support-in-documents) [Was ist neu in Catenda Hub?](https://intercom.help/bimsync-arena/en/articles/7150907-what-s-new-in-catenda-hub) [Was ist neu in Catenda Site?](https://intercom.help/bimsync-arena/en/articles/7161448-what-s-new-in-catenda-site)

<a class="intercom-content-link" href="" target="_blank">Projekteinstellungen</a>
[Tabellenansicht in einem issue board](https://support.catenda.com/en/articles/6941099-table-view-in-an-issue-board)

[Listenansicht in einem issue board](https://support.catenda.com/en/articles/6941232-list-view-in-an-issue-board)

**Artikel, die sich geändert haben:**

[3D Viewer-Einstellungen](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings)

[Dokumentengenehmigung](https://support.catenda.com/en/articles/5784717-document-approval)

[Multi-Faktor-Authentifizierung](https://support.catenda.com/en/articles/4969891-multi-factor-authentication)

## 2. Behobene Probleme

**Importprobleme:**

- IFC-Dateien mit fehlenden Entitäten, die aus MagiCAD exportiert wurden, können nun leichter importiert werden.
- IFC-Dateien mit Nicht-Unicode-Zeichen in IfcPerson und IfcOrganization führen nicht länger zu Ausfällen bei den Gittern

**Viewer-Probleme:**

- Modelle können erneut ohne Probleme rotiert werden. (Das Rotationsfeld war für kurze Zeit leer)
- Objekte können erneut gelöscht werden (Modelle wurden für kurze Zeit zweimal geladen)
- Gitter, die von Revit mit dem offiziellen IFC4-Exporter exportiert wurden, sind nun sichtbar
  Die erste gemessene Messung ist nun sofort sichtbar, wenn Sie auf Inspizieren auf Bildschirmen klicken, wo kein Platz für die Anzeige des Inspizieren-Bedienfelds und des 3D-Viewers gleichzeitig vorhanden ist.
- Objekte können nun erneut transparent gemacht werden. (Transparentmachen würde stattdessen andere für einige Zeit ausblenden)
- Bedienfelder wie Eigenschaften bleiben nun offen, auch wenn Sie auf leeren Raum und dann auf das gleiche Objekt klicken

**Weitere Probleme:**

- Das Verschieben von Dateien ermöglicht nun erneut die Navigation vom Stammordner aus (Der Stammordner zeigte für kurze Zeit keinen Inhalt an)
- Der Storey-Konfigurator ermöglicht nun erneut die Platzierung von Zeichnungen, die vorher Platzierungen von vor dem Rebranding hatten.
