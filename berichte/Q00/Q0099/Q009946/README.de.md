[English](README.md) · [Deutsch](README.de.md)

# Swift: Little UUID (Or CBUUID) Pitfall

Bericht Q009946 · Quelle medium.com · Datum 2026-01-07 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-little-uuid-or-cbuuid-pitfall-4789ece19695)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Artikel beschreibt zwei vom Autor berichtete Probleme durch unterschiedliche Groß- und Kleinschreibung von UUIDs: bei Bluetooth-Diensten in der `info.plist` und beim Abgleich einer Nutzer-ID mit einem Supabase-Storage-Ordner. Als Abhilfe für den Backend-Fall empfiehlt der Autor einen serverseitigen Vergleich ohne Beachtung der Schreibweise; die Ursachen werden anhand persönlicher Erfahrungen erläutert, nicht systematisch untersucht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
