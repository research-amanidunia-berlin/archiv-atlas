[English](README.md) · [Deutsch](README.de.md)

# Techniques for training large neural networks

Report Q008106 · Source openai.com · Date 2022-06-09 · [Open original](https://openai.com/index/techniques-for-training-large-neural-networks/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht erklärt Daten-, Pipeline- und Tensor-Parallelität sowie Mixture-of-Experts als Ansätze, das Training großer neuronaler Netze über mehrere GPUs zu verteilen. Ergänzend beschreibt er Speichertechniken wie Checkpointing, gemischte Genauigkeit, Auslagern und Kompression und weist auf jeweilige Kosten und Abwägungen hin.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 9 / 69 % | 37 / 70 % | 6 / 17 % | 0 / 0 % | 3 / 12 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 23 / 73 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 4 / 9 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 20 / 73 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 17 / 76 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 16 / 84 % | 2 / 22 % | 8 / 26 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 10 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 5 / 70 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 3 / 42 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
