# Operationen auf Dokumentbibliothekselementen

## 1. **1. Ordneroperationen**

Dies sind die verschiedenen Operationen, die je nach Zugriffsstufen an einem Ordner durchgeführt werden können.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Vorgang</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Erforderlicher Zugriff</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ordnerinhalte anzeigen / Ordnerlink teilen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lesen</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Dokument erstellen, Unterordner hinzufügen, Ordner umbenennen</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Schreiben</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Verschieben, löschen, Zugriffseinstellungen ändern (ACL)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vollständiger Zugriff</p></td></tr></tbody></table></div>

### 1.1 **1.1 Erforderlicher Zugriff: Lesen**

**Standardverhalten** Alle Mitglieder haben standardmäßig mindestens Schreibzugriff. Ein Mitglied kann Lesezugriff auf einen Ordner haben, wenn dieser in einem Ordner erstellt wurde, in dem Lesezugriff konfiguriert wurde, oder wenn Lesezugriff speziell für den Ordner konfiguriert wurde. Der Ordner kann später verschoben worden sein, daher muss sein Zugriff nicht unbedingt mit dem des Ordners übereinstimmen, in dem er sich befindet.

**Ordnerinhalte anzeigen** Mitglieder mit Lesezugriff können zu den Inhalten eines Ordners navigieren. Unterschiedliche Zugriffe können auf die Inhalte des Ordners konfiguriert werden, daher haben Mitglieder mit Lesezugriff möglicherweise keinen Zugriff auf alle Elemente im Ordner.

**Ordner teilen** Mitglieder mit Lesezugriff können Links zu Ordnern mit Sharelink oder durch Verlinkung der URL teilen. Der Sharelink-Empfänger kann unterschiedliche Zugriffe haben und sieht möglicherweise nicht die gleichen Inhalte des Ordners. Ein öffentlicher Link zu einer Sammlung kann mit den Inhalten des Ordners erstellt werden, sodass jeder den Inhalt der Sammlung unabhängig von den Zugriffseinstellungen herunterladen kann.

### 1.2 **1.2 Erforderlicher Zugriff: Schreiben**

**Standardverhalten** Alle Mitglieder haben standardmäßig mindestens Schreibzugriff.

**Dokument im Ordner erstellen** Mitglieder mit Schreibzugriff auf einen Ordner können neue Dokumente in diesem Ordner erstellen.

**Ordner im Ordner hinzufügen** Mitglieder mit Schreibzugriff auf einen Ordner können neue Ordner in diesem Ordner erstellen.

**Ordner umbenennen** Mitglieder mit Schreibzugriff auf einen Ordner können den Ordner umbenennen.

### 1.3 **1.3 Erforderlicher Zugriff: Vollständiger Zugriff**

**Standardverhalten** Der Ordnereigentümer (Ersteller des Ordners) und Administratoren haben standardmäßig vollständigen Zugriff.

**Ordner verschieben** Mitglieder mit vollständigem Zugriff können Ordner in andere Ordner verschieben. Ordnereigentümer (Ersteller des Ordners) haben oft vollständigen Zugriff und können dadurch ihre eigenen Ordner verschieben. Mitglieder haben oft Schreibzugriff auf Dokumente, die von anderen Mitgliedern erstellt wurden. Daher können Mitglieder oft nur Ordner verschieben, die sie selbst erstellt haben, es sei denn, sie befinden sich in einem Ordner, in dem ihnen mehr Zugriff gewährt wurde.

**Ordner löschen** Mitglieder mit vollständigem Zugriff können einen Ordner unabhängig vom Zugriff auf den Ordner löschen.

**Ordner-ACL ändern** Mitglieder mit vollständigem Zugriff auf einen Ordner können die Zugriffseinstellungen für diesen Ordner ändern.

## 2. **2. Dokumentoperationen**

Dies sind die verschiedenen Operationen, die je nach Zugriffsstufen an einem Dokument durchgeführt werden können.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Vorgang</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Erforderlicher Zugriff</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Dokumentlink teilen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lesen</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Objekte verknüpfen/entfernen, Etiketten bearbeiten, erstellen, umbenennen, Modell erstellen (IFC)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Schreiben</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>In einen anderen Ordner verschieben, löschen, ACL ändern</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vollständiger Zugriff</p></td></tr></tbody></table></div>

> **Hinweis:** Das Erstellen oder Entfernen eines Modells aus einem IFC-Dokument erfordert auch Schreibzugriff auf "Erstellen und Entfernen von Modellen" in den Projekteinstellungen.

### 2.1 **2.1 Erforderlicher Zugriff: Lesen**

