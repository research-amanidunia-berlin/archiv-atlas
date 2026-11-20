[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Add An Toolbar Accessory View

Bericht Q009733 · Quelle medium.com · Datum 2026-06-25 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-macos-add-an-toolbar-accessory-view-311eb1049c73)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht erklärt, wie eine zusätzliche SwiftUI-Ansicht unter der macOS-Titelleiste mithilfe von `NSTitlebarAccessoryViewController`, `NSHostingView` und einem Helfer zum Ermitteln des `NSWindow` eingebunden wird. Als Einschränkungen nennt der Autor abweichendes Verhalten der SwiftUI-Nachbildung mit Split-Navigation oder Inspector sowie mögliche Layoutprobleme von `accessoryBar(id:)` mit Inspector; systematische Tests werden nicht beschrieben.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
