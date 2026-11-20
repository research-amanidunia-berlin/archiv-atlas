[English](README.md) · [Deutsch](README.de.md)

# Swift: Little UUID (Or CBUUID) Pitfall

Report Q009946 · Source medium.com · Date 2026-01-07 · [Open original](https://medium.com/@itsuki.enjoy/swift-little-uuid-or-cbuuid-pitfall-4789ece19695)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Artikel beschreibt zwei vom Autor berichtete Probleme durch unterschiedliche Groß- und Kleinschreibung von UUIDs: bei Bluetooth-Diensten in der `info.plist` und beim Abgleich einer Nutzer-ID mit einem Supabase-Storage-Ordner. Als Abhilfe für den Backend-Fall empfiehlt der Autor einen serverseitigen Vergleich ohne Beachtung der Schreibweise; die Ursachen werden anhand persönlicher Erfahrungen erläutert, nicht systematisch untersucht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
