[English](README.md) · [Deutsch](README.de.md)

# AWS Glue Table from Dynamo JSON in S3 2 Ways

Bericht Q010567 · Quelle medium.com · Datum 2024-10-19 · [Original öffnen](https://medium.com/gitconnected/aws-glue-table-from-dynamo-json-in-s3-2-ways-960edfe85b88)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel beschreibt zwei CDK-Ansätze, um nach S3 exportierte DynamoDB-Daten mit Glue für Athena verfügbar zu machen: einen Crawler mit automatischer Schemaerkennung und eine direkt definierte Tabelle mit festem Schema. Die Beispiele setzen bestimmte Exportpfade beziehungsweise beim direkten Ansatz eine String-Spalte `event_id` voraus; für Athena wird gezeigt, wie der verschachtelte Wert gezielt abgefragt wird.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
