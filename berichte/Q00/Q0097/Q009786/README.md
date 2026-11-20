[English](README.md) · [Deutsch](README.de.md)

# Swift: Wait! Locale.current is NOT My Current Locale?

Report Q009786 · Source medium.com · Date 2026-05-15 · [Open original](https://medium.com/@itsuki.enjoy/swift-wait-locale-current-is-not-my-current-locale-b68a571e99a1)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor berichtet, dass `Locale.current` in seiner nur englischsprachigen App zwar die richtige Region, aber nicht die erwartete Gerätesprache liefert. Er empfiehlt `Locale.preferredLocales` oder `Locale.preferredLanguages`, die laut ihm bevorzugte Sprachen und App-spezifische Überschreibungen abbilden; eine umfassende Prüfung legt der Bericht nicht vor.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
