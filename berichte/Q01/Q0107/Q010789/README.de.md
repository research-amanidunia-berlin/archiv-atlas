[English](README.md) · [Deutsch](README.de.md)

# Upload/Download Files to/from Amazon S3 through API Gateway (Console & CDK)

Bericht Q010789 · Quelle medium.com · Datum 2024-01-20 · [Original öffnen](https://medium.com/aws-tip/upload-files-to-amazon-s3-through-api-gateway-console-cdk-eaee1a34dbd7)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt, wie API Gateway per direkter S3-Integration Objekte eines festgelegten Buckets auflisten, abrufen und hochladen kann, und beschreibt die Einrichtung in der Konsole sowie mit CDK. Laut Autor liefert die Auflistung XML; Binärdateien benötigen zusätzliche Medientyp- und Durchreicheinstellungen, und Schlüssel mit Sonderzeichen müssen kodiert werden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 47 / 73 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
