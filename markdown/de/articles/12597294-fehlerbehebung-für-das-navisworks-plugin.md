# Fehlerbehebung für das Navisworks-Plugin

Fehler, die beim Navisworks-Plugin auftreten können, und deren Lösungen werden in diesem Artikel erläutert.

## 1. **AddTopic**

Wenn das Themenmenü geöffnet wird, ohne angemeldet zu sein, wird der folgende Fehler angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/01-addtopic.png)

Um dies zu beheben, gehen Sie bitte zum Einstellungsmenü und klicken Sie oben rechts auf Anmelden.

## 2. **PopulateIssueBoards**

Wenn in einem der Projekte, an dem ein Mitglied beteiligt ist, keine Themen vorhanden sind, wird der folgende Fehler angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/02-populateissueboards.png)

Nachdem ein Thema im Projekt erstellt wurde, wird der Fehler nicht mehr angezeigt.

## 3. **Plugin zurücksetzen**

Nach der Aktualisierung von Navisworks könnten Probleme bei der Installation des Catenda-Navisworks-Plugins auftreten. Um das Plugin zurückzusetzen, führen Sie bitte die folgenden Schritte aus:

Ändern Sie zunächst in den Windows-Ordneroptionen die Einstellung, um versteckte Dateien und Ordner anzuzeigen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/03-resetting-the-plugin.jpg)

Dann finden wir die Navisworks-Anwendungseinstellungen im Ordner C:\\Benutzer\\_Benutzername\\_AppData\\Local. Sie können sich in den Ordnern Autodesk\_Inc oder/und Autodesk\_Ltd befinden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/04-resetting-the-plugin.jpg)

Navisworks-Einstellungen befinden sich in Ordnern, deren Namen mit "Roamer.exe\_Url…" beginnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/05-resetting-the-plugin.jpg)

Wir können diese Einstellungen zurücksetzen, indem wir den Ordner Roamer.exe\_Url… einschließlich Unterordnern und Dateien löschen.

Um zu überprüfen, zu welchen Plugins die Einstellungen gehören: Die nächste Ebene zeigt die Version von Navisworks an, z. B. 19 für Navisworks 2022, 18 für 2021 usw.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/06-resetting-the-plugin.jpg)

In diesem Ordner können wir die eigentliche Konfigurationsdatei _user.config_ finden, die mit einem Text-Editor geöffnet werden kann. Bitte beachten Sie! Es ist besser, den gesamten Pfad ab der Ebene Roamer.exe\_Url zu löschen, als zu versuchen, einzelne Plugins mit dem Text-Editor zu entfernen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/07-resetting-the-plugin.jpg)
