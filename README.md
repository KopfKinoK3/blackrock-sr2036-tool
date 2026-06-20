# Blackrock: Shadowrun 2036 — Würfeltool

Ein schlankes Spielleiter- und Spieler-Tool für die Shadowrun-2036-Runde **Blackrock**.
Würfelpool-Roller, Charakterbögen und Initiative-Tracker — alles in einer einzigen HTML-Datei. Keine Installation, kein Server, keine Abhängigkeiten.

**▶ Live-Demo:** https://KopfKinoK3.github.io/blackrock-sr2036-tool/

> Inoffizielles Fan-Tool. Läuft komplett lokal im Browser — deine Daten verlassen das Gerät nicht.

---

## Features

- **🎲 Würfler** — Shadowrun-Würfelpool (D6): Erfolge (5–6), Patzer-Würfel (1), Erkennung von Patzer und Kritischem Patzer, Wurf-Animation, Statistik zu Erfolgen und Summe.
- **👤 Charaktere** — Mehrere Charakterbögen mit Attributen, Edge („Push the Limit"), situativem Modifikator und Proben per Klick.
- **❤️ Zustandsmonitor** — Getrennte Schadensspuren für Körper und Geist, automatischer Wundabzug (−1 je 3 Kästchen), K.-o.-Status und Heilung.
- **🛡️ Widerstand & Schaden** — Schadenswiderstand (KON + Panzerung − Durchschlagskraft), Entzug-Probe, automatische Bestimmung der Schadensart.
- **⚡ Initiative** — Reihenfolge inklusive NSCs, Verzögern von Aktionen, Rundenzählung.
- **💾 Auto-Speicherung** — Speichert automatisch lokal im Browser; JSON-Export/-Import für Backups und Gerätewechsel.

## Schnellstart

**Online:** Die [Live-Demo](https://KopfKinoK3.github.io/blackrock-sr2036-tool/) öffnen.

**Lokal:**

1. Repo herunterladen (grüner **Code**-Button → **Download ZIP**) oder klonen.
2. `index.html` im Browser öffnen — fertig. Kein Build, keine Installation.

## Würfel-Logik (Kurzreferenz)

| Ergebnis | Bedeutung |
|---|---|
| 5–6 | Erfolg |
| 1 | Patzer-Würfel |
| ≥ 50 % Einsen | Patzer |
| Patzer + 0 Erfolge | Kritischer Patzer |

## Daten & Datenschutz

Das Tool nutzt ausschließlich den `localStorage` deines Browsers. Es gibt **keinen Server, keine Cookies, kein Tracking**. Über **⬇ Export / ⬆ Import** sicherst du deinen Spielstand als JSON-Datei oder überträgst ihn auf ein anderes Gerät. Mit **↺ Standard** setzt du auf den Auslieferungszustand zurück.

## Roadmap

Version **1.0** ist die stabile Erstfassung. Eine **Ausbaustufe ist in Vorbereitung** — Details siehe [CHANGELOG.md](CHANGELOG.md).

## Lizenz

Code unter der [MIT-Lizenz](LICENSE) — frei nutzbar, änderbar und weiterverteilbar mit Namensnennung.

**Marken-Hinweis:** *Shadowrun* ist eine eingetragene Marke von The Topps Company, Inc. und wird unter Lizenz von Catalyst Game Labs verwendet. Dies ist ein inoffizielles, nicht-kommerzielles Fan-Tool und steht in keiner Verbindung zu den Rechteinhabern. Die MIT-Lizenz bezieht sich ausschließlich auf den Code dieses Projekts.
