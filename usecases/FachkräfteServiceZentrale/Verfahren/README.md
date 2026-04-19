# Dokumentenmappe — Davit Mgeladze
## Anerkennungsverfahren Hochschulabschluss | ZAB Statement of Comparability

---

> **Fallnummer:** AE-2026-GE-00147
> **Antragsteller:** Davit Mgeladze (`დავით მგელაძე`)
> **Verfahren:** Akademische Anerkennung (ZAB) — Eilverfahren
> **Stand:** April 2026
> **Status:** ⏳ Apostille ausstehend — Antrag noch nicht gestellt

---

## Inhaltsverzeichnis

| # | Dokument | Datei | Format | Status |
|---|----------|-------|--------|--------|
| 1 | **Lebenslauf (Curriculum Vitae)** | `cv_davit_mgeladze.md` | Markdown | ✅ Vollständig |
| 2 | **Anschreiben / Motivationsschreiben ZAB** | `motivationsschreiben_zab.md` | Markdown | ✅ Vollständig |
| 3 | **Hochschuldiplom (Urkunde)** | `diplom_urkunde.md` | Markdown | ⚠️ Apostille fehlt |
| 4 | **Transcript of Records (Notenübersicht)** | `transcript_of_records.md` | Markdown | ⚠️ Apostille fehlt |
| 5 | **Diploma Supplement** | `diploma_supplement.md` | Markdown | ⚠️ DE-Übersetzung ausstehend |
| 6 | **Jobangebot Baltic Software Solutions GmbH** | `jobangebot_baltic_software.md` | Markdown | ✅ Vollständig |
| 7 | **Goethe-Zertifikat B1** | `goethe_zertifikat_b1.md` | Markdown | ✅ Vollständig |
| — | **Fallakte (Metadaten, YAML)** | `../fallakte_davit_mgeladze.yml` | YAML | ✅ Vollständig |
| — | **Mission-Flow (Verfahren)** | `../hochschul_anerkennung_georgien.yml` | YAML | ✅ Bereit |

---

## Übersicht Dokumentenstatus

```
Dokumentenmappe Davit Mgeladze
│
├── ✅ Lebenslauf                     → vollständig
├── ✅ Anschreiben ZAB                → vollständig (inkl. Eilverfahren-Begründung)
├── ⚠️  Hochschuldiplom               → vorhanden, APOSTILLE FEHLT
├── ⚠️  Transcript of Records         → vorhanden, APOSTILLE FEHLT
├── ⚠️  Diploma Supplement            → vorhanden (EN), DE-Übersetzung ausstehend
├── ✅ Jobangebot (Eilverfahren)      → vollständig, mit Firmenstempel
└── ✅ Goethe-Zertifikat B1           → vollständig
```

---

## Zur Person

| Feld | Wert |
|---|---|
| **Name** | Davit Mgeladze / დავით მგელაძე |
| **Geburtsdatum** | 14. März 1999, Tiflis, Georgien |
| **Staatsangehörigkeit** | Georgisch |
| **Wohnsitz DE** | Fichtenweg 8, 18057 Rostock, MV |
| **Aufenthaltstitel** | § 20 AufenthG — Arbeitsplatzsuche (bis 01.09.2025) |
| **Abschluss** | B.Sc. Computer Science, TSU Tiflis, 2021 |
| **Gesamtnote** | B — 83/100 — „Very Good" / GPA 3.4 |
| **Jobangebot** | Baltic Software Solutions GmbH, Rostock (Start 01.07.2026) |

---

## Offene Punkte / To-Do

- [ ] **Apostille für Diplom + Transcript** — Beantragung beim LEPL National Bureau of Enforcement, Tbilisi läuft (Ref. NBE-2026-APO-38812). Eltern beauftragen Abholung und DHL-Express-Versand nach Rostock (ca. 2–3 Wochen).
- [ ] **Deutsche Übersetzung Diploma Supplement** — Vereidigter Übersetzer Mag. Nana Kvareli, Frankfurt, beauftragen. Geschätzte Kosten: 80–120 €, Bearbeitungszeit: 1 Woche.
- [ ] **ZAB-Antrag stellen** — Sobald Apostille vorliegt. Portal: [zab.kmk.org](https://zab.kmk.org). Gebühr: 208 €.
- [ ] **Eilverfahren beantragen** — Jobangebot Baltic Software Solutions GmbH liegt bei.

---

## Verwendung mit Mission-Flow

Diese Dokumentenmappe dient als Input für den Mission-Flow:

```bash
uv run python examples/flow.py --mission missions/hochschul_anerkennung_georgien.yml
```

Der Flow verarbeitet die Fallakte und führt folgende Schritte durch:
1. anabin-Prüfung & rechtliche Einordnung
2. Dokumentenprüfung & Mängelfeststellung
3. Antragstellung simulieren
4. Behördliche Prüfung & Bescheid
5. Gesamtfallbewertung & Musterbericht

---

## Wichtige Kontakte & Links

| Institution | Kontakt | Link |
|---|---|---|
| ZAB — Zentralstelle für ausländisches Bildungswesen | Berlin | [zab.kmk.org](https://zab.kmk.org) |
| anabin-Datenbank (KMK) | — | [anabin.kmk.org](https://anabin.kmk.org) |
| BundID (Antragspflicht) | — | [id.bund.de](https://id.bund.de) |
| IQ-Netzwerk MV — migra e.V. Rostock | 0381 444 311 60 | [iq-mv.de](https://www.iq-mv.de) |
| LEPL National Bureau of Enforcement (Apostille GE) | Tbilisi | [nba.gov.ge](https://nba.gov.ge) |
| TSU (Heimathochschule) | Tbilisi | [tsu.ge](https://www.tsu.ge) |

---

*Alle Dokumente in dieser Mappe sind fiktive Darstellungen zu Simulations- und Schulungszwecken.*
*Keine der enthaltenen Personen, Unternehmen oder Aktenzeichen existiert in der Realität.*
