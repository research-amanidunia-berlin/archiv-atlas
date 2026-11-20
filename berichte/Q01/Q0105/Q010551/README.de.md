[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Floating Window/Panel

Bericht Q010551 · Quelle medium.com · Datum 2024-11-09 · [Original öffnen](https://medium.com/gitconnected/swiftui-macos-floating-window-panel-4eef94a20647)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht zeigt anhand von SwiftUI-Beispielcode, wie eine Unterklasse von `NSPanel` ein schwebendes macOS-Fenster mit konfigurierbarem Stil und Verhalten bereitstellt. Der Autor berichtet, dass `close()` in seinem Beispiel erst funktionierte, nachdem beim Öffnen zusätzlich zu `orderFront()` auch `makeKey()` aufgerufen wurde; eine systematische Prüfung für andere Umgebungen enthält der Beitrag nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
