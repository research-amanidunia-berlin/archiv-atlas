[English](README.md) · [Deutsch](README.de.md)

# Rust: Handle (A tons of ) Optional Fields in Struct: Best Practice?

Report Q010657 · Source medium.com · Date 2024-07-02 · [Open original](https://medium.com/stackademic/rust-handle-a-tons-of-optional-fields-in-struct-best-practice-53b4e0bb7b91)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor schlägt als persönliche Lösung vor, optionale Rust-Felder in eine separate, mit `flatten` eingebundene Struktur auszulagern und sie über eine `HashMap<String, Value>` an eine Konstruktorfunktion zu übergeben. Unbekannte Schlüssel lösen laut Beitrag keinen Fehler aus; deshalb sollen zulässige Schlüssel dokumentiert werden, und bei `camelCase`-Serialisierung muss auch die Map diese Schreibweise nutzen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
