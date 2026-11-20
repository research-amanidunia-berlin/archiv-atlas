[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Supporting “Open With” is Easy, but there is a little Pitfall…

Report Q009720 · Source medium.com · Date 2026-07-08 · [Open original](https://medium.com/@itsuki.enjoy/swiftui-macos-supporting-open-with-is-easy-but-there-is-a-little-pitfall-63a20b5eed03)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht erklärt eine SwiftUI-Stolperfalle beim Öffnen von Bildern über macOS’ „Öffnen mit“: Ein zusätzlicher Aufruf von `openWindow(value:)` kann neben einem Fenster mit Datei-URL auch leere Fenster erzeugen. Der Autor empfiehlt, die URL direkt in die an `WindowGroup` gebundene Variable zu schreiben; ohne primäres Fenster oder Menüleistenoberfläche könne dennoch ein leeres Fenster aufgehen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
