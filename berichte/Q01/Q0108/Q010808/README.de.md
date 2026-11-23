[English](README.md) · [Deutsch](README.de.md)

# Continuous Migration from PostgreSQL on Amazon EC2 to RDS

Bericht Q010808 · Quelle medium.com · Datum 2023-11-24 · [Original öffnen](https://medium.com/aws-tip/continuous-migration-from-postgresql-on-amazon-ec2-to-rds-be12ef09f63a)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag beschreibt, wie DMS eine PostgreSQL-Datenbank auf EC2 zu Aurora PostgreSQL in RDS migrieren und laufende Änderungen replizieren soll. Der Autor berichtet von einer erfolgreich eingerichteten Aufgabe, liefert aber keine unabhängigen Prüfungen der Datenkonsistenz oder Angaben zu Dauer und Umfang; das Beispiel nutzt teilweise eine Dev/Test-Konfiguration.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 8 / 60 % | 1 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
