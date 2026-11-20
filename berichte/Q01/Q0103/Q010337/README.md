[English](README.md) · [Deutsch](README.de.md)

# Rust Excel Reader (Parser) Part2: Parse Some Drawings!

Report Q010337 · Source medium.com · Date 2025-05-26 · [Open original](https://medium.com/gitconnected/rust-excel-reader-parser-part2-parse-some-drawings-93adcc6b503b)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Artikel gibt einen Überblick darüber, wie ein Rust-Parser Zeichnungen in Excel-Dateien über DrawingML-Beziehungen findet und deren Inhalte, Verankerung, Position, Gestaltung und Text ausliest. Der Autor sieht vollständiges Parsen von Grafikrahmen wegen ihrer beliebigen XML-Inhalte als kaum praktikabel an und beschränkt den möglichen Ansatz auf die Erkennung des Objekttyps; die Darstellung bleibt insgesamt auf hoher Ebene.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
