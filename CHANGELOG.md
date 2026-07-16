# Changelog

Alle nennenswerten Änderungen an diesem Projekt werden hier dokumentiert.
Format orientiert sich an [Keep a Changelog](https://keepachangelog.com/de/1.1.0/),
Versionierung nach [Semantic Versioning](https://semver.org/lang/de/).

## [Unveröffentlicht]

- Nichts Offenes.

## [2.0.0] — 2026-07-16

Ausbaustufe: Der Blackrock-Regelteil (5 Leagues) kommt dazu. Das Tool deckt damit
beide Systeme ab — den Shadowrun-Würfelpool (D6) und den Blackrock-Hack (2W6).

### Neu

- **Blackrock-Tab**: Eigener Bereich für den 5-Leagues-Regelteil.
- **Avatar-Werte**: Wert antippen würfelt 2W6 + Wert gegen Zielwert 9.
- **Berufe**: Probe aus 2W6 + Stufe + Attribut + Spezialisierung gegen 9.
- **Kampf (5 Leagues)**: Vollständige Abwicklung mit bis zu 3 Abtauschen, Nah- und
  Fernkampf, Gegnerwerten (Kampfwert, Rüstung, KON, Wunden bis Fall, Schadensbonus),
  eigener Rüstung, Taktik-Wahl und einstellbarer Wirkung der Stärke im Schaden.
- **Einstellungen**: Werden mit im Spielstand gespeichert.

### Unverändert

- Würfler, Charaktere, Zustandsmonitor, Widerstand & Schaden und Initiative aus 1.0
  bleiben vollständig erhalten. Das Speicherformat ist unverändert — bestehende
  Spielstände werden weiter gelesen.

## [1.0.0] — 2026-06-20

Erste öffentliche Fassung.

### Enthalten

- **Würfler**: Shadowrun-Würfelpool (D6) mit Erfolgen (5–6), Patzer-Würfeln (1),
  Erkennung von Patzer und Kritischem Patzer, Wurf-Animation und Statistik.
- **Charaktere**: Mehrere Charakterbögen mit Attributen, Edge („Push the Limit"),
  situativem Modifikator und Proben per Klick.
- **Zustandsmonitor**: Getrennte Spuren für Körper- und Geistschaden, automatischer
  Wundabzug, K.-o.-Status und Heilung.
- **Widerstand & Schaden**: Schadenswiderstand, Entzug-Probe und automatische
  Bestimmung der Schadensart.
- **Initiative**: Reihenfolge inkl. NSCs, Verzögern und Rundenzählung.
- **Speicherung**: Automatische lokale Speicherung (`localStorage`) sowie
  JSON-Export/-Import.

[Unveröffentlicht]: https://github.com/KopfKinoK3/blackrock-sr2036-tool/compare/v2.0.0...HEAD
[2.0.0]: https://github.com/KopfKinoK3/blackrock-sr2036-tool/releases/tag/v2.0.0
[1.0.0]: https://github.com/KopfKinoK3/blackrock-sr2036-tool/releases/tag/v1.0.0
