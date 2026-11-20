[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Custom Dock Icon PRIMARY Action

Bericht Q009861 · Quelle medium.com · Datum 2026-03-07 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-macos-custom-dock-icon-primary-action-2d8fadd37a88)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht schlägt vor, den Dock-Klick über `applicationShouldHandleReopen` im `NSApplicationDelegate` abzufangen und mit `OpenWindowAction` ein bestimmtes SwiftUI-Fenster zu öffnen. Laut Autor verhindern die Rückgabe `false`, `.moveToActiveSpace` und ein einmaliges Öffnen mit anschließendem Schließen, dass das erste Fenster erscheint und das Ziel-Fenster im falschen Arbeitsbereich landet.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
