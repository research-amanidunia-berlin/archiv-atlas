[English](README.md) · [Deutsch](README.de.md)

# Writing effective tools for AI agents

Report Q003764 · Source anthropic.com · Date 2025-09-11 · [Open original](https://www.anthropic.com/research/writing-tools-for-agents)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic empfiehlt, Agentenwerkzeuge anhand realistischer Aufgaben iterativ zu entwickeln und zu messen. Klare Zuständigkeiten, verständliche Beschreibungen und kontextsparsame, relevante Antworten sollen Fehlbedienung und unnötige Aufrufe reduzieren; die berichteten Verbesserungen stammen aus internen Slack- und Asana-Evaluationen, deren konkrete Zahlen im Text fehlen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 41 % | 26 / 87 % | 92 / 96 % | 19 / 45 % | 4 / 16 % | 12 / 28 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 13 / 58 % | 87 / 93 % | 17 / 50 % | 7 / 18 % | 16 / 39 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 35 % | 66 / 95 % | 46 / 61 % | 15 / 37 % | 0 / 3 % | 12 / 23 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 20 / 46 % | 52 / 89 % | 40 / 81 % | 25 / 53 % | 5 / 21 % | 15 / 36 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 44 / 66 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 38 / 88 % | 10 / 30 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 25 / 53 % | 0 / 0 % | 14 / 40 % | 3 / 11 % | 17 / 34 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 24 / 54 % | 8 / 24 % | 2 / 9 % | 7 / 13 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 19 / 51 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 6 / 11 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 19 / 66 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 17 / 45 % | 0 / 0 % | 6 / 17 % | 2 / 8 % | 7 / 15 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 14 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 9 / 46 % | 12 / 31 % | 7 / 24 % | 1 / 8 % | 4 / 11 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 9 / 66 % | 0 / 0 % | 5 / 13 % | 0 / 2 % | 8 / 13 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 27 % | 0 / 0 % | 8 / 18 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 6 / 24 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 2 / 8 % | 6 / 15 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 3 / 5 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 5 / 10 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 5 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
