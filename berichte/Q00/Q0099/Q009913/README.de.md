[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: A Little PitFall on Lazy Grid I Tripped On

Bericht Q009913 · Quelle medium.com · Datum 2026-02-01 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-a-little-pitfall-on-lazy-grid-i-tripped-on-cb0e864caff6)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht beschreibt, dass ein `LazyVGrid` beim Wechsel zwischen zwei Datenmodellen mit denselben IDs laut Autor alte Inhalte beibehält. Als Abhilfe empfiehlt er modellabhängige IDs für die Elemente oder `.id(modelDisplayed)` für das Raster; seine Aussage beruht auf einem Beispiel und enthält keine Benchmarks zur UUID-Leistung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
