[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Get Text Cursor (Caret) Position

Bericht Q009910 · Quelle medium.com · Datum 2026-02-02 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-macos-get-text-cursor-caret-position-05f1419c5cc8)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt, wie sich die Position eines Text-Carets in einem fokussierten macOS-Element über Accessibility-APIs auslesen lässt, und nennt nötige Berechtigungen sowie den Umgang mit `AXValue` und Koordinatensystemen. Die Methode ist laut Autor nicht universell: Bei Google Sheets und möglicherweise anderen Web-Apps ohne native Textelemente können die Bounds fehlerhaft sein.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
