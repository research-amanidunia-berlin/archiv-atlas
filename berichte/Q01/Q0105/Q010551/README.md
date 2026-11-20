[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Floating Window/Panel

Report Q010551 · Source medium.com · Date 2024-11-09 · [Open original](https://medium.com/gitconnected/swiftui-macos-floating-window-panel-4eef94a20647)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht zeigt anhand von SwiftUI-Beispielcode, wie eine Unterklasse von `NSPanel` ein schwebendes macOS-Fenster mit konfigurierbarem Stil und Verhalten bereitstellt. Der Autor berichtet, dass `close()` in seinem Beispiel erst funktionierte, nachdem beim Öffnen zusätzlich zu `orderFront()` auch `makeKey()` aufgerufen wurde; eine systematische Prüfung für andere Umgebungen enthält der Beitrag nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
