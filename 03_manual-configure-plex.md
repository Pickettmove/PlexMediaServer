# Plex Media Server konfigurieren

## Mediatheken erstellen, bearbeiten und löschen
Mediatheken können nur als Administrator/Verwalter bearbeitet werden.
Hierzu muss man sich also als erstes mit dem entsprechendem Benutzer anmelden.

Unter Einstellungen > Verwalten > Mediatheken können die eigenen Mediatheken verwaltet werden.

### Mediathek erstellen
Mit der Option "Mediathek hinzufügen" kann eine neue Mediathek erstellt werden.
Man kann dabei zwischen Filme, Serien, Musik, Fotos und Andere Videos auswählen und gleich einen Namen definieren.
Anschliessend können ein oder mehrere Medienordner auf dem Server verlinkt werden.

Note:
Für eine saubere Struktur ist zu empfehlen auf dem Server unter /var/lib/plexmediaserver als erstes einen Ordner für jedes Medium (Filme, Serien, Musik usw.) zu erstellen. So lassen sich später die einzelnen Mediatheken auf dem Server etwas besser verwalten/sortieren.

Unter der Option "Erweitert" können dann noch zusätzliche Einstellungen vorgenommen werden. 
Für Filme und Serien kann hier unter anderem z. B. ausgewählt werden, welche Informationen und wie dargestellt werden sollen.

### Daten einlesen
Rechts neben der Option "Mediathek hinzufügen" können die Mediathek-Dateien eingelesen werden.
Wurden z. B. neue Filme einer Bibliothek hinzugefügt kann man die Dateien einlesen, damit sie auch im Plex angezeigt werden.

### Mediathek bearbeiten und lösen
In der Liste der Mediatheken hat man dann noch zusätzliche Einstellungsmöglichkeiten. 
Nützlich ist vorallem  die Verwaltung der Empfehlungen, die Verwaltung des Zugriffs sowie die Aktualisierung der Metadaten. 
Hier kann auch eine Mediathekt gelöscht werden.


## Medien auf Server laden
XX

### DVDs rippen
XX

## Benutzer verwalten
XX

## Streamingdienste integrieren
Unter Einstellungen > Streaming-Dienste können aktuelle Streaming-Plattformen mit dem Plex Media Server verlinkt werden (Schnittstelle).
Hier befindet sich eine Liste aller gängigen Streaming-Anbieter darunter Netflix, Disney+, Prime Video usw.
Wird ein Streaming-Dienst zum Server hinzugefügt, wird die gesamte Medienauswahl des Anbieters im Plex angezeigt. Vorteilt hat dies besonders dann, wenn man z. B. als Familie Abonnements bei verschiedenen Anbietern hat. Möchte man einen bestimmten Film ansehen, kann man über Plex zentral alle abonnierten Anbieter gleichzeitig durchsuchen und sehen, wo der gesuchte Film verfügbar ist.

Note:
Befindet sich ein Film bei einem Streaming-Anbieter und ist nicht lokal auf dem Plex Media Server gespeichert, muss man fürs Abspielen des Films auf die Plattform des entsprechenden Anbieters wechseln. Dazu kann man einfach beim enstprechenden Film unter "Hier anschauen" auf den Anbieter klicken. Man wird automatisch auf die Wiedergabeseite des Film weitergeleitet und kann, wenn man bereits angemeldet ist, den Film gleich ansehen.

## Plex App nutzen
Die Plex App gibt es für fast jedes App-fähige Gerät (Windows, IOS, Android) und kann im jeweiligen Store einfach heruntergeladen werden.
Wird der Plex Media Server nur intern eingesetzt, muss sich das Endgerät im gleichen Netz befinden. Ansonsten muss/kann der Plex Media Server noch nach extern freigegeben werden.

Detaillierte Scrennshots sind [hier](pictures/configure-plex) abgespeichert.