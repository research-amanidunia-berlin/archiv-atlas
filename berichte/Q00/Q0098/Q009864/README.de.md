[English](README.md) · [Deutsch](README.de.md)

# Little Swift Tip: Encode/Decode Dates

Bericht Q009864 · Quelle medium.com · Datum 2026-03-06 · [Original öffnen](https://medium.com/@itsuki.enjoy/little-swift-tip-encode-decode-dates-e9f5628ad5bb)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt, dass Swift-Datumswerte bei der Standard-Codable-Verarbeitung anders interpretiert werden können als Unix-Zeitstempel und dadurch im Beispiel um rund 31 Jahre abweichen. Eigene Strategien oder manuelles Codable bieten Abhilfe, haben laut Autor aber Einschränkungen bei Präzision, Einsatzkontext oder zusätzlichem Code; die passende Speicherung hängt auch davon ab, ob der Typ ein Datenbankmodell ist.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
