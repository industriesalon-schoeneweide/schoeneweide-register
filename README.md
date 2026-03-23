# Eigentümer- & Investorenregister – Zukunftsort Schöneweide

Interaktives Register mit **68 Standort-Profilen** für den Touchscreen im Industriesalon Schöneweide.

**Version:** Beta_01 (03-2026) · **Live:** [industriesalon-schoeneweide.github.io/schoeneweide-register/](https://industriesalon-schoeneweide.github.io/schoeneweide-register/)

## Inhalt

`index.html` — Komplettes Register als Single-File-App (keine Abhängigkeiten, offline-fähig, ~180 KB).

## Features

| Feature | Beschreibung |
|---------|-------------|
| 🔍 **Volltextsuche** | Durchsucht alle Felder: Name, Eigentümer, Branche, Adresse, aktueller Stand |
| 🧭 **Navigationskarte** | Geo-orientierte Übersichtskarte mit Spree, S-Bahn-Stationen und 5 klickbaren Gebietszonen |
| 🗺️ **Schematische Karte** | Detaillierte Standortkarte Nord → Süd mit allen 68 Einträgen, Zonen-Dimming bei Filterung |
| 🏷️ **Status-Filter** | Aktiv / Entwicklung / Geplant / Unklar / Mieter |
| 🌍 **Gebietsfilter** | Oberschöneweide / Niederschöneweide / Nalepastraße / Wuhlheide / Plänterwald |
| ↕️ **Sortierung** | Nach ID (#), Name (A–Z), Gebiet, Status |
| 📖 **Verzeichnis A–Z** | Alphabetische Liste aller 68 Akteure mit eigener Suchfunktion |
| 🆕 **Änderungsprotokoll** | „Neu"-Button zeigt alle neuen Einträge der aktuellen Version |
| ⬇️ **Datenexport** | CSV- und JSON-Export des gesamten Registers |
| 📊 **Statistik-Dashboard** | Verteilung nach Rollen, Status, Gebieten und Top-Branchen |
| ℹ️ **Über den Standort** | Einleitung mit Geschichte der Elektropolis und Facts & Figures |
| 📚 **Quellenverzeichnis** | Vollständiges Verzeichnis aller 60+ Quelldokumente |
| ❓ **Ungeklärte Areale** | 6 Standorte mit unbekannten Eigentümern |
| 📱 **Touchscreen-optimiert** | Dark Theme, Inter + Playfair Display, offline-fähig |

## Facts & Figures (nach Teilgebiet)

| Teilgebiet | Profile | Eigentümer | Mieter | Projektentwickler | Aktiv | Entwicklung |
|------------|---------|-----------|--------|-------------------|-------|-------------|
| Oberschöneweide | 49 | 23 | 16 | 7 (+3 E+P) | 34 | 7 |
| Niederschöneweide | 9 | 4 | 4 | 1 | 6 | 2 |
| Nalepastraße | 3 | 2 | — | — (+1 E+P) | 1 | 1 |
| Weitere (Wuhlheide, Plänterwald etc.) | 7 | 3 | 3 | — (+1 E+P) | 4 | 1 |
| **Gesamt** | **68** | **32** | **23** | **8 (+5 E+P)** | **45** | **11** |

Kennzahlen: 130 ha Zukunftsort · 63 ha Rahmenplangebiet · ~1,5 Mrd. EUR geschätztes Investitionsvolumen · 14.000+ HTW-Studierende

## Datenquellen

| Quelle | Umfang | Seit Version |
|--------|--------|-------------|
| LOKATION:S Rahmenplan Oberschöneweide 2025–2026 | 142 Seiten | v06 |
| WISTA Regionalmanagement Schöneweide 2011–2017 | 57 Seiten | v06.1 |
| Gründungserklärung Standortgemeinschaft | Mai 2024 | v07 |
| Protokolle Gründungskomitee | Juni–Okt. 2024 | v07 |
| Stellungnahme der Standortgemeinschaft | Sept. 2025 | v07 |
| Standort-Workshop OSW (Dokumentation + Folien) | Juni 2025 | v07 |
| Machbarkeitsstudie Industriemuseum (Band 1–4) | 144 Seiten | v07 |
| BZI-Broschüre 2023 | 2023 | v07 |
| Potenzial Schöneweide / Brüssel-Videokonferenz | 2020 | v07 |
| Tourismus-Konzept Treptow-Köpenick (CIMA) | 2025–2026 | v07 |
| Transformationsort / Gelingensbedingungen | März 2026 | v07 |
| Futura Biennale Dokumentation | 2026 | v07 |
| DIEAG-Szenarien BE-Ufer | Nov. 2024 | v07 |
| UKSW-Mitgliederverzeichnis | 2026 | v08 |
| WF-Geschichte (Schimko 2026) | 2026 | v08 |
| Diverse PPTX (Umfragen, Berichte, Präsentationen) | 2023–2025 | v07 |

## Versionshistorie

- **Beta_01 / v08** (2026-03-22): **UKSW-Mitglieder-Integration + 12 neue Features + Atelier-Korrekturen.** 68 Einträge (+10 neue: IRIS GmbH, TGS Schöneweide, BTB GmbH, 1. FC Union Berlin, FEZ Berlin, ADMOS Immobilien, Stephanus gGmbH, ibis Styles Hotel, ksg Architekten, Ateliergemeinschaft G59/G60). 4 Einträge korrigiert: #16 Treptow-Ateliers (nicht mehr auf W-Str. 83-85, Teilumzug Wilms-Gebäude), #31 XTRO (Blunck, G83), #50 Atelierhaus 79 (GSE=Vermieter, Sven Hermann), #06 Urban Banks (3 Ateliergemeinschaften). 1 Eintrag gelöscht: #41 Atelierhaus 82 (existiert nicht, bestätigt Albert Markert). Quellen: UKSW-Mitgliederverzeichnis, WF-Geschichte (Schimko 2026), Albert Markert (Vor-Ort-Wissen März 2026).
- **v07** (2026-03-13): **Vollständige Workspace-Integration + Facts & Figures.** 59 Einträge (+4 neue: Innovationspark Wuhlheide, TGS Spreeknie, Electropolis Berlin/Industriemuseum-Projekt, botspot GmbH). 25 bestehende Einträge aktualisiert aus 60+ Workspace-Dokumenten. Neue Features: „Über den Standort"-Panel mit Einleitung und Facts & Figures nach Teilgebiet. „Quellen"-Panel mit vollständigem Quellenverzeichnis. Quellenmanifest (source_manifest.json) als Prozesssicherung eingeführt.
- **v06.1** (2026-03-13): **WISTA Regionalmanagement 2011-17 Integration.** 16 Einträge mit RM-Daten angereichert.
- **v06** (2026-03-13): **LOKATION:S Rahmenplan Vollintegration.** 55 Einträge (+4 neue: Handwerkerhof, ITZ 4.0, IBA 2034, Standortgemeinschaft).
- **v05** (2026-03-12): 51 Einträge (+4 neue: Spreepark, Atelierhaus Reinbeckstraße, Atelierhaus 79, Rahmenplan OSW).
- **v04** (2026-03-12): 47 Einträge, Umlaut-Korrektur, Quellen erweitert
- **v03** (2026-03-12): Spree 27 korrigiert (Tabbertstraße, 18.000 m² BGF)
- **v02** (2026-03-11): 47 Einträge (+4 neue: W90a, W91, W92, W93)
- **v01** (2026-03-10): 43 Einträge, Erstversion GitHub Pages

## Neue Einträge v08

| # | Name | Eigentümer/Betreiber | Gebiet | Branche |
|---|------|---------------------|--------|---------|
| 60 | IRIS GmbH | Andreas Thun (Gründer) | Oberschöneweide | Mikrosystemtechnik, Sensorik |
| 61 | TGS Schöneweide | HTW Berlin | Oberschöneweide | Gründerzentrum, Inkubator |
| 62 | BTB GmbH | BTB GmbH Berlin | Oberschöneweide | Energieversorgung, Geothermie |
| 63 | 1. FC Union Berlin | 1. FC Union Berlin e.V. | Niederschöneweide | Profifußball, Wirtschaftsfaktor |
| 64 | FEZ Berlin | Land Berlin | Wuhlheide | Freizeit, Bildung, Kultur |
| 65 | ADMOS Immobilien AG | ADMOS Immobilien AG | Oberschöneweide | Immobilien |
| 66 | Stephanus gGmbH | Stephanus-Stiftung | Oberschöneweide | Sozialwirtschaft, Inklusion |
| 67 | ibis Styles Hotel | Accor Hotels | Oberschöneweide | Hotellerie |
| 68 | ksg Architekten | ksg Architekten | Oberschöneweide | Architektur, Stadtplanung |
| 69 | Ateliergemeinschaft G59/G60 | GSE gGmbH (Mieter) / XIOR (vermutet) | Oberschöneweide | Kunst, Ateliers |

## Literatur & Quellen

- LOKATION:S – Rahmenplan Oberschöneweide 2025–2026 (142 Seiten)
- WISTA Regionalmanagement Schöneweide 2011–2017 (57 Seiten)
- Machbarkeitsstudie Industriemuseum Berlin Schöneweide (Band 1–4)
- BZI-Broschüre 2023 (Berliner Zentrum für Industriekultur)
- Gründungserklärung & Stellungnahme Standortgemeinschaft Schöneweide
- Standortkonferenz-Dokumentation Juni 2025
- UKSW-Mitgliederverzeichnis 2026
- Schimko (2026): WF-Geschichte – Werk für Fernsehelektronik, 42 Ausgründungen
- Metropole Berlin. Die Wiederentdeckung der Industriekultur (bebra verlag)
- Berliner Schriften zur Industriekultur, Bd. 2
- Grün Berlin GmbH – Spreepark Projektdokumentation 2024–2027
- entwicklungsstadt.de | Berliner Morgenpost | Berliner Zeitung | Tagesspiegel | rbb24

## Technisch

- **Single-File-App**: Alles in einer `index.html` (HTML + CSS + JS + Daten, ~180 KB)
- **Keine Abhängigkeiten**: Kein Build-Prozess, keine externen Libraries, kein Framework
- **Offline-fähig**: Funktioniert ohne Internetverbindung (Fonts als Fallback)
- **GitHub Pages**: Automatisches Deployment bei Push auf `main`
- **Datenstruktur**: JavaScript-Array `const P=[...]` mit 18 Feldern pro Eintrag
- **Zwei Karten**: Geo-Navigationskarte (Überblick) + schematische Detailkarte (alle Einträge)
- **1.180+ Zeilen** Code (HTML + CSS + JS), 68 Datensätze, 15 Features

## Herausgeber

Industriesalon Schöneweide e.V. · Version Beta_01 (03-2026)
