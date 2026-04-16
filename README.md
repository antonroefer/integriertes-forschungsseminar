# GEO(G) 412 - Integriertes Forschungsseminar I

Dieses Repository begleitet das Seminarprojekt im SoSe 2026. Es dient als Arbeitsraum für die Recherche, die Dokumentation des KI-Einsatzes, die Ausarbeitung der Hausarbeit, die Präsentation und das begleitende Schreib- und Visualisierungsprojekt.

Schwerpunkt des Seminars ist GeoAI: aktuelle Themenfelder der geographischen Künstlichen Intelligenz kennenlernen, KI-Werkzeuge experimentell und reflektiert einsetzen und den gesamten Arbeitsprozess nachvollziehbar dokumentieren.

## Was in diesem Repository abgelegt wird

- Forschungstagebuch mit Experimenten, Ideen, Zwischenschritten und kritischen Reflexionen
- Literatur, Notizen und Material zur Hausarbeit
- Entwürfe für Präsentation und Diskussion
- Ergebnisse des Schreib- und Visualisierungsprojekts
- Code, Auswertungen und Abbildungen, sofern sie für das jeweilige Thema benötigt werden

## Prüfungsleistungen

Die Modulprüfung setzt sich aus folgenden Bestandteilen zusammen:

- Forschungstagebuch: 25 %
- Hausarbeit: 50 %
- Präsentation: 25 %

Wichtig für die Hausarbeit:

- Umfang: 3500 Wörter im Textteil
- Format: Arial 11, 1,15-zeilig, A4
- Literaturverweise im APA-Stil
- Abgabe elektronisch in Moodle
- Vor der Abgabe von Struktur und Bibliographie findet ein kurzes Gespräch mit dem Dozenten statt

## KI-Nutzung und Dokumentation

Die Nutzung von KI-Werkzeugen ist im Seminar ausdrücklich erlaubt, muss aber offengelegt und dokumentiert werden. Dafür gilt:

- KI-Einsatz in einem separaten KI-Quellenverzeichnis dokumentieren
- mindestens Werkzeugname, Version und Nutzungsdatum angeben
- direkte Übernahmen und Zwischenschritte nachvollziehbar kennzeichnen
- vollständige Prompts und Ausgaben dokumentieren, wenn sie für die Nachvollziehbarkeit nötig sind

Die zugehörige Freigabeerklärung liegt unter [references/Geo412-s2026 Freigabeerklärung.pdf](references/Geo412-s2026%20Freigabeerkl%C3%A4rung.pdf).

## Wichtige Termine

Die Termine können sich laut Kursbeschreibung noch ändern. Der aktuelle Wochenplan enthält unter anderem diese Fristen:

| Datum | Inhalt |
| --- | --- |
| 25.04.2026 | kurze Beiträge zu den KI-Experimenten |
| 27.04.2026 | Abgabe von Struktur und Bibliographie der Hausarbeit |
| 05.06.2026 | Abgabe der Hausarbeit |
| 13.07.2026 | Abgabe des Schreib- / Visualisierungsprojekts und des Forschungstagebuchs |

## Projektstruktur

```
├── README.md          <- Einstieg und Arbeitsübersicht
├── requirements.txt   <- Python-Abhängigkeiten
├── data               <- Daten des Projekts
│   ├── external       <- Externe Rohdaten und Quellen
│   ├── interim        <- Zwischenergebnisse der Aufbereitung
│   ├── processed      <- Endgültig aufbereitete Daten
│   └── raw            <- Unveränderte Originaldaten
├── models             <- Modelle, Modellstände und Vorhersagen
├── notebooks          <- Notebooks für Exploration, Analyse und Dokumentation
├── references         <- Kursunterlagen, Literatur und weitere Begleitdokumente
├── reports            <- Berichte, Abbildungen und Exportdateien
└── src                <- Python-Code für Datenaufbereitung, Analyse und Modellierung
```

## Lokale Einrichtung

1. Python-Umgebung anlegen oder die vorhandene `.venv` verwenden.
2. Abhängigkeiten installieren:

```bash
pip install -r requirements.txt
```

3. Die Beispieldatei für Umgebungsvariablen kopieren:

```bash
copy .env.example .env
```

4. Optional eigene Schlüssel oder Pfade in `.env` ergänzen.

## Arbeitsweise im Projekt

- Rohdaten unverändert in `data/raw` ablegen.
- Aufbereitete Zwischenstände in `data/interim` oder `data/processed` speichern.
- Quellen, Kursunterlagen und Literatur in `references` sammeln.
- Ergebnisse für die Abgabe in `reports` ablegen.
- Wiederverwendbaren Code in `src` entwickeln statt Logik nur in Notebooks zu lassen.

## Zugehörige Unterlagen

- [Kursbeschreibung](references/Geo412-s2026%20Kursbeschreibung.pdf)
- [Freigabeerklärung](references/Geo412-s2026%20Freigabeerkl%C3%A4rung.pdf)
- [KI-Leitfaden der Universität Basel](references/Leitfaden_KI_Universit%C3%A4t_Basel.pdf)