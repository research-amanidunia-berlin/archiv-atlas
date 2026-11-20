[English](README.md) · [Deutsch](README.de.md)

# Amazon QuickSight: Combining and Visualizing Multiple RDS Databases All at Once

Bericht Q010802 · Quelle medium.com · Datum 2023-12-18 · [Original öffnen](https://medium.com/aws-tip/amazon-quicksight-combining-and-visualizing-multiple-rds-databases-all-at-once-6d23835f3597)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor beschreibt, wie Tabellen aus mehreren gleich strukturierten RDS-Datenbanken über Lake Formation, S3 und Athena per `UNION` in einem QuickSight-Dataset zusammengeführt und anhand einer Herkunftsspalte im gemeinsamen Dashboard gefiltert werden können. Der Ansatz setzt eine eingerichtete Datenübernahme und passende QuickSight-Berechtigungen voraus; die Tabellen müssen dieselben Spalten haben.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
