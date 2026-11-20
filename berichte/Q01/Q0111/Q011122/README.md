[English](README.md) · [Deutsch](README.de.md)

# BERT Meets GPUs

Report Q011122 · Source medium.com · Date 2019-04-24 · [Open original](https://medium.com/future-vision/bert-meets-gpus-403d3fbed848)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht schildert NVIDIAs Optimierung von BERT-large: Mit Mixed Precision und XLA habe sich das Vortraining auf Volta-GPUs in einem Versuch von 6,8 auf 3,3 Tage verkürzt, bei laut NVIDIA vergleichbarer Genauigkeit. Die Autoren veröffentlichen Trainingsrezepte und nennen Messwerte für SQuAD-Feinabstimmung und Inferenz; diese Ergebnisse gelten für die beschriebenen Daten, Software- und Hardwarebedingungen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 43 / 84 % | 0 / 0 % | 85 / 93 % | 41 / 64 % | 0 / 0 % | 10 / 28 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 80 / 97 % | 0 / 0 % | 31 / 53 % | 20 / 45 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 16 / 68 % | 0 / 0 % | 58 / 68 % | 7 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 21 / 58 % | 0 / 0 % | 56 / 74 % | 8 / 21 % | 0 / 0 % | 5 / 12 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 48 / 56 % | 6 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 32 / 58 % | 0 / 0 % | 41 / 62 % | 16 / 34 % | 0 / 0 % | 11 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 20 / 56 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 9 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 43 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
