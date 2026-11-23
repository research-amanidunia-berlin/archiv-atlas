[English](README.md) · [Deutsch](README.de.md)

# The "think" tool for complex tool use

Report Q003776 · Source anthropic.com · Date 2025-03-20 · [Open original](https://www.anthropic.com/research/claude-think-tool)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet, dass ein separates „think“-Werkzeug Claude bei komplexen, mehrstufigen Werkzeugaufgaben und detaillierten Richtlinien helfen kann. In τ-Bench stiegen die ausgewiesenen Ergebnisse in Airline- und Retail-Aufgaben, besonders mit einer optimierten Anleitung im Airline-Bereich; der Bericht nennt für diesen Wert allerdings zwei unterschiedliche Zahlen. Das Werkzeug kostet zusätzliche Tokens und soll bei einfachen Aufgaben wenig bringen. Laut Aktualisierung empfiehlt Anthropic inzwischen erweitertes Denken in den meisten Fällen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 22 / 39 % | 47 / 86 % | 98 / 99 % | 20 / 47 % | 3 / 12 % | 11 / 24 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 20 / 37 % | 0 / 0 % | 76 / 84 % | 18 / 45 % | 0 / 0 % | 14 / 29 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 15 / 35 % | 75 / 95 % | 52 / 76 % | 25 / 50 % | 2 / 10 % | 8 / 18 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 70 / 97 % | 38 / 55 % | 11 / 39 % | 1 / 7 % | 8 / 16 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 27 / 61 % | 0 / 0 % | 17 / 47 % | 3 / 10 % | 13 / 25 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 22 / 50 % | 0 / 0 % | 0 / 0 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 22 / 39 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 7 / 69 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 5 / 8 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 3 % | 7 / 14 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 6 / 79 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
