[English](README.md) · [Deutsch](README.de.md)

# SwiftData: Some Predicates that Look FINE but Error on build or Just CRASH!

Bericht Q009640 · Quelle medium.com · Datum 2026-09-20 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftdata-some-predicates-that-look-fine-but-error-on-build-or-just-crash-bd8f2be1468c)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor berichtet von drei problematischen SwiftData-Prädikaten: Enum-Vergleiche, Array-Prüfungen und `ClosedRange.contains` können laut seinen Beispielen beim Bauen oder Abfragen fehlschlagen. Er nennt funktionierende Alternativen, darunter einen vorab gespeicherten Enum-Rohwert, Tags als eigene Modelle mit einer Zählprüfung sowie explizite Datumsgrenzen; die Beobachtungen sind ein persönlicher, nicht umfassender Erfahrungsbericht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 8 / 37 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
