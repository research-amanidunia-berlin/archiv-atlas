[English](README.md) · [Deutsch](README.de.md)

# SwiftData: ResultObserver Needs ModelActor!

Bericht Q009634 · Quelle medium.com · Datum 2026-09-28 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftdata-resultobserver-needs-modelactor-76d9e23dbc7d)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor beschreibt einen SwiftData-Absturz beim Löschen, der sich beim Anzeigen eines Modellfelds zeigt, und vermutet als Ursache ein Datenrennen zwischen `ResultsObserver` und Löschvorgang. Er empfiehlt, CRUD-Operationen und Observer-Erstellung in einem `@ModelActor` mit gemeinsamem Modellkontext auszuführen; die genaue Fehlerursache bleibt im Bericht unbewiesen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
