[English](README.md) · [Deutsch](README.de.md)

# Continuous Migration from PostgreSQL on Amazon EC2 to RDS

Report Q010808 · Source medium.com · Date 2023-11-24 · [Open original](https://medium.com/aws-tip/continuous-migration-from-postgresql-on-amazon-ec2-to-rds-be12ef09f63a)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag beschreibt, wie DMS eine PostgreSQL-Datenbank auf EC2 zu Aurora PostgreSQL in RDS migrieren und laufende Änderungen replizieren soll. Der Autor berichtet von einer erfolgreich eingerichteten Aufgabe, liefert aber keine unabhängigen Prüfungen der Datenkonsistenz oder Angaben zu Dauer und Umfang; das Beispiel nutzt teilweise eine Dev/Test-Konfiguration.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 8 / 60 % | 0 / 0 % | 1 / 13 % | 0 / 0 % | 0 / 0 % |
