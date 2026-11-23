[English](README.md) · [Deutsch](README.de.md)

# Improved Techniques for Training Consistency Models

Report Q007786 · Source openai.com · Date 2024-06-20 · [Open original](https://openai.com/index/improved-techniques-for-training-consistency-models/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Die Autoren schlagen vor, Consistency Models ohne Destillation und mit mehreren Änderungen am Trainingsverfahren direkt aus Daten zu trainieren. Sie berichten verbesserte FID-Werte auf CIFAR-10 und ImageNet; der bereitgestellte Text enthält jedoch keine Einzelheiten zum Versuchsaufbau oder zu Unsicherheiten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 44 / 78 % | 19 / 36 % | 11 / 28 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 43 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 29 / 45 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