**Standardverhalten** Alle Mitglieder haben standardmäßig mindestens Schreibzugriff. Ein Mitglied kann Lesezugriff auf ein Dokument haben, wenn es in einen Ordner hochgeladen wurde, in dem Lesezugriff konfiguriert wurde, oder wenn Lesezugriff speziell für das Dokument konfiguriert wurde. Das Dokument kann später verschoben worden sein, daher muss sein Zugriff nicht unbedingt mit dem des Ordners übereinstimmen, in dem es sich befindet.

**Dokument teilen** Dokumente können mit Sharelink oder durch Verlinkung der URL geteilt werden. Der Sharelink-Empfänger kann unterschiedliche Zugriffe haben und sieht möglicherweise nicht die gleichen Dokumentversionen. Ein öffentlicher Link zu einer Sammlung kann mit einer bestimmten Dokumentversion erstellt werden, sodass jeder den Inhalt der Sammlung unabhängig von den Zugriffseinstellungen herunterladen kann.

### 2.2 **2.2 Erforderlicher Zugriff: Schreiben**

**Standardverhalten** Alle Mitglieder haben standardmäßig mindestens Schreibzugriff.

**Objekte verknüpfen/entfernen** Mitglieder mit mindestens Schreibzugriff können Objekte mit einem Dokument verknüpfen und entfernen.

**Etiketten bearbeiten** Mitglieder mit mindestens Schreibzugriff können Etiketten von einem Dokument hinzufügen und entfernen.

**Neues Dokument erstellen** Mitglieder mit mindestens Schreibzugriff auf den übergeordneten Ordner können Dokumente in diesem Ordner erstellen.

**Dokument umbenennen** Mitglieder mit mindestens Schreibzugriff können Dokumente umbenennen.

**Modell erstellen** Mitglieder mit mindestens Schreibzugriff auf ein Dokument können ein Modell aus einem IFC-Dokument erstellen, damit es auf der Modellseite angezeigt wird. Erforderliche Erweiterung: `.ifc` oder `.ifczip` _Erforderlicher zusätzlicher Zugriff:_ Schreibzugriff auf Erstellen und Entfernen von Modellen in den Projekteinstellungen

**Modell entfernen** Mitglieder mit mindestens Schreibzugriff können den Modelllink von einem Dokument entfernen, das mit einem Modell verknüpft ist, sodass es von der Modellseite verschwindet. _Erforderlicher zusätzlicher Zugriff:_ Schreibzugriff auf Erstellen und Entfernen von Modellen in den Projekteinstellungen

### 2.3 **2.3 Erforderlicher Zugriff: Vollständiger Zugriff**

**Standardverhalten** Der Dokumenteigentümer (Ersteller des Dokuments und häufig der Uploader der ersten Version) und Administratoren haben standardmäßig vollständigen Zugriff.

**Dokument in einen anderen Ordner verschieben** Mitglieder mit vollständigem Zugriff können Dokumente in andere Ordner verschieben. Dokumenteigentümer (Ersteller des Dokuments und häufig der Uploader der ersten Version) haben oft vollständigen Zugriff und können dadurch ihre eigenen Dokumente verschieben. Mitglieder haben oft Schreibzugriff auf Dokumente, die von anderen Mitgliedern erstellt wurden. Daher können Mitglieder oft nur Dokumente verschieben, die sie selbst erstellt haben, es sei denn, sie befinden sich in einem Ordner, in dem ihnen mehr Zugriff gewährt wurde.

**Dokument löschen** Mitglieder mit vollständigem Zugriff können ein Dokument unabhängig vom Zugriff auf den Ordner löschen.

**ACL ändern** Mitglieder mit vollständigem Zugriff auf ein Dokument können den Zugriff auf dieses Dokument ändern.

## 3. **3. Operationen auf veröffentlichten Versionen**

Die folgende Tabelle zeigt die Operationen, die an einer veröffentlichten Version durchgeführt werden können, in Bezug auf die Zugriffsstufen. Standardmäßig werden alle neuen Versionen in Dokumenten veröffentlicht. Wenn gemeinsam genutzte Versionen aktiviert wurden, werden alle neuen Versionen in Dokumenten standardmäßig als gemeinsam genutzte Versionen erstellt.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Vorgang</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Erforderlicher Zugriff</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vorschau in Catenda Hub, Zugriff in Apps (Mobil / Catenda Site), 2D/3D-Viewer, Download, Vergleich, zu Sammlung hinzufügen, teilen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lesen</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Zurückziehen</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vollständiger Zugriff</p></td></tr></tbody></table></div>

