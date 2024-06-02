# Python API 4 ABAP 

## Description

B-Tocs Python API for ABAP - Überblick

Diese Videoreihe zeigt, wie man Python basierende Services aus SAP ABAP verwenden kann. 
Das kann beispielsweise sehr hilfreich sein, um auf Python basierende KI Services vom ABAP aus verfügbar zu machen.

Es wird ein neues Python Projekt Step-By-Step angelegt, das mit der Bibliothek FastAPI mit wenig Aufwand eine openAPI erstellt (auch als Swagger UI bekannt). Diese wird dann mit Beispielreports aus dem SAP aufgerufen. 

Wie die Verbindung vom SAP zum Entwicklerrechner erstellt und debugged werden kann, wird ebenfalls gezeigt. Die ausgetestete API kann dann in einen Container "verpackt" und auf verschiedenen Plattformen (z.B. On-Premise).  

Die Reihe besteht aus drei Teilen:
- Teil A: Erstellen Python API Service
- Teil B: Aufruf der API mit SAP ABAP
- Teil C: Erstellen eines Containers für das Multi-Target-Deployment 

## Inhalt


## Links
- PyAPI4ABAP Github: https://github.com/b-tocs/pyapi4abap


## Hashtag: 
B-Tocs, B2X, Python, SDK, SAP, ABAP, VSC, FastAPI, Swagger, OpenAPI, Docker, Container 


# Trailer

00:00 Begrüßung
01:15 Python Service mit openAPI (Swagger UI)
01:58 SAP als Client
02:20 API Container
02:47 Github: Step-By-Step-Guide, Big Picture
03:23 Ausblick



# A - Python API Service

00:00 Begrüßung
00:23 Github Projekt
00:57 Vorausetzungen
01:37 Vorausetzungen prüfen: git, python, vsc
02:40 Andere IDEs
03:12 Neues Projekt
04:50 Visual Studio Code (VSC) öffnen
05:25 VSC Erweiterungen
06:05 Virtual Environment
08:42 VENV für VSC bestätigen
09:10 Environment aktivieren
09:36 pip update
10:15 Python requirements.txt installieren
12:25 Service starten
13:05 OpenAPI/Swagger UI öffnen
16:48 Redoc UI
17:28 Python Code erklärt: GET Beispiele
20:20 Python POST Beispiel (Analogie zum SAP Funktionsbaustein)
22:10 Starup Code mit Environment Parametern
23:35 Zusammenfassung 


# B - ABAP Konsument

## Inhalt

00:00 Begrüßung
00:20 Ausgangsszenario
00:50 Freigabe des lokalen Ports im Internet
01:35 Start ngrok
03:13 SAP RFC Destination anlegen
05:00 Verbindungstest
06:20 ABAP Demoprogramme
07:28 API Test /check
09:07 API Test /process
10:15 ABAP Code für /process
11:36 Exkurs: B-Tocs ABAP SDK
12:00 Fortsetzung ABAP Code für /process
15:15 ABAP Code für /check
16:07 Zusammenfassung Step-by-Step Guide
16:48 Debugger aktivieren
18:45 Debugging
20:14 Weitere Hinweise
21:00 Zusammenfassung

## Links
- B-Tocs ABAP SDK Github: https://github.com/b-tocs/abap_btocs_core
- abapGit: https://abapgit.org
- abapGit Erweiterungen: https://dotabap.org/
- NGROK: https://ngrok.com/download
- Playlist ABAP SDK: https://www.youtube.com/playlist?list=PL_olJj6T96MEEhWYNtlFO8zRH7gaHouPZ



# C - Container Deployment

## Inhalt

00:00 Begrüßung
00:33 Ausgangssituation
00:58 Container erstellen über compose
02:12 Service aus Container aufrufen
02:55 Swagger UI aus Container starten
03:30 Container stoppen (compose)
03:55 Container erstellen (docker build)
04:27 Container Deployment - Einleitung
05:16 Ergebnis: Container Image in Github
06:00 Container image taggen
06:45 Container Resgistry Login
07:07 Upload bzw. docker push
08:44 Lokalen Container aus Container Registry starten
08:16 Hinweise Multi-Target-Deployment (Portainer)
10:48 Zusammenfassung

## Links
- PyAPI4ABAP Image auf Github: https://github.com/users/b-tocs/packages/container/package/pyapi4abap
- Playlist Container Service Farm: https://www.youtube.com/playlist?list=PL_olJj6T96MGW2h61g-7UHTEnMQqUlqWy
