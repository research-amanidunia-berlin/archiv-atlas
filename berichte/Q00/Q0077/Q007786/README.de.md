[English](README.md) · [Deutsch](README.de.md)

# Improved Techniques for Training Consistency Models

Bericht Q007786 · Quelle openai.com · Datum 2024-06-20 · [Original öffnen](https://openai.com/index/improved-techniques-for-training-consistency-models/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Die Autoren schlagen vor, Consistency Models ohne Destillation und mit mehreren Änderungen am Trainingsverfahren direkt aus Daten zu trainieren. Sie berichten verbesserte FID-Werte auf CIFAR-10 und ImageNet; der bereitgestellte Text enthält jedoch keine Einzelheiten zum Versuchsaufbau oder zu Unsicherheiten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 44 / 78 % | – | 19 / 36 % | 11 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 0 / 0 % | – | 43 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 29 / 45 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
