[English](README.md) · [Deutsch](README.de.md)

# Rust: Handle (A tons of ) Optional Fields in Struct: Best Practice?

Bericht Q010657 · Quelle medium.com · Datum 2024-07-02 · [Original öffnen](https://medium.com/stackademic/rust-handle-a-tons-of-optional-fields-in-struct-best-practice-53b4e0bb7b91)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor schlägt als persönliche Lösung vor, optionale Rust-Felder in eine separate, mit `flatten` eingebundene Struktur auszulagern und sie über eine `HashMap<String, Value>` an eine Konstruktorfunktion zu übergeben. Unbekannte Schlüssel lösen laut Beitrag keinen Fehler aus; deshalb sollen zulässige Schlüssel dokumentiert werden, und bei `camelCase`-Serialisierung muss auch die Map diese Schreibweise nutzen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
