[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: A Little Better Way of Asynchronous Data Fetch + Refresh

Bericht Q009960 · Quelle medium.com · Datum 2025-12-28 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-a-little-better-way-of-asynchronous-data-fetch-refresh-761be092230f)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor empfiehlt, Datenabrufe in SwiftUI über `.task(id:)` zu steuern: Eine Zustandsvariable dient als ID und wird bei einer Aktualisierung erhöht, wodurch der Abruf erneut ausgeführt wird. So lassen sich der Aufruf beim Anzeigen und beim Aktualisieren bündeln; die behaupteten Vorteile bei der Abbruchmöglichkeit werden im kurzen Beitrag nicht durch Messungen belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
