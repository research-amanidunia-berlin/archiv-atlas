[English](README.md) · [Deutsch](README.de.md)

# SwiftData: ResultObserver Needs ModelActor!

Report Q009634 · Source medium.com · Date 2026-09-28 · [Open original](https://medium.com/@itsuki.enjoy/swiftdata-resultobserver-needs-modelactor-76d9e23dbc7d)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor beschreibt einen SwiftData-Absturz beim Löschen, der sich beim Anzeigen eines Modellfelds zeigt, und vermutet als Ursache ein Datenrennen zwischen `ResultsObserver` und Löschvorgang. Er empfiehlt, CRUD-Operationen und Observer-Erstellung in einem `@ModelActor` mit gemeinsamem Modellkontext auszuführen; die genaue Fehlerursache bleibt im Bericht unbewiesen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
