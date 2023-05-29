# VM für Plex Media Server vorbereiten

Folgende Anleitung beschreibt die Installation eines Plex Media Servers auf Ubuntu.
Der Media Server wird in einer VM über die VMware Workstation eingerichtet.

## Ubuntu Server VM vorbereiten
Download ISO file von [Ubuntu Server](https://ubuntu.com/download/server) (aktuelle Version 22.04.2 LTS)
Wechsle anschliessend zu VMware Workstation

### VM erstellen
(Info! Wird keine Auswahl beschrieben, können die Einstellungen bei default belassen werden.) 
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

