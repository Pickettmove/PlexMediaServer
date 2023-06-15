# VM für Plex Media Server vorbereiten

Folgende Anleitung beschreibt die Installation eines Plex Media Servers auf Ubuntu.
Der Media Server wird in einer VM über die VMware Workstation eingerichtet.

### Ubuntu Server VM vorbereiten
Download ISO file von [Ubuntu Server](https://ubuntu.com/download/server) (aktuelle Version 22.04.2 LTS)
Wechsle anschliessend zu VMware Workstation.
(Info! Wird keine Auswahl beschrieben, können die Einstellungen bei default belassen werden.) 

## VM erstellen
1. Wähle oben links unter File > New Virtual Machine...
2. **Type of configuration** > Custom (advanced)
3. **Installer disc image file (iso)** > Pfad zu Ubuntu Server ISO angeben
4. **Name and location** > VM benennen und Speicherpfad eintragen
5. **Number of cores** > Anzahl Cores festlegen z. B. 4
6. **Memory** > Idealerweise mind. 4GB RAM zuweisen
7. **Network** > Use network address translation (NAT)
8. **I/o Controller** > Recommended wählen
9. **Disk Type** > Recommended wählen
10. **Disk** > Create a new virtual disk
11. **Disk Capacity** > Disk size angeben z. B. 50GB
(Disk size ist abhängig von den später abzuspeicherenden Dateien. Die Disk kann nachträglich auch vergrössert werden.)
12. **Disk file** > Speicherpfad angeben
13. **Summary** > Finish und VM starten

Detaillierte Scrennshots sind [hier](pictures/create-vm) abgespeichert.

## Ubuntu Server installieren
1. **Language** > Deutsch
2. **Installer-Aktualisierung** > Aktualisieren auf neuen Installer
3. **Keyboard Layout** > Switzerland
4. **Installation type** > Ubuntu Server
5. **Network** > Default
6. **Proxy** > None
7. **Storage** > Use an entire disk
8. **Storage configuration** > Default
9. **Profile setup** > Definiere Name, Servername, Username und Passwort
10. **Ubuntu Pro** > Skip for now
11. **SSH Setup** > Enable
12. **Featured Server Snaps** > None
13. Wenn Installation beendet ist > Reboot der VM und CD/DVD in den Settings auswerfen

Detaillierte Scrennshots sind [hier](pictures/install-ubuntu) abgespeichert.