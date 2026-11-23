[English](README.md) · [Deutsch](README.de.md)

# A Guide to Optimizer Implementation for BERT at Scale

Bericht Q011109 · Quelle medium.com · Datum 2019-12-09 · [Original öffnen](https://medium.com/nvidia-ai/a-guide-to-optimizer-implementation-for-bert-at-scale-8338cc7f45fd)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der NVIDIA-Bericht beschreibt NVLAMB als schichtweise adaptierte AdamW-Variante für BERT-Training mit großen Batches. NVIDIA berichtet, dass Gradientenvor-Normalisierung und Bias-Korrektur für die Konvergenz wichtig waren; für die getesteten Lernraten-Abklingvarianten zeigte sich laut Artikel kein beobachtbarer Unterschied. Der Vergleich ist eingeschränkt, weil LAMB mit doppelt so vielen Trainingsbeispielen wie AdamW trainiert wurde und alternative Rezepte nicht geprüft wurden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 11 / 50 % | 81 / 88 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 5 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
