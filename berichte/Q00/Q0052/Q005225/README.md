[English](README.md) · [Deutsch](README.de.md)

# Few-Shot Recalibration of Language Models

Report Q005225 · Source deepmind.google · Date 2024-03-27 · [Open original](https://deepmind.google/research/publications/47848/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Text enthält nur den Abstract, nicht den vollständigen Artikel. Er beschreibt ein Verfahren, das Konfidenzwerte von Sprachmodellen anhand weniger ungelabelter Beispiele für einzelne Bereiche nachkalibrieren soll; laut Abstract verbessert es unter anderem den Kalibrierungsfehler von PaLM2-Large auf MMLU um 16 Prozent gegenüber Temperature Scaling. Weitere Versuchsdetails und Einschränkungen sind im Auszug nicht enthalten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 7 / 44 % | 0 / 7 % | 94 / 97 % | 8 / 22 % | 5 / 16 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 41 / 74 % | 0 / 0 % | 76 / 92 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % |
