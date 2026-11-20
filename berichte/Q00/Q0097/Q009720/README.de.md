[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Supporting “Open With” is Easy, but there is a little Pitfall…

Bericht Q009720 · Quelle medium.com · Datum 2026-07-08 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-macos-supporting-open-with-is-easy-but-there-is-a-little-pitfall-63a20b5eed03)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht erklärt eine SwiftUI-Stolperfalle beim Öffnen von Bildern über macOS’ „Öffnen mit“: Ein zusätzlicher Aufruf von `openWindow(value:)` kann neben einem Fenster mit Datei-URL auch leere Fenster erzeugen. Der Autor empfiehlt, die URL direkt in die an `WindowGroup` gebundene Variable zu schreiben; ohne primäres Fenster oder Menüleistenoberfläche könne dennoch ein leeres Fenster aufgehen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
