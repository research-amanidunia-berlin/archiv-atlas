[English](README.md) · [Deutsch](README.de.md)

# Connect QuickSight with RDS in Private Subnet

Bericht Q010810 · Quelle medium.com · Datum 2023-11-15 · [Original öffnen](https://medium.com/aws-tip/connect-quicksight-with-rds-in-private-subnet-3cd03aa99080)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel beschreibt, wie QuickSight über eine VPC-Verbindung auf eine private RDS-Datenbank zugreifen kann: mit einer regional begrenzten Sicherheitsgruppenregel, deren Zuordnung zur Datenbank und einer IAM-Ausführungsrolle für QuickSight. Der Autor empfiehlt, Änderungen am RDS-System im Wartungsfenster anzuwenden, und schlägt einen Verbindungstest über einen neuen RDS-Datensatz vor; die Anleitung belegt keine allgemeine Funktionsgarantie und verwendet teils weit gefasste Berechtigungen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 30 / 64 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
