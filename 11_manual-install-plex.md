# Plex Media Server installieren

In diesem Teil der Anleitung wird dir beschrieben, wie du den Plex Media Server auf dem Ubuntu System installieren kannst. 
Sobald du den Webzugriff zum Plex hast, kannst du zur Anleitung [03_manual-configure-plex.md](03_manual-configure-plex.md) und mit der Konfiguration des Media Servers weitermachen.

## Plex installieren
1. Via SSH auf den Server verbinden z. B. mit PuTTY
(IP-Adresse der VM kann mit `ip a` herausgefunden werden.)

2. Repository hinzufügen
`echo deb https://downloads.plex.tv/repo/deb public main | sudo tee /etc/apt/sources.list.d/plexmediaserver.list`
`curl https://downloads.plex.tv/plex-keys/PlexSign.key | sudo apt-key add -`

3. Paketlisten aktualisieren
`sudo apt-get update`
`sudo apt-get upgrade`

4. Plex Media Server installieren
`sudo apt-get install plexmediaserver`

5. Firewall-Konfiguration
`sudo ufw allow 32400`
`sudo ufw reload`

## Plex einrichten
Der Plex Media Server kann nun via Webbrowser z. B. auf dem Host mit folgender URL aufgerufen werden.
`http://<IP-Adresse-des-Servers>:32400/web`