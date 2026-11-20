[English](README.md) · [Deutsch](README.de.md)

# Replay for LLM Continual Learning with Multi-Teacher On-Policy Distillation

Report Q000394 · Source arxiv.org · Date – · [Open original](https://arxiv.org/abs/2611.02746)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Text ist nur der Abstract-Auszug eines arXiv-Berichts. Er beschreibt Replay für fortlaufende Modell-Destillation: Frühere Domänen werden mit dem Student der vorherigen Lernstufe erneut trainiert, sodass laut Abstract keine Experten oder Modellzwischenstände gespeichert werden müssen. In Tests über fünf Domänen und 14 Benchmarks schließe das Verfahren den Großteil des Abstands zur gemeinsamen Destillation; ein festes Replay-Budget je Domäne erreiche dem Abstract zufolge das Niveau der Wiederherstellung mit gespeicherten Zwischenständen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 60 / 68 % | 10 / 27 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 28 / 66 % | 0 / 0 % | 10 / 34 % | 11 / 31 % | 0 / 0 % | 7 / 17 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 8 / 38 % | 0 / 0 % | 27 / 47 % | 7 / 17 % | 0 / 0 % | 3 / 9 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 0 / 0 % | 6 / 13 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 5 / 10 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % |
