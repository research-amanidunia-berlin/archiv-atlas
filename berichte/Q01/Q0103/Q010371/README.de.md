[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Get Notified on TextField Entry/Delete

Bericht Q010371 · Quelle medium.com · Datum 2025-04-30 · [Original öffnen](https://medium.com/gitconnected/swiftui-get-notified-on-textfield-entry-delete-be04a68c0046)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht erklärt, dass SwiftUIs `.onChange` gleiche Ersetzungen und Rücktasten bei leerem Text nicht meldet, weil sich der Wert nicht ändert. Als Lösung zeigt er ein per `UIViewRepresentable` eingebundenes `UITextField` mit Delegate-Kennzeichen und überschriebenem `deleteBackward()`; die behauptete Wirkung wird mit Code und GIFs illustriert, ohne breitere Kompatibilitätsangaben.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