### 3.1 **3.1 Erforderlicher Zugriff: Lesen**

**Vorschau in Catenda Hub** Mitglieder mit mindestens Lesezugriff auf ein Dokument können veröffentlichte Versionen in Catenda Hub in der Vorschau anzeigen.

**Zugriff in Anwendungen** Mitglieder mit mindestens Lesezugriff auf ein Dokument können auf veröffentlichte Versionen aus Anwendungen zugreifen, die auf die API zugreifen, wie unsere mobile Anwendung, Catenda Site.

**2D/3D-Viewer-Schaltflächen** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit veröffentlichten 3D-Dokumentversionen können die 2D- und 3D-Schaltflächen in der Viewer-Spalte verwenden, um das 3D-Dokument in den jeweiligen Viewer zu laden. Eine der folgenden Bedingungen ist erforderlich:

- Dokument verknüpft mit Modell und neueste Version ist eine erfolgreich verarbeitete `.ifc` oder `.ifczip`
- Neueste Version ist eine Punktwolke
- Neueste Version ist ein CityGML

**Veröffentlichte Version teilen** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit veröffentlichten Versionen können Links zu Versionen via Sharelink oder durch Verlinkung der URL teilen. Der Sharelink-Empfänger kann unterschiedliche Zugriffe haben und kann das Dokument möglicherweise nicht anzeigen. Ein öffentlicher Link zu einer Sammlung kann mit einer bestimmten veröffentlichten Version erstellt werden, sodass jeder den Inhalt der Sammlung unabhängig von den Zugriffseinstellungen herunterladen kann.

**Vergleichen** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit mindestens zwei vorhandenen PDF-Versionen können die Vergleichsfunktion verwenden. Erforderlicher zusätzlicher Zugriff: Zweite veröffentlichte PDF-Version im Dokument vorhanden

**Download** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit veröffentlichten Versionen können die veröffentlichten Versionen im Dokument herunterladen.

**Zu Sammlung hinzufügen** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit veröffentlichten Versionen können eine veröffentlichte Version von einem Dokument zu einer Sammlung hinzufügen.

### 3.2 **3.2 Erforderlicher Zugriff: Vollständiger Zugriff**

**Zurückziehen** Mitglieder mit vollständigem Zugriff auf ein Dokument können veröffentlichte Versionen im Dokument zurückziehen.

## 4. **4. Entwurfsversionoperationen - Legacy**

Die folgende Tabelle zeigt die Operationen, die an einer Entwurfsversion durchgeführt werden können, in Bezug auf die Zugriffsstufen. Entwurfsversionen sind nur in Projekten verfügbar, die vor dem 2. Oktober 2025 erstellt wurden.

### 4.1 **4.1 Erforderlicher Zugriff: Kein Zugriff**

**Zugriff in Anwendungen** Nur veröffentlichte Versionen können aus Anwendungen zugegriffen werden, die auf unsere API zugreifen, wie unsere mobile Anwendung, Catenda Site.

**Zu Sammlung hinzufügen** Nur veröffentlichte Versionen können zu Sammlungen hinzugefügt werden.

### 4.2 **4.2 Erforderlicher Zugriff: Lesen**

**Vorschau in Catenda Hub** Mitglieder mit mindestens Lesezugriff auf ein Dokument und Lesezugriff auf Entwürfe in den Projekteinstellungen können Entwurfsversionen in Catenda Hub in der Vorschau anzeigen. _Erforderlicher zusätzlicher Zugriff:_ Lesezugriff auf Dokumententwürfe in den Projekteinstellungen.

**Entwurfsversion teilen** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit Entwurfsversionen und Lesezugriff auf Entwürfe in den Projekteinstellungen können Links zu Entwurfsversionen via Sharelink oder durch Verlinkung der URL teilen. Der Sharelink-Empfänger kann unterschiedliche Zugriffe haben und kann das Dokument möglicherweise nicht anzeigen.

**Download** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit Entwurfsversionen und Lesezugriff auf Entwürfe in den Projekteinstellungen können Entwurfsversionen herunterladen. Entwurfsversionen können einzeln heruntergeladen werden, indem Sie auf die Download-Schaltfläche im Versionsbereich des rechten Menüs der Version auf der Dokumentvorschauseite klicken. _Erforderlicher zusätzlicher Zugriff:_ Lesezugriff auf Dokumententwürfe in den Projekteinstellungen

### 4.3 **4.3 Erforderlicher Zugriff: Schreiben**

**Vorschau in Catenda Hub** _Erforderlicher zusätzlicher Zugriff:_ Dokumenteigentümer

