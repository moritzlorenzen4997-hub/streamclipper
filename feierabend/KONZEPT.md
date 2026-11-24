# Feierabend – Sprach-Assistent für Handwerker

**Ein Satz:** Auf der Baustelle ins Handy sprechen – Stundenzettel, Bautagebuch, Materialliste und Rechnung entstehen automatisch.

## Problem
Handwerker verbringen abends 1–2 Stunden mit Papierkram: Stunden aufschreiben, Material zusammensuchen, Rechnung tippen. Zettel gehen verloren, Material wird vergessen und nie berechnet.

## Ablauf
1. Auf der Baustelle: „Bei Müller 6 Stunden zu zweit, 2 Steckdosen gesetzt, 12 m NYM 3x1,5 verlegt“ + Foto.
2. Die App ordnet es der Baustelle zu: Stunden, Arbeiten, Material, Fotos.
3. Am Ende: „Rechnung erstellen“ → alle offenen Einträge werden zur Rechnung (Stunden × Stundensatz, Material mit gelernten Preisen, USt., § 35a-Ausweis für Privatkunden) → PDF.
4. Bautagebuch mit Fotos als PDF für Kunde/Architekt.

## Geld verdienen
| Paket | Preis | Inhalt |
|---|---|---|
| Solo | 29 €/Monat | 1 Nutzer, unbegrenzt Baustellen & Rechnungen, KI-Erfassung |
| Team | 49 €/Monat + 9 € je Mitarbeiter | Gesellen erfassen per Handy, Chef rechnet ab |
| Später | Zusatz | E-Rechnung (XRechnung/ZUGFeRD), DATEV-Export, Angebote |

Rechenbeispiel: 500 Betriebe × Ø 40 € = 20.000 € Umsatz/Monat. KI-Kosten pro Betrieb: wenige Euro/Monat.

Vertrieb: Innungen, Großhändler (Elektro/SHK), Facebook-/WhatsApp-Gruppen von Handwerkern, Empfehlung von Betrieb zu Betrieb. 30 Tage kostenlos testen.

## Stand des Prototyps
- Installierbare Web-App (PWA), offline nutzbar, Daten nur lokal (localStorage + IndexedDB für Fotos).
- Diktat per Spracheingabe; lokaler deutscher Parser (Kunde, Datum, Stunden „von 7 bis 15:30 mit Pause“, „zu zweit“, Material mit Einheiten).
- Optional Claude-KI mit eigenem API-Schlüssel für freie Sprache und fachliche Materialbezeichnungen.
- Wochen-Stundenzettel mit CSV-Export, Rechnungen mit fortlaufender Nummer, bezahlt/offen/überfällig.

## Fehlt noch (vor dem Verkauf)
- Konten, Cloud-Sync, Team-Funktion; KI über eigenen Server statt API-Schlüssel im Browser.
- E-Rechnung (XRechnung/ZUGFeRD) – für Rechnungen an Firmen in Deutschland schrittweise Pflicht.
- GoBD-konforme Archivierung (Rechnungen unveränderbar speichern), Storno/Gutschrift statt Bearbeiten.
- Angebote/Kostenvoranschläge, DATEV-Export.
- Rechtliche Prüfung der Rechnungsvorlagen durch Steuerberater.
