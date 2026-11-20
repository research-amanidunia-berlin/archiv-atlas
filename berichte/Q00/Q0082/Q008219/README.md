[English](README.md) · [Deutsch](README.de.md)

# Simplifying, stabilizing, and scaling continuous-time consistency models

Report Q008219 · Source openai.com · Date 2024-10-23 · [Open original](https://openai.com/index/simplifying-stabilizing-and-scaling-continuous-time-consistency-models/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt sCM als Verfahren, das kontinuierliche Consistency-Modelle stabiler trainieren und auf zwei Sampling-Schritte beschleunigen soll. Laut Bericht erreicht es dabei vergleichbare Qualität zu führenden Diffusionsmodellen bei deutlich geringerem Sampling-Aufwand, bleibt aber von vortrainierten Diffusionsmodellen abhängig und weist einen kleinen Qualitätsabstand auf; zudem bildet FID Qualität nur begrenzt ab.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 80 / 87 % | 12 / 31 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 67 / 85 % | – | 18 / 34 % | 14 / 32 % | 7 / 15 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | – | 60 / 67 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 7 / 47 % | – | 38 / 59 % | 6 / 14 % | 4 / 9 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 20 / 43 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 19 / 34 % | 9 / 26 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 5 / 10 % |
