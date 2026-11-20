[English](README.md) · [Deutsch](README.de.md)

# Little SwiftUI Tip: Get View Size without Displaying the View

Bericht Q009897 · Quelle medium.com · Datum 2026-02-09 · [Original öffnen](https://medium.com/@itsuki.enjoy/little-swiftui-tip-get-view-size-without-displaying-the-view-346225197828)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Artikel empfiehlt zum Messen nicht angezeigter SwiftUI-Views unter iOS `UIHostingController.sizeThatFits(in:)` und unter macOS `NSHostingView.fittingSize`; eine Geometrie-Messung einer nicht dargestellten View ergebe laut Autor null. Die Hosting-Messungen wichen in den Beispielen geringfügig ab, was der Autor für meist ausreichend genau hält, ohne allgemeine Genauigkeitswerte zu nennen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
