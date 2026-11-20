[English](README.md) · [Deutsch](README.de.md)

# Connect QuickSight with RDS in Private Subnet

Report Q010810 · Source medium.com · Date 2023-11-15 · [Open original](https://medium.com/aws-tip/connect-quicksight-with-rds-in-private-subnet-3cd03aa99080)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Artikel beschreibt, wie QuickSight über eine VPC-Verbindung auf eine private RDS-Datenbank zugreifen kann: mit einer regional begrenzten Sicherheitsgruppenregel, deren Zuordnung zur Datenbank und einer IAM-Ausführungsrolle für QuickSight. Der Autor empfiehlt, Änderungen am RDS-System im Wartungsfenster anzuwenden, und schlägt einen Verbindungstest über einen neuen RDS-Datensatz vor; die Anleitung belegt keine allgemeine Funktionsgarantie und verwendet teils weit gefasste Berechtigungen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 30 / 64 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
