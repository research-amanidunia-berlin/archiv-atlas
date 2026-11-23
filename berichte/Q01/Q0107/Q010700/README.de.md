[English](README.md) · [Deutsch](README.de.md)

# New Relic for Monitoring AWS: Lambda Metrics & CloudWatch Logs

Bericht Q010700 · Quelle medium.com · Datum 2024-05-16 · [Original öffnen](https://medium.com/aws-tip/new-relic-for-monitoring-aws-lambda-metrics-cloudwatch-logs-7ae355a00b3e)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor schildert, wie sich AWS-Metriken über Metric Streams und Lambda- sowie CloudWatch-Logs über New Relic integrieren lassen, einschließlich IAM-, CloudFormation- und CLI-Schritten. Er berichtet von sichtbaren Daten nach der Einrichtung und nennt Fehlerquellen wie fehlende Log-Gruppen und mögliche Log-Kaskaden; unabhängige Tests enthält der Beitrag nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 7 / 42 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
