# Mapping von Baureihen und Fahrzeugnummern auf die Fahrzeugnamen

Diese Datei enthält eine Zuordnung von Baureihen und Fahrzeugnummern zu den entsprechenden Fahrzeugnamen.

## Aufbau der `baureihen.csv`

Die CSV-Datei ist durch Semikolons getrennt.

Die Spalten sind wie folgt aufgebaut:

- `uic_regex`: Ein regulärer Ausdruck, der die UIC-Nummer beschreibt
- `coachgroup`: Der Verbundsname des Fahrzeugs
- `short_name`: Der Kurzname der Baureihe
- `name`: Der vollständige Name der Baureihe
- `additional_info`: Zusätzliche Informationen zur Baureihe (z.B. Anzahl der Wagen)
- `colloquial_names`: Umgangssprachliche Namen der Baureihe durch Komma getrennt
- `comments`: Zusätzliche Kommentare soweit nötig

## Aufbau der `fahrzeuge.csv`

Die CSV-Datei ist durch Semikolons getrennt.

Die Spalten sind wie folgt aufgebaut:

- `uic_number`: Die UIC-Nummer des Fahrzeugs
- `coachgroup`: Der Verbundsname des Fahrzeugs
- `given_name`: Der Taufname des Fahrzeugs
- `special_features`: Besondere Merkmale des Fahrzeugs (z.B. besondere Beklebung)
- `comments`: Zusätzliche Kommentare soweit nötig
