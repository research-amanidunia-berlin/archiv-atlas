[English](README.md) · [Deutsch](README.de.md)

# Quantifying generalization in reinforcement learning

Report Q008468 · Source openai.com · Date 2018-12-06 · [Open original](https://openai.com/index/quantifying-generalization-in-reinforcement-learning/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt CoinRun als Testumgebung vor, um zu messen, wie gut Reinforcement-Learning-Agenten auf ungesehene Levels verallgemeinern. Die Experimente zeigen laut Autor, dass Überanpassen auch bei großen Trainingsmengen bestehen bleibt, während unter anderem IMPALA-CNN und stochastische Umgebungen die Testleistung verbessern; offen bleibt, wie weit sich diese Erkenntnisse auf komplexere Aufgaben übertragen lassen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 49 / 80 % | – | 94 / 97 % | 12 / 33 % | 9 / 23 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 56 / 85 % | – | 68 / 77 % | 8 / 21 % | 5 / 14 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 13 / 53 % | – | 33 / 55 % | 7 / 18 % | 4 / 12 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 12 / 29 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 30 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 4 / 7 % |
