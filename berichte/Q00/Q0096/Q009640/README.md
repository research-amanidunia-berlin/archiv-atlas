[English](README.md) · [Deutsch](README.de.md)

# SwiftData: Some Predicates that Look FINE but Error on build or Just CRASH!

Report Q009640 · Source medium.com · Date 2026-09-20 · [Open original](https://medium.com/@itsuki.enjoy/swiftdata-some-predicates-that-look-fine-but-error-on-build-or-just-crash-bd8f2be1468c)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor berichtet von drei problematischen SwiftData-Prädikaten: Enum-Vergleiche, Array-Prüfungen und `ClosedRange.contains` können laut seinen Beispielen beim Bauen oder Abfragen fehlschlagen. Er nennt funktionierende Alternativen, darunter einen vorab gespeicherten Enum-Rohwert, Tags als eigene Modelle mit einer Zählprüfung sowie explizite Datumsgrenzen; die Beobachtungen sind ein persönlicher, nicht umfassender Erfahrungsbericht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 8 / 37 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
