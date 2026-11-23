[English](README.md) · [Deutsch](README.de.md)

# Relaxed Recursive Transformers: Effective Parameter Sharing with Layer-wise LoRA

Bericht Q005082 · Quelle deepmind.google · Datum 2025-04-26 · [Original öffnen](https://deepmind.google/research/publications/122290/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Auszug beschreibt eine Methode, die Transformer-Parameter über wiederholte Schichten teilt und sie mit schleifenspezifischen LoRA-Adaptern ergänzt. Laut Abstract können solche Modelle bei geringerem Umfang konkurrenzfähig bleiben; ein dynamisches Batching-Verfahren könnte den Durchsatz theoretisch um bis zu das 2,76-Fache steigern. Versuchsdetails aus dem vollständigen Artikel liegen hier nicht vor.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 33 / 59 % | 78 / 86 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 25 / 41 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 67 / 75 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 14 % |
