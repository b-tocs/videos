---
marp: true
theme: b2x-default
---

# Container Service Farm
#### Videoreihe DPP - Debian, Podman, Portainer 

![bg left h:5in](res/csf_pdd_green.gif)

#### Teil 1 - Installation

---
# Container Service Farm
#### Videoreihe DPP - Debian, Podman, Portainer 
Inhalt:
1. **Installation**
2. Einführung Portainer
3. Container Stacks
4. Security Themen
5. Weitere Hinweise

---
# Teil 1 - Installation
#### CSF1: DPP - Debian, Podman, Portainer  


Inhalt:
- Überblick
- Serverauswahl
- Installation Debian 12
- Installation Podman + Portainer

---
# Überblick
![height:500px ](res/mermaid-diagram.png)

---
# Serverauswahl

Kriterien:
- Eigenes RZ vs. Hoster
- Internet vs. nur intern
- hier verwendet: Strato Linux V-Server
- Strato ist hier kein Sponsor!

![bg right height:4in](res/strato_vps.png)

---
# Debian 12

- Strato installiert Debian nicht als Vorschlag
- Daher Neuinstallation nötig - Kundenportal
- Sicheres root-Passwort verwenden > 20 Zeichen
- SSH-Login mit RSA Key, wenn möglich

![bg left height:7in](res/strato_neu_installation.png)

---
# Erster Login

- SSH Client benötigt
- Empfehlung PortableApps.com und PuTTY
- SSH Login mit Public Key - siehe Bild 

![bg left height:5in](res/ssh_login.png)


---
# Installation

- Github Repository öffnen: `https://github.com/b-tocs/csf_dpp`
- Schritte unter 1 abarbeiten

![bg left height:5in](res/github_repo.gif)

---
# Geschafft!

Aktueller Stand:
- Server konfiguriert
- Portainer ist einsatzbereit
- Backup, Update und Reboot wurde getestet

Nächster Schritt:
- Einführung Portainer


![bg right height:5in](res/csf_pdd_green.gif)