**Veröffentlichen** In Projekten, in denen der Status-Workflow vor dem 2. Oktober 2025 aktiviert wurde, ist das Kontrollkästchen Entwurfsversion standardmäßig im Upload-Menü aktiviert, kann aber deaktiviert werden, um stattdessen eine veröffentlichte Version hochzuladen.

## 5. **5. Gemeinsam genutzte Version**

Die folgende Tabelle zeigt die Operationen, die an einer gemeinsam genutzten Version durchgeführt werden können, in Bezug auf die Zugriffsstufen. Wenn gemeinsam genutzte Versionen aktiviert wurden, werden alle neuen Versionen in Dokumenten standardmäßig als gemeinsam genutzte Versionen erstellt.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Vorgang</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Erforderlicher Zugriff (+ Zusatzbedingung)</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vorschau, teilen, herunterladen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lesen (+ "Gemeinsam genutzte Versionen anzeigen" aktiviert)</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Veröffentlichen</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Schreiben (+ "Kann veröffentlichen" aktiviert)</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Zurückziehen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>"Gemeinsam genutzte Versionen anzeigen" aktiviert</p></td></tr></tbody></table></div>

> **Hinweis:** Hinweis: Nur veröffentlichte Versionen können aus Apps zugegriffen oder zu Sammlungen hinzugefügt werden.

### 5.1 **5.1 Erforderlicher Zugriff: Kein Zugriff**

**Zugriff in Anwendungen** Nur veröffentlichte Versionen können aus Anwendungen zugegriffen werden, die auf unsere API zugreifen, wie unsere mobile Anwendung, Catenda Site.

**Zu Sammlung hinzufügen** Nur veröffentlichte Versionen können zu Sammlungen hinzugefügt werden.

### 5.2 **5.2 Erforderlicher Zugriff: Lesen**

**Vorschau in Catenda Hub** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit gemeinsam genutzten Versionen und Zugriff auf die Anzeige der gemeinsam genutzten Versionen eines Dokuments können gemeinsam genutzte Versionen in Catenda Hub in der Vorschau anzeigen. _Erforderlicher zusätzlicher Zugriff:_ "Gemeinsam genutzte Versionen anzeigen" aktiviert im Dokumentzugriffsmenu

**Gemeinsam genutzte Version teilen** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit gemeinsam genutzten Versionen und Zugriff auf die Anzeige der gemeinsam genutzten Versionen eines Dokuments können Links zu gemeinsam genutzten Versionen via Sharelink oder durch Verlinkung der URL teilen. Der Sharelink-Empfänger kann unterschiedliche Zugriffe haben und kann das Dokument möglicherweise nicht anzeigen.

**Download** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit gemeinsam genutzten Versionen und Zugriff auf die Anzeige der gemeinsam genutzten Versionen eines Dokuments können gemeinsam genutzte Versionen herunterladen. Die neuesten gemeinsam genutzten Versionen von Dokumenten, die im Arbeitsbereich-Tab der Dokumenttabelle ausgewählt sind, können mit der Download-Aktion heruntergeladen werden. Frühere gemeinsam genutzte Versionen können einzeln heruntergeladen werden, indem Sie auf die Download-Schaltfläche im Versionsbereich des rechten Menüs der Version auf der Dokumentvorschauseite klicken. _Erforderlicher zusätzlicher Zugriff:_ "Gemeinsam genutzte Versionen anzeigen" ist im Dokumentzugriffsmenu aktiviert

### 5.3 **5.3 Erforderlicher Zugriff: Schreiben**

**Veröffentlichen** Mitglieder mit mindestens Schreibzugriff auf ein Dokument mit gemeinsam genutzten Versionen, Zugriff auf die Anzeige der gemeinsam genutzten Versionen eines Dokuments und Zugriff auf das Veröffentlichen von Versionen im Dokument können eine der gemeinsam genutzten Versionen, die seit der neuesten veröffentlichten Version im Dokument hochgeladen wurden, veröffentlichen. _Erforderlicher zusätzlicher Zugriff:_ "Kann veröffentlichen" ist im Dokumentzugriffsmenu aktiviert

### 5.4 **5.4 Erforderlicher Zugriff: Vollständiger Zugriff**

**Zurückziehen** Mitglieder mit mindestens Lesezugriff auf ein Dokument mit gemeinsam genutzten Versionen und Zugriff auf die Anzeige der gemeinsam genutzten Versionen eines Dokuments können gemeinsam genutzte Versionen im Dokument zurückziehen. _Erforderlicher zusätzlicher Zugriff:_ "Gemeinsam genutzte Versionen anzeigen" ist im Dokumentzugriffsmenu aktiviert
