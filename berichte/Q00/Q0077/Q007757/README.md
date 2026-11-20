[English](README.md) · [Deutsch](README.de.md)

# Procgen Benchmark

Report Q007757 · Source openai.com · Date 2019-12-03 · [Open original](https://openai.com/index/procgen-benchmark/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI stellt Procgen als Benchmark mit 16 prozedural erzeugten RL-Umgebungen vor, der Generalisierung und Stichprobeneffizienz messen soll. Laut den berichteten Experimenten überanpassten Agenten bei kleinen Trainingsmengen häufig; vielfältige Level und getrennte Tests mit unbekannten Leveln machten Schwächen sichtbar, wobei der vorliegende Text keine konkreten Diagrammwerte enthält.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 51 / 88 % | – | 94 / 97 % | 11 / 30 % | 0 / 0 % | 10 / 22 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 45 / 92 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 15 / 47 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 10 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 19 % | 0 / 0 % | 5 / 13 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 5 / 10 % |
