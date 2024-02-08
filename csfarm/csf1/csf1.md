# CSF1 - DPP Debian Podman Portainer Stack

## Videoreihe

| Video                         | Länge | Slides                                                                            | Youtube                                   |
| ---                           | ---   | ---                                                                               | ---                                       |
| Überbllick                    | 04:06 | [MD](slides/video0.md), [PDF](slides/video0.pdf), [HTML](slides/video0.html)      | [Link](https://youtu.be/pQMxzP7Dptk)      |
| Teil 1 - Installation         | 12:14 | [MD](slides/video1.md), [PDF](slides/video1.pdf), [HTML](slides/video1.html)      | [Link](https://youtu.be/fq9-Zjbto6U)      |
| Teil 1 - Portainer            | 19:37 | [MD](slides/video2.md), [PDF](slides/video2.pdf), [HTML](slides/video2.html)      | [Link](https://youtu.be/PXfcnG8PrT4)      |
| Teil 3 - Stacks               | 32:10 | [MD](slides/video3.md), [PDF](slides/video3.pdf), [HTML](slides/video3.html)      | [Link](https://youtu.be/6CxVlpExPps)      |
| Teil 4 - Security             | 27:25 | [MD](slides/video4.md), [PDF](slides/video4.pdf), [HTML](slides/video4.html)      | [Link](https://youtu.be/vg_AjCiIj2o)      |
| Teil 5 - Weitere Hinweise     | 01:58 | [MD](slides/video5.md), [PDF](slides/video5.pdf), [HTML](slides/video5.html)      | [Link](https://youtu.be/3dAtQ_1gt3o)      |


## Videos Description

Diese Videoreihe zeigt, wie man auf Basis Debian 12, Podman und Portainer eine Container Service Farm aufbaut. Also eine Landschaft, in der man beliebige Lösungen installieren kann, die als Container ausgeliefert werden. Das kann dann die Grundlage sein, um privat oder dienstlich, für das (kleine) Unternehmen oder den Verein eigene cloud-native Lösungen zu installieren. 

In der Reihe wird beispielsweise die Installation von Odoo, einem Open Source ERP mit Homepagebaukasten, Online Shop, CRM und weiteren interessanten Modulen gezeigt. Oder Libretranslate - einem Übersetzungsservice -, der über seine Schnittstellen sogar an SAP Systeme angeschlossen werden kann. 

Zielgruppe sind Einsteiger in die Cloud-native Welt. Eine Welt, welche die Möglichkeiten der Cloud nutzt und trotzdem im eigenen Smarthome oder Unternehmenskeller stehen kann.

Die Videoreihe ist in 5 Teile unterteilt:
1. Auswahl und Installation des Servers
2. Überblick Portainer
3. Installation von Container Stacks
4. Security Themen
5. Weitere Thenen 

Teil 5 sind einzelne kleine Videos, die ggf. auch später noch ergänzt werden können.

Links:
- [Slides & Infos](https://github.com/b-tocs/videos/blob/main/csfarm/csf1/csf1.md)
- [Step-By-Step Guides DPP](https://github.com/b-tocs/csf_dpp)
- [Youtube Kanal](https://www.youtube.com/@B-Tocs)
- [B-Tocs Community](https://b-tocs.org)

Hashtags:
#B2X #Debian #Podman #Portainer #Container #Docker #Compose #Stack #Linux #Homepage #Community #SAP #ERP #Odoo

## Teile

### Teil 0 - Trailer

In diese Video wird ein Überblick über die Videoreihe und einen kurzer Ausblick auf die verwendeten Tools und Lösungen gegeben.

Inhalt:
00:00   Einleitung
01:18   Portainer
01:43   Stirling PDF
02:10   LibreTranslate
02:37   Odoo
03:04   Nginx Proxy Manager
03:17   Youtube Kanal
03:32   Github


### Teil 1 - Installation

In diesem Teil 1 geht es um die Installation des Debian 12 Linux Systems mit Podman als Container Engine und Portainer als grafische Oberfläche.

Inhalt:
00:00   Einleitung
00:39   Big Picture
00:59   Serverauswahl
02:14   Installation Debian 12
03:45   Erste Anmeldung mit SSH/PuTTY
04:58   Update Debian
06:35   Git und Installationsskripte
07:58   Installationskript starten
09:11   Kontrolle Installation
10:06   Podman prüfen
11:55   Zusammenfassung


Links:
- [PortableApps](https://portableapps.com/)
- [Putty](https://putty.org/)

### Teil 2 - Portainer

In diesem Teil 2 geht es um die Portainer Management Software, grundlegende Begriffe und Funktionen und die Installation eines ersten Containers.

Inhalt:
00:00   Einleitung
01:07   Big Picture
02:00   Portainer Administrator Passwort
03:15   Erste Anmeldung - Environment
04:35   Portainer Volumes
05:45   Portainer Networks
07:15   Portainer Images
08:00   Container Image laden
10:35   Container starten
13:15   Container testen
14:22   Portainer Update
17:02   System Update
18:40   Container prüfen und starten
19:15   Zusammenfassung


Links:
- [Docker Hub](https://hub.docker.com/)
- [Portainer Webseite](https://www.portainer.io/)
- [Portainer Container](https://hub.docker.com/r/portainer/portainer-ce)

### Teil 3 - Stacks

In diesem Teil 3 werden verschiedene containerbasierte Lösungen als Stacks in der Container Farm installiert. 

Inhalt:
00:00   Einleitung
00:57   Vorstellung der Stack Beispiele
02:27   Big Picture
02:48   Git Repository 
03:15   Container spdf stoppen
03:40   Stack "spdf"
06:43   Portkonflikte
09:45   Container "spdf" löschen
10:50   Stack "spdf" Port auf "8080" stellen
11:30   Stack mit Volumes - "libre"
15:38   Stack "libre" testen - mit Fehlern
15:55   Logs und Statistik von Containern
16:50   Nachtest und Demo Stack "libre"
18:00   Volumes vom Stack "libre"
18:45   Stack mit mehreren Containern - "odoo"
20:49   Erklärung Template mit Volumes, Networks, Services, Environment Variablen 
23:00   Pflege von Environment Variablen im Portainer
23:50   Prüfen Stack "odoo": Container, Logs, Ports
24:48   Ersteinrichtung Odoo
26:07   Login Odoo
26:28   Odoo Apps und Webseite einrichten
28:30   Überblick Webseite
29:35   Weitere Apps aktivieren
30:20   Portainer Review: Images, Volumes, Network
31:39   Zusammenfassung    

Links:
- [Portainer Webseite](https://www.portainer.io/)
- [Portainer Container](https://hub.docker.com/r/portainer/portainer-ce)
- [Stirling PDF Webseite](https://stirlingtools.com/)
- [Stirling PDF Container](https://hub.docker.com/r/frooodle/s-pdf)
- [LibreTranslate Webseite](https://libretranslate.com/)
- [LibreTranslate Container](https://hub.docker.com/r/libretranslate/libretranslate)
- [Odoo Webseite](https://www.odoo.com/de_DE)
- [Odoo Container](https://hub.docker.com/_/odoo)


### Teil 4 - Security

In diesem Teil 4 geht es um verschiedene Security Aspakte wie ungeschützte Ports, die Einrichtung eines Reverse Proxy oder die Einrichtung von HTTPS-SSL-Verschlüsselung für eigene Services.

Inhalt:
00:00   Einleitung
00:31   Inhalt
01:03   Offene Ports
01:36   Big Picture - Angriffsszenarien
03:40   Github Step-by-Step
04:37   Ports deaktivieren
09:22   Namensauflösung (Workaround)
11:09   Installation Nginx Proxy Manager
13:05   Erster Login Nginx Proxy Manager
15:44   Proxy Host anlegen
19:34   Aktueller Stand Reverse Proxy und Routen über Namen
19:57   Zugriffslisten
21:38   HTTPS/SSL 
23:54   Aktueller Status HTTP/HTTPS Routen
24:40   Weitere Hinweise
26:48   Zusammenfassung

Links:
- [NginxPM Webseite](https://nginxproxymanager.com/)
- [NginxPM Container](https://hub.docker.com/r/jc21/nginx-proxy-manager)

### Teil 5 - Weitere Hinweise

In diesem Teil 5 gibt es noch weitere Hinweise zur Reihe und wie es weitergeht. Teil 5 wird ggf. durch weitere Videos ergänzt.
Welche das sein werden ergibt sich aus dem Feedback zur Videoreihe.

Inhalt:
00:00   Einleitung
00:29   Inhalt
01:20   Youtube Kanal
01:36   Github
