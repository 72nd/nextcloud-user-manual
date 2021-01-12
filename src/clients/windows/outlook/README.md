# Outlook (Kontakte, Termine und Aufgaben) synchronisieren

Dieser Abschnitt beschäftigt sich mit dem Einrichten von Nextcloud mit Outlook. Hierfür ist ein Plugin erforderlich, dessen Installation und Konfiguration nun erklärt wird.

## Plugin installieren

Für die Integration wird das Plugin [Outlook CalDav Synchronizer](https://caldavsynchronizer.org/) benötigt. Gehe zunächst auf [diese Seite](https://caldavsynchronizer.org/download-2/) und klicke auf »Download« um das Herunterladen zu starten.

![Installationsdatei herunterladen](./assets/outlook-01.png)

Wenn der Download abgeschlossen ist, klicke auf die heruntergeladene Datei um sie zu öffnen.

![ZIP Datei öffnen](./assets/outlook-02.png)

Ein Dateifenster öffne sich. Starte die Installation mit einem Doppelklick auf die Datei »CalDavSynchronizer Setup«.

![Installer öffnen](./assets/outlook-03.png)

Klicke auf »Next«.

![Weiter](./assets/outlook-04.png)

Klicke auf »Next«.

![Weiter](./assets/outlook-05.png)

Erlaube das Durchführen der Installation mit einem Klick auf »Ja«.

![Installtion zulassen](./assets/outlook-06.png)

Warte, bis die Installation abgeschlossen ist und beende sie mit einem Klick auf »Close«.

![Installationsassistent schliessen](./assets/outlook-07.png)


## Konfiguration

Öffne nun Outlook. _Achtung:_ Wenn Outlook während der Installation des CalDavSynchronizer offen war, musst du Outlook schliessen und nochmals öffnen.

Outlook verfügt nun über eine neue Registerkarte (»CalDav Synchronizer«). Öffne diese, indem du auf diese  klickst.

![Plugin Registerkarte öffnen](./assets/outlook-08.png)

Klicke nun auf »Synchronization Profiles«.

![Profile öffnen](./assets/outlook-09.png)

Lege ein neues Profil mit einem Klick auf das grüne Plus an.

![Neues Profil anlegen](./assets/outlook-10.png)

Wähle die »Generic CalDAV/CardDAV« Option aus (1) und bestätige diese Wahl mit einem Klick auf »Ok«.

![Typ auswählen](./assets/outlook-11.png)

Das Profil kann nun weiter editiert werden. Gibt zunächst (1) dem Profil einen Namen. Dieser hat keine weitere Funktion, hilft aber bei der Unterscheidung mehrerer Profile. Es empfiehlt sich einfach den Namen des Kontaktbuches oder Kalenders zu verwenden, welcher synchronisiert werden soll.

Aufgrund des Aufbaus von Outlook, muss jedes Kontaktbuch/Kalender/Aufgabenliste _separat_ in einem eigenen Profil angelegt werden. Der Abschnitt »Konfiguration« muss also für alle Kontaktbücher/Kalender/Aufgabenlisten einzeln wiederholt werden. In Folge wird das Vorgehen anhand eines Kalenders gezeigt. Die Schritte für Kontaktbücher oder Aufgabenlisten sind aber die selben, auf Unterschiede wird hingewiesen werden.

Klicke auf den »...« Button.

![Profilname und Ordner](./assets/outlook-12.png)

Klicke auf »Neu«.

![Ordnerübersicht](./assets/outlook-13.png)

Es muss nun ein neuer Ordner für den Kalender/Kontaktbuch/Aufgabenliste (ab jetzt »Ressource« genannt) angelegt werden. Vergebe hierzu zunächst (1) einen Namen. Dieser kann frei gewählt werden, am besten benennst du ihn so, wie die Ressource in der Nextcloud heisst. In einem zweiten Schritt (2) musst du den Elemententyp auswählen. Dieser entspricht der Ressource. In anderen Worten: Wenn du einen Kalender synchronisieren möchtest, brauchst du einen »Kalender« Typ etc.

Abschliessend (3) musst du den Speicherort wählen. Aktiviere hierzu den passenden Ort. Wenn du eine Aufgabenliste synchronisieren möchtest wähle »Aufgaben« (A), für Kalender »Kalender« (B) und für Kontakte »Kontakte« (C). Schliesse deine Eingaben mit einem Klick auf »Ok« (4) ab.

![Neuer Ordner anlegen](./assets/outlook-14.png)

Wähle den soeben angelegten Kalender/Kontaktbuch/Aufgabenliste aus (1) und bestätige deine Wahl mit »Ok« (2).

![Neuer Ordner auswählen](./assets/outlook-15.png)

Aktiviere zunächst (1) die Option »Synchronize items immediately after change« und gib danach die Kalender-URL ein (2), wie du diese herausfindest erfährst du [hier](/clients/general/cal-url/index.html). Weiter gibst du dein Benutzername (3) sowie Passwort (4) ein. Abschliessend gib deine Mailadresse, welche auch von deinem Nextcloud-Account verwendet wird ein (5).

Klicke nun auf »Test or discover settings«.

![Daten eingeben](./assets/outlook-16.png)

Es öffnet sich nun ein weiterer Dialog, indem du aus den vorhandenen Kalender/Kontaktbücher/Aufgabenlisten auswählen kannst. Klicke auf die gewünschte Ressource (1) und bestätige die Auswahl mit »Ok« (2).

![Ressource auswählen](./assets/outlook-17.png)

Die Konfiguration ist nun abgeschlossen. Mit einem Klick auf »Ok« werden deine Einstellungen gespeichert und du kannst die neue Ressource nutzen.

![Konfiguration abschliessen](./assets/outlook-18.png)

_Hinweis:_ Vergiss nicht, für jeden weiteren Kalender/Kontaktbuch/Aufgabenliste ein neues Profil und einen neuen Ordner anzulegen.

