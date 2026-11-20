[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Expose App Actions to Folder/File Context Menu With NSService

Report Q009726 · Source medium.com · Date 2026-06-29 · [Open original](https://medium.com/@itsuki.enjoy/swiftui-macos-expose-app-actions-to-folder-file-context-menu-with-nsservice-ecaffb69b2f8)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht erläutert, wie macOS-Apps mit `NSServices` Finder-Kontextmenüaktionen bereitstellen, Datei-URLs über das `NSPasteboard` verarbeiten und sie SwiftUI-Ansichten oder neuen Fenstern übergeben können. Er empfiehlt unter anderem `NSRequiredContext` zu setzen, die Zwischenablage nach der Verarbeitung zu leeren und bei sandboxed Apps die Fensterwiederherstellung zu deaktivieren, da gespeicherte URLs später möglicherweise nicht verfügbar sind.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
