# Projektdokumentation – M158 LB2 <br>

# Projektdokumentation – Webserver-Projekt

## Aufgabe 1 – Projektplan erstellen

### Stufe 3

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#6e5849',
      'primaryTextColor': '#ffffff',
      'primaryBorderColor': '#3e3e3e',
      'lineColor': '#556b2f',
      'secondaryColor': '#d2b48c',
      'tertiaryColor': '#f5f5dc',
      'fontSize': '16px',
      'textColor': '#1a1a1a',
      'mainBkg': '#fdfdfd',
      'nodeBorder': '#8b7355',
      'clusterBkg': '#fffaf0',
      'clusterBorder': '#a9a9a9',
      'defaultLinkColor': '#708090'
    }
  }
}%%



 
gantt
  dateFormat  DD-MM-YYYY
  title       Projektplan Software-Migration M158
  excludes    weekends

  section Phase 1: Planung & Vorbereitung
  Projekt definieren              :a1, 12-05-2025, 8d
  Dokumentation / Journal         :after a1, 50d

  section Phase 2: Infrastruktur
  AWS-Setup                       :b1, after a1, 7d
  Snapshot 1                      : milestone, after b1, 0d

  section Phase 3: Systemkonfiguration
  OS-Konfiguration                :c1, after b1, 7d
  Snapshot 2                      : milestone, after c1, 0d
  Webserver & DB                  :c2, after c1, 7d
  Snapshot 3                      : milestone, after c2,
  DNS-Server                      :c4, after c3, 7d
  Snapshot 4                     : milestone, after c4, 0d

  section Phase 5: Test & Abnahme
  Funktionstests                 :e1, after d3, 7d
```


## Aufgabe 2 – Architekturdiagramm erstellen

### Stufe 1
Ich hatte vor mit diesem Architekturdiagramm zu arbeiten. Jedoch habe ich meine Meinung im Verlauf des Projekts geändert und hatte keine Zeit eine neues Architekturdiagramm zu erstellen
![alt text](image-26.png)

### Stufe 2
Das war die zweite Version die ich am Anfang geplant habe aber nicht abschliessen konnte
![alt text](image-28.png)

### Stufe 3



---

## Aufgabe 3 – AWS-Umgebung einrichten

### Stufe 1

![alt text](image-25.png)

### Stufe 2

![alt text](image-23.png)

### Stufe 3

![alt text](image-24.png)

---

## Aufgabe 4 – DNS-Konfiguration

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

![alt text](image.png)

## Aufgabe 5 – Webserver konfigurieren

### Stufe 1
Nach der erfolgreichen Installation und Konfiguration des Apache2-Webservers wird beim Aufruf der Server-IP oder Domain im Browser die Standardseite von Apache angezeigt.
![alt text](image-3.png)
![alt text](image-1.png)
![alt text](image-2.png)
### Stufe 2

![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)
### Stufe 3
![alt text](image-7.png)
![alt text](image-8.png)

## Aufgabe 6 – PHP einrichten

### Stufe 1
php erscheint über den mit DNS gesetzten url
![alt text](image-9.png)

### Stufe 2

![alt text](image-10.png)

### Stufe 3
![alt text](image-11.png)
![alt text](image-12.png)
![alt text](image-13.png)
![alt text](image-14.png)

## Aufgabe 7 – MySQL/MariaDB aufsetzen

### Stufe 1
Hier wird mariaDB und MySQL heruntergeladen und eingerichtet
![alt text](image-15.png)
mariaDB client wird heruntergeladen für den Zugriff von Webserver auf MariaDB
![alt text](image-17.png)
![alt text](image-18.png)
### Stufe 2
Auf das heruntergeladene MariaDB die Datenbank und User erstellen
![alt text](image-19.png)

### Stufe 3

Ich habe einen Webserver und DB also 2 Instanzen.

---

## Aufgabe 8 – Web-Datenbanktool phpMyAdmin

### Stufe 1
phpmyadmin wird heruntergeladen
![alt text](image-20.png)

### Stufe 2
Über Website auf phpmyadmin zugreifen
![alt text](image-21.png)
File wird konfiguriert
![alt text](image-22.png)
### Stufe 3

Ich habe einen Webserver und eine DB also 2 Instanzen.

---

## Aufgabe 9 – FTP-Zugang einrichten

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 10 – WordPress migrieren

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 11 – Backup-Konzept umsetzen

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 12 – Testing der Webapplikation

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 13 – Deployment automatisieren

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 14 – Docker verwenden

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---
