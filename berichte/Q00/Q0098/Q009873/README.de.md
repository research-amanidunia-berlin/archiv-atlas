[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Extract Word From Index Two Ways

Bericht Q009873 · Quelle medium.com · Datum 2026-02-27 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-extract-word-from-index-two-ways-f8c47823bba2)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht zeigt zwei Swift-Methoden, um das Wort an einem Zeichenkettenindex zu bestimmen: den `UITextInputTokenizer` über `UITextView`/`UITextField` und `NLTagger`. Laut Autor kann `NLTagger` Satzzeichen und Leerraum als Wortbereiche behandeln; ergänzender Code filtert solche Bereiche, und eine Hilfsinitialisierung wandelt ganzzahlige Offsets in `String.Index` um.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
