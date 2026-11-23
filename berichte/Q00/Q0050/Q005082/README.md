[English](README.md) · [Deutsch](README.de.md)

# Relaxed Recursive Transformers: Effective Parameter Sharing with Layer-wise LoRA

Report Q005082 · Source deepmind.google · Date 2025-04-26 · [Open original](https://deepmind.google/research/publications/122290/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Auszug beschreibt eine Methode, die Transformer-Parameter über wiederholte Schichten teilt und sie mit schleifenspezifischen LoRA-Adaptern ergänzt. Laut Abstract können solche Modelle bei geringerem Umfang konkurrenzfähig bleiben; ein dynamisches Batching-Verfahren könnte den Durchsatz theoretisch um bis zu das 2,76-Fache steigern. Versuchsdetails aus dem vollständigen Artikel liegen hier nicht vor.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 33 / 59 % | 78 / 86 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 25 / 41 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 67 / 75 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 14 % |
