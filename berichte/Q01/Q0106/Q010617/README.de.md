[English](README.md) · [Deutsch](README.de.md)

# Swift/MacOS: Why Cannot We Read User Selected File?

Bericht Q010617 · Quelle medium.com · Datum 2024-08-14 · [Original öffnen](https://medium.com/gitconnected/swift-macos-why-cannot-we-read-user-selected-file-a220b0c07b26)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor berichtet, dass ein erfolgreicher SwiftUI-Dateiimport auf macOS zwar eine Video-URL liefert, die Datei aber ohne gestarteten Sicherheitszugriff nicht lesbar ist. `startAccessingSecurityScopedResource()` vor der Verwendung soll das Problem in seinem Fall beheben; anschließend empfiehlt er, den Zugriff bei Nichtgebrauch mit `stopAccessingSecurityScopedResource()` zu beenden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
