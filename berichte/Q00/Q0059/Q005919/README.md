[English](README.md) · [Deutsch](README.de.md)

# Premise Order Matters in Reasoning with Large Language Models

Report Q005919 · Source deepmind.google · Date 2024-02-14 · [Open original](https://deepmind.google/research/publications/75421/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Abstract-Auszug berichtet, dass große Sprachmodelle bei Schlussfolgerungsaufgaben stark von der Reihenfolge der Prämissen abhängen und Umordnungen die Genauigkeit deutlich senken können. Auch für den neu vorgestellten, auf GSM8K basierenden Benchmark R-GSM melden die Forschenden einen Rückgang; Details zu Methoden und Auswertung enthält der Auszug nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 9 / 30 % | – | 7 / 17 % | 0 / 0 % | 4 / 11 % | 0 / 5 % | 23 / 38 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
