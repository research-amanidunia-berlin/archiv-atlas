[English](README.md) · [Deutsch](README.de.md)

# Swift: Encode Struct Preserving Nil 3 Ways!

Bericht Q009718 · Quelle medium.com · Datum 2026-07-10 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-encode-struct-preserving-nil-3-ways-8a009f27959b)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht erläutert drei Swift-Ansätze, um optionale `nil`-Werte als JSON-`null` statt als fehlende Felder zu kodieren: Property Wrapper, Überschreiben von `encodeIfPresent` und eine `NilEncodable`-Konformität mit Reflection. Der Autor bevorzugt den letzten Weg, weist aber auf zusätzlichen Aufwand, begrenzte Steuerbarkeit und mögliche Leistungseinbußen hin; systematische Benchmarks enthält der Bericht nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
