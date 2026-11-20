[English](README.md) · [Deutsch](README.de.md)

# Estimating training compute of deep learning models

Report Q004371 · Source epoch.ai · Date 2022-01-20 · [Open original](https://epoch.ai/publications/estimating-training-compute)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Epoch AI stellt eine architekturbasierte FLOP-Zählung und eine Schätzung anhand von GPU-Zeit und Spitzenleistung vor. Beide hängen von Annahmen ab: besonders von Architekturdetails beziehungsweise Hardware, Zahlenpräzision und tatsächlicher GPU-Auslastung; Profiler können ebenfalls ungenau sein. Der Bericht empfiehlt, beide Schätzungen nach Möglichkeit als gegenseitige Plausibilitätskontrolle zu nutzen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 45 / 65 % | 78 / 98 % | 50 / 89 % | 54 / 79 % | 63 / 79 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 55 / 91 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 9 / 46 % | 0 / 0 % | 40 / 67 % | 11 / 30 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 30 / 54 % | 19 / 89 % | 0 / 0 % | 22 / 53 % | 15 / 41 % | 18 / 29 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 5 / 82 % | 0 / 0 % | 28 / 55 % | 6 / 16 % | 5 / 13 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 5 / 43 % | 1 / 18 % | 0 / 0 % | 11 / 30 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 11 / 63 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 9 / 16 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 28 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 5 / 49 % | 0 / 0 % | 0 / 0 % | 6 / 21 % | 8 / 16 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 0 % |
