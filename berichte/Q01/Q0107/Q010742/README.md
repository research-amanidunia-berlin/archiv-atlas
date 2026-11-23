[English](README.md) · [Deutsch](README.de.md)

# AWS: Cross Account Resource Access

Report Q010742 · Source medium.com · Date 2024-04-02 · [Open original](https://medium.com/stackademic/aws-cross-account-resource-access-4aad24a0d394)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Artikel zeigt, wie eine Lambda-Funktion über `sts:AssumeRole` temporäre Zugangsdaten erhält und damit S3-Buckets in einem anderen AWS-Konto auflistet; laut Bericht war ein Konsolentest erfolgreich. Er weist auf die begrenzte Unterstützung ressourcenbasierter Richtlinien hin, doch das Beispiel vergibt `AmazonS3FullAccess` und erläutert keine feinere Begrenzung der S3-Rechte.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 63 / 90 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
