[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Expose App Actions to Folder/File Context Menu With NSService

Bericht Q009726 · Quelle medium.com · Datum 2026-06-29 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-macos-expose-app-actions-to-folder-file-context-menu-with-nsservice-ecaffb69b2f8)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht erläutert, wie macOS-Apps mit `NSServices` Finder-Kontextmenüaktionen bereitstellen, Datei-URLs über das `NSPasteboard` verarbeiten und sie SwiftUI-Ansichten oder neuen Fenstern übergeben können. Er empfiehlt unter anderem `NSRequiredContext` zu setzen, die Zwischenablage nach der Verarbeitung zu leeren und bei sandboxed Apps die Fensterwiederherstellung zu deaktivieren, da gespeicherte URLs später möglicherweise nicht verfügbar sind.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
