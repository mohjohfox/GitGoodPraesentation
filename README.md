# GitGoodPraesentation

**Technologien:**
- Frontend: Angular -> Typescript
- Backend: SpringBoot -> Java/Kotlin
- Agile: Jira (https://gitgood.atlassian.net/jira/software/projects/SE/boards/1)
- Datenbank: MariaDB


**Weitere mögliche Anforderungen:**
- Dartscheibe mit möglicher Punkteeingabe -> Mögliche Umsetzung: https://gitlab.com/bmcallis/dartboard
- Anpassung für mobile Nutzung
- Lobby Raum und joinbar mit anderem Gerät
- Eingabemaske mit den anderen Geräten und allgemeine Darstellung im Raum

---

## Programmentwurf:

### 1. Anforderungsanalyse

- Was oder welche Probleme soll das Projekt/Programm lösen?
- Wie sind die Rahmenbedingungen? (Systemgrenzen)
- Wozu wird es benötigt? Ziele/Zielgruppen?
- Wie groß ist der Umfang?

- [ ] (4) Anforderungserfassung in natürlicher Sprache => z.B. Satzschablonen oder User Stories
- [ ] (2) Ziele und Zielgrupen festhalten => z.B. Produkt Vision Board / Personas formulieren
- [ ] (2) Anforderungen gliedern => Epics / User Story Map
- [ ] (10) Pitch / Kickoff Präsentation/Disskussion
- [ ] (2) grobes zeitliches Schätzen der Anforderungen => in Personentagen oder in UserStoryPoints / FunctionPoints

Bonus:
- [ ] (4) Eventstorming Board Phase 1 und 2 (Ermitteln der Domänenevents)
- [ ] (2) Glosar für Fachbegriffe

### 2. Systementwurf

- Welche Komponenten/Tools/Frameworks/Sprachen kommen warum/wo zum Einsatz?
- Wie wird das System von einzlenen Akteuren genutzt?
- Wie sehen die konkreten Workflows aus?
- Wie ist das System aufgebaut? Architektur/Schnittstellen.

- [ ] (2) Festhalten der Technologieentscheidungen => Pro Contra Vergleich zu mindestens einer anderen Sprache/Framework/Tool (Lernkurve/Erfahrung ist auch ein Faktor)
- [ ] (4) Use-Case Diagramme für grobes Verhalten des Systems
- [ ] (6) Aktivitätsdiagramm pro Teamperson eins oder ein ausführliches Zustandsdiagramm, falls besser für Projekt geeignet
- [ ] (3) Klassendiagramm: nur Entity Klassen
- [ ] (2) Schnittstellen Web/Persistenz/Ui visualisieren => Komponentendiagramm
- [ ] (3) Sequenzdiagram

Bonus:
- [ ] (4)  Mockups/Wireframes der UI

### 3. Implementierung:

- Wurden Clean-Code Prinzipien eingehalten?

- [ ] (4) Code-Review => Naming Variablen / Funktionen / Klassen
- [ ] (8) Code-Review => SOLID Prinzipien
- [ ] (2) Code-Review => DRY
- [ ] (6) Code-Review => Error-Handling

Bonus:
- [ ] (2) Code-Review => Code-Kommentare und einheitliche Formatierung

### 4. Test:

- Wie wird sichergestellt, dass sich das entwickelte System wie spezifiziert verhält?

- [ ] (2) Manuelles Testkonzept => kurze Schrittanleitung für manuelle Tests
- [ ] (4) Unit Tests => Pro Person mindestens eine Klasse / Funktionalität testen
- [ ] (4) Integrationstest oder Ende-zu-Ende Test gegen eine Persistenz oder eine API

### 5. Build / Deploy / Maintanance:

- Wie wird eine eindeutige Version verwaltet und für den Kunden erzeugt?
- Wie wird die Software ausgeliefert?
- Wo wird die Software betrieben?

- [ ] (6) Buildkonzept: 
    - Wie wird der Build getriggert?
    - Was wird gebaut( Setup / JAR/Exe / Container)?
    - Wo wird gebaut?
    - Wann/Wie oft werden welche Tests ausgeführt?
    - Wer wird wann informiert Entwickler/Kunde/DevOps
- [ ] (2) Script für Semantic Versioning erstellen
- [ ] (2) Testautomatisierung in der Builpipeline

### 6. Querschnittsthemen:

Projektmanagement und Dokumentation wird zu unterschiedlichen Zeitpunkten im Projekt immer wieder relevant.

### 6.1 Projektmanagement:

- Welche Rollen gibt es im Team / Wer macht was?
- Wie/Wann wird vorgegangen? (MVP)
- Wann sollte welches Feature entwickelt werden?

- [ ] (3) Teamaufgaben festlegen, z.B.:
    - Wer arbeitet im UI/Backend?
    - Wer kümmert sich um was?
- [ ] (2) Vorgehen festlegen, z.B.:
    - Agiles vorgehen: welche Sprint Zyklen
- [ ] (3) Erneutes Schätzen nach Systementwurf und vor Implementierung
- [ ] (2) MVP festlegen und einzelne Aufgaben : Welches Feature ist am wichtigsten und wird als erstes umgesetzt, was wäre nice to have

Bonus:
- [ ] (4) Kanban/Scrum Board aufsetzen

### 6.2 Dokumentation:

- Wie kann die Zielgruppe das Projekt/Programm nutzen?
- Wie kann eine technische Schnittstelle verwedent werden?
- Wie kann ein Entwickler das System bauen/testen/weiterentwickeln?

- [ ] (4) Handbuch bzw. How to Anleitung oder kurzes Screen-Video
- [ ] (3) generierte Doku z.B. SwaggerUi, JDoc, JSDoc, XML-Doc
- [ ] (3) Readme.md für Entwickler:
    - Wie kann gebaut/getestet werden?
