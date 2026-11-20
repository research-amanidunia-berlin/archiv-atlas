[English](README.md) · [Deutsch](README.de.md)

# An empirical analysis of compute-optimal large language model training

Report Q002273 · Source deepmind.google · Date 2022-04-12 · [Open original](https://deepmind.google/blog/an-empirical-analysis-of-compute-optimal-large-language-model-training/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Die Autoren schätzen anhand von Trainingsversuchen, dass große Sprachmodelle ihrer Zeit für ihr Rechenbudget zu groß und mit zu wenigen Tokens trainiert waren. Chinchilla (70 Milliarden Parameter, 1,3 Billionen Tokens) habe bei gleichem Trainingsaufwand Gopher auf nahezu allen verglichenen Aufgaben übertroffen; der Bericht nennt jedoch keine Einzelwerte und weist beim PaLM-Vergleich auf einen anderen Trainingskorpus hin.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 56 / 89 % | 0 / 0 % | 81 / 89 % | 7 / 21 % | 5 / 12 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 41 / 56 % | 6 / 22 % | 6 / 14 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 15 / 65 % | 0 / 0 % | 23 / 42 % | 7 / 22 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 18 / 72 % | 1 / 11 % | 14 / 38 % | 17 / 42 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 33 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 5 / 13 % | 5 / 10 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 4 / 47 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % |
