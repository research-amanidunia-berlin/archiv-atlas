[English](README.md) · [Deutsch](README.de.md)

# Swift/MacOS: Why Cannot We Read User Selected File?

Report Q010617 · Source medium.com · Date 2024-08-14 · [Open original](https://medium.com/gitconnected/swift-macos-why-cannot-we-read-user-selected-file-a220b0c07b26)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor berichtet, dass ein erfolgreicher SwiftUI-Dateiimport auf macOS zwar eine Video-URL liefert, die Datei aber ohne gestarteten Sicherheitszugriff nicht lesbar ist. `startAccessingSecurityScopedResource()` vor der Verwendung soll das Problem in seinem Fall beheben; anschließend empfiehlt er, den Zugriff bei Nichtgebrauch mit `stopAccessingSecurityScopedResource()` zu beenden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
