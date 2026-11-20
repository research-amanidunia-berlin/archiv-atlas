[English](README.md) · [Deutsch](README.de.md)

# Automatic deployment of docker image based lambda function using AWS CodePipeline

Bericht Q010834 · Quelle medium.com · Datum 2023-08-21 · [Original öffnen](https://medium.com/aws-tip/automatic-deployment-of-docker-image-based-lambda-function-using-aws-codepipeline-114a23a5cb18)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor beschreibt einen AWS-Ablauf, der bei Änderungen in CodeCommit per CodePipeline und CodeBuild ein Docker-Image in ECR neu baut und damit eine Lambda-Funktion aktualisiert. Er ergänzt einen S3-Auslöser für veränderliche Daten und berichtet, dass CodeDeploy in seinem Versuch an den erforderlichen Versionsangaben scheiterte; die Funktionsnachweise sind Beispiele aus seiner eigenen Einrichtung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 49 / 73 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
