---
title: Artefakte
subtitle: Version 1.1.0
date: 26.02.2018
author: Gruppe 5 (Bucher, Kiser, Meyer, Sägesser)
---

# Hinweise
Die Artefakte sind für jeden Meilenstein unabhängig voneinander definiert und in die Gruppen "Projektmanagement", "Systemspezifikation" und "Applikation" gegliedert.
- Projektmanagement-Artefakte beziehen sich auf den Projektmanagementplan sowie die dazugehörigen Dokumente für den Anhang
- Systemspezifikation-Artefakte beziehen sich auf die Systemspezifikation sowie die dazugehörigen Dokumente für den Anhang
- Applikation-Artefakte basieren auf den Muss-Features der Zwischen- und Schlussabgabe (siehe Aufgabenstellung)

# Meilenstein 1 (Interface)
## Projektmanagement
### Projektorganisation
- Die Grundstruktur des Projektmanagementplans anhand der Vorlage der HSLU steht
- Der Organisationsplan steht
- Die Rollen und Zuständigkeiten sind definiert

### Projektführung
- Der Projektstrukturplan steht
- Der Rahmenplan steht
- Der Iterationsplan steht
- Der Meilensteinplan steht
- Der Ressourcenplan steht
- Mind. ein Vorgehen zur Projektkontrolle wird eingesetzt
- Der ProductBacklog für Meilenstein 1 steht
- Der SprintBacklog für Sprint 1 und 2 steht
- Das Risikomanagement steht

### Projektunterstützung
- Tools für Entwicklung, Test & Abnahme sind definiert

### Testplan
- Erste Gedanken zum Testdesign gemacht
- Erste Gedanken zu den Testfällen gemacht

### Anhänge
- Meilensteinreview für Meilenstein 1 verfasst

## Systemspezifikation
- Die Grundstruktur des Dokuments steht## Applikation
- Alle Teammitglieder haben ihre IDE für den Projektstart eingerichtet
- Interface-Definition wurde durch das Interface-Komitee erstellt

# Meilenstein 2 (Zwischenabgabe)
## Projektmanagement
### Projektführung
- Der Ressourcenplan ist aktuell
- Die Projektkontrolle ist aktuell
- Der ProductBacklog für Meilenstein 2 steht
- Der SprintBacklog für Sprint 3 und 4 steht

### Projektunterstützung
- Tools für Entwicklung, Test & Abnahme sind aktuell
- Konfigurationsmanagement ist aktuell
- Releasemanagement ist aktuell

### Testplan
- Testdesign ist vollständig definiert
- Testfälle für implementierter Code sind vorhanden

### Anhänge
- Meilensteinreview für Meilenstein 2 verfasst
- Sprintreview für Sprint 1 verfasst
- Sprintreview für Sprint 2 verfasst

## Systemspezifikation
- TODO (weitere Infos folgen in späteren Wochen)

## Applikation
- Der Logger-Komponente ist als Komponente mithilfe von Interfaces austauschbar
- Die Applikation (Game of Life) gibt bei jedem Log einen Message-Level mit
- Die API der Logger-Komponente kann einen Level-Filter setzen, um die zu übertragenden Logs einzuschränken
- Der Level-Filter kann während der Laufzeit geändert werden
- Die Logs werden durch Logger-Komponenten und den Logger-Server kausal und verlässlich aufgezeichnet
- Die Logger-Komponente ist austauschbar
- Die Logger-Komponente ist plattformunabhängig
- Der Komponentenaustausch ist ausserhalb der IDE und ohne Code-Anpassung (Neukompilation) möglich
- Es können mehrere Instanzen der Logger-Komponente parallel auf den Logger-Server loggen
- Die Logs können dauerhaft auf dem Logger-Server in einem einfachen und lesbaren Textfile gespeichert werden
- Das Textfile enthält mind. die Quelle der Logmeldung, den Zeitstempel der Erstellung, den Zeitstempel beim Erreichen beim Server, den Message-Level und den Message-Text
- Das Schreiben des Textfiles erfolgt serverseitig unter der Verwendung der StringPersistor-Schnittstelle
- Die StringPersistorFile-Komponente persistiert die Logs
- Die Daten werden in strukturierter Form dem Payload-Parameter der StringPersistor-Schnittstelle unter Verwendung des Adapter-Pattern übergeben

# Meilenstein 3 (Schlussabgabe)
## Projektmanagement
### Projektführung
- Der Ressourcenplan ist aktuell
- Die Projektkontrolle ist aktuell
- Der Product Backlog für Sprint 3 und 4 steht

### Projektunterstützung
- Tools für Entwicklung, Test & Abnahme sind aktuell
- Konfigurationsmanagement ist aktuell
- Releasemanagement ist aktuell

### Testplan
- Testfälle für implementierter Code sind vorhanden

### Anhänge
- Meilensteinbericht für Meilenstein 3 verfasst
- Sprintreview für Sprint 3 verfasst
- Sprintreview für Sprint 4 verfasst

## Systemspezifikation
- TODO (weitere Infos folgen in späteren Wochen)

## Applikation
- Die Qualitätsmerkmale der vorgegeben StringPersistor-Schnittstelle sind erreicht
- Das Speicherformat für das Textfile ist über verschiedene, austauschbare Strategien leicht anpassbar
- Statische Konfigurationsdaten der Komponenten sind definiert und können ohne Programmierung angepasst werden
- Die Socketverbindung kann mit Netzwerkunterbrüchen umgehen
- Die Logs können mittels eines Viewers angeschaut werden
