# Krankenkassenprämien 2027 Schweiz (CSV)

Freier Datensatz zu den Prämien der obligatorischen Krankenversicherung (Grundversicherung) 2027, je Kanton und je
Prämienregion, mit dem Vergleich zu 2026. Gerechnet aus den Prämiendaten des Bundesamts für Gesundheit (BAG).

Herausgeber: [knety.ch](https://knety.ch/krankenkasse/praemien-2027#daten), dort steht die Auswertung mit Grafiken und
Erklärungen. Die Dateien hier sind dieselben wie die Downloads auf knety.ch.

## Dateien

| Datei | Inhalt |
|---|---|
| [`daten/kantone-2027.csv`](daten/kantone-2027.csv) | 26 Kantone: Schnitt der Monatsprämien aller Kassen 2026 und 2027, Veränderung in CHF und Prozent |
| [`daten/praemienregionen-2027.csv`](daten/praemienregionen-2027.csv) | 42 Prämienregionen: Anzahl Kassen, günstigste Kasse und Prämie 2027 und 2026, ob die günstigste Kasse wechselt, Spanne zwischen teuerster und günstigster Kasse aufs Jahr |

Format: UTF-8, Komma als Trennzeichen, Punkt als Dezimalzeichen, Beträge in CHF pro Monat (Spanne pro Jahr).

## Profil

Alle Zahlen gelten für **Erwachsene, Franchise CHF 300, Standardmodell, mit Unfall**. «Schnitt der Kassen» heisst:
jede Kasse gleich gewichtet, nicht nach Versicherten. Er ist deshalb nicht dasselbe wie die mittlere Prämie, die das
BAG über alle Versicherten rechnet. Prämienregion 0 heisst: Der Kanton hat keine Prämienregionen.

## Quelle und Lizenz

- Grundlage: Prämiendaten des BAG ([priminfo.admin.ch](https://www.priminfo.admin.ch/de/sparen/grundversicherung)).
- Lizenz: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de) (Text in [`LICENSE`](LICENSE)). Nutzung,
  Weitergabe und Bearbeitung sind frei, auch kommerziell, mit Quellenangabe:

  > Quelle: knety.ch, auf Basis der BAG-Prämiendaten

  Online bitte mit Link auf https://knety.ch/krankenkasse/praemien-2027.

Verbindlich sind die Prämien, die die Kasse in der Offerte nennt. Fehler gefunden? Bitte ein Issue eröffnen oder an
hallo@knety.ch schreiben.

---

**English:** Swiss mandatory health insurance premiums 2027 by canton and premium region (adults, CHF 300 deductible,
standard model, accident cover included), computed from the Federal Office of Public Health (FOPH/BAG) premium data.
CSV, UTF-8. License CC BY 4.0, attribution: «Quelle: knety.ch, auf Basis der BAG-Prämiendaten».
Details: https://knety.ch/krankenkasse/praemien-2027
