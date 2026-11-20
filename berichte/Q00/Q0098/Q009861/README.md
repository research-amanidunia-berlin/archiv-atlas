[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Custom Dock Icon PRIMARY Action

Report Q009861 · Source medium.com · Date 2026-03-07 · [Open original](https://medium.com/@itsuki.enjoy/swiftui-macos-custom-dock-icon-primary-action-2d8fadd37a88)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht schlägt vor, den Dock-Klick über `applicationShouldHandleReopen` im `NSApplicationDelegate` abzufangen und mit `OpenWindowAction` ein bestimmtes SwiftUI-Fenster zu öffnen. Laut Autor verhindern die Rückgabe `false`, `.moveToActiveSpace` und ein einmaliges Öffnen mit anschließendem Schließen, dass das erste Fenster erscheint und das Ziel-Fenster im falschen Arbeitsbereich landet.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
