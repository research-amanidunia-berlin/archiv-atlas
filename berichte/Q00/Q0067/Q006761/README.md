[English](README.md) · [Deutsch](README.de.md)

# MoE vs AI dense models: How do they compare in inference?

Report Q006761 · Source epoch.ai · Date 2024-12-20 · [Open original](https://epoch.ai/gradient-updates/moe-vs-dense-models-inference)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor argumentiert, dass MoEs bei gleicher Gesamtgröße häufig günstiger als dichte Modelle sind, aber ihre aktiven Parameter allein die Inferenzkosten nicht erklären. Der Vorteil hängt vom Einsatzfall ab: Beim Prefill zählt stärker die Rechenarbeit, beim schnellen Decoding eher Speicher, Modelltiefe und GPU-Kommunikation; die genannten dichten Vergleichsgrößen sind grobe, annahmenabhängige Schätzungen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 25 / 79 % | 0 / 0 % | 95 / 98 % | 5 / 13 % | 3 / 9 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 25 / 62 % | 0 / 0 % | 49 / 65 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
