[English](README.md) · [Deutsch](README.de.md)

# Inside OpenAI’s in-house data agent

Report Q008121 · Source openai.com · Date 2026-01-29 · [Open original](https://openai.com/index/inside-our-in-house-data-agent/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt einen internen Datenagenten, der mit Kontext aus Metadaten, Code, Unternehmenswissen, gespeicherten Erkenntnissen und Live-Abfragen Analysen in natürlicher Sprache erstellen soll. Der Beitrag erläutert außerdem Evaluierungen, Berechtigungen und praktische Entwicklungslehren; Leistungs- und Sicherheitsvorteile werden dabei vom Unternehmen behauptet und nicht unabhängig belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 42 / 59 % | 95 / 99 % | – | 100 / 100 % | 69 / 83 % | 55 / 71 % | 38 / 59 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 27 / 42 % | 24 / 83 % | – | 95 / 97 % | 35 / 61 % | 32 / 50 % | 11 / 25 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 84 / 97 % | – | 76 / 84 % | 15 / 39 % | 0 / 0 % | 10 / 25 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 47 % | 83 / 95 % | – | 76 / 81 % | 45 / 69 % | 41 / 61 % | 28 / 46 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 15 / 31 % | 68 / 87 % | – | 72 / 83 % | 12 / 35 % | 9 / 18 % | 2 / 10 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 65 / 85 % | 18 / 37 % | 10 / 17 % | 6 / 14 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 23 / 49 % | – | 47 / 61 % | 5 / 15 % | 0 / 0 % | 1 / 6 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 42 / 84 % | – | 18 / 54 % | 12 / 29 % | 0 / 0 % | 2 / 6 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 40 / 74 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 37 / 94 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 1 / 6 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 12 / 29 % | 34 / 71 % | – | 6 / 21 % | 18 / 40 % | 23 / 40 % | 10 / 21 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 6 / 45 % | – | 26 / 46 % | 8 / 22 % | 0 / 0 % | 3 / 10 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 24 / 47 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 14 / 27 % | 17 / 64 % | – | 0 / 0 % | 15 / 39 % | 22 / 37 % | 2 / 8 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 13 / 27 % | 0 / 0 % | – | 0 / 0 % | 9 / 21 % | 8 / 15 % | 5 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 12 / 25 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 5 / 10 % | 2 / 5 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 11 / 21 % | 3 / 9 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 3 / 63 % | – | 0 / 0 % | 10 / 31 % | 10 / 23 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 22 % | 0 / 0 % | 1 / 4 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 0 / 0 % | 2 / 5 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 12 % | 1 / 2 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 2 % |
