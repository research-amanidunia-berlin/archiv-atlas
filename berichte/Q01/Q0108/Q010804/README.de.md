[English](README.md) · [Deutsch](README.de.md)

# Amazon SQS Triggered AWS Lambda: Console and CDK

Bericht Q010804 · Quelle medium.com · Datum 2023-12-12 · [Original öffnen](https://medium.com/aws-tip/amazon-sqs-triggered-aws-lambda-console-and-cdk-9c65d2922693)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag beschreibt die Einrichtung einer SQS-Lambda-Verarbeitung über AWS-Konsole und CDK und erläutert Unterschiede zwischen Standard- und FIFO-Warteschlangen sowie den Umgang mit Stapelfehlern. Die Beispiele enthalten erkennbare Mängel: Das CDK-Zeitlimit für die Sichtbarkeit widerspricht der eigenen Empfehlung, und der Handler-Code wirkt teilweise fehlerhaft.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 45 / 86 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
