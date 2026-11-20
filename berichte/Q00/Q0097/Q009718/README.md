[English](README.md) · [Deutsch](README.de.md)

# Swift: Encode Struct Preserving Nil 3 Ways!

Report Q009718 · Source medium.com · Date 2026-07-10 · [Open original](https://medium.com/@itsuki.enjoy/swift-encode-struct-preserving-nil-3-ways-8a009f27959b)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht erläutert drei Swift-Ansätze, um optionale `nil`-Werte als JSON-`null` statt als fehlende Felder zu kodieren: Property Wrapper, Überschreiben von `encodeIfPresent` und eine `NilEncodable`-Konformität mit Reflection. Der Autor bevorzugt den letzten Weg, weist aber auf zusätzlichen Aufwand, begrenzte Steuerbarkeit und mögliche Leistungseinbußen hin; systematische Benchmarks enthält der Bericht nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
