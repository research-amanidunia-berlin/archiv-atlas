[English](README.md) · [Deutsch](README.de.md)

# A Guide to Optimizer Implementation for BERT at Scale

Report Q011109 · Source medium.com · Date 2019-12-09 · [Open original](https://medium.com/nvidia-ai/a-guide-to-optimizer-implementation-for-bert-at-scale-8338cc7f45fd)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der NVIDIA-Bericht beschreibt NVLAMB als schichtweise adaptierte AdamW-Variante für BERT-Training mit großen Batches. NVIDIA berichtet, dass Gradientenvor-Normalisierung und Bias-Korrektur für die Konvergenz wichtig waren; für die getesteten Lernraten-Abklingvarianten zeigte sich laut Artikel kein beobachtbarer Unterschied. Der Vergleich ist eingeschränkt, weil LAMB mit doppelt so vielen Trainingsbeispielen wie AdamW trainiert wurde und alternative Rezepte nicht geprüft wurden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 11 / 50 % | 81 / 88 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 5 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
