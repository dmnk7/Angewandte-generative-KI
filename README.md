# Angewandte-generative-KI

## Minimaler Umfang

- ChatBot um Dokumente lokal zu durchsuchen
- Verweise auf die jeweilige Quelle
- GUI/ CLI
- Neue und bestehende Dokumente sortieren und korrekt benennen

## Nice-to-have

- Kalender auslesen
- Mails lesen
- Kontakte synchronisieren
- Externe API als "Experte"


## Kurzbeschreibung

Wir entwickeln einen lokalen KI-Assistenten für die persönliche Dokumentenverwaltung. Das System durchsucht lokale Dateien per Chat, beantwortet Fragen direkt mit Angabe der jeweiligen Quelle und organisiert neue sowie bestehende Dokumente automatisch. Da die Kernfunktionen lokal laufen, bleiben sensible Daten auf dem eigenen Rechner.

## Minimal- und Optimalversion

### Minimalversion

* Lokale Dokumentensuche (ChatBot)
* Quellenverweise
* Benutzeroberfläche (GUI)
* Dokumenten-Management

### Optimalversion (Nice-to-have)

* Kalender auslesen
* Mails lesen
* Kontakte lesen
* Externe API als Experte
* CLI

| AP | Arbeitspaket & Kurzbeschreibung |
| --- | --- |
| **AP 1.1** | **Dokumente lokal einlesen:** Textinhalte aus den lokalen Dateien extrahieren. |
| **AP 1.2** | **Lokale Suche:** Extrahierte Inhalte indexieren und durchsuchbar machen. |
| **AP 1.3** | **ChatBot-Kern:** Nutzerfragen entgegennehmen und auf Basis der gefundenen lokalen Inhalte beantworten. |
| **AP 2.1** | **Quellendaten speichern:** Dateiname, Dateipfad und konkrete Textstelle beim Einlesen erfassen. |
| **AP 2.2** | **Quellenverweise ausgeben:** Die genutzten Quellen direkt in den Antworten des ChatBots anzeigen. |
| **AP 3.1** | **CLI:** Bedienung des ChatBots und der Dokumentenfunktionen über die Kommandozeile umsetzen. |
| **AP 3.2** | **GUI:** Einfache grafische Oberfläche für den Chat und die Anzeige der Quellen entwickeln. |
| **AP 4.1** | **Bestehende Dokumente sortieren:** Vorhandene Dateien inhaltlich erfassen, korrekt benennen und in passende Ordner verschieben. |
| **AP 4.2** | **Neue Dokumente verarbeiten:** Neu hinzukommende Dateien erkennen, automatisch benennen und direkt einsortieren. |
| **AP 5.1** | **Kalender auslesen (Nice-to-have):** Kalenderdaten einlesen und für Abfragen verfügbar machen. |
| **AP 5.2** | **Mails lesen (Nice-to-have):** E-Mails auslesen und in die lokale Suche einbinden. |
| **AP 5.3** | **Kontakte synchronisieren (Nice-to-have):** Kontaktdaten abgleichen und im System verfügbar machen. |
| **AP 5.4** | **Externe API als Experte (Nice-to-have):** Anbindung einer externen API für Fragen, die über die lokalen Dokumente hinausgehen. |
| **AP 6.1** | **Evaluierung:** Ergebnisse und Funktionsweise des Projekts auswerten. |
| **AP 6.2** | **Dokumentation:** Projektdokumentation schreiben. |
| **AP 6.3** | **Präsentation:** Abschlusspräsentation vorbereiten. |
