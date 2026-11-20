[English](README.md) · [Deutsch](README.de.md)

# Swift: Hooks for Foundation Models. A Little Cleaner Way!

Report Q009750 · Source medium.com · Date 2026-06-13 · [Open original](https://medium.com/@itsuki.enjoy/swift-hooks-for-foundation-models-a-little-cleaner-way-c822ed2cb25b)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Artikel zeigt anhand von Swift-Beispielcode, wie `LanguageModelSession.DynamicProfile` Hooks für Werkzeugaufrufe, Nutzereinwilligungen und weitere Sitzungsereignisse bereitstellen kann. Der Autor empfiehlt `.preserveTranscript`, damit bei Fehlern der Gesprächsverlauf erhalten bleibt; die Lösung wird demonstriert, aber nicht systematisch getestet oder hinsichtlich Plattformanforderungen bewertet.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 42 / 62 % | 89 / 96 % | 0 / 0 % | 98 / 99 % | 49 / 70 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 50 / 72 % | 0 / 0 % | 83 / 89 % | 12 / 25 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 41 % | 5 / 26 % | 0 / 0 % | 80 / 90 % | 23 / 46 % | 12 / 26 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 27 / 46 % | 0 / 0 % | 0 / 0 % | 57 / 68 % | 24 / 45 % | 16 / 31 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 28 / 52 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 38 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 17 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
