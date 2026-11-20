[English](README.md) · [Deutsch](README.de.md)

# LlamaIndex with Structured Data (RDS and S3): An alternative to QuickSight Q?

Bericht Q010795 · Quelle medium.com · Datum 2024-01-03 · [Original öffnen](https://medium.com/aws-tip/llamaindex-with-structured-data-rds-and-s3-an-alternative-to-quicksight-q-e7441633ce74)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag zeigt, wie LlamaIndex natürlichsprachliche Fragen in SQL für RDS-PostgreSQL sowie für über Athena zugängliche S3-Daten umsetzt und wie sich dafür GPT-4 konfigurieren lässt. Der Autor sieht Potenzial für Datenfragen, berichtet aber von Kontextlimits bei vielen Tabellen und hält einen Ersatz für QuickSight Q wegen ungeprüfter komplexer Anfragen und fehlender Visualisierungen nur für teilweise möglich.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | – | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | – | 0 / 0 % |
