[English](README.md) · [Deutsch](README.de.md)

# Little Swift Tip: AttributedString Attention Points

Report Q009644 · Source medium.com · Date 2026-09-19 · [Open original](https://medium.com/@itsuki.enjoy/little-swift-tip-attributedstring-attention-points-60285ed4cfd8)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor nennt vier Probleme bei Swift-Attributtexten: Formatierungen können bei `transformAttributes` über mehrere unterschiedlich formatierte Runs verloren gehen, `transform(updating:)` betreffe seiner Interpretation nach den gesamten String, das Zusammenführen könne das Entfernen von Attributen über `nil` ignorieren, und eigene Attribute würden nicht automatisch in Schreibattribute übernommen. Er zeigt mögliche Umgehungen, weist aber selbst auf Grenzen hin, insbesondere bei nicht zusammenhängenden Auswahlen; eine systematische Versionsprüfung beschreibt der Erfahrungsbericht nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
