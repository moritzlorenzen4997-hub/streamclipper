# Kopf frei – Konzept

**Ein Satz:** Alles, was dir im Kopf herumgeht, in ein Feld tippen oder sprechen – Kopf frei sortiert es automatisch in Termine, Aufgaben, Einkaufsliste und Ideen.

## Täglicher Ablauf
| Wann | Was | Dauer |
|---|---|---|
| Morgens | „Heute“-Tab: Termine + Top 3 | 30 Sek. |
| Tagsüber | Gedanke kommt → reinsprechen → Sortieren | 5 Sek. |
| Im Supermarkt | Einkaufsliste, nach Abteilungen sortiert | – |
| Abends | „Rückblick“: Offenes auf morgen schieben, Serie halten | 1 Min. |

## Geld verdienen
1. **Freemium-Abo** – Lokal sortieren gratis; Pro 3,99 €/Monat bzw. 29,99 €/Jahr (unbegrenzt KI, Erinnerungen, Kalender-Sync, Geräte-Sync). Familie 5,99 €/Monat (geteilte Einkaufsliste – stärkster Grund zum Upgraden und für Weiterempfehlung).
2. **Affiliate über die Einkaufsliste** – „Online bestellen“ übergibt die Liste an Lieferdienste (REWE, Picnic, Flink …) gegen Provision.
3. **Später B2B** – Team-Version für kleine Betriebe (Handwerker, Praxen).

Kosten: Eine KI-Sortierung kostet Bruchteile eines Cents bis ca. 1 Cent – ein Pro-Nutzer mit 10 Dumps/Tag kostet unter 3 € im Monat; mit einem kleineren Modell deutlich weniger.

## Status Prototyp
- Läuft als installierbare Web-App (PWA), offline, Daten nur lokal im Browser.
- Lokaler deutscher Parser (Datum, Uhrzeit, Priorität, Lebensmittel-Kategorien).
- Optional echte KI: eigenen Claude-API-Schlüssel in den Einstellungen eintragen (für den Prototyp; im Produkt läuft die KI über einen eigenen Server, damit kein Schlüssel im Browser liegt).
- Noch nicht gebaut: Bezahlung, Konten/Sync, Push-Erinnerungen, Lieferdienst-Anbindung.
