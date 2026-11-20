[English](README.md) · [Deutsch](README.de.md)

# How to measure FLOP for neural networks empirically?

Report Q004906 · Source epoch.ai · Date 2021-11-29 · [Open original](https://epoch.ai/publications/measure-FLOP-empirically)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

In Versuchen mit 13 Netzen auf einer Tesla P100 schätzt der Autor die GPU-Auslastung für die meisten Architekturen auf 0,3 bis 0,75 und das Rückwärts-zu-Vorwärts-Verhältnis meist auf etwa 2:1. MobileNet und EfficientNet sind mit rund 0,04 Ausreißer; eine vermutete Ursache sind fehlerhafte Profiler-Zählungen, doch die Messungen sind generell durch Über- und Unterzählungen sowie mögliche Fehler eingeschränkt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 33 / 78 % | 0 / 0 % | 90 / 94 % | 6 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 88 / 94 % | 0 / 0 % | 4 / 10 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 31 / 75 % | 8 / 39 % | 31 / 52 % | 48 / 70 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 8 / 15 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 0 / 0 % |
