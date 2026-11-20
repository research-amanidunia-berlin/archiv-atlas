[English](README.md) · [Deutsch](README.de.md)

# Access an Amazon RDS Database Using Lambda function (Python)

Bericht Q010805 · Quelle medium.com · Datum 2023-12-09 · [Original öffnen](https://medium.com/aws-tip/access-an-amazon-rds-database-using-lambda-function-python-293a014d1cd5)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht erläutert, wie eine Python-Lambda-Funktion PostgreSQL-Abfragen auf Amazon RDS ausführt und optional über einen RDS-Proxy verbindet. Der Autor empfiehlt den Proxy vor allem für regelmäßige Zugriffe, beschreibt Mehrkosten und weist auf die besondere Paketierung von psycopg2 hin; seine Aussagen zu den Proxy-Vorteilen werden nicht durch Vergleichsmessungen belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 28 / 56 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
