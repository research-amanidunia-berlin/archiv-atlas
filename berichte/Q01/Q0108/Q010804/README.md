[English](README.md) · [Deutsch](README.de.md)

# Amazon SQS Triggered AWS Lambda: Console and CDK

Report Q010804 · Source medium.com · Date 2023-12-12 · [Open original](https://medium.com/aws-tip/amazon-sqs-triggered-aws-lambda-console-and-cdk-9c65d2922693)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag beschreibt die Einrichtung einer SQS-Lambda-Verarbeitung über AWS-Konsole und CDK und erläutert Unterschiede zwischen Standard- und FIFO-Warteschlangen sowie den Umgang mit Stapelfehlern. Die Beispiele enthalten erkennbare Mängel: Das CDK-Zeitlimit für die Sichtbarkeit widerspricht der eigenen Empfehlung, und der Handler-Code wirkt teilweise fehlerhaft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 45 / 86 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
