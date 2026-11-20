[English](README.md) · [Deutsch](README.de.md)

# AWS: Cross Account Resource Access

Bericht Q010742 · Quelle medium.com · Datum 2024-04-02 · [Original öffnen](https://medium.com/stackademic/aws-cross-account-resource-access-4aad24a0d394)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Artikel zeigt, wie eine Lambda-Funktion über `sts:AssumeRole` temporäre Zugangsdaten erhält und damit S3-Buckets in einem anderen AWS-Konto auflistet; laut Bericht war ein Konsolentest erfolgreich. Er weist auf die begrenzte Unterstützung ressourcenbasierter Richtlinien hin, doch das Beispiel vergibt `AmazonS3FullAccess` und erläutert keine feinere Begrenzung der S3-Rechte.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 63 / 90 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
