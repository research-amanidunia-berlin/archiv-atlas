[English](README.md) · [Deutsch](README.de.md)

# Amazon Cognito Lambda Trigger (CDK)

Bericht Q010493 · Quelle medium.com · Datum 2025-01-23 · [Original öffnen](https://medium.com/aws-tip/amazon-cognito-lambda-trigger-cdk-7e13db15b135)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Artikel erläutert die CDK-Anbindung von Cognito-Lambda-Triggern und zeigt eine Rust-Lambda als Post-Confirmation-Beispiel. Der Autor empfiehlt bei synchronen Triggern eine schnelle Antwort und die Rückgabe der Ereignisdaten; seine Aussage, VPC-Lambdas benötigten dafür keine zusätzliche Konfiguration, wird nicht durch Tests belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 46 / 75 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
