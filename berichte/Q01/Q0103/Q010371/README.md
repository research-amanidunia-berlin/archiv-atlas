[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Get Notified on TextField Entry/Delete

Report Q010371 · Source medium.com · Date 2025-04-30 · [Open original](https://medium.com/gitconnected/swiftui-get-notified-on-textfield-entry-delete-be04a68c0046)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht erklärt, dass SwiftUIs `.onChange` gleiche Ersetzungen und Rücktasten bei leerem Text nicht meldet, weil sich der Wert nicht ändert. Als Lösung zeigt er ein per `UIViewRepresentable` eingebundenes `UITextField` mit Delegate-Kennzeichen und überschriebenem `deleteBackward()`; die behauptete Wirkung wird mit Code und GIFs illustriert, ohne breitere Kompatibilitätsangaben.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
