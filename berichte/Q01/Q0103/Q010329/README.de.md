[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: UITextView with Dynamic Height + An Optional MaxHeight

Bericht Q010329 · Quelle medium.com · Datum 2025-06-01 · [Original öffnen](https://medium.com/gitconnected/swiftui-uitextview-with-dynamic-height-an-optional-maxheight-bd84ef7f8b55)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel schlägt vor, die Höhe eines in SwiftUI eingebetteten `UITextView` mit `sizeThatFits` zu messen und über ein Binding an `.frame(maxHeight:)` weiterzugeben. Die vom Autor erprobten Alternativen führten unter anderem zu unerwünschter Anfangshöhe oder fehlendem Textumbruch; systematische Tests für weitere Umgebungen beschreibt der Bericht nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
