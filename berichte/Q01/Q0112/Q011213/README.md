[English](README.md) · [Deutsch](README.de.md)

# Ornith-1.5: A 9B Open-Source Model Built to Improve Itself

Report Q011213 · Source medium.com · Date 2026-08-22 · [Open original](https://medium.com/coding-nexus/ornith-1-5-a-9b-open-source-model-built-to-improve-itself-ab3055ef6e88)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt Ornith-1.5 als offene Modellfamilie vor, deren Modelle laut Projekt eigene Lernaufgaben erzeugen und zur Verbesserung nutzen sollen. Der Autor berichtet starke Benchmarkwerte und hebt besonders die lokal betreibbare 9B-Version mit Werkzeugaufrufen und bis zu 262.144 Tokens Kontext hervor; die Leistungsangaben werden im Text nicht unabhängig überprüft, und die Erweiterung auf rund eine Million Tokens erfordert laut Bericht eine bedarfsgerechte YaRN-Konfiguration.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 35 / 63 % | 91 / 99 % | 51 / 80 % | 98 / 100 % | 57 / 79 % | 50 / 68 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 14 / 40 % | 52 / 88 % | 1 / 10 % | 96 / 98 % | 12 / 36 % | 8 / 23 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 16 / 46 % | 15 / 77 % | 1 / 6 % | 87 / 95 % | 8 / 23 % | 5 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 9 / 38 % | 0 / 0 % | 56 / 80 % | 7 / 22 % | 5 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 39 / 74 % | 0 / 3 % | 42 / 70 % | 9 / 31 % | 8 / 19 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 10 / 41 % | 42 / 70 % | 2 / 12 % | 38 / 73 % | 18 / 41 % | 9 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 13 / 41 % | 29 / 72 % | 1 / 6 % | 0 / 0 % | 7 / 21 % | 8 / 24 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 52 % | 6 / 14 % | 2 / 7 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 20 / 44 % | 1 / 32 % | 0 / 0 % | 0 / 0 % | 6 / 22 % | 11 / 23 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 13 / 48 % | 15 / 71 % | 1 / 5 % | 12 / 33 % | 12 / 33 % | 7 / 16 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 44 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 7 / 19 % | 7 / 14 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 11 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 9 / 20 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 3 / 44 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 7 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 8 / 15 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 5 / 10 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 5 / 12 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 6 / 12 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 2 / 27 % | 0 / 3 % | 0 / 0 % | 6 / 20 % | 5 / 13 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 6 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 4 / 10 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 1 / 28 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 2 / 7 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 4 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
