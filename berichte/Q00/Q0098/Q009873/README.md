[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Extract Word From Index Two Ways

Report Q009873 · Source medium.com · Date 2026-02-27 · [Open original](https://medium.com/@itsuki.enjoy/swiftui-extract-word-from-index-two-ways-f8c47823bba2)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht zeigt zwei Swift-Methoden, um das Wort an einem Zeichenkettenindex zu bestimmen: den `UITextInputTokenizer` über `UITextView`/`UITextField` und `NLTagger`. Laut Autor kann `NLTagger` Satzzeichen und Leerraum als Wortbereiche behandeln; ergänzender Code filtert solche Bereiche, und eine Hilfsinitialisierung wandelt ganzzahlige Offsets in `String.Index` um.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
