[English](README.md) · [Deutsch](README.de.md)

# Decoupled DiLoCo: Resilient, Distributed AI Training at Scale

Report Q002708 · Source deepmind.google · Date 2026-04-23 · [Open original](https://deepmind.google/blog/decoupled-diloco/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind und Google Research stellen Decoupled DiLoCo als Ansatz vor, der Modelltraining über getrennte Rechenzentren mit weniger Synchronisation und größerer Ausfalltoleranz ermöglichen soll. Der Beitrag berichtet von geringerem Bandbreitenbedarf, höherem Goodput in Ausfalltests und vergleichbarer Benchmark-Leistung; ein Teil der Vergleiche beruht auf Simulationen, und die Ergebnisse werden vom Team selbst dargestellt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 42 / 75 % | 82 / 87 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 39 / 89 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 30 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 23 / 66 % | 36 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 19 / 92 % | 32 / 56 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 23 / 72 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 5 / 10 % | 0 / 5 % | 7 / 21 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 17 / 62 % | 21 / 39 % | 8 / 21 % | 0 / 0 % | 5 / 14 % | 1 / 10 % | 22 / 42 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 15 / 70 % | 20 / 35 % | 11 / 35 % | 0 / 0 % | 0 / 0 % | 1 / 10 % | 11 / 27 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 27 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 9 / 43 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
