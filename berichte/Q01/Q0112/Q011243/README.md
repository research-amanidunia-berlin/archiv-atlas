[English](README.md) · [Deutsch](README.de.md)

# I Stopped “Prompting” AI to Write Code. I Built an Agentic Coding System Instead.

Report Q011243 · Source medium.com · Date 2026-07-18 · [Open original](https://medium.com/coding-nexus/i-stopped-prompting-ai-to-write-code-i-built-an-agentic-coding-system-instead-0e59c0d1664b)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht empfiehlt, Coding-Agenten mit Projektdokumentation, festen Abläufen, Tests, unabhängigen Reviews, Automatisierung und Feedbackschleifen in eine strukturierte Arbeitsumgebung einzubetten. Der Autor behauptet, dies mache sie verlässlicher und teamähnlicher, belegt die Vorteile im Text aber nicht mit Messungen oder Fallstudien.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 41 % | 63 / 91 % | 98 / 99 % | 33 / 58 % | 9 / 23 % | 19 / 41 % | 3 / 14 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 31 / 51 % | 52 / 95 % | 93 / 98 % | 31 / 56 % | 11 / 34 % | 19 / 41 % | 7 / 35 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 38 / 82 % | 85 / 94 % | 7 / 17 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 6 / 36 % | 76 / 85 % | 5 / 13 % | 0 / 0 % | 5 / 8 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 37 % | 72 / 95 % | 29 / 46 % | 10 / 30 % | 5 / 14 % | 10 / 20 % | 1 / 4 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 18 / 33 % | 59 / 86 % | 56 / 63 % | 6 / 18 % | 6 / 15 % | 9 / 19 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 54 / 91 % | 47 / 78 % | 8 / 20 % | 2 / 7 % | 6 / 12 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 18 / 42 % | 54 / 70 % | 4 / 9 % | 1 / 4 % | 3 / 9 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 15 / 37 % | 7 / 49 % | 2 / 12 % | 11 / 27 % | 6 / 23 % | 12 / 29 % | 1 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 12 / 31 % | 3 / 43 % | 14 / 31 % | 8 / 26 % | 3 / 14 % | 6 / 16 % | 0 / 2 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 0 % | 10 / 20 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 1 / 23 % | 0 / 0 % | 8 / 25 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 2 % | 4 / 7 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 7 % | 5 / 11 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 46 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
