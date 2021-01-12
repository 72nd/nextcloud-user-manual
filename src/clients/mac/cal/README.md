# Mac Kalender einrichten

Die Kalender Applikation von macOS kann mit Nextcloud verbunden werden.

Öffne hierzu zunächst die Kalenderapp auf deinem Mac. Danach klicke in der Menüleiste auf »Kalender« (1) und danach auf »Accounts...« (2).

![Accounteinstellungen öffnen](./assets/cal-01.png)

Dies öffnet die Accounteinstellungen des Kalenders. Wenn du bereits über Accounts verfügst (der Dialog also nicht so wie unten aussieht) klicke zunächst auf das Plus links unten (1). Danach klicke auf »Anderen Account hinzufügen« (2). Wenn du noch über keinen Account verfügst, kannst du den ersten Schritt überspringen und gleich auf »Anderen Account hinzufügen« klicken.

![Neuen Account hinzufügen](./assets/cal-02.png)

Wähle als Typ »CalDAV-Account« aus.

![CalDAV Typ auswählen](./assets/cal-03.png)

Im nächsten Dialog müssen die korrekten Einstellungen gesetzt werden. Wähle zunächst (1) als Accounttyp `Erweitert` aus. Danach kannst du die Einstellungen (2) wie folgt setzten:

| Einstellung      | Was                                                                                                         | Beispiel                               |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------|
| Benutzername     | Dein Loginname für Nextcloud.                                                                               | `max`                                  |
| Passwort         | Das Passwort, welches du für Nextcloud verwendest.                                                          |                                        |
| Serveradresse    | Die URL der Nextcloud ohne den `https://` Teil.                                                             | `nx15150.your-storageshare.de`         |
| Serverpfad       | `remote.php/dav/principals/users/BENUTZER/` wobei `BENUTZER` durch dein Loginname ersetzt werden muss. | `remote.php/dav/principals/users/max/` |
| Port             | `433`                                                                                                       | `433`                                  |
| SSL Verwenden    | Aktivieren (Hacken muss gesetzt sein).                                                                      |                                        |
| Kerbos v5 zur... | Deaktiviert (Hacken nicht gesetzt)                                                                          |                                        |

Die Beispielswerte gelten für den User mit dem Namen `max` auf der Nextcloud mit der URL `https://nx15150.your-storageshare.de`.

Die Eingabe mit einem Klick auf »Anmelden« abschließen.

![Servereinstellungen](./assets/cal-04.png)

Erlaube den Zugriff mit einem Klick auf »Immer erlauben«.

![Zugriff immer erlauben](./assets/cal-05.png)

Die neue Kalenderverbindung befindet sich nun bei deinen Kalenderaccounts. Wenn du die Aufgabenlisten (ToDo's) in die Erinnerungen App integrieren möchtest, aktiviere das entsprechend.

![Neuer Account](./assets/cal-06.png)

Du kannst nun auf alle Kalender von der Nextcloud zugreifen. Es kann sein, dass du diese zunächst nicht siehst. Um dies zu ändern, Klicke in der Hauptansicht von Kalender auf »Kalender« und aktiviere die gewünschten Kalender.

![Kalender anzeigen](./assets/cal-07.png)